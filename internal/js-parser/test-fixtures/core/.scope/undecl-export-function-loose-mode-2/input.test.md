# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > scope > undecl-export-function-loose-mode-2`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 30
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExportLocalDeclaration {
			declaration: undefined
			exportKind: "value"
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 13
					index: 13
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			specifiers: Array [
				JSExportLocalSpecifier {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 10
							index: 10
							line: 1
						}
						start: Object {
							column: 9
							index: 9
							line: 1
						}
					}
					exported: JSIdentifier {
						name: "a"
						loc: Object {
							filename: "input.js"
							identifierName: "a"
							end: Object {
								column: 10
								index: 10
								line: 1
							}
							start: Object {
								column: 9
								index: 9
								line: 1
							}
						}
					}
					local: JSReferenceIdentifier {
						name: "a"
						loc: Object {
							filename: "input.js"
							identifierName: "a"
							end: Object {
								column: 10
								index: 10
								line: 1
							}
							start: Object {
								column: 9
								index: 9
								line: 1
							}
						}
					}
				}
			]
		}
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "a"
				loc: Object {
					filename: "input.js"
					identifierName: "a"
					end: Object {
						column: 10
						index: 24
						line: 2
					}
					start: Object {
						column: 9
						index: 23
						line: 2
					}
				}
			}
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 15
					index: 29
					line: 2
				}
				start: Object {
					column: 0
					index: 14
					line: 2
				}
			}
			body: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 15
						index: 29
						line: 2
					}
					start: Object {
						column: 13
						index: 27
						line: 2
					}
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
						column: 12
						index: 26
						line: 2
					}
					start: Object {
						column: 10
						index: 24
						line: 2
					}
				}
			}
		}
	]
}
```