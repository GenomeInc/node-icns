# node-icns

A command line tool to generate .icns files from a PNG file size 1024 or greater.

Obviously only meant to run on OSX.

## Install

`npm install -g node-icns`

## Usage

The file being used needs to be 1024x1024.

`nicns [--in <inFile>, --out <outFile>]`

If you do not provide an `--in <inFile>`, the current directory name is used and it will search for a PNG in the folder.

If you do not provide an `--out <outFile>`, the current directory name is used for the .icns file.

## License

node-icns is copyright 2015 typefoo, a division of uh-sem-blee, Co.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
