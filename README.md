# aseprite-win-builder
Build the latest Aseprite Windows release with GitHub Actions.
# Guide
- Copy .github/workflows/build.yml to your workflow or fork this repo 
- `<Action > Build Aseprite for Windows > run workflow`
  <img width="1976" height="942" alt="step1" src="https://github.com/user-attachments/assets/67f5051d-a82e-48e5-af0b-c822d67d6f08" />
- Wait for the workflow to finish, then download the release-zip.
- Build artifacts are not published to this `public repository`.They are stored `temporarily` as GitHub Actions artifacts and will be automatically removed after `3 days`.
<img width="1912" height="942" alt="step2" src="https://github.com/user-attachments/assets/3fc89ee3-ca5c-4729-b96f-7c8f27f7c565" />

