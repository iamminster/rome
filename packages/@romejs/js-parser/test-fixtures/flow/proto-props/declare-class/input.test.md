# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > proto-props > declare-class`

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
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 103
      line: 12
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FlowDeclareClass {
      id: BindingIdentifier {
        name: 'A'
        loc: Object {
          filename: 'input.js'
          identifierName: 'A'
          end: Object {
            column: 15
            index: 15
            line: 1
          }
          start: Object {
            column: 14
            index: 14
            line: 1
          }
        }
      }
      extends: Array []
      implements: Array []
      mixins: Array []
      typeParameters: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 31
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: FlowObjectTypeAnnotation {
        exact: false
        inexact: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 31
            line: 3
          }
          start: Object {
            column: 16
            index: 16
            line: 1
          }
        }
        properties: Array [
          FlowObjectTypeProperty {
            kind: 'init'
            key: Identifier {
              name: 'proto'
              loc: Object {
                filename: 'input.js'
                identifierName: 'proto'
                end: Object {
                  column: 7
                  index: 25
                  line: 2
                }
                start: Object {
                  column: 2
                  index: 20
                  line: 2
                }
              }
            }
            value: FlowGenericTypeAnnotation {
              id: ReferenceIdentifier {
                name: 'T'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'T'
                  end: Object {
                    column: 10
                    index: 28
                    line: 2
                  }
                  start: Object {
                    column: 9
                    index: 27
                    line: 2
                  }
                }
              }
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 10
                  index: 28
                  line: 2
                }
                start: Object {
                  column: 9
                  index: 27
                  line: 2
                }
              }
            }
            optional: false
            proto: false
            static: false
            variance: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 10
                index: 28
                line: 2
              }
              start: Object {
                column: 2
                index: 20
                line: 2
              }
            }
          }
        ]
      }
    }
    FlowDeclareClass {
      id: BindingIdentifier {
        name: 'B'
        loc: Object {
          filename: 'input.js'
          identifierName: 'B'
          end: Object {
            column: 15
            index: 48
            line: 5
          }
          start: Object {
            column: 14
            index: 47
            line: 5
          }
        }
      }
      extends: Array []
      implements: Array []
      mixins: Array []
      typeParameters: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 66
          line: 7
        }
        start: Object {
          column: 0
          index: 33
          line: 5
        }
      }
      body: FlowObjectTypeAnnotation {
        exact: false
        inexact: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 66
            line: 7
          }
          start: Object {
            column: 16
            index: 49
            line: 5
          }
        }
        properties: Array [
          FlowObjectTypeProperty {
            kind: 'init'
            key: Identifier {
              name: 'x'
              loc: Object {
                filename: 'input.js'
                identifierName: 'x'
                end: Object {
                  column: 9
                  index: 60
                  line: 6
                }
                start: Object {
                  column: 8
                  index: 59
                  line: 6
                }
              }
            }
            value: FlowGenericTypeAnnotation {
              id: ReferenceIdentifier {
                name: 'T'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'T'
                  end: Object {
                    column: 12
                    index: 63
                    line: 6
                  }
                  start: Object {
                    column: 11
                    index: 62
                    line: 6
                  }
                }
              }
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 12
                  index: 63
                  line: 6
                }
                start: Object {
                  column: 11
                  index: 62
                  line: 6
                }
              }
            }
            optional: false
            proto: true
            static: false
            variance: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 12
                index: 63
                line: 6
              }
              start: Object {
                column: 2
                index: 53
                line: 6
              }
            }
          }
        ]
      }
    }
    FlowDeclareClass {
      id: BindingIdentifier {
        name: 'C'
        loc: Object {
          filename: 'input.js'
          identifierName: 'C'
          end: Object {
            column: 15
            index: 83
            line: 9
          }
          start: Object {
            column: 14
            index: 82
            line: 9
          }
        }
      }
      extends: Array []
      implements: Array []
      mixins: Array []
      typeParameters: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 102
          line: 11
        }
        start: Object {
          column: 0
          index: 68
          line: 9
        }
      }
      body: FlowObjectTypeAnnotation {
        exact: false
        inexact: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 102
            line: 11
          }
          start: Object {
            column: 16
            index: 84
            line: 9
          }
        }
        properties: Array [
          FlowObjectTypeProperty {
            kind: 'init'
            key: Identifier {
              name: 'x'
              loc: Object {
                filename: 'input.js'
                identifierName: 'x'
                end: Object {
                  column: 10
                  index: 96
                  line: 10
                }
                start: Object {
                  column: 9
                  index: 95
                  line: 10
                }
              }
            }
            value: FlowGenericTypeAnnotation {
              id: ReferenceIdentifier {
                name: 'T'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'T'
                  end: Object {
                    column: 13
                    index: 99
                    line: 10
                  }
                  start: Object {
                    column: 12
                    index: 98
                    line: 10
                  }
                }
              }
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 13
                  index: 99
                  line: 10
                }
                start: Object {
                  column: 12
                  index: 98
                  line: 10
                }
              }
            }
            optional: false
            proto: true
            static: false
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 13
                index: 99
                line: 10
              }
              start: Object {
                column: 2
                index: 88
                line: 10
              }
            }
            variance: FlowVariance {
              kind: 'plus'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 9
                  index: 95
                  line: 10
                }
                start: Object {
                  column: 8
                  index: 94
                  line: 10
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
