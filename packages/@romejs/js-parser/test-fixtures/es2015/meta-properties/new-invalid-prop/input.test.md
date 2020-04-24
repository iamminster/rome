# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > meta-properties > new-invalid-prop`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 8
      index: 8
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'The only valid meta property for new is new.target'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 8
          index: 8
          line: 1
        }
        start: Object {
          column: 4
          index: 4
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 8
          index: 8
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: MetaProperty {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 8
            index: 8
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        meta: Identifier {
          name: 'new'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 3
              index: 3
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
        }
        property: Identifier {
          name: 'prop'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 8
              index: 8
              line: 1
            }
            start: Object {
              column: 4
              index: 4
              line: 1
            }
          }
        }
      }
    }
  ]
}
```