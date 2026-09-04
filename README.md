# Maks_Rish
[BUG] Soft Keyboard Overlaps 'Confirm Swap' Button on Android

Environment:
- OS: Android
- Browser/Wallet: Phantom In-App Browser
- Network: Mainnet-Beta

Severity: Major

Description:
When entering an amount in the input field, the Android soft keyboard pushes the UI layout upward, completely obscuring the 'Confirm Swap' button and preventing transaction execution.

Steps to Reproduce:
1. Open dApp inside Phantom Browser on Android.
2. Connect wallet.
3. Tap on the token amount input field to trigger the soft keyboard.
4. Observe the bottom action area.

Expected Result:
The UI should scale properly or scroll, keeping the 'Confirm Swap' button visible and clickable above the keyboard.

Actual Result:
The button is completely covered by the keyboard, blocking the user journey.
