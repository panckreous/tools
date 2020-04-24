# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 40`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
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
      column: 40
      index: 40
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 40
          index: 40
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 40
            index: 40
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'a'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 40
                  index: 40
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
              meta: PatternMeta {
                definite: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 40
                    index: 40
                    line: 1
                  }
                  start: Object {
                    column: 4
                    index: 4
                    line: 1
                  }
                }
                typeAnnotation: FlowObjectTypeAnnotation {
                  exact: false
                  inexact: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 40
                      index: 40
                      line: 1
                    }
                    start: Object {
                      column: 7
                      index: 7
                      line: 1
                    }
                  }
                  properties: Array [
                    FlowObjectTypeProperty {
                      kind: 'init'
                      key: Identifier {
                        name: 'param1'
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 14
                            index: 14
                            line: 1
                          }
                          start: Object {
                            column: 8
                            index: 8
                            line: 1
                          }
                        }
                      }
                      value: NumberKeywordTypeAnnotation {
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 22
                            index: 22
                            line: 1
                          }
                          start: Object {
                            column: 16
                            index: 16
                            line: 1
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
                          column: 22
                          index: 22
                          line: 1
                        }
                        start: Object {
                          column: 8
                          index: 8
                          line: 1
                        }
                      }
                    }
                    FlowObjectTypeProperty {
                      kind: 'init'
                      key: Identifier {
                        name: 'param2'
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 30
                            index: 30
                            line: 1
                          }
                          start: Object {
                            column: 24
                            index: 24
                            line: 1
                          }
                        }
                      }
                      value: StringKeywordTypeAnnotation {
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 39
                            index: 39
                            line: 1
                          }
                          start: Object {
                            column: 33
                            index: 33
                            line: 1
                          }
                        }
                      }
                      optional: true
                      proto: false
                      static: false
                      variance: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 39
                          index: 39
                          line: 1
                        }
                        start: Object {
                          column: 24
                          index: 24
                          line: 1
                        }
                      }
                    }
                  ]
                }
              }
            }
            init: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 40
                index: 40
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
      }
    }
  ]
}
```