# SelectBlock

Expand a selection to the current top-level declaration, defined roughly as the
enclosing lines around a selection, expanding upwards to the nearest
non-indented line, and downwards to the next non-indented line.

Intended to 'select top-level declaration' command for languages that define
scope by indentation, such as Python or Haskell.

One command is provided, `select_block`. By default, this
command can be triggered with `ctrl+shift+u` on Linux and Windows, and
`cmd+shift+u` on MacOS.

== License

All of SelectBlock is licensed under the MIT license.

  Copyright (c) 2019 Elliot Marsden <elliot.marsden@gmail.com>

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
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
  SOFTWARE.
