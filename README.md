# google-chips
This library is a fork of the Google Chips library:
<https://android.googlesource.com/platform/frameworks/opt/chips/>.

Current fork is based on branch `nougat-mr2.1-release`.

### Modifications

Most changes of this library are meant to expose class members and methods to child classes.
Localization string files have also been removed to reduce space.

### Updating

One way to update this library would be to rebase the `add ci mods` commit onto the
latest branch from the original repo.
