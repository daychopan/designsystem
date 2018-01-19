# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

<a name="2.0.1"></a>
## [2.0.1](***REMOVED***) (2018-01-18)




**Note:** Version bump only for package ffe-file-upload-react

<a name="2.0.0"></a>

# 2.0.0 (2018-01-12)

### Chores

* **ffe-file-upload-react:** Moving in ([9fb27cd](***REMOVED***))

### BREAKING CHANGES

* **ffe-file-upload-react:** Requires React 16.2 or newer

With this ffe-file-upload-react is moved to the monorepo. A breaking
change is introduced to remove support for React 15. The upgrade should
be a drop-in upgrade for users of React 16.2 or newer.

## v1.2.0

* aria-label is now set by label

## v1.1.0

* Moved clearing of input to enable multiple upload
* Adding success and info message support
* Adding support for multiple error messages

## v1.0.1

* Fixed bug where file input element was not cleared after each upload(causing sequential upload of files with same filename to not perform onChange and therefore no upload)

## v1.0.0

* Initial version