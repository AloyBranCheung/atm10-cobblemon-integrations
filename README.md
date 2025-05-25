# ATM10 w/ Cobblemon :D

Base:

- All The Mods 10
- MC - 1.21.1
- Neoforge - 21.1.172

## Users

- Download the curseforge-profile.zip
- Go to the curseforge client > minecraft > `My Modpacks`
- Under `My Modpacks` there should be an `Import` option
- Click `Import` and select `Import profile .zip`
- Select the `curseforge-profile.zip` you just downloaded

### Customizing Your Profile

You can customize your profile (e.g. the name and ram allocation) by right-clicking your profile and clicking `Profile Options`.

## Developers

### Getting Started

- Download the repo
- Make sure to have `git lfs` installed
- Then run `git lfs install`
- `git lfs pull origin`
- `git lfs ls-files` to check

### Adding/Removing Mods for this repo

1. Unzip `mods.zip` to `mods/` and `server.zip` to `server/` e.g. `unzip mods.zip -d mods`
2. Add/remove mods to the new mods/server folders
   - The mods folder used to track 'override/non-modpack' mods, e.g. cobblemon
   - These mods will also need to be in the `server/mods` folder such that the client and servers have the same mods
3. Rezip, commit and push to repo

#### Updating Curseforge Profile

1. Install ATM10 modpack (check start of readme file for mc and neoforge versions). This will be the `Master` profile.
> [!Caution]
> Don't run this master profile as it will create starter files.
2. Copy the extra mods to the 'Master' profile and then export and select all files from that profile to export
3. Commit and upload the new profile to the repo
4. Ask users to update their local profiles from `mods.zip` or re-import new profile (not tested if this will keep users progress on server but should since it is tracked by unique names)
