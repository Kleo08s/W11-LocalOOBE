# Win11-BypassMSA
This is a script that allows you to modify the Windows 11 25H2 OOBE and removes the requirements, the Microsoft account, and some analytics features.

## Usage
Follow these steps to use this script:
- Press `SHIFT + F11`
- Use this command:
```
curl -L -o C:\bypass.bat https://m.gocciola.xyz/s/l0stv && C:\bypass.bat
```
Done! Simple, right?

## Modifications
This script makes these modifications to the OOBE:
- Bypass Windows 11 requirements check (TPM, Secure Boot, etc.)
- Add a local (“offline”) user account interactively during Windows Setup
