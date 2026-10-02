# Fonts

The four font files the mobile app loads in `mobile/App.tsx`, copied from the
`@expo-google-fonts/lora` and `@expo-google-fonts/plus-jakarta-sans` packages.

| File | Family | Weight | Used for |
| --- | --- | --- | --- |
| `Lora_600SemiBold.ttf` | Lora | 600 | Titles and highlighted figures |
| `PlusJakartaSans_400Regular.ttf` | Plus Jakarta Sans | 400 | Body text |
| `PlusJakartaSans_500Medium.ttf` | Plus Jakarta Sans | 500 | Field text, captions |
| `PlusJakartaSans_700Bold.ttf` | Plus Jakarta Sans | 700 | Labels, buttons |

Both families are distributed under the SIL Open Font License 1.1; the license
texts shipped with the packages are `Lora-OFL.txt` and `PlusJakartaSans-OFL.txt`.

`../tokens.css` declares the matching `@font-face` rules. A web page that uses
the tokens must serve these files itself, next to its copy of `tokens.css`.
