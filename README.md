TO DO
=====

- Copy user data (flatpak installation)


NOTES
=====

## archive

Install with archive works well with auto-updating software

## flatpak

On flathub currently the only available release branch is ESR.
But Thunderbird has announced to change this: https://connect.mozilla.org/t5/ideas/add-thunderbird-release-branch-to-flathub-and-snap/idi-p/98257

HOW TO
======

## Migrate from pre-exisiting non-flatpak installations:

- `cp -r ~/.thunderbird ~/.var/app/org.mozilla.Thunderbird/`
- In case Thunderbird opens a new profile instead of the existing one, run:  
- `flatpak run org.mozilla.Thunderbird -P`
- then select the right profile and tick "_Use the selected profile without asking on startup_" box.
