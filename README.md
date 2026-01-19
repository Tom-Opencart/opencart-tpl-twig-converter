# OpenCart TPL ↔ Twig Converter v2.1

Professional template converter for migrating OpenCart 2.x TPL templates to OpenCart 3.x+ Twig format and vice versa.

## 🎯 Features

- **Bidirectional Conversion**: TPL → Twig and Twig → TPL
- **Intelligent Pattern Recognition**: Handles complex nested structures
- **Full Offline Operation**: No internet dependencies
- **Modern Interface**: Dark theme with syntax highlighting
- **Real-time Statistics**: Line and character counting
- **Error Handling**: Detailed conversion feedback

## 🚀 Supported Conversions

### Basic Patterns
- Variables: `<?php echo $var; ?>` ↔ `{{ var }}`
- Arrays: `$array['key']` ↔ `array.key`
- Loops: `foreach($arr as $item)` ↔ `{% for item in arr %}`
- Conditions: `if (in_array($x, $arr))` ↔ `{% if x in arr %}`
- Escaping: `htmlspecialchars($var)` ↔ `{{ var|escape }}`

### Advanced Features
- Nested arrays and complex structures
- Multi-line PHP blocks
- Conditional statements with operators
- String concatenation handling
- Token conversion (token ↔ user_token)

## 🛠️ Installation

Simply download and open `tpl_to_twigconverter.html` in any modern browser.

```bash
git clone https://github.com/yourusername/opencart-tpl-twig-converter.git
cd opencart-tpl-twig-converter
# Open tpl_to_twigconverter.html in your browser
```

## 📖 Usage

1. Open the HTML file in your browser
2. Select conversion direction (TPL→Twig or Twig→TPL)
3. Paste your template code in the left editor
4. Click "Convert" button
5. Copy the converted code from the right editor

## 🔧 Technical Details

- **Language**: Pure HTML/CSS/JavaScript
- **Size**: Single self-contained file (~50KB)
- **Browser Support**: All modern browsers
- **Dependencies**: None (fully offline)

## 📊 Statistics

- **Total Lines**: ~1,200 lines of code
- **Conversion Rules**: 600+ pattern matching rules
- **File Size**: ~50KB
- **Performance**: Real-time conversion

## 🤝 Contributing

Contributions welcome! Please feel free to submit pull requests for:
- Additional conversion patterns
- Interface improvements
- Performance optimizations
- Bug fixes

## 📄 License

MIT License - see LICENSE file for details

## 👤 Author

Created by Tom for OpenCart template migration projects.

## 🆘 Support

For issues or feature requests, please open an issue on GitHub.
