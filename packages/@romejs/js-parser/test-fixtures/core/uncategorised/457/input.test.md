# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 457`

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
      column: 33
      index: 33
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'No loop label found'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 22
          index: 22
          line: 1
        }
        start: Object {
          column: 22
          index: 22
          line: 1
        }
      }
    }
  ]
  body: Array [
    SwitchStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 33
          index: 33
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      discriminant: ReferenceIdentifier {
        name: 'x'
        loc: Object {
          filename: 'input.js'
          identifierName: 'x'
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
      cases: Array [
        SwitchCase {
          test: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 31
              index: 31
              line: 1
            }
            start: Object {
              column: 20
              index: 20
              line: 1
            }
          }
          consequent: Array [
            ContinueStatement {
              label: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 31
                  index: 31
                  line: 1
                }
                start: Object {
                  column: 22
                  index: 22
                  line: 1
                }
              }
            }
          ]
        }
      ]
    }
  ]
}
```
