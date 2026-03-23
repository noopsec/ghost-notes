# GhostNotes

GhostNotes is an offline desktop notes app for Windows built around encrypted `.ghostnote` files, local vault protection, and detachable sticky-note presentation.

It is designed for people who want:

- local-first notes with no cloud dependency
- password-locked vault access
- encrypted note export/import
- desktop sticky-note projection without turning the sticky into the source file
- snapshots, backups, and diagnostics in one desktop tool

## What GhostNotes Does

- Stores notes as encrypted `.ghostnote` containers
- Locks the local vault with a user-set password
- Lets you export a note as a password-protected `.ghostnote` file
- Lets another user drag and drop that file into GhostNotes and unlock it with the shared password
- Keeps sticky notes as a secondary presentation layer, not the canonical note
- Supports snapshots, encrypted backups, local defaults, and diagnostics

## Install

1. Download `GhostNotes-Setup.exe` from the GitHub Release.
2. Run the installer.
3. Choose the install location and whether to create a desktop shortcut.
4. Launch GhostNotes.
5. On first run, create your local vault password.

## First Run

On first launch, GhostNotes asks you to create a vault password.

- That password is used locally to unlock your vault
- Notes stay on the device
- No account, licence key, or online activation is required

### Write Notes

- Create a normal note or a sticky-enabled note
- Write in the main editor
- Switch between muted navy and white page modes

### Use Sticky Notes

- Enable sticky mode for a note
- Pin it to the desktop from the sticky drawer
- The sticky is only a live projection of the source note
- The encrypted source note remains the canonical file

### Share a Protected Note

1. Export a note as `.ghostnote`
2. Set a share password for that exported note
3. Send the file to another GhostNotes user
4. They drag it into GhostNotes or import it from the app
5. They enter the password
6. GhostNotes decrypts it and re-encrypts it into their local vault

## Privacy And Storage

GhostNotes is local-first by design.

- No cloud sync
- No server dependency
- No web account required
- Canonical notes stay encrypted on disk

Typical Windows storage location:

- `%APPDATA%\GhostNotes\vault`

Inside the vault, GhostNotes manages:

- encrypted note files
- snapshot files
- backup files
- sticky assets such as imported backgrounds

## Features

- Offline desktop note vault
- Encrypted `.ghostnote` storage
- Local vault password lock
- Password-protected `.ghostnote` sharing
- Drag-and-drop note import
- Detached desktop sticky-note windows
- Snapshot history
- Encrypted vault backups
- Settings and diagnostics
- Custom branded Windows installer

## License

Copyright Opsec Services LTD.
