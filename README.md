# ATM10 w/ Cobblemon :D

## Getting Started

- Make sure to have `git lfs` installed
- Then run `git lfs install`
- `git lfs pull origin`
- `git lfs ls-files` to check

## Adding/Removing Mods for this repo

1. unzip `mods.zip` to `mods/` and `server.zip` to `server/` e.g. `unzip mods.zip -d mods`
2. add/remove mods to the new mods/server folders (mods folder used to track 'override' mods e.g. cobblemon and need the same mods in server)
3. rezip, commit and push to repo

### Updating Curseforge Profile

1. Copy the extra mods to the 'Master' profile and then export all files from that profile
2. Commit and upload the new profile to the repo
3. Ask users to update their local profiles or re-import new profile (not tested if this will keep users progress on server but should since it is tracked by unique names)
