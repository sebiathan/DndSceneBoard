# APK bauen

Das Repository enthält einen GitHub-Actions-Workflow unter `.github/workflows/build-apk.yml`.
Bei jedem Push auf `main` oder manuell per `workflow_dispatch` wird eine installierbare Debug-APK gebaut.

Ausgabe: `app/build/outputs/apk/debug/app-debug.apk`
Artifact-Name: `DndSceneBoard-APK`
