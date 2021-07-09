# aludo

With a focus on sets of categorical hints (aludo), check if a system might have incremental changes, since the last run, in the form of clues (indico). If so, trigger data collection (supportconfig) along with the captured clue metadata for further analysis.

## Usage

From this source code repo:
- git clone "this repo"
- cd aludo
- sudo ./bin/aludo
  - then review the cited Log/Report (and the collected data bundle)

Or for packaged-based (RPM) for openSUSE/SUSE, see [OBS](https://build.opensuse.org/package/show/home:bwgartner:SCA/aludo)
- this has suggested package dependencies
  - supportutils
  - btrfsprogs snapper
  - systemd
- provides systemd.timers for regular runs (still need to be systemctl enabled)

