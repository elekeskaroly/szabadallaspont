# Szabadállásponti mérés – Android app

1. Hozz létre egy ingyenes GitHub-fiókot, majd egy új, üres repót (pl. "szabadallaspont").
2. Add file -> Upload files: húzd be ennek a mappának a TELJES tartalmát (a .github mappát is!).
   Ha a .github mappa nem látszik (Macen: Cmd+Shift+. a rejtett fájlokhoz), a repóban
   Add file -> Create new file, a név legyen: .github/workflows/build.yml, és másold bele a build.yml tartalmát.
3. Commit changes.
4. Actions fül -> "Build APK" -> a legfrissebb futás -> lent az Artifacts alatt "szabadallaspont-apk".
5. Töltsd le, csomagold ki: app-debug.apk. Másold a telefonra, nyisd meg, és engedélyezd az
   ismeretlen forrásból való telepítést.

Az exportált .txt fájlok a telefon Letöltések mappájába kerülnek.
