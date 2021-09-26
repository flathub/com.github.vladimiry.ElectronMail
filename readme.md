### Installing from the flathub.org repository

See https://flathub.org/apps/details/com.github.vladimiry.ElectronMail for details.

### Local build

- Use `flatpak-builder --force-clean --repo=repo --user --install build-dir com.github.vladimiry.ElectronMail.yaml`
  command to "build & install" the app into the local `./repo` repository. The `./repo`, `./build-dir` and `./.flatpak-builder` directories added
  to the `./.gitignore` file.
- Then use `flatpak run com.github.vladimiry.ElectronMail` command to start the app.
