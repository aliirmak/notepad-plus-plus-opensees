# notepad-plus-plus-opensees
Notepad++OpenSees is a user defined language option for Notepad++ to support syntax highlighting for the OpenSees.

## Jump to Section

- [Features](#features)
- [Installation](#installation)
- [Updating](#updating)
- [Issues](#issues)
- [Contribute](#contribute)
- [License](#license)

## Features

- Support for OpenSees and Tcl syntax in Notepad++

## Installation

1. You need to first install [Notepad++][npp] to use this tool.
2. Download the [zip package][zipPackage] and extract.
3. Click `Language > Define your language...` menu.
4. Import the extracted `OpenSees.xml` file.
5. Restart Notepad++.
6. Open your `.tcl` file and click `Language > OpenSees` menu.

## Updating

1. Check [project page][home] for updates.
2. Click `Language > Define your language...` menu.
3. Select OpenSees and remove.
4. Follow installation steps [above](#installation).

## Issues

- Due to limitations of User Defined Language Engine of Notepad++, Tcl keywords are not supported natively. A workaround is performed by defining Tcl keywords manually. On the other hand, this issue does not affect usability of the tool much.
- Currently, auto-completion is not supported. I am planning to release one. Your contribution is most welcome.
- Works best on dark themes. Not tested for light themes.

## Contribute

- You can contribute to the project by reporting any bug or feature request [here][issues].
- You are welcome to fork and submit pull requests.

## License

All of the source code is available at github [project][home] under the MIT licence:
```
Copyright (c) 2015 Ali Irmak Ozdagli <aliirmak@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

[npp]: https://notepad-plus-plus.org/download/ "Notepad++"
[home]: https://github.com/aliirmak/notepad-plus-plus-opensees "Home"
[zipPackage]: https://github.com/aliirmak/notepad-plus-plus-opensees/archive/master.zip "Zip Package"
[issues]: https://github.com/aliirmak/notepad-plus-plus-opensees/issues "Issues"
