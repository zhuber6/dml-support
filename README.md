# dml-support README

This extension provides language support for Simics Device Modeling Language (DML). This is a C like language where Simics autogenerates the C code and then compiles.

## Features

This extension's features are limited to keyword matching for Simics's DML.

## Known Issues

This is not necessarily an issue but just a fact of the language itself is that the `data` keyword can be used to declare global variables. Because of this, matching all `data` patterns can make the readability confusing. I suggest not using data as a local variable because of this limitation.

## Release Notes

### 1.0.0

Initial release of Simics Device Modeling Language support.
