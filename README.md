# Lukas Lehmann - Resume

[![Build PDF](https://github.com/lukas-crafts/resume/actions/workflows/build.yml/badge.svg)](https://github.com/lukas-crafts/resume/actions/workflows/build.yml)
[![Release](https://img.shields.io/github/v/release/lukas-crafts/resume)](https://github.com/lukas-crafts/resume/releases)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> A modern resume maintained in Markdown, automatically built to PDF using [Resumx](https://resumx.dev).

---

## Quick Links

- **[Download Resume (PDF)](./output/resume.pdf)** - Latest version
- **[View Resume (Markdown)](./resume.md)** - Source file
- **[Releases](https://github.com/lukas-crafts/resume/releases)** - All versions

---

## About

This repository contains my professional resume maintained as a Markdown file. The PDF is automatically generated using the Resumx toolchain, ensuring a consistent and professional look.

### Why Markdown?

- **Version Control**: Track changes to my resume over time
- **Collaborative**: Easy to review and edit
- **Portable**: Plain text is future-proof
- **Automated**: CI/CD handles PDF generation and releases

---

## Repository Structure

```
.
├── resume.md              # Source resume in Markdown
├── output/
│   └── resume.pdf        # Generated PDF (Git LFS)
├── .github/
│   └── workflows/
│       ├── build.yml     # CI: Validate PDF builds
│       └── release.yml   # CI: Automated releases
├── CHANGELOG.md          # Version history
├── .gitattributes        # Git LFS configuration
└── .gitignore           # Ignore dev files
```

---

## Changelog

See [CHANGELOG.md](./CHANGELOG.md) for version history.

---

## Technologies Used

- **Resumx** - Markdown-to-PDF resume renderer
- **Git LFS** - Version control for binary files
- **GitHub Actions** - CI/CD automation
- **Semantic Versioning** - Version management

---

## License

This resume is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to:
- **Share** — copy and redistribute the material
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit

---

## Contact

Feel free to reach out for professional opportunities or questions about this project.

---

<p align="center">
  <sub>Built with ❤️ and maintained in Markdown</sub>
</p>
