# Anti-GH-Pages-Yank

## GH Pages Yank Issue

This project addresses the issue of GitHub Pages domain yanking due to CNAME corpses.

When GitHub users delete their repositories with a linked custom domain via a CNAME file, the CNAME entry will remain in the registry. This allows any other user on GitHub to then claim the domain that already points towards GitHub Pages.

This project is an attempt to identify all cases of this issue and to notify the domain owners of the potential security risk.
