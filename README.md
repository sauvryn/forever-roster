# Forever Roster

A phone-friendly tracker for World of Warcraft: Forever characters: professions, equipment, and side-by-side comparison.

## Put it on GitHub Pages

1. Create a new **public** repository and upload everything in this folder, keeping the folder layout
   (`index.html`, `characters.txt`, `data/`, `.github/workflows/sync.yml`).
2. Repository **Settings → Pages**: under "Build and deployment" choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Repository **Settings → Actions → General → Workflow permissions**: choose **Read and write permissions**.
4. Open `https://<your-username>.github.io/<repo-name>/` on your phone.

## Adding characters

- **Automatic:** add the character's Armory link as a new line in `characters.txt`. The sync job runs when that file
  changes, every 6 hours, and whenever you press **Actions → Sync Armory data → Run workflow**. Then tap **Sync all** in the app.
- **In the app:** tap **+ Add**. If the character is not in the repo's data yet, the app offers a copy-and-paste import,
  or you can enter everything by hand.

Edits made in the app (and notes) live in that browser only. Use **Backup → Export** to move them between devices.
A sync replaces a character's professions and equipment with what the Armory shows; notes are kept.

Fan-made. Not affiliated with Blizzard Entertainment.
