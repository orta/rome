# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > opaque-type-alias > opaque_declare_t_and_st`

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
      index: 35
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Expected a semicolon or a line terminator'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
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
    }
  ]
  body: Array [
    FlowDeclareOpaqueType {
      id: BindingIdentifier {
        name: 'Foo'
        loc: Object {
          filename: 'input.js'
          identifierName: 'Foo'
          end: Object {
            column: 23
            index: 23
            line: 1
          }
          start: Object {
            column: 20
            index: 20
            line: 1
          }
        }
      }
      impltype: undefined
      typeParameters: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 28
          index: 28
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      supertype: FlowGenericTypeAnnotation {
        id: ReferenceIdentifier {
          name: 'Bar'
          loc: Object {
            filename: 'input.js'
            identifierName: 'Bar'
            end: Object {
              column: 28
              index: 28
              line: 1
            }
            start: Object {
              column: 25
              index: 25
              line: 1
            }
          }
        }
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 28
            index: 28
            line: 1
          }
          start: Object {
            column: 25
            index: 25
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 30
          index: 30
          line: 1
        }
        start: Object {
          column: 29
          index: 29
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 30
            index: 30
            line: 1
          }
          start: Object {
            column: 29
            index: 29
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 34
          index: 34
          line: 1
        }
        start: Object {
          column: 31
          index: 31
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'Baz'
        loc: Object {
          filename: 'input.js'
          identifierName: 'Baz'
          end: Object {
            column: 34
            index: 34
            line: 1
          }
          start: Object {
            column: 31
            index: 31
            line: 1
          }
        }
      }
    }
  ]
}
```
