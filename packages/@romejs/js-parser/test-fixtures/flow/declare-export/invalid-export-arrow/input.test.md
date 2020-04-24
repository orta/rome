# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > declare-export > invalid-export-arrow`

```javascript
Program {
  comments: Array []
  corrupt: true
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
      index: 36
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
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'No valid start for Flow declare export declaration found'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 0
          index: 0
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
  body: Array [
    FlowDeclareExportDefault {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 14
          index: 14
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: StringLiteralTypeAnnotation {
        value: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 14
            index: 14
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 35
          index: 35
          line: 1
        }
        start: Object {
          column: 15
          index: 15
          line: 1
        }
      }
      expression: ArrowFunctionExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 35
            index: 35
            line: 1
          }
          start: Object {
            column: 15
            index: 15
            line: 1
          }
        }
        body: ReferenceIdentifier {
          name: 'number'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 35
              index: 35
              line: 1
            }
            start: Object {
              column: 29
              index: 29
              line: 1
            }
          }
        }
        head: FunctionHead {
          async: false
          hasHoistedVars: false
          predicate: undefined
          rest: undefined
          returnType: undefined
          thisType: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 29
              index: 29
              line: 1
            }
            start: Object {
              column: 15
              index: 15
              line: 1
            }
          }
          params: Array [
            BindingIdentifier {
              name: 'a'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 28
                  index: 28
                  line: 1
                }
                start: Object {
                  column: 29
                  index: 29
                  line: 1
                }
              }
              meta: PatternMeta {
                optional: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 28
                    index: 28
                    line: 1
                  }
                  start: Object {
                    column: 29
                    index: 29
                    line: 1
                  }
                }
                typeAnnotation: NumberKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 24
                      index: 24
                      line: 1
                    }
                    start: Object {
                      column: 18
                      index: 18
                      line: 1
                    }
                  }
                }
              }
            }
          ]
        }
      }
    }
  ]
}
```