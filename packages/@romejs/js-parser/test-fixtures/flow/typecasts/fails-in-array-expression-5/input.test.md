# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > typecasts > fails-in-array-expression-5`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 25
      index: 25
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
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'The type cast expression is expected to be wrapped with parentheses'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 21
          index: 21
          line: 1
        }
        start: Object {
          column: 12
          index: 12
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
          column: 25
          index: 25
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: CallExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 24
            index: 24
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        callee: ReferenceIdentifier {
          name: 'async'
          loc: Object {
            filename: 'input.js'
            identifierName: 'async'
            end: Object {
              column: 5
              index: 5
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
        }
        arguments: Array [
          ArrayExpression {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 23
                index: 23
                line: 1
              }
              start: Object {
                column: 7
                index: 7
                line: 1
              }
            }
            elements: Array [
              ReferenceIdentifier {
                name: 'a'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'a'
                  end: Object {
                    column: 9
                    index: 9
                    line: 1
                  }
                  start: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                }
              }
              ArrayExpression {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 22
                    index: 22
                    line: 1
                  }
                  start: Object {
                    column: 11
                    index: 11
                    line: 1
                  }
                }
                elements: Array [
                  FlowTypeCastExpression {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 21
                        index: 21
                        line: 1
                      }
                      start: Object {
                        column: 12
                        index: 12
                        line: 1
                      }
                    }
                    typeAnnotation: StringKeywordTypeAnnotation {
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 21
                          index: 21
                          line: 1
                        }
                        start: Object {
                          column: 15
                          index: 15
                          line: 1
                        }
                      }
                    }
                    expression: ReferenceIdentifier {
                      name: 'b'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'b'
                        end: Object {
                          column: 13
                          index: 13
                          line: 1
                        }
                        start: Object {
                          column: 12
                          index: 12
                          line: 1
                        }
                      }
                    }
                  }
                ]
              }
            ]
          }
        ]
      }
    }
  ]
}
```
