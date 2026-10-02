# Kérdezd a CV-met – telepítési útmutató

Streamlit-alkalmazás, amely a Claude API-val válaszol, kizárólag a `tudasbazis.md` alapján.

## Fájlok
- `app.py` – az alkalmazás
- `tudasbazis.md` – a tudásbázis (**csak igaz tényeket írj bele!**)
- `requirements.txt` – csomagok
- `.streamlit/secrets.toml.example` – minta a kulcshoz (helyi futtatáshoz)
- `.gitignore` – megakadályozza, hogy a kulcs GitHubra kerüljön

## 1. API-kulcs és költségkorlát
1. Regisztrálj a Claude Console-ban (console.anthropic.com), tölts fel kis egyenleget.
2. Hozz létre egy API-kulcsot.
3. **Állíts be havi költségkorlátot** (Limits / Spend limit), pl. néhány dollárt. Így semmilyen visszaélés nem okozhat nagy számlát.
4. Részletek: https://docs.claude.com/en/api/overview

## 2. Helyi kipróbálás (VS Code)
```
pip install -r requirements.txt
copy .streamlit\secrets.toml.example .streamlit\secrets.toml   (Windows)
# írd be a kulcsot a secrets.toml-ba
streamlit run app.py
```

## 3. Közzététel (ingyenes Streamlit Community Cloud)
1. Tedd fel a mappát egy **nyilvános vagy privát GitHub-repóba** (a `secrets.toml` NE kerüljön fel).
2. share.streamlit.io → *Create app* → válaszd a repót és az `app.py`-t.
3. *Advanced settings → Secrets*: `ANTHROPIC_API_KEY = "…"`
4. Deploy. A kapott linket teheted a CV-be vagy a portfólióoldalra.
5. **Teszteld inkognitó ablakban**, bejelentkezés nélkül – a toborzó is így fogja látni.

## Beépített védelmek
- Csak a tudásbázisból válaszol; ha valami nincs benne, megmondja, és e-mailt javasol.
- Kérdéskorlát munkamenetenként (`MAX_QUESTIONS`), rövid előzmény és válaszhossz – kis költség.
- Bérigényre, magánéletre, a jelenlegi munkáltató belső ügyeire nem válaszol.
- A legolcsóbb modellt használja (`MODEL` az `app.py` elején).

## Mielőtt linkeled
- Kérdezz tőle 15–20 kérdést, köztük olyat is, amire **nem** tudhatja a választ (pl. „Van SAP-tapasztalata?”, „Mennyi a bérigénye?”). Csak akkor jó, ha ezekre azt mondja: nincs információja.
- Ingyenes Streamlit-tárhelyen az alkalmazás egy idő után „elalszik”; az első megnyitás ilyenkor fél percig tarthat. Beadás előtt nyisd meg egyszer.
