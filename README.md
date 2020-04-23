# scratch-vscode

This repository contains my Visual Studio Code workspace files for Scratch 3.0 repositories. I use this repository to
track my own configuration settings, but maybe over time this can become useful to other Scratch contributors. If
that's you: feel free to try it out, and file a pull request if you think you can make it better! :)

Thanks, and enjoy!

## Structure

The Scratch 3.0 repositories are assumed to be siblings to this one, for example:

```sh
$ cd somewhere/
$ ls -1
scratch-desktop
scratch-gui
scratch-link
scratch-vm
scratch-vscode # <-- this repository
scratch-www
```

In general the workspaces in this repository are [multi-root
workspaces](https://code.visualstudio.com/docs/editor/multi-root-workspaces) and assume that you have all relevant
workspaces cloned locally. Even workspaces containing only one repository are set up in the multi-root style for
consistency and to keep VS Code files out of those repositories.

## Workspaces

### Workspace `scratch-vscode`

This workspace is for working on the `scratch-vscode` repository itself, including this `README.md` file.

Contents:

- scratch-vscode

### Workspace `scratch-www`

This workspace is for working on the Scratch web site, including the Scratch editor. This is sort of the "everything"
workspace for Scratch work, though it excludes `scratch-desktop` and `scratch-link`.

Contents:

- scratch-www
- eslint-config-scratch
- paper.js
  - This is expected to be the LLK fork or a derivative
- scratch-audio
- scratch-blocks
- scratch-gui
- scratch-l10n
- scratch-paint
- scratch-render
- scratch-render-fonts
- scratch-storage
- scratch-svg-renderer
- scratch-vm

## Repositories

This is the list of repositories currently covered by these workspaces:

- eslint-config-scratch
- paper.js
- scratch-audio
- scratch-blocks
- scratch-gui
- scratch-l10n
- scratch-paint
- scratch-render
- scratch-render-fonts
- scratch-storage
- scratch-svg-renderer
- scratch-vm
- scratch-vscode
- scratch-www
