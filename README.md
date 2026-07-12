# homebrew-devforgekit

The official Homebrew tap for [DevForgeKit](https://github.com/NouradinAbdurahman/DevForgeKit) - a local-first development environment and workstation lifecycle manager.

## Install

```bash
brew tap NouradinAbdurahman/devforgekit
brew install devforgekit
devforgekit install
```

## What this installs

Just the `devforgekit` command itself (the launcher, its Node CLI, and the bash scripts/registry/templates it dispatches to) - not any of the toolchains it can go on to provision. Run `devforgekit install` afterward for that; see the [main repository](https://github.com/NouradinAbdurahman/DevForgeKit) for details.

## Formula source

The formula lives at [`Formula/devforgekit.rb`](Formula/devforgekit.rb) in this repo, mirrored from the main repository's own copy at [`Formula/devforgekit.rb`](https://github.com/NouradinAbdurahman/DevForgeKit/blob/main/Formula/devforgekit.rb) - see that file's own comments for the update flow.
