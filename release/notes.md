**Important fix. Please update.**

This fixes a bug that could happen when EA app (or Steam) **updated the game after you used Switch**:

- The app kept showing the version you switched to, not the version EA app had just installed.
- Clicking **Undo** then stopped half way and left the game without its program files.
- After that, the app could not find the game any more.

**If this happened to you: your files were not deleted.** They are in the `_VersionVault_Undo` and `_VersionVault_Leftovers` folders inside your game folder. Update to this version, open it, and click **Undo**. It puts every file back. Do not delete those two folders first.

**What changed**

- "Current version" now always reads the game's own version file.
- Undo now either finishes or changes nothing. It checks first that no other program is using the files, and if a move still fails it reverses the moves it made.
- If the game was updated after a switch, the app says so and shows **Finish**. That only tidies the files saved for Undo. Your updated game is not touched.
- Clean up is switched off while an Undo is unfinished.

Tip: turn off automatic updates for FC 27 in EA app or Steam while you are on an older version.

Open the app and click **Update** on the yellow strip. New here? Download `FC-Version-Vault-Setup.exe`.

Not affiliated with or endorsed by Electronic Arts.
