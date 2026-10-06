# RiffForge

Procedural guitar riff and solo generator: plucked-string guitar sound (clean, acoustic, metal), text-to-solo, a style model you can train on your own MIDI files, and export to MIDI, GP3 (Ample Guitar) and Guitar Pro 7/8.

## Run
    npm install
    npm start

## Build installers
    npm run dist

Or push to GitHub: the **Build** workflow makes Windows, macOS and Linux installers on every push to `main` (download them from the run's Artifacts). Push a tag such as `v1.0.0` to attach them to a GitHub Release.

## Upload to GitHub
    git init && git add . && git commit -m "RiffForge"
    git branch -M main
    git remote add origin https://github.com/YOUR-USER/riffforge.git
    git push -u origin main
    git tag v1.0.0 && git push origin v1.0.0

macOS builds are unsigned: right-click, Open on first launch.
