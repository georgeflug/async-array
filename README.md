# library-starter
Starter Repo for my projects

## Instructions

1. Clone this repo: `git clone git@github.com:georgeflug/async-array.git [new-project-name]`
2. Delete `CHANGELOG.md` and `package-lock.json`
3. Replace all instances of "library-starter" with the new project's name.
4. Update this README.
5. Reset the version in package.json to 1.0.0.
6. Run `npm install`
7. Run `git remote set-url origin git@github.com:georgeflug/${new-project-name}.git`
8. Add NPM_TOKEN variable to the new repo's Secrets settings page.
9. Push changes to Github to publish the first version.

## Bumping the version

The patch version is automatically bumped on every commit. To release a major or
minor version, run the interactive command `npm run release`.
