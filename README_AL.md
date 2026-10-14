DJ VALI MUSIC PLAYER — version PWA
Përmbajtja:
- index.html: aplikacioni, bazuar në skedarin tënd
- manifest.webmanifest: emri dhe ikona e aplikacionit
- sw.js: cache bazë për hapje offline të faqes
- icons/: ikonat për Home Screen

PËR TA SHTUAR NË IPHONE:
1. Ngarko të gjithë përmbajtjen e kësaj dosjeje në një host HTTPS (p.sh. Netlify Drop).
2. Hape URL-në e faqes në Safari në iPhone.
3. Shtyp Share -> Add to Home Screen -> Add.
4. Ikona e Home Screen përdor ikonën e përfshirë këtu. Nëse ke logon origjinale, mund ta zëvendësosh ikonën në icons/ para se ta ngarkosh.
Kujdes: ikonat e Home Screen zakonisht nuk shfaqen nga një skedar HTML i hapur lokalisht; faqja duhet të shërbehet me HTTPS.
Muzika e importuar ruhet në IndexedDB të shfletuesit. Mos e fshi historikun/të dhënat e faqes, sepse mund të humbasësh bibliotekën lokale. Mbështetja për audio në sfond varet nga iOS/Safari dhe nuk mund të garantohet vetëm nga HTML.
