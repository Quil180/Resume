# 📄 Personal Resume

A professional, ATS-friendly resume built with LaTeX.  This modular template makes it easy to maintain and customize your resume. 

<p align="center">
  <a href="Awad_Yousef.pdf">📥 View PDF</a>
</p>

## ✨ Features

- **ATS-Optimized** — Machine-readable PDF output for applicant tracking systems
- **Modular Structure** — Separate files for each section (education, experience, projects, etc.)
- **Clean Design** — Professional formatting with customizable styling
- **Easy to Customize** — Simply edit the section files to update your resume

## 📁 Project Structure

```
Resume/
├── Awad_Yousef.tex      # Main document entry point
├── libraries.tex        # Package imports & custom commands
├── Awad_Yousef.pdf      # Compiled resume output
└── sections/
    ├── education.tex    # Education section
    ├── experience.tex   # Work experience section
    ├── leadership.tex   # Leadership & activities
    ├── projects.tex     # Technical projects
    └── skills.tex       # Skills & technologies
```

## 🛠️ Prerequisites

You'll need a LaTeX distribution installed on your system: 

| Platform | Recommended Distribution |
|----------|--------------------------|
| Windows  | [MiKTeX](https://miktex.org/) |
| macOS    | [MacTeX](https://www.tug.org/mactex/) |
| Linux    | [TeX Live](https://www.tug.org/texlive/) |

## 🚀 Building the Resume

Navigate to the repository directory and compile: 

```bash
pdflatex Awad_Yousef.tex
```

> **Note:** Run the command twice if you have cross-references or a table of contents to ensure proper linking.

### Using Overleaf

You can also import this project into [Overleaf](https://www.overleaf.com/) for online editing and compilation without local setup.

## ✏️ Customization

1. **Update personal info** — Edit `Awad_Yousef.tex` with your name and contact details
2. **Modify sections** — Update files in the `sections/` directory with your information
3. **Adjust styling** — Customize fonts, margins, and formatting in `libraries.tex`

### Included LaTeX Packages

| Package | Purpose |
|---------|---------|
| `hyperref` | Clickable links |
| `fancyhdr` | Header/footer customization |
| `titlesec` | Section title formatting |
| `enumitem` | List customization |
| `tabularx` | Flexible tables |

## 📜 License

Feel free to use this template for your own resume! 

---

<p align="center">
  Made with ❤️ and LaTeX
</p>
