# action-prepare-release

Common release prep action for Sentry projects, wrapping [Craft](https://github.com/getsentry/craft).

## Publishing

To release a new version of this action:

```terminal
git checkout main
git pull
git tag -f v1
git tag -f v1.5
git tag -f v1.5.2
git push --tags -f
```

Make sure to update major, minor and patch versions accordingly.

After tagging, [create a new release](https://github.com/getsentry/action-prepare-release/releases/new) with the title and tag in `v1.5.2` format and appropriate changelog.
All checkboxes should be left unchecked and no additional files should be attached.
