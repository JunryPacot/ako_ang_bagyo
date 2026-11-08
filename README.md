# Ako ang Bagyo

A fullscreen animated lyrics backdrop made with Python and Tkinter.

## Requirements

- Python 3.13 or newer
- Windows 10/11
- A song file named `ako_ang_bagyo.mp3` in the same folder as this project

## Project Files

- `ako_ang_bagyo.py` - main animation script
- `ako_ang_bagyo.mp3` - background music file
- `README.md` - setup instructions

## Setup

1. Install Python from the official site:
   https://www.python.org/downloads/windows/

2. Make sure Python is added to PATH during installation.

3. Open PowerShell in the project folder:

   ```powershell
   cd "C:\Users\Administrator\OneDrive\Desktop\akoangbagyo"
   ```

4. Confirm Python is installed:

   ```powershell
   python --version
   ```

5. Install the required audio library for MP3 playback:

   ```powershell
   python -m pip install pygame
   ```

6. Place your background music file in the same folder and name it exactly:

   ```text
   ako_ang_bagyo.mp3
   ```

## Run the app

From the project folder, run:

```powershell
python .\ako_ang_bagyo.py
```

If PowerShell does not run it directly, use:

```powershell
.\ako_ang_bagyo.py
```

## Notes

- The script plays the MP3 once when it starts.
- Press `Esc` to close the animation window.
- This project uses Tkinter for the visual effects and `pygame` for audio playback.

## GitHub Upload

After setup, you can push the project to GitHub using:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/JunryPacot/ako_ang_bagyo
git push -u origin main
```

## Troubleshooting

### Python command not found

Try:

```powershell
py --version
```

If that works, run:

```powershell
py .\ako_ang_bagyo.py
```

### `pygame` install fails

Use a Python version compatible with your environment, usually Python 3.13 is supported for this setup.

### No sound plays

Make sure:
- the file is named exactly `ako_ang_bagyo.mp3`
- the file is in the same folder as the script
- the file is not corrupted

## License

This project is for personal use and educational purposes unless otherwise specified.
