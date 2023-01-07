# fud-project
Uniform Project Settings

This project is a simple shim to generate editor specific configurations from a single json configuration. I use a combination of Nova, atom, vscode, and other editors/IDEs and while I always have a preference, I don't have strong opinions unless an editor is set to rewrite on save (looking at you vscode). At the same time I've notice a number of "node" projects that are essentially broken under node and only run using the editor setting specified in the project. You may even get these broken tooling generated PRs, and wonder it's all about.

This is designed for the project maintainer to facilitate delivery from developers with a wide array of contribution preferences, without forcing the maintainer into syncing a bunch of proprietary editor settings. instead you just generate the config for your tool and get working.
