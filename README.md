# apostrophecms-vs-snippets README

## Features

A snippet library for ApostropheCMS development.

### Template Snippets
- `apos.area`
- `apos.singleton`
- `apos.log`

### Schemas
#### Further Reading: [http://apostrophecms.org/docs/tutorials/getting-started/schema-guide.html](http://apostrophecms.org/docs/tutorials/getting-started/schema-guide.html)

- `apos.schema.area`
- `apos.schema.singleton`

- `apos.schema.field` - generic field
- `apos.schema.string`
- `apos.schema.integer`
- `apos.schema.url`
- `apos.schema.password` - password text field
- `apos.schema.float`
- `apos.schema.slug`
- `apos.schema.tags`
- `apos.schema.textarea`
- `apos.schema.attachment`
- `apos.schema.video`
- `apos.schema.time`
- `apos.schema.date`
- `apos.schema.boolean`
- `apos.schema.select`
- `apos.schema.select.choice` - individual choice object
- `apos.schema.checkboxes`

- `apos.schema.array` - array field
- `apos.schema.joinByOne` - join to a single piece
- `apos.schema.joinByArray` - join to an array of pieces
- `apos.schema.joinByOneReverse` - other end of a joinByOne
- `apos.schema.joinByArrayReverse` - other end of a joinByArray

### Misc
- `apos.self.find` - Fetch a cursor from within a module that extends apostrophe-pieces
- `apos.docs.find` - Fetch a cursor from within a module outside of the one you are currently in
- `apos.piece` - A piece defition

## Requirements

ApostropheCMS

### 1.4.0

Start