# Utvecklingsmiljö

En utvecklingsmiljö för HTML och CSS.

---

## Innan du börjar: GitHub Student Developer Pack

För att använda Codespaces gratis behöver du registrera dig för GitHub Student Developer Pack med din universitetsmail.

1. Gå till **[GitHub Student Developer Pack](https://education.github.com/pack)**
2. Klicka på **"Sign up for Student Developer Pack"**
3. Skapa ett **GitHub konto**
4. Verifiera med din **@stud.hkr.se**-adress
5. Efter inloggning klicka på knappen **"Start an application"** (via [GitHub Education Benefits](https://github.com/settings/education/benefits))
6. Välj **Student**
7. Välj **lärosäte**, exempelvis Högskolan Kristianstad
8. Klicka på knappen **Share Location**
9. Klicka på knappen **Continue**
10. Välj alternativet **3. Dated enrollment letter on school letterhead** under knappen **Select...**
11. Gå till **LADOK** (via [https://student.ladok.se/](https://student.ladok.se/))
12. Gå till **Intyg** → **Skapa intyg** → **Registreringsintyg** → Välj **period** och ange språk till **Engelska**
13. Använd **webbkamera eller mobilen** för att ta bild på registreringsintyget → Tryck på knappen **Capture**
14. Välj alternativet **All coursework is via distance learning** om du läser på distans
15. **IGEN** Använd **webbkamera eller mobilen** för att ta bild på registreringsintyget → Tryck på knappen **Capture**
16. Du ska nu ha fått beskedet **Your application has been submitted**

**OBS:** Det kan ta upp till **24 timmar** innan förmånerna aktiveras.

## Om du får beskedet Denied

1. Kontrollera att du har aktiverat **two-factor authentication** under [GitHub Security](https://github.com/settings/security).
2. Uppdatera din **Billing information** under [GitHub Billing Information](https://github.com/settings/billing/payment_information). Ange fullständigt namn, måste matcha LADOK intyget.
3. Uppdatera din **Profile** → Klicka på **ikonen längst upp till höger** → Välj Profile → Klicka på knappen **Edit profile** → Uppdatera ditt **fullständiga namn** → Logga ut och in igen → Ansök på nytt via [GitHub Education Benefits](https://github.com/settings/education/benefits).
4. Upprepa steg 5-16 enligt ovan. **OBS! Ibland funkar det snabbare om man zoomar in på tre detaljer:**
   a) Ditt fullständiga namn
   b) Namn på högskolan/universitetet
   c) Beskrivning som indikerar distansutbildning
5. **Ibland kan det ta över 5 gånger** innan ansökan går igenom och det beror på att varje gång checkar systemet av ovanstående tre detaljer.

### Vad ingår?
| Förmån | Beskrivning |
|--------|-------------|
| **GitHub Pro** | Obegränsade privata repos |
| **Copilot Pro** | AI-kodassistent gratis |
| **Codespaces** | 180 timmar/månad för molnkodning |

---

## Hantera dina Codespaces-timmar

### Kontrollera återstående timmar
1. Gå till **github.com** → Klicka på din profilbild → **Settings**
2. **Billing and licensing** → **Overview**
3. Under **Metered usage**, klicka på **Codespaces**
4. Klicka på **View details** till höger

### Automatisk timeout
En Codespace stängs automatiskt efter **30 minuters inaktivitet**. Din kod sparas och du slutar förbruka timmar.

### Stäng manuellt (rekommenderas!)

| Metod | Instruktion |
|-------|-------------|
| **Kortkommando** | `Cmd+Shift+P` (Mac) / `Ctrl+Shift+P` (Win) → Skriv "stop" → **Stop Current Codespace** |
| **Från GitHub** | [github.com/codespaces](https://github.com/codespaces) → Klicka på knappen **<> Code** → Välj fliken **Codespaces** → Klicka på **⋯** → **Stop codespace** |

Din kod försvinner inte – nästa gång fortsätter du där du slutade!

---

## Kom igång

1. Klicka på **"Use this template"** → **"Open in a codespace"**.
2. Vänta medan miljön byggs (ca 1 minut första gången).
3. Webbservern startar automatiskt. Klicka på **PORTS**-fliken och öppna länken vid port **3000** för att se din webbplats.
4. Redigera `index.html` och `assets/css/style.css` — spara så uppdateras sidan automatiskt i webbläsaren.

## Filstruktur

```
/
├── index.html              ← Startsida (redigera denna)
├── assets/
│   ├── css/
│   │   └── style.css       ← Din CSS (redan länkad i index.html)
│   └── images/             ← Lägg dina bilder här
└── .devcontainer/          ← Konfiguration (rör ej)
```
