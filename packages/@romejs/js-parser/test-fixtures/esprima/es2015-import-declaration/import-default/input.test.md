# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-import-declaration > import-default`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 23
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ImportDeclaration {
      importKind: undefined
      namedSpecifiers: Array []
      namespaceSpecifier: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 22
          index: 22
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      source: StringLiteral {
        value: 'foo'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 21
            index: 21
            line: 1
          }
          start: Object {
            column: 16
            index: 16
            line: 1
          }
        }
      }
      defaultSpecifier: ImportDefaultSpecifier {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 10
            index: 10
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        local: ImportSpecifierLocal {
          name: BindingIdentifier {
            name: 'foo'
            loc: Object {
              filename: 'input.js'
              identifierName: 'foo'
              end: Object {
                column: 10
                index: 10
                line: 1
              }
              start: Object {
                column: 7
                index: 7
                line: 1
              }
            }
          }
          importKind: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 10
              index: 10
              line: 1
            }
            start: Object {
              column: 7
              index: 7
              line: 1
            }
          }
        }
      }
    }
  ]
}
```
