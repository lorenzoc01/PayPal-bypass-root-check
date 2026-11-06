# PayPal - Bypass Root Check
Lucky Patcher custom patch to bypass the root check in PayPal android app.

## Usage
1. Insert the txt file inside `/storage/emulated/0/Android/data/[luckypatcher package name]/files/LuckyPatcher/CustomPatches`
2. In LuckyPatcher, apply the custom patch to PayPal app (or "Create Modified APK File" with the patch applied and install the rebuilt apk)

## Compatibility
The patch was tested and is working on versions:
- `10.19.0`

It could work in future versions too, but that's not guaranteed.

For older versions you can check the commit history.

## Explanation
The patch bypasses the execution of 2 methods in the dex files:
- a method that crashes the app on statup when root privileges are found.
- a method that crashes the app on statup when files/methods integrity is not preserved.

## ⚠️**Disclaimer**

This project is provided solely for educational, research, interoperability, and security-testing purposes.

The author does not endorse, encourage, or condone any malicious, fraudulent, unauthorized, or unlawful use of this project or modified versions of PayPal.

Use is permitted only on devices you own or are explicitly authorized to modify and test. Users are solely responsible for complying with all applicable laws, regulations, licenses, and terms of service.

The author assumes no responsibility for misuse or any consequences arising from the use, modification, or distribution of this project.
