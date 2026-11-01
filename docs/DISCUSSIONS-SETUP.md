# GoodToKnow Discussions: categorii RO/EN

Actualizat 2026-11-01. Acest document pregătește organizarea repository-ului public. **Nu dovedește că toate categoriile au fost create în GitHub.** Niciun cod sau issue intern din repository-ul privat nu este publicat aici.

GitHub oferă implicit categorii precum Announcements, General, Ideas, Polls, Q&A și Show and tell. Verifică înainte să adaugi o categorie nouă, pentru a nu duplica.

## Categorii recomandate

| Categorie | Format GitHub | Descriere RO / EN | Stare |
| --- | --- | --- | --- |
| 📣 Announcements | Announcement | Noutăți oficiale și schimbări lansate / Official news and released changes | Implicită, mesajul de bun venit publicat de proprietar |
| 💡 Ideas | Open-ended | Propuneri de funcționalități / Feature suggestions and improvements | Folosește categoria implicită, dacă există |
| 🗳 Polls | Polls | Consultări privind prioritățile / Community priority polls | Folosește categoria implicită, dacă există |
| 🙏 Q&A | Question and answer | Întrebări despre proiect / Questions about the project | Folosește categoria implicită |
| 🌍 Traduceri / Translations | Open-ended | Text, terminologie, localizare RO/EN și corecturi / Wording, localization, and corrections | De creat |
| 🎨 Design și accesibilitate / Design & accessibility | Open-ended | Feedback UI, mobil, tastatură, contrast / UI and accessibility feedback | De creat |
| 🧪 Testare / Beta testing | Open-ended | Feedback pentru funcții testate pe site / Preview and beta feedback | De creat |

Folosește **GitHub Issues** pentru bug-uri reproductibile, cu formularele `.github/ISSUE_TEMPLATE/`. Vulnerabilitățile nu se discută nici în Issues, nici în Discussions. Proprietarul a confirmat activarea Private Vulnerability Reporting; `SECURITY.md` indică ruta de raportare.

## Cum le configurează administratorul

1. Deschide `https://github.com/csivpunctro/goodtoknow-community/discussions`.
2. În bara laterală, lângă **Categories**, apasă pictograma creion pentru **Manage discussion categories**.
3. Păstrează categoriile standard relevante. Apasă **New category** pentru cele trei categorii noi de mai sus.
4. Alege formatul **Open-ended discussion**, adaugă descrierea bilingvă, salvează categoria.
5. Verifică în interfață că apare pentru o discuție nouă; nu publica postări false pentru testare.

GitHub Docs: https://docs.github.com/en/discussions/managing-discussions-for-your-community/managing-categories-for-discussions

## Moderare și proces

O idee publică nu creează automat issue, PR sau release în proiectul privat. Moderatorii grupează duplicatele, marchează ideile analizate și sincronizează public doar stări aprobate explicit. Nu se copiază loguri, capturi de ecran cu date personale, vulnerabilități ori fișiere din repo-ul privat. Licența și drepturile contribuțiilor la documentație trebuie stabilite înainte de invitarea contribuțiilor în masă.

Ordinea de implementare ulterior: formulare de idei în produs -> sesiune și moderare -> legătură la statusul public -> integrare GitHub App cu permisiuni limitate, doar după testare.
