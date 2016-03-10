# Dokku revision info

Revision information in your Dokku environment.

## Requirements

* Dokku 0.4.0+

## Installation

```
dokku plugin:install https://github.com/leominov/dokku-revision-info.git dokku-revision-info
```

## Variables

* `REVISION_INFO`
* `REVISION_BRANCH`
* `REVISION_AUTHOR`
* `REVISION_HASH`
* `REVISION_DATE`
* `REVISION_BUILD_DATE`

## Hooks

This plugin provides hooks:

* `post-release-buildpack`
* `post-release-dockerfile`

## Thanks

* cjblomqvist for plugin idea (https://github.com/cjblomqvist).
