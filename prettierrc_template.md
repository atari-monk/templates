# Template for .prettierrc file

Formatter config for project formatter VSCode extension.   
Name file:

```plaintext
.prettierrc
```

Content for nice basic format:

```json
{
  "tabWidth": 2,
  "semi": false,
  "singleQuote": true,
  "arrowParens": "avoid",
  "trailingComma": "es5",
  "printWidth": 80,
  "endOfLine": "crlf",
  "bracketSpacing": false
}
```

This will:
- Use 2 spaces for indentation (`tabWidth`).
- Avoid semicolons at the end of statements (`semi`).
- Enforce single quotes for strings (`singleQuote`).
- Use `avoid` for arrow function parentheses (`arrowParens`).
- Add trailing commas where valid in ES5 (like arrays and objects) (`trailingComma`).
- Set a max line length of 80 characters (`printWidth`).
- Use Windows-style line endings (`endOfLine: "crlf"`).
- Remove spaces inside object braces (`bracketSpacing: false`).

Looks perfect for a clean, readable, and consistent codebase!
