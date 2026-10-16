# iOS Simulator Apps

The shared list of apps shown in the App Store of the [iOS Simulator](https://github.com/chrisdlb1/iOS-Simulator).

`apps.json` is fetched by the simulator. Each entry is either a GitHub repository of an app (`{ "repo": "owner/name" }`, optionally `"featured": true`)
or a built-in app of the simulator (`"builtin"`). The name, icon, description and version of a repository's app come from the repository itself
(`iphone-app.json` and its latest release), so an entry never needs updating when an app is.

## Submit an app

[Open a submission](../../issues/new?template=submit-app.yml). Your repository needs an `iphone-app.json` file and a published release.
Instructions are in the simulator: Settings > Store > Instructions.

Accepted apps are added to `apps.json`.
