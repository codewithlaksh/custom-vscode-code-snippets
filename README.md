# VS code custom user code snippets

After reading this guide , you will be able to generate your own code snippets for your vs code workspace.

Steps:

- Open any folder containing no files
- Create a folder named ".vscode".
- Go to File > Preferences > Configure User Snippets
- You will get options to make the code snippet file as global or only for the current workspace. You can select any one them. For convinience I am selecting the second option.
- Paste the following code after the comments to generate an html, css and js boilerplate code

```json
"Html5 starter template code": {
		"prefix": "html5:starter",
		"description": "This is a basic structure of a html website.",
		"body": "<!doctype html>\n<html>\n<head>\n\t<meta charset=\"utf-8\">\n\t<title>This is my document</title>\n\t<link rel=\"stylesheet\" href=\"$1\">\n</head>\n<body>\n\t$2\n\t<script src=\"$3\"></script>\n</body>\n</html>"
},
"Css3 starter code": {
    "prefix": "css3:starter",
    "description": "This is a basic structure of a css styling.",
    "body": "*{\n\tmargin: 0;\n\tpadding: 0;\n}"
},
"JavaScript console prints": {
    "prefix": "js:console",
    "description": "This is a snippet to generate diffrent types of console logs in js.",
    "body": "console.log(\"Hello world\");\nconsole.warn(\"This is a warning!\");\nconsole.error(\"This is an error!\");\nconsole.assert(9>10);"
}
```

Thanks for viewing this repository!
