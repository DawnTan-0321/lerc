# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased][unreleased]

### No entries yet

### Fixed - 2017-02-18

* resolved a Huffman code table parsing issue in JavaScript decoder [#31](https://github.com/Esri/lerc/pull/31)

## 1.0 - 2016-11-30

### Milestones reached
- This LERC API and all language decoders (C++, C, C#, Python, JavaScript) are now in sync with these ESRI ArcGIS versions to be released soon: ESRI ArcMap 10.5, ESRI ArcGIS Pro 1.4. LERC encoded binary blobs of any previous version of ArcMap or ArcGIS Pro can be read / decoded.

### What will trigger a major version change
- A change to this LERC API that is not backwards compatible and requires users to update / change their code in order to use an upgraded .dll or .so file.
- A change to the LERC bitstream that is not backwards compatible and requires users to upgrade their LERC encoder and / or decoder.

[unreleased]: https://github.com/Esri/lerc/compare/v1.0...HEAD