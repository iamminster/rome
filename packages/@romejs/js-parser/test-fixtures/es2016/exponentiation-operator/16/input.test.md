# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2016 > exponentiation-operator > 16`

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
      column: 0
      index: 11
      line: 2
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
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Illegal expression. Wrap left hand side or entire exponentiation in parentheses.'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 3
          index: 3
          line: 1
        }
        start: Object {
          column: 2
          index: 2
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
      expression: BinaryExpression {
        operator: '**'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 8
            index: 8
            line: 1
          }
          start: Object {
            column: 1
            index: 1
            line: 1
          }
        }
        right: NumericLiteral {
          value: 6
          format: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 8
              index: 8
              line: 1
            }
            start: Object {
              column: 7
              index: 7
              line: 1
            }
          }
        }
        left: UnaryExpression {
          operator: '-'
          prefix: true
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 3
              index: 3
              line: 1
            }
            start: Object {
              column: 1
              index: 1
              line: 1
            }
          }
          argument: NumericLiteral {
            value: 5
            format: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 3
                index: 3
                line: 1
              }
              start: Object {
                column: 2
                index: 2
                line: 1
              }
            }
          }
        }
      }
    }
  ]
}
```
