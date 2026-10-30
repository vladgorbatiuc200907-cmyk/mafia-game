# Mafia — Power & Deception

Joc web multiplayer în limba română, cu 15 roluri și instrucțiuni în aplicație.

## Pornire locală
1. Instalează Node.js 20+ de la https://nodejs.org
2. Deschide folderul proiectului în VS Code.
3. În terminal rulează `npm install`, apoi `npm start`.
4. Intră pe `http://localhost:3000`.

## Joacă online fără domeniu cumpărat
1. Creează un cont gratuit pe https://github.com și un repository nou.
2. Urcă **fișierele din acest folder** în repository (nu urca `node_modules`).
3. Creează un cont pe https://render.com, apoi `New` → `Web Service`.
4. Conectează repository-ul GitHub și selectează planul Free dacă este disponibil.
5. Build Command: `npm install`; Start Command: `npm start`.
6. După deploy, deschide URL-ul `https://...onrender.com` atribuit de Render.
7. Apasă `Creează cameră`, trimite linkul prietenilor, așteaptă minimum 5 jucători și pornește jocul.

**Limitări importante:** versiunea actuală este un MVP pentru testare. Voice chat nu este încă implementat; pentru voce folosiți Discord/WhatsApp. Camerele sunt în memorie și se pierd la restart sau la repausul instanței gratuite. Pentru partide reale recomandăm testarea regulilor și a interacțiunilor dintre roluri înainte de utilizare competitivă. Render Free poate intra în repaus după inactivitate; verifică limitele actuale.

## Ce conține
- Camere cu cod și link, Ready, 5–20 participanți.
- Roluri secrete, ghid complet în site.
- Zi 90 secunde, noapte 45 secunde, vot simplu 5–7 și nominalizare + apărare 8+.
- Chat public și privat Mafia, chat morți.
- Abilități și atacuri rezolvate pe server, rezultate private, dezvăluire rol la moarte.
- Reconectare în același browser.

## Ce necesită îmbunătățiri înainte de versiunea finală
- Voice chat WebRTC / TURN.
- Persistență a camerelor și anti-abuz.
- Teste automate exhaustive ale interacțiunilor, echilibrarea configurațiilor.
- Moderare chat și accesibilitate.
