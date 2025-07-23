# Installer Folder

This folder contains ZeepFly ACARS Client installer-related files that should not be versioned in Git.

## Contents

- `ZeepFly_ACARS_Installer.exe` - Generated installer executable
- `ACARS_Setup.iss` - Inno Setup script to generate the installer
- Other temporary and build files

## Notes

- This folder is ignored by `.gitignore` as it contains binary and temporary files
- Installer configuration files (like `ACARS_Setup.iss`) should be kept in the main repository
- The final installer is generated during the build process and published in releases

## Build Process

1. Application files are compiled
2. Inno Setup uses the `.iss` script to generate the installer
3. Installer is moved to this folder
4. Installer is published in the release

---

*This folder is necessary for the build process but its contents should not be versioned*

