# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > input-not-followed-by-regex`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/yield/input-not-followed-by-regex/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/yield/input-not-followed-by-regex/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "f2"
				loc: Object {
					filename: "es2015/yield/input-not-followed-by-regex/input.js"
					identifierName: "f2"
					end: Object {
						column: 12
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/yield/input-not-followed-by-regex/input.js"
				end: Object {
					column: 34
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/yield/input-not-followed-by-regex/input.js"
					end: Object {
						column: 14
						line: 1
					}
					start: Object {
						column: 12
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "es2015/yield/input-not-followed-by-regex/input.js"
					end: Object {
						column: 34
						line: 1
					}
					start: Object {
						column: 15
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "es2015/yield/input-not-followed-by-regex/input.js"
							end: Object {
								column: 32
								line: 1
							}
							start: Object {
								column: 17
								line: 1
							}
						}
						expression: JSArrowFunctionExpression {
							loc: Object {
								filename: "es2015/yield/input-not-followed-by-regex/input.js"
								end: Object {
									column: 32
									line: 1
								}
								start: Object {
									column: 17
									line: 1
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								params: Array []
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "es2015/yield/input-not-followed-by-regex/input.js"
									end: Object {
										column: 22
										line: 1
									}
									start: Object {
										column: 17
										line: 1
									}
								}
							}
							body: JSBinaryExpression {
								operator: "/"
								loc: Object {
									filename: "es2015/yield/input-not-followed-by-regex/input.js"
									end: Object {
										column: 32
										line: 1
									}
									start: Object {
										column: 23
										line: 1
									}
								}
								left: JSReferenceIdentifier {
									name: "yield"
									loc: Object {
										filename: "es2015/yield/input-not-followed-by-regex/input.js"
										identifierName: "yield"
										end: Object {
											column: 28
											line: 1
										}
										start: Object {
											column: 23
											line: 1
										}
									}
								}
								right: JSNumericLiteral {
									value: 1
									format: undefined
									loc: Object {
										filename: "es2015/yield/input-not-followed-by-regex/input.js"
										end: Object {
											column: 32
											line: 1
										}
										start: Object {
											column: 31
											line: 1
										}
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

### `diagnostics`

```
✔ No known problems!

```