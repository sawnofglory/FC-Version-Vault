<p align="center"><img src="icon.png" width="120" alt="FC Version Vault icon"></p>

# FC Version Vault

**Back up your EA SPORTS FC 27 version, and switch back to it after a title update.**

By SAWNOFGLORY. Free. Windows 10 and 11. Only supports FC 27 for now.

## Download

Go to **[Releases](../../releases/latest)** and download one of these:

| File | What it is |
| --- | --- |
| `FC-Version-Vault-Setup.exe` | The installer. Adds shortcuts and shows up in Windows' "Installed apps". **Most people want this one.** |
| `FC-Version-Vault.exe` | The same app without installing. Just run it. |

Windows may show a blue box that says **"Windows protected your PC"**. That happens because the app is new and does not have a paid code-signing certificate. If you downloaded it from this page, click **More info**, then **Run anyway**. You can check your download against `SHA256.txt` on the release page first.

## What it does

- Shows your **current version** of FC 27 next to the **latest version**.
- **Backs up** the version you have now (your own game files), so you can come back to it after EA updates the game.
- **Switches** to any version you have a backup or zip of.
- **Undo** puts your own version back exactly as it was.
- 13 languages.
- Squad files and Compdata tabs: coming soon.

Works with EA app and Steam installs.

## What it does not do

- It does **not** contain or download any game files. Backups are copies of **your own** files, kept on **your** PC. Do not share them.
- It does not collect or send any of your data. The only thing it does online is ask this GitHub page whether a newer version of the app exists.

## How it keeps you safe

- Nothing of yours is deleted when you switch. Your files are moved aside so Undo can put them back.
- A zip that tries to write files outside the game folder is refused.
- After a switch, every program file that came from a zip must be digitally signed by Electronic Arts. If one is not, the app undoes the switch by itself.
- App updates are only accepted if they carry the author's digital signature. Nothing is downloaded until you click **Update**.
- It does not ask for administrator rights unless Windows blocks the game folder, and then it asks you first.

## Good to know

- Turn off automatic updates for FC 27 in EA app or Steam, or the game may update itself again.
- Online modes will probably not work on an older version. Offline Career Mode is the intended use.
- The translations were written by an AI. Corrections are welcome.

## Feedback

Send feedback and ideas to **@sawnofgod** on Discord, or open an Issue here.

## Licence and legal

Free to use and share unchanged. Not open source. See [LICENCE.txt](LICENCE.txt).

FC Version Vault is a fan-made tool. It is not affiliated with or endorsed by Electronic Arts. EA SPORTS FC is a trademark of Electronic Arts Inc.
