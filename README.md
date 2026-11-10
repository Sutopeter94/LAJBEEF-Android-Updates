# LAJ BEEF – Android frissítések

Ez a **nyilvános APK-letöltési tárhely**, nem a LAJ BEEF alkalmazás forráskódja és nem a Synology NAS biztonsági mentése.

- Az Android-forráskód a **privát** `Sutopeter94/LAJBEEF-Android` repositoryban marad.
- A kiadási automatizmus ellenőrzött, **azonos kulccsal aláírt APK-t** és a hozzá tartozó `latest.json` leírófájlt teszi ide.
- A mobilalkalmazás az új verziót a `https://sutopeter94.github.io/LAJBEEF-Android-Updates/latest.json` címen ellenőrzi.
- Az Android-rendszernek a telepítést jóvá kell hagynia. A telepítés nem történik láthatatlanul.

**Kiadásig még nincs itt letölthető frissítés.** A `latest.json` csak az első ténylegesen aláírt APK elkészültekor kerülhet ide, így nem mutatunk nem létező vagy nem ellenőrzött verziót.

## Közzétételi biztonság

Ne tölts fel ide jelszavakat, keystore-fájlt, tokeneket, adatbázist, rendeléseket vagy vevőadatokat. A nyilvános APK visszafejthető, ezért semmilyen titok nem kerülhet az alkalmazásba.

A kiadási folyamatot az Android privát repository `.github/workflows/signed-update.yml` fájlja kezeli. A `LAJBEEF_UPDATES_TOKEN` jogosultságát kizárólag erre a frissítési repositoryra, Contents: Read and write engedélyre kell korlátozni.

A GitHub Pages közzétételt a repository Settings → Pages menüjében egyszer engedélyezni kell, a `main` ág `/(root)` mappájára állítva.
