# cordova-plugin-file-transfer (fork)

This is a fork of `cordova-plugin-file-transfer` by [Moodle HQ](https://moodle.com/). If you are looking for the documentation, you can read the original at [apache/cordova-plugin-file-transfer](https://github.com/apache/cordova-plugin-file-transfer).

## Modifications from the original

We created this fork for [our mobile application](https://github.com/moodlehq/moodleapp) because there are some commits in the development branch that haven't been released. So this package doesn't have any extra modifications (other than name and version). This package was forked from commit [648b577](https://github.com/apache/cordova-plugin-file-transfer/commit/648b57792f2f33ffc9da6d2fa020d26a48799048).

## Installation

You can install this package using the [original installation instructions](https://github.com/apache/cordova-plugin-file-transfer#installation), but installing this package instead:

```sh
cordova plugin add @moodlehq/cordova-plugin-file-transfer@1.7.1-moodle.1
```

Depending on your cordova version, this command will add the plugin to your package.json as `cordova-plugin-file-transfer` (for example, under `cordova.plugins`). In that case, you also need to add `@moodlehq/cordova-plugin-file-transfer` so that the project restores the fork properly in other machines. Make sure that it is listed before the unscoped plugin name.
