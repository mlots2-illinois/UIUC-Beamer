# UIUC-Beamer

This is a **Beamer Template** customized for the University of Illinois Urbana-Champaign based on the Frankfurt Beamer theme. This template is designed to help you create professional, visually appealing presentations in LaTeX using the Beamer class. It is tailored for users at **Illinois**, but it can also be adapted for use by other institutions.

The template includes features such as custom fonts, institutional color schemes, branded logos, and various layout options to meet a wide range of presentation needs.

---

## Features

- **Custom University of Illinois Urbana-Chmapaign Branding:**
  - Includes official Illinois logos and color schemes.
  - Supports college-specific branding (e.g., Grainger Engineering, LAS, ACES).

- **Modern Fonts and Typography:**
  - Uses **Source Sans Pro** for clean, modern text.
  - Includes **Montserrat** for bold and medium headings.

- **Flexible Design Options:**
  - Title slides with custom backgrounds and diagonal overlays.
  - Section slides with different layout options.
  - Full-page, half-page, and column-based layouts.

- **Support for Advanced Features:**
  - Mathematical equations using the `amsmath` package.
  - Code highlighting with the `listings` package.
  - Professional-looking tables with the `booktabs` package.
  - High-quality diagrams using `TikZ`.

- **Interactive Content:**
  - iClicker-style multiple-choice questions for audience engagement.
  - Customizable navigation symbols.

---

## File Structure

The project includes the following files and folders:

- **`UIUC-BeamerTemplate.tex`:** The main LaTeX file containing the presentation template.
- **`University Graphics/`:** A folder for Illinois logos in various formats (e.g., `.eps`).
- **`University Photography/`:** A folder for campus images to use as backgrounds.

---

## Getting Started

### Prerequisites

1. **LaTeX Distribution:**
   - Install a LaTeX distribution such as [TeX Live](https://www.tug.org/texlive/), [MikTeX](https://miktex.org/), or [MacTeX](https://tug.org/mactex/).

2. **XeLaTeX Compiler:**
   - This template requires the **XeLaTeX** compiler to support custom fonts and advanced features.

3. **Required Packages:**
   - The following LaTeX packages are used in the template:
     - `sourcesanspro`
     - `fontspec`
     - `amsmath`
     - `graphicx`
     - `xcolor`
     - `tikz`
     - `listings`
     - `booktabs`
     - `enumitem`

   Ensure these packages are installed in your LaTeX environment.

---

### Usage

1. Clone or download the repository:
   ```bash
   git clone https://github.com/mlots2-illinois/UIUC-BeamerTemplate.git
   ```

2. Open `UIUC-BeamerTemplate.tex` in your preferred LaTeX editor.

3. Customize the following sections:
   - **Title Page:** Update the `\title`, `\author`, and `\date` commands.
   - **Logos and Branding:** Replace logos or adjust college-level branding as needed.
   - **Content:** Add your own frames (`\begin{frame} ... \end{frame}`) and sections (`\section{}`).

4. Compile the document using XeLaTeX:
   ```bash
   xelatex UIUC-BeamerTemplate.tex
   ```

5. View the generated PDF presentation.

---

## Examples

### Title Slide Variations
The template provides several title slide designs:
- With the Block I logo
- With college-level logos
- Custom background images and overlays

### Frame Layouts
- Bullet lists, enumerated lists, and multi-column layouts
- Highlighted blocks (`alertblock`, `exampleblock`)
- Full-page or half-page images

### Advanced Features
- Code blocks (e.g., Stata scripts)
- Mathematical equations
- Tables with professional formatting

---

## Customization

### Color Scheme
The template includes predefined UIUC colors (e.g., Illini Orange, Illini Blue). You can find these in the **Institutional Color Scheme** section of the `.tex` file:
```latex
\definecolor{IlliniOrange}{cmyk}{0,0.8,1,0}
\definecolor{IlliniBlue}{cmyk}{1,0.90,0.10,0.50}
```

### Fonts
The default font is **Source Sans Pro**. You can change it by modifying the `\setsansfont` command:
```latex
\setsansfont{YourPreferredFont}[Weight=300]
```

### Logos
Replace logo files in the `University Graphics/` folder if your unit is not included in the sample template. Update file paths in the `.tex` file accordingly.

---

## Contributing

If you encounter issues or have suggestions for improvement:
1. Fork this repository.
2. Make your changes or additions.
3. Submit a pull request.

We welcome contributions to make this template more versatile and user-friendly!

---

## License

This project is licensed under the University of Illinois/NCSA Open Source License.

For more information on branding guidelines, please refer to the resources at https://brand.illinois.edu.

Happy presenting! 🎉
