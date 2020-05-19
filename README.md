# MeasureXForm - Solidworks Macro

## Introduction

The purpose of this macro is to provide Solidworks users with a transformation matrix between coordinate systems in the feature tree, including user-defined and the default (global) coordinate system(s). The user interface is meant to make this quick and easy.

## Instructions

- When the user interface window appears, use the "Coordinate System 1" drop-down menu to choose the coordinate system (or frame) that the user desires to be the destination of the transformation matrix.

- Use the "Coordinate System 2" drop-down menu to choose the frame that the user desires to be the source of the transformation matrix.

	- In other words, the calculated transformation matrix is the transform of Coordinate System 1 with respect to Coordinate System 2.

	- Both frames are set to the document's frame (global frame) by default.

- The "Units" drop-down menu can be used to change the units of the x/y/z translations. This is set to the document units by default.

- The desired 4x4 trasnformation matrix is provided in the text box at the bottom of the window. After highlighting and copying the matirx, the matrix can be pasted into Excel. Each of the 16 elements will paste into its own cell.

## License

Copyright 2020, Aeroanion

The MIT License:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

