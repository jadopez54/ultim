# Com generar l'APK amb GitHub Actions

Aquest projecte ja porta preparat el fitxer automàtic de GitHub Actions:

`.github/workflows/build-apk.yml`

Quan el pugis a GitHub, GitHub compilarà l'app i et deixarà descarregar l'APK.

## Passos resumits

1. Entra a https://github.com
2. Crea un compte o inicia sessió.
3. Crea un repositori nou.
4. Puja tots els fitxers d'aquest ZIP.
5. Entra a la pestanya **Actions**.
6. Obre l'acció **Generar APK Android**.
7. Prem **Run workflow**.
8. Espera que acabi en verd.
9. A baix de tot, a **Artifacts**, descarrega **Passaport-Aventureres-APK**.
10. Dins del ZIP descarregat hi haurà l'APK: normalment `app-debug.apk`.

## Instal·lació al mòbil

1. Envia l'APK al mòbil.
2. Obre'l des del mòbil.
3. Android pot demanar permís per instal·lar apps desconegudes.
4. Dona permís només al navegador o gestor de fitxers que estiguis usant.
5. Instal·la l'app.

## Nota

Aquesta APK és de tipus **debug**, suficient per instal·lar-la al teu mòbil i provar-la. No és per publicar a Google Play.
