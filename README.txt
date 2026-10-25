GitHub / jsDelivr package — Deltarune mod v10b

Repository: https://github.com/sektanaymikon/deltarune-flirt-web

1. Create a PUBLIC repository named deltarune-flirt-web under sektanaymikon. Use the main branch.
2. Extract Deltarune-Flirt-Mod-GitHub-jsDelivr.zip on your computer.
3. In the repository, choose Add file > Upload files. Upload ALL files INSIDE the extracted folder directly to the repository root, then Commit changes. Upload the extracted files, not the ZIP and not an extra outer folder. Keep filenames unchanged. No Git LFS is needed.
4. Open Deltarune-Flirt-Mod-CodeHS-jsDelivr-index.txt in Notepad. Copy all its contents into the SAME CodeHS project's index.html, replacing the old code. Save and reload the output.
5. Press Play. The game downloads compressed chunks, checks them, decompresses them, applies the existing Garden compatibility fixes and starts the mod. Save import/export and music fixes remain included.

Upload check: https://cdn.jsdelivr.net/gh/sektanaymikon/deltarune-flirt-web@main/manifest.json
It should display JSON. If GitHub shows the files but the CDN reports missing files, allow time for CDN availability. Do not change the game part names. For future updates, pin launcher and asset URLs to the new Git commit, or use a new release filename to avoid an older cached main-branch file.

Hosting: the launcher, modified game chunks and rebuilt runtime come from your repository through cdn.jsdelivr.net. Existing music/video/helper assets come from ByAlvaro19/deltarune at the pinned revision, also through cdn.jsdelivr.net. No Cloudflare or raw.githubusercontent.com download URLs are used.

The school device must permit cdn.jsdelivr.net and WebAssembly. CDN delivery cannot guarantee access on every managed device. No remote repository has been created or uploaded automatically, and the complete game cannot be checked from your new CDN path until the files are uploaded. Keep using the same CodeHS project and browser to preserve its saved progress. This package contains no supplied save files.

Attribution: mod by DuckRoguer; original game by Toby Fox and contributors; browser runner from ByAlvaro19, with original ports credited to bog. Original asset ownership is unchanged.
