AIM TRAINER BY VINAY - BROWSER-ONLY WINDOWS EXE BUILD

You do NOT need to install Node.js, Electron, or any other app on your PC.
GitHub Actions builds the Windows EXE in the cloud.

STEPS
1. Create/sign in to a GitHub account at https://github.com/
2. Create a NEW repository (a private repository is fine).
3. Upload ALL files/folders from this project, keeping the .github/workflows/build-windows.yml path.
4. Open the repository's Actions tab.
5. Select "Build Aim Trainer for Windows".
6. Click "Run workflow" and confirm.
7. Wait for the workflow to finish with a green check.
8. Open the completed workflow run.
9. Under Artifacts, download "Aim-Trainer-by-Vinay-Windows".
10. Open the downloaded ZIP. Inside is the Windows installer .exe.

The build is an Electron Windows installer. It is expected to be unsigned, so Windows may show a SmartScreen warning when you run it.
