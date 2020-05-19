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

The MIT License, which is very permissive. See the LICENSE.md file for license body.