# Merge notes

Base: KinesisCorporation/Adv360-Pro-ZMK V3.0 at commit 97f5d7394d36f60754a483bf5551e16d996fe406.
Custom source: user fork at commit 6afa41ef3c3e2004b23b003ac8b9da001eb8cb4f.

Merged changes:
- Preserved Japanese/English IME toggle: &kp LA(GRAVE).
- Preserved base-layer macro positions: &macro_quotes, &macro_braces, &macro_dquotes, &macro_parens.
- Preserved custom macro implementations for macro_quotes, macro_dquotes, macro_braces, and macro_parens.
- Kept latest V3.0 repository/workflow/board/ZMK/Clique-related changes.
- Kept latest Mod-layer additions: studio_unlock and STP_BAT.
- Removed the old no-op Layer #4 from keymap.json; latest V3.0 keeps reserved extra layers in adv360.keymap.

Build this repository in GitHub Actions and use the firmware-clique artifact unless you intentionally need the non-Clique build.
