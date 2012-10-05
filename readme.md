TypeScriptGenerator
===================

TypeScriptGenerator is Custom Tool for **Visual Studio 2010** for automated compiling **[TypeScript](http://www.typescriptlang.org)** to JavaScript.

Usage
-----

1. Install TypeScript compiler via [TypeScript for Visual Studio 2012](http://go.microsoft.com/fwlink/?LinkID=266563) (Node.js package doesn't work for some reason).

2. Download and compile TypeScriptGenerator.

3. Run `TypeScriptGenerator.reg`.

4. Create TypeScript file with `.ts` extension in your web project. Visual Studio automatically associates it with TypeScriptGenerator custom tool and creates compiled JavaScript file.

Known Issues
------------
`tsc` can't compile files in UTF-8 with BOM encoding.