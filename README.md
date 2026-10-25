# Argus OS apt channel

Signed apt repository for the Argus OS desktop packages. It holds binaries only: each suite is a GitHub Release (`apt-stable`, `apt-dev`) whose assets are the .debs plus `Packages`, `Release`, `InRelease` and `Release.gpg`.

Installed Argus systems use it through `/etc/apt/sources.list.d/argus.sources` (package `argus-archive-keyring`). The indexes are signed with the Argus archive key, fingerprint `66041183D27F1493F70B7C912A53C61FB830878C`.
