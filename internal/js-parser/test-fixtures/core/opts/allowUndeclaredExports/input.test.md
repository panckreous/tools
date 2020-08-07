# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > opts > allowUndeclaredExports`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/opts/allowUndeclaredExports/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "core/opts/allowUndeclaredExports/input.js"
		end: Object {
			column: 15
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExportLocalDeclaration {
			declaration: undefined
			exportKind: "value"
			loc: Object {
				filename: "core/opts/allowUndeclaredExports/input.js"
				end: Object {
					column: 15
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			specifiers: Array [
				JSExportLocalSpecifier {
					loc: Object {
						filename: "core/opts/allowUndeclaredExports/input.js"
						end: Object {
							column: 12
							line: 1
						}
						start: Object {
							column: 9
							line: 1
						}
					}
					exported: JSIdentifier {
						name: "foo"
						loc: Object {
							filename: "core/opts/allowUndeclaredExports/input.js"
							identifierName: "foo"
							end: Object {
								column: 12
								line: 1
							}
							start: Object {
								column: 9
								line: 1
							}
						}
					}
					local: JSReferenceIdentifier {
						name: "foo"
						loc: Object {
							filename: "core/opts/allowUndeclaredExports/input.js"
							identifierName: "foo"
							end: Object {
								column: 12
								line: 1
							}
							start: Object {
								column: 9
								line: 1
							}
						}
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```