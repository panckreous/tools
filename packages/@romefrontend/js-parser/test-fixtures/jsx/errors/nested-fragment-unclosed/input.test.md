# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > errors > nested-fragment-unclosed`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "input.jsx"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array ["jsx"]
	loc: Object {
		filename: "input.jsx"
		end: Object {
			column: 0
			index: 8
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
			origins: Array [Object {category: "parse/js"}]
			location: Object {
				filename: "input.jsx"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 7
					index: 7
					line: 1
				}
				start: Object {
					column: 7
					index: 7
					line: 1
				}
			}
			description: Object {
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Unclosed JSX element"}
				advice: Array [
					log {
						category: "info"
						text: "Originated from this opening tag"
					}
					frame {
						location: Object {
							filename: "input.jsx"
							end: Object {
								column: 2
								index: 2
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
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.jsx"
				end: Object {
					column: 7
					index: 7
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSXFragment {
				loc: Object {
					filename: "input.jsx"
					end: Object {
						column: 7
						index: 7
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				children: Array [
					JSXFragment {
						children: Array []
						loc: Object {
							filename: "input.jsx"
							end: Object {
								column: 7
								index: 7
								line: 1
							}
							start: Object {
								column: 2
								index: 2
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

### `diagnostics`

```

 input.jsx:1:7 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unclosed JSX element

  ℹ Originated from this opening tag

    <><></>
    ^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```