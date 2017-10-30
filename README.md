# Release Notes Schema

[![Subscribe to Release Notes](https://release-notes.com/badges/v1.svg)](https://release-notes.com/@release-notes/release-notes-schema)

# About

The goal of this repository is to implement [JSON Schema Definitions](https://trac.tools.ietf.org/html/draft-wright-json-schema-validation-01)
of the [Release Notes Specification](https://github.com/release-notes/release-notes-spec).

The following schemas are defined:

* [ReleaseNotes](definitions/release-notes.json)
* [Release](definitions/release.json)
* [ModificationList](definitions/modification-list.json)
* [Modification](definitions/modification.json)
* [TagList](definitions/tag-list.json)
* [Tag](definitions/tag.json)

## Installation

`$ npm i -S @release-notes/schema`

## Usage

```js
const ReleaseNotesSchema = require('@release-notes/schema');

console.info(
  'Required fields of release notes: %s',
  ReleaseNotesSchema.ReleaseNotes.required.join(', ')
);
```

---

### LICENSE

The files in this archive are released under MIT license.
You can find a copy of this license in [LICENSE](LICENSE).

