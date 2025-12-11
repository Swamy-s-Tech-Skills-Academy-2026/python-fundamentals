# 📋 Repository Structure

This document provides a detailed overview of the Python Fundamentals repository structure.

---

## 📁 Complete Repository Structure

```text
python-fundamentals/
├── 📚 docs/
│   ├── images/                 # Screenshots and educational images
│   │   └── S1/                # Session 1 images (help screenshots, bytecode diagram)
│   └── sessions/
│       └── L1/                # Level 1: Noob → Nerd
│           ├── Plan.md        # Complete Level 1 curriculum plan
│           ├── S1.md          # Session 1: Python Introduction & Environment Setup
│           ├── S2.md          # Session 2: Variables & Data Types
│           # S3.md and beyond - coming soon
├── 💻 src/
│   └── L1/
│       ├── S1/                # Session 1 practice files
│       │   ├── 01_hello.py
│       │   ├── 02_interactive_hello.py
│       │   └── bytecode_demo.py
│       └── S2/                # Session 2 practice files
│           ├── 01_variables.py
│           ├── 02_data_types.py
│           └── 03_type_conversion.py
├── 🔧 scripts/               # Development and utility scripts
│   ├── docs-lint.ps1         # Markdown linting script
│   ├── docs-links.ps1        # Link validation script
│   ├── show-tree.ps1         # Repository structure generator
│   └── repo-structure.txt    # Generated structure
├── ⚙️ .github/
│   ├── workflows/
│   │   └── docs-quality.yml  # CI/CD for documentation quality
│   └── copilot-instructions.md
├── 📄 README.md              # This file
├── 📄 LICENSE                # MIT License
└── 📋 Configuration files    # .markdownlint*, lychee.toml, .gitignore
```

---

## 📂 Directory Descriptions

### `docs/`

Contains all educational documentation:

- **`images/`**: Educational images organized by session (S1, S2, etc.)
- **`sessions/`**: Session documentation organized by level (L1, L2, etc.)
  - Each level contains:
    - `Plan.md`: Complete level curriculum plan
    - `S1.md`, `S2.md`, etc.: Individual session documentation

### `src/`

Contains all practice code files:

- Organized by level (`L1/`, `L2/`, etc.)
- Each level contains session directories (`S1/`, `S2/`, etc.)
- Practice files use numeric prefixes: `01_name.py`, `02_name.py`, etc.

### `scripts/`

PowerShell utility scripts for development:

- **`docs-lint.ps1`**: Markdown linting automation
- **`docs-links.ps1`**: Link validation using Lychee
- **`show-tree.ps1`**: Repository structure generator
- **`repo-structure.txt`**: Generated structure output

### `.github/`

GitHub configuration:

- **`workflows/`**: CI/CD pipelines for quality assurance
- **`copilot-instructions.md`**: AI assistant guidelines

### `.cursor/`

Cursor AI configuration:

- **`rules/`**: Modular rule files for Cursor AI
  - `01_educational-content-rules.mdc`
  - `02_repository-structure.mdc`
  - `03_quality-assurance.mdc`
  - `04_markdown-standards.mdc`
  - `05_primary-directives.mdc`
  - `06_cross-level-integration.mdc`

---

## 📝 File Naming Conventions

### Python Practice Files

- Format: `{number}_{descriptive_name}.py`
- Examples: `01_hello.py`, `02_interactive_hello.py`, `03_type_conversion.py`
- Location: `src/L{level}/S{session}/`

### Session Documentation

- Format: `S{session}.md` or `Plan.md`
- Examples: `S1.md`, `S2.md`, `Plan.md`
- Location: `docs/sessions/L{level}/`

### Images

- Format: `{descriptive_name}.PNG` or `.png`
- Examples: `Help_V1.PNG`, `Py_Source_ByteCode.PNG`
- Location: `docs/images/S{session}/`

---

## 🔗 Path Reference Patterns

### Practice File References

```markdown
`src/L1/S1/01_hello.py`
`src/L1/S2/01_variables.py`
```

### Session Documentation References

```markdown
[Session 1](docs/sessions/L1/S1.md)
[Level 1 Plan](docs/sessions/L1/Plan.md)
```

### Image References

```markdown
![Help System](../../images/S1/Help_V1.PNG)
```

---

## 📊 Current Repository Status

### Level 1 (Noob → Nerd)

- ✅ **Session 1**: Complete with 3 practice files
- ✅ **Session 2**: Complete with 3 practice files
- 🔄 **Sessions 3-10**: Coming soon
- 🔄 **Mini Projects**: Coming soon

### Future Levels

- 🔄 **Level 2-9**: Planned for future development

---

## 🚀 Quick Navigation

- **Main README**: [README.md](../README.md)
- **Level 1 Plan**: [docs/sessions/L1/Plan.md](sessions/L1/Plan.md)
- **Session 1**: [docs/sessions/L1/S1.md](sessions/L1/S1.md)
- **Session 2**: [docs/sessions/L1/S2.md](sessions/L1/S2.md)

---

**Last Updated**: December 2025
