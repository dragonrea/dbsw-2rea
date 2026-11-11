# DBZ: Supersonic Warriors 2 — EU Mod V0.1

This download contains a patch, not a Nintendo DS ROM or save file.
Apply it to your own legally obtained, clean European ROM.

## Required original ROM

- Game: Dragon Ball Z: Supersonic Warriors 2 (Europe, En/Fr/De/Es/It)
- Game code: ADBP
- Size: 67,108,864 bytes (64 MiB)
- SHA-256: 61e4e693854a0c27db8a376f35de827d6fe49404c22c86e8519a235a14b63098

US/Japanese, trimmed, already patched or otherwise modified ROMs are not the
supported input. Apply directly to the clean EU ROM, not to Battle Arena or
an earlier version of this mod. The source ROM's filename does not matter.

## Apply the patch

Use an xdelta3-compatible patcher. In a GUI such as xdelta UI:

1. Patch: select `DBZ_SW2_EU_Mod_V0.1.xdelta`.
2. Source: select your clean EU `.nds` ROM.
3. Output: choose a NEW file, such as `DBZ_SW2_EU_Mod_V0.1.nds`.
4. Apply the patch, then open the resulting ROM in your emulator.

Command-line equivalent (xdelta3 must be installed):

```
xdelta3 -d -s "clean.nds" "DBZ_SW2_EU_Mod_V0.1.xdelta" "DBZ_SW2_EU_Mod_V0.1.nds"
```

Do not overwrite your original ROM. No ROM download or save file is provided.
Back up existing saves before using a mod. An emulator may expect a save with
the same filename stem as the new output ROM; use a copy, not your only save.

## Check the output

- Expected size: 65,285,832 bytes
- Expected SHA-256: 6380343a0972742c0e06f48ae639b12d3953f790430a7e22d5327899ebbcf924

Linux: `sha256sum "file.nds"`
Windows PowerShell: `Get-FileHash "file.nds" -Algorithm SHA256`
macOS: `shasum -a 256 "file.nds"`

If patching reports a checksum/source error, check the original ROM's hash.
Do not force past checksum errors. An unexpected output hash is not a verified
V0.1 build.

## Included in V0.1

- EX/EP roster extensions using 20 selected Battle Arena character variants.
- EP above DP2, including the remaining four variants and Goku placeholders.
- One EP Goku uses Piccolo ranged/special attacks while retaining Goku's
  character animation; the nine-orb release/seek phase is corrected.
- Beerus' Planet, Hell, Tournament of Power and New Planet Plant in the added
  stage-selection spaces; original stage positions preserved.
- Neko Majin restored to SP with a native-portrait hex icon and corrected
  pixel packing. Shared locked-cell colours are preserved.
- EX/EP labels appear on initial character-selection entry.

## Known limits

- Neko's support selection/icon is verified.
- Goku melee/ability/Team Arts 
  and KI costs remain native; this is not a full Piccolo moveset transplant.
- No exhaustive Story/AI/localization/multiplayer verification.
- Earlier ROM builds and original inputs were not modified by packaging.

See CREDITS.txt for attribution and existing third-party license conditions.
