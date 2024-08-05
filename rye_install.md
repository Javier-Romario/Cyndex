The rye directory /Users/****/.rye/shims was not detected on PATH.
It is highly recommended that you add it.

✔ Should the installer add Rye to PATH via .profile? · no
note: did not manipulate the path. To make it work, add this to your .profile manually:

    source "$HOME/.rye/env"

To make it work with zsh, you might need to add this to your .zprofile:

    source "$HOME/.rye/env"

To make it work with fish, run this once instead:

    set -Ua fish_user_paths "$HOME/.rye/shims"

For more information read https://rye.astral.sh/guide/installation/

All done!
