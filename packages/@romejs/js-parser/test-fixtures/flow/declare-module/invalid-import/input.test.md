# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > declare-module > invalid-import`

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
      column: 0
      index: 43
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Imports within a `declare module` body must always be `import type` or `import typeof`'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 20
          index: 20
          line: 1
        }
        start: Object {
          column: 21
          index: 21
          line: 1
        }
      }
    }
  ]
  body: Array [
    FlowDeclareModule {
      id: StringLiteral {
        value: 'M'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 18
            index: 18
            line: 1
          }
          start: Object {
            column: 15
            index: 15
            line: 1
          }
        }
      }
      kind: 'commonjs'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 42
          index: 42
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 42
            index: 42
            line: 1
          }
          start: Object {
            column: 19
            index: 19
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
                column: 40
                index: 40
                line: 1
              }
              start: Object {
                column: 21
                index: 21
                line: 1
              }
            }
            source: StringLiteral {
              value: 'TM'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 39
                  index: 39
                  line: 1
                }
                start: Object {
                  column: 35
                  index: 35
                  line: 1
                }
              }
            }
            defaultSpecifier: ImportDefaultSpecifier {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 29
                  index: 29
                  line: 1
                }
                start: Object {
                  column: 21
                  index: 21
                  line: 1
                }
              }
              local: ImportSpecifierLocal {
                name: BindingIdentifier {
                  name: 'T'
                  loc: Object {
                    filename: 'input.js'
                    identifierName: 'T'
                    end: Object {
                      column: 29
                      index: 29
                      line: 1
                    }
                    start: Object {
                      column: 28
                      index: 28
                      line: 1
                    }
                  }
                }
                importKind: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 29
                    index: 29
                    line: 1
                  }
                  start: Object {
                    column: 28
                    index: 28
                    line: 1
                  }
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
