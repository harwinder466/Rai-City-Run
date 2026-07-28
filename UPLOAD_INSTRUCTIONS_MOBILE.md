# GitHub mobile upload instructions

The real workflow is already included here:

`.github/workflows/build-apk.yml`

Some Android file managers hide folders beginning with a dot. If GitHub Actions does not appear after upload:

1. Open the repository on GitHub.
2. Tap **Add file** → **Create new file**.
3. In the filename box enter exactly:
   `.github/workflows/build-apk.yml`
4. Open `WORKFLOW_BACKUP/build-apk.yml` from this package, copy all its text, and paste it into GitHub.
5. Tap **Commit changes**.
6. Open **Actions** → **Build Rai City Run APK** → **Run workflow**.

After the green tick, download the `Rai-City-Run-APK` artifact. The APK inside is `app-debug.apk`.
