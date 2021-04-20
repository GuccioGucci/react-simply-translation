## Release

```sh

npm version -h

# npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease [--preid=<prerelease-id>] | from-git]
# (run in package dir)
# 'npm -v' or 'npm --version' to print npm version (6.14.6)
# 'npm view <pkg> version' to view a package's published version
# 'npm ls' to inspect current package/dependency versions

# Creates a new version by incrementing the major, minor, or patch number of the current version.
npm version [major | minor | patch]

# Creates a new prerelease version by incrementing the major, minor, or patch number of the current version and adding a prerelease number.
npm version [major | minor | patch] --preid beta

# Push branch and tags
git push origin main --follow-tags
```