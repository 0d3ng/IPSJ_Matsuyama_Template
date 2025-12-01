# IPSJ Matsuyama LaTeX Template

LaTeX template for IPSJ (Information Processing Society of Japan) International Conference submissions.

## 📋 About

This template is used for writing papers to be submitted to IPSJ international conferences. The format and style follow the official IPSJ guidelines.

## 🔗 Official Website

- **IPSJ International Events**: https://www.ipsj.or.jp/english/event/intl/index.html
- Check the official website for latest information about:
  - Conference deadlines
  - Submission guidelines
  - Formatting requirements
  - Author instructions

## 📁 File Structure

```
.
├── template.tex          # Main LaTeX file
├── references.bib        # Bibliography file
├── figures/             # Folder for figures/images
└── README.md            # This file
```

## 🚀 Usage

### Compile Document

```bash
# Compile LaTeX → PDF
pdflatex template.tex

# Generate bibliography
bibtex template

# Compile again for final references
pdflatex template.tex
pdflatex template.tex
```

### Or use latexmk (recommended):

```bash
latexmk -pdf template.tex
```

## 📝 Writing Tips

1. **Title & Authors**: Edit `\title{}` and `\author{}` sections in template.tex
2. **Abstract**: Write abstract in English, maximum 150-200 words
3. **Sections**: Use `\section{}`, `\subsection{}`, `\subsubsection{}`
4. **Figures**: Save images in `figures/` folder, use `.pdf` or `.png` format
5. **References**: Add references in `references.bib` file using BibTeX format

## 📦 Required Packages

- LaTeX distribution (TeX Live / MiKTeX)
- Basic packages are usually already included

## 📄 License

Follow IPSJ's licensing terms for submission and publication.

## 📧 Contact

For questions regarding the template or conference, contact:
- IPSJ Official: https://www.ipsj.or.jp/english/

---

**Note**: Always check the latest IPSJ guidelines before submitting your paper!
