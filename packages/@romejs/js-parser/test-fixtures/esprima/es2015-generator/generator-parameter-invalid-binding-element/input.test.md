# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-generator > generator-parameter-invalid-binding-element`

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
      index: 48
      line: 4
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Expected an identifier'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 13
          index: 28
          line: 2
        }
        start: Object {
          column: 13
          index: 28
          line: 2
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 2
          index: 47
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: FunctionExpression {
        id: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 46
            line: 3
          }
          start: Object {
            column: 1
            index: 1
            line: 1
          }
        }
        head: FunctionHead {
          async: false
          generator: true
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
              column: 12
              index: 12
              line: 1
            }
            start: Object {
              column: 10
              index: 10
              line: 1
            }
          }
        }
        body: BlockStatement {
          directives: Array []
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 1
              index: 46
              line: 3
            }
            start: Object {
              column: 13
              index: 13
              line: 1
            }
          }
          body: Array [
            FunctionDeclaration {
              id: BindingIdentifier {
                name: ''
                loc: Object {
                  filename: 'input.js'
                  identifierName: ''
                  end: Object {
                    column: 14
                    index: 29
                    line: 2
                  }
                  start: Object {
                    column: 13
                    index: 28
                    line: 2
                  }
                }
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 29
                  index: 44
                  line: 2
                }
                start: Object {
                  column: 4
                  index: 19
                  line: 2
                }
              }
              body: BlockStatement {
                body: Array []
                directives: Array []
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 29
                    index: 44
                    line: 2
                  }
                  start: Object {
                    column: 27
                    index: 42
                    line: 2
                  }
                }
              }
              head: FunctionHead {
                async: false
                generator: true
                hasHoistedVars: false
                predicate: undefined
                rest: undefined
                returnType: undefined
                thisType: undefined
                typeParameters: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 26
                    index: 41
                    line: 2
                  }
                  start: Object {
                    column: 14
                    index: 29
                    line: 2
                  }
                }
                params: Array [
                  BindingAssignmentPattern {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 25
                        index: 40
                        line: 2
                      }
                      start: Object {
                        column: 14
                        index: 29
                        line: 2
                      }
                    }
                    right: YieldExpression {
                      delegate: false
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 25
                          index: 40
                          line: 2
                        }
                        start: Object {
                          column: 18
                          index: 33
                          line: 2
                        }
                      }
                      argument: NumericLiteral {
                        value: 3
                        format: undefined
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 25
                            index: 40
                            line: 2
                          }
                          start: Object {
                            column: 24
                            index: 39
                            line: 2
                          }
                        }
                      }
                    }
                    left: BindingIdentifier {
                      name: 'x'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'x'
                        end: Object {
                          column: 15
                          index: 30
                          line: 2
                        }
                        start: Object {
                          column: 14
                          index: 29
                          line: 2
                        }
                      }
                      meta: PatternMeta {
                        optional: undefined
                        typeAnnotation: undefined
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 15
                            index: 30
                            line: 2
                          }
                          start: Object {
                            column: 14
                            index: 29
                            line: 2
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
      }
    }
  ]
}
```
