# Markdown To PNG

**markdown-to-png** is a Python package designed to convert Markdown files into beautifully styled PNG images. Whether you want to create visually appealing graphics from text or simply share Markdown content in an image format, this tool has you covered.

This package is designed to be simple to use yet flexible enough to accommodate future enhancements and features.

---

## Features
- Convert Markdown files to PNG images effortlessly.
- Support for custom CSS styling to match your desired visual design.
- Lightweight and easy to integrate into your projects.

---

## Installation
You can install the package using `pip` (once published to PyPI):
```bash
pip install markdown-to-png
```

If you're cloning the repository for development:
```bash
git clone https://github.com/richiepagard/markdown-to-png.git
cd markdown-to-png
pip install -e .
```

---

## Usage
Here’s a basic example of how to use the package:
```python
from markdown_to_png import convertor

# convert a markdown file to png
convertor.markdown_to_png("path/to/markdown_file.md", "path/to/output.png")
```

### Optional Parameters
- **CSS File**: Customize the style by specifying a custom CSS file.
```python
convertor.markdown_to_png("path/to/markdown_file.md", "path/to/output.png", css_path="path/to/custom_style.css")
```

---

## Future Plans
This project is a work in progress, and more features are planned for future versions:
- Add support for multiple output formats (e.g., PDF, JPEG).
- Command-line interface for easier use.
- Enhanced error handling and logging.
- Predefined themes for styling.
- Integration with Markdown extensions like tables and footnotes.

Stay tuned for updates!

---

## Contributing
Contributions are welcome! If you have ideas, suggestions, or bug reports, please feel free to open an issue or submit a pull request on [GitHub](https://github.com/richiepagard/markdown-to-png).

---

## License
This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this package as per the terms of the license.

---

## Contact
If you have any questions or feedback, feel free to reach out:
- GitHub: [richiepagard](https://github.com/richiepagard) (Richie)
- Email: richiepagard@gmail.com
