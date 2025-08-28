# 🧾 Code Review: Pokédex Projekt

**⏳ Tidsåtgång:** 45 - 60 minuter

---

### 1. 👥 Gruppindelning
* Ni är i grupper om ca 4 personer.
* [Gruppindelare](https://toolie.se/groupie)

---

### 2. 🎤 Presentation av projektet
* Varje student presenterar sitt projekt i tur och ordning. Fokusera på tankesättet bakom dina lösningar.
    * 🛠️ **Berätta om din process:** Hur tog du dig an uppgiften? Började du med att bygga ut enskilda komponenter, eller satte du upp rutten först?
    * 💻 **Visa upp din kod:** Förklara hur du strukturerat ditt projekt. Visa upp dina **Featured Pokémon** och din lösning för **Random Pokémon**-knappen eller någon annan lösning du hunnit göra.
* 💡 **Tips:** Använd live-share för att de andra i gruppen enkelt ska kunna läsa din kod och förbereda frågor.

---

### 3. ⭐ Feedback: "2 Stars and a Wish" ✨
* Efter varje presentation ger de andra studenterna feedback i form av:
    * 🌟 **2 Stars (Stjärnor):** Två saker du gjorde bra. Kan vara allt från kodens struktur till en cool designlösning.
    * 🌠 **1 Wish (Önskan):** En sak med förbättringspotential. Fokusera på en specifik del av koden som kan göras bättre, renare eller mer effektiv. Förklara gärna varför.

---

### 4. ❓ Code Review-frågor
Efter att alla har presenterat, diskutera följande frågor i gruppen. Jämför era lösningar och lär av varandra.

* 📦 **Om struktur & dataflöde**
    * 🧩 Hur organiserade du dina komponenter? Vilka delar gjorde du till separata komponenter, och varför?
    * 🔗 Hur löste du dataflödet? Hur skickade du data från `page.tsx` ner till dina barnkomponenter, som till exempel `Header` eller `PokemonCard`?
    * 🌐 Hur hanterade du att hämta API-data? Vilken API-strategi valde du (REST eller GraphQL) och hur ser ditt anrop ut? Varför valde du just den metoden?

* ⚙️ **Om implementation**
    * 🎲 Hur löste du slumpningen? Vad är det högsta ID-numret du hämtar? Hur fick du enskilda Pokémon att dyka upp i UI:t efter knapptryckningen?
    * 🖼️ Hur fick du de fyra featured Pokémon att visas när sidan laddas? Vilken Next.js-funktion använde du för att hämta datan asynkront?
    * 🧑‍💻 Stötte du på några problem med **serverkomponenter vs. klientkomponenter**? Var var du tvungen att lägga till `'use client';` och varför?

---

### 5. 📝 Sammanfattning
* 📌 Sammanfatta era viktigaste insikter i några punkter.
* 🤔 Finns det några gemensamma frågor eller utmaningar ni stötte på?
* 🗣️ Dyk sedan in på intressanta diskussioner i helklass!

---

✨ Lycka till & ha kul! ✨
