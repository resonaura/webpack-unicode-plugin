# webpack-unicode-plugin 🌍✨

[![Version](https://img.shields.io/badge/Version-1.0.2-blue.svg)](package.json)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](package.json)
[![Webpack](https://img.shields.io/badge/Webpack-Plugin-8DD6F9.svg?logo=webpack&logoColor=black)](package.json)
[![npm](https://img.shields.io/badge/npm-webpack--unicode--plugin-CB3837.svg?logo=npm&logoColor=white)](https://www.npmjs.com/package/webpack-unicode-plugin)

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/resonaura)

The `webpack-unicode-plugin` helps ensure your JavaScript files maintain proper Unicode encoding when bundled with Webpack. This is especially useful in scenarios where character encoding might get mixed up during the build process, leading to unexpected characters in your output files.

---

## Problem it Solves

Often during the webpack bundling process, non-ASCII characters can end up misrepresented in the final output due to encoding issues. This plugin converts all non-ASCII characters to Unicode escape sequences, ensuring your JavaScript files look and function as expected across all environments.

## Usage

1. Install the plugin via npm:

```bash
npm install webpack-unicode-plugin --save-dev
