# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 464`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 48
			index: 48
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
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "No loop label found"}
			}
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 33
					index: 33
					line: 1
				}
				start: Object {
					column: 33
					index: 33
					line: 1
				}
			}
		}
	]
	body: Array [
		JSLabeledStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 48
					index: 48
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			label: JSIdentifier {
				name: "x"
				loc: Object {
					filename: "input.js"
					identifierName: "x"
					end: Object {
						column: 1
						index: 1
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
			}
			body: JSWhileStatement {
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 48
						index: 48
						line: 1
					}
					start: Object {
						column: 3
						index: 3
						line: 1
					}
				}
				test: JSBooleanLiteral {
					value: true
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 14
							index: 14
							line: 1
						}
						start: Object {
							column: 10
							index: 10
							line: 1
						}
					}
				}
				body: JSBlockStatement {
					directives: Array []
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 48
							index: 48
							line: 1
						}
						start: Object {
							column: 16
							index: 16
							line: 1
						}
					}
					body: Array [
						JSExpressionStatement {
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 46
									index: 46
									line: 1
								}
								start: Object {
									column: 18
									index: 18
									line: 1
								}
							}
							expression: JSFunctionExpression {
								id: undefined
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 44
										index: 44
										line: 1
									}
									start: Object {
										column: 19
										index: 19
										line: 1
									}
								}
								head: JSFunctionHead {
									async: false
									generator: false
									hasHoistedVars: false
									params: Array []
									rest: undefined
									returnType: undefined
									thisType: undefined
									typeParameters: undefined
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 30
											index: 30
											line: 1
										}
										start: Object {
											column: 28
											index: 28
											line: 1
										}
									}
								}
								body: JSBlockStatement {
									directives: Array []
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 44
											index: 44
											line: 1
										}
										start: Object {
											column: 31
											index: 31
											line: 1
										}
									}
									body: Array [
										JSContinueStatement {
											label: undefined
											loc: Object {
												filename: "input.js"
												end: Object {
													column: 42
													index: 42
													line: 1
												}
												start: Object {
													column: 33
													index: 33
													line: 1
												}
											}
										}
									]
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

### `diagnostics`

```

 input.js:1:33 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ No loop label found

    x: while (true) { (function () { continue; }); }
                                     ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```