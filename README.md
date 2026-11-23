[README (5).md](https://github.com/user-attachments/files/35297087/README.5.md)
# CBL Acoustic Logging Animator

S. Siddhu | SOGE | Central

Single-file HTML training aid showing how a conventional cement bond log (CBL) and variable density log (VDL) are acquired and built.

## Run
Open `CBL_Acoustic_Logging_Animator.html` in Chrome or Edge. It works offline with nothing to install. Press F11 for full screen.

## Quick start
1. Click **Auto run**: the tool runs in hole, stops on bottom, then logs up.
2. For slow motion, click **Ray path**, tick **Stop at each stage**, and use **Step** to move through one firing.
3. Pause, then click any logged depth to inspect its waveforms.
4. To change the job, edit the **Logging program** row (log top and bottom, TOC, float collar, TD) and click **Apply & reset**.

## Model basis
- Slownesses from the FEU deck: steel 57, cement 75, fluid 189 µs/ft.
- Receivers at 3 ft (CBL) and 5 ft (VDL). Tool OD selectable (1-11/16" to 3-5/8"; sizes too large for the casing are disabled).
- Free-pipe amplitude and TT come from the FEU deck table. The model TT uses head-wave geometry plus a 48 µs delay.
- Gate opens at TT − 10 µs and is 36 µs wide; TT threshold is 1 mV.
- Attenuation and the bond profile are illustrative, so read the amplitudes qualitatively.

## Files
- `CBL_Acoustic_Logging_Animator.html`: the animator
- `CBL_Animator_User_Manual.docx`: the full user manual

## Roadmap
USIT and CAST-V ultrasonic tools (already listed in the Logging tool drop-down, disabled for now).
