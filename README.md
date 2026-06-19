# Arabic Debt Ledger

تطبيق دفتر ديون عربي يعمل أوفلاين، مع إعلان AdMob حقيقي في أعلى الصفحات.

## New app identity

- Package name: `com.explapp.arabic_debt_ledger`
- Version: `1.0.0+1`
- APK artifact: `arabic-debt-ledger-v1-signed-apk`
- Direct APK path inside build: `apk/arabic-debt-ledger-v1.apk`

## Important

This project requires fixed Android signing secrets in GitHub Actions.

Read:

`SIGNING_SETUP.md`

Do not publish or commit the keystore file or signing passwords.

## Build

Upload the project files to GitHub, add the required signing secrets, then run:

`.github/workflows/build-apk.yml`
