# Sheet Price Calculator

A simple Android app that divides the total sheet price by the number of pieces.
GST is not added.

Example: 55 SAR / 400 pieces = 0.1375 SAR per piece.

## Build an APK online with GitHub Actions (no Android Studio)

1. Create/sign in to a GitHub account at https://github.com.
2. Create a new repository. You can name it `SheetPriceCalculator`.
3. Upload the contents of this project ZIP to the repository (upload the files and folders, not the ZIP file itself).
4. Open the repository's **Actions** tab.
5. If GitHub asks, enable workflows.
6. Select **Build Android APK** (or the workflow named "Build Android APK") and click **Run workflow**.
7. Wait for the run to finish successfully.
8. Open the completed workflow run. Under **Artifacts**, download `SheetPriceCalculator-debug-apk`.
9. Extract the downloaded artifact ZIP. It contains `app-debug.apk`.

You can also trigger a build by pushing a commit to the `main` branch.

Note: GitHub Actions builds the APK on GitHub's cloud computers. A GitHub account is required. The APK is a debug APK for personal testing, not a Play Store release.
