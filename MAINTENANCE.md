# MD Favorites Maintenance

MD Favorites is a Marcus Dilectite maintained build of the upstream Favorites plugin by Kyle Phillips.

## Source

- Upstream repository: https://github.com/kylephillips/favorites
- MD repository: https://github.com/Markus-Dilectite/md-favorites
- Security patch base commit: `bfa87ad0c219f60c87d727a3f9585e697dec72c9`

## Current Build

- Plugin name: MD Favorites
- Version: `2.3.6-md.1`
- WordPress plugin folder: `md-favorites`
- Composer autoload files are committed so the plugin can run on shared hosting without Composer installed.

## Staging Checks

1. Install from the MD repository using the GitHub deployer.
2. Activate MD Favorites.
3. Confirm the plugin settings screen loads.
4. Save settings and confirm existing settings are not erased.
5. Disable anonymous favorites and confirm anonymous clicks redirect to login or registration.
6. Confirm logged-in users can favorite and unfavorite posts.
7. Confirm no PHP fatal errors appear in logs.

