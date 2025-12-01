# REST API og Databehandling - Veiledning

## 📚 Hva er nytt?

Kursmaterialet er nå delt opp i **8 mindre moduler** i stedet for én stor notebook. 

---

## 🗂️ Moduloversikt

| Modul | Tema | Innhold | Anbefalt rekkefølge |
|-------|------|---------|---------------------|
| **Del 01** | Klasser og dataclass | Grunnleggende klasser, `@dataclass` dekoratør | ⭐ Start her |
| **Del 02** | Validering med pydantic | Introduksjon til `pydantic`, `BaseModel` | ⭐ Deretter |
| **Del 03** | Pydantic med API | REST Countries API, nestede modeller, `ConfigDict` | ⭐ Viktig |
| **Del 04** | Avansert pydantic | `Field`, validatorer, avanserte features | 💡 Ved behov |
| **Del 05** | Oppgaver (del 1) | Grunnleggende oppgaver med restcountries | 📝 Øving |
| **Del 06** | URL-encoding | `urllib.parse`, query parameters, encoding/decoding | 🔧 Nyttig verktøy |
| **Del 07** | Oppgaver (del 2) | Pandas, regex, databehandling | 📊 Dataanalyse |
| **Del 08** | Oppgaver (del 3) | Pandas, plotting, valutaanalyse | 📊 Visualisering |

---

## 📖 Hva lærer du i hver modul?

### Del 01 - Klasser og dataclass
- Egendefinerte klasser for API-håndtering
- `LocationForecastCompactApi` eksempel
- Sammenligning: vanlig klasse vs `@dataclass`
- `Kontakt` og `Adresse` eksempler

**Nøkkelkonsepter:** `__init__`, `self`, `@dataclass`

---

### Del 02 - Validering med pydantic
- Installere og importere `pydantic`
- `BaseModel` grunnleggende
- Automatisk type-konvertering
- Valideringsfeil og feilmeldinger

**Nøkkelkonsepter:** `BaseModel`, type hints, validering

---

### Del 03 - Pydantic med API
- REST Countries API i praksis
- Nestede modeller (`CountryName`, `Currency`)
- `ConfigDict` for ekstra konfigurasjon
- Håndtering av ekstra data (ignore/forbid/allow)

**Nøkkelkonsepter:** API-integrering, nestede strukturer, `ConfigDict`

---

### Del 04 - Avansert pydantic
- Valgfrie felt (`None | str = None`)
- `Field()` for ekstra konfigurasjon
- `field_validator` for custom validering
- `ValidationInfo` for kompleks validering

**Nøkkelkonsepter:** `Field`, `field_validator`, custom validering

---

### Del 05 - Oppgaver (del 1)
- Praktiske oppgaver med REST Countries
- Regex for telefonnummer
- Valideringskjeder
- Teste pydantic-modeller

**Fokus:** Øving på det du har lært

---

### Del 06 - URL-encoding
- Hvorfor URL-encoding er viktig
- `quote`, `quote_plus`, `urlencode`
- Dekoding: `unquote`, `parse_qs`
- Query parameters med `requests`
- Spesialtegn (æøå) i URLs

**Nøkkelkonsepter:** URL-encoding, `urllib.parse`, query strings

---

### Del 07 - Oppgaver (del 2)
- Hente regiondata fra API
- Pandas DataFrame operasjoner
- Regex-mønster for postnummer
- Datafiltrering og transformering

**Fokus:** Pandas grunnleggende

---

### Del 08 - Oppgaver (del 3)
- Avansert pandas
- Matplotlib plotting
- Landegrenser analyse
- Valutafordeling i Europa
- Kakediagram og bar plots

**Fokus:** Datavisualisering

---

## 💡 Tips

### Før du starter:
1. **Har initialisert virtuelt miljø:**
    ```bash
    python -m venv .venv
    ```

2. **Aktiver virtual environment:**
   ```bash
   .venv\Scripts\Activate.ps1  # Windows
   source .venv/bin/activate    # Mac/Linux
   ```

3. **Sjekk at du har installert dependencies:**
   ```bash
   pip install -r requirements.txt
   ```


---

## 🎯 Læringsmål

✅ Strukturere data med klasser og dataclass  
✅ Bruke pydantic til datavalidering  
✅ Hente og behandle data fra REST API-er  
✅ Håndtere URL-encoding korrekt  
✅ Validere data med custom validators  
✅ Bruke pandas til dataanalyse  
✅ Visualisere data med matplotlib  
✅ Arbeide selvstendig med API-dokumentasjon  
