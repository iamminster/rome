# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0220`

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
      index: 50
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Legacy octal literals are not allowed in strict mode'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 39
          index: 39
          line: 1
        }
        start: Object {
          column: 39
          index: 39
          line: 1
        }
      }
    }
  ]
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'hello'
        loc: Object {
          filename: 'input.js'
          identifierName: 'hello'
          end: Object {
            column: 14
            index: 14
            line: 1
          }
          start: Object {
            column: 9
            index: 9
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 49
          index: 49
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        params: Array []
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 16
            index: 16
            line: 1
          }
          start: Object {
            column: 14
            index: 14
            line: 1
          }
        }
      }
      body: BlockStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 49
            index: 49
            line: 1
          }
          start: Object {
            column: 17
            index: 17
            line: 1
          }
        }
        directives: Array [
          Directive {
            value: 'use strict'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 32
                index: 32
                line: 1
              }
              start: Object {
                column: 19
                index: 19
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
                column: 47
                index: 47
                line: 1
              }
              start: Object {
                column: 33
                index: 33
                line: 1
              }
            }
            expression: ObjectExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 45
                  index: 45
                  line: 1
                }
                start: Object {
                  column: 34
                  index: 34
                  line: 1
                }
              }
              properties: Array [
                ObjectProperty {
                  key: StaticPropertyKey {
                    value: NumericLiteral {
                      value: 17
                      format: 'octal'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 39
                          index: 39
                          line: 1
                        }
                        start: Object {
                          column: 36
                          index: 36
                          line: 1
                        }
                      }
                    }
                    variance: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 39
                        index: 39
                        line: 1
                      }
                      start: Object {
                        column: 36
                        index: 36
                        line: 1
                      }
                    }
                  }
                  value: NumericLiteral {
                    value: 42
                    format: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 43
                        index: 43
                        line: 1
                      }
                      start: Object {
                        column: 41
                        index: 41
                        line: 1
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 43
                      index: 43
                      line: 1
                    }
                    start: Object {
                      column: 36
                      index: 36
                      line: 1
                    }
                  }
                }
              ]
            }
          }
        ]
      }
    }
  ]
}
```
