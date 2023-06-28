# jsonstruct

A Python package to extract and simplify JSON structure.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install jsonstruct.

```bash
pip install jsonstruct
```

## Usage

pythonCopy code

`import jsonstruct

json_obj = {...} # Your JSON object
structure = jsonstruct.build_structure(json_obj)
nested_structure = jsonstruct.nested_dict(structure)

print(json.dumps(nested_structure, indent=2))`

## License

[MIT](https://choosealicense.com/licenses/mit/)

markdownCopy code

`**LICENSE.txt**`

MIT License

Copyright (c) 2023 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit
persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the
Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.