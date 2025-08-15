# DePalma Workshop Templates

Reusable templates and boilerplate files for DePalma Workshop projects.

## 🎯 What This Repository Contains

Standard templates for consistent project setup and documentation across all DePalma Workshop repositories.

## 🚀 Quick Start

### Using a Template

```bash
# Download a license template
curl -o LICENSE https://raw.githubusercontent.com/depalmaworkshop/templates/main/license/template-license-cc-by-sa-4.0.md

# Download a README template
curl -o README.md https://raw.githubusercontent.com/depalmaworkshop/templates/main/readme/template-readme-generic.md

# Download a .gitignore template
curl -o .gitignore https://raw.githubusercontent.com/depalmaworkshop/templates/main/github/template-gitignore-generic.md
```

## 📁 Repository Structure

```
templates/
├── license/
│   └── template-license-cc-by-sa-4.0.md
├── readme/
│   └── template-readme-generic.md
├── github/
│   ├── template-gitignore-generic.md
│   ├── template-pull-request.md
│   └── template-issue-bug.md
└── doc/
    ├── template-contributing.md
    ├── template-security.md
    └── template-code-of-conduct.md
```

## 📊 Current Templates

### License Templates
- **CC BY-SA 4.0** (`template-license-cc-by-sa-4.0.md`) - Our standard open source license

### README Templates
- **Generic README** (`template-readme-generic.md`) - Universal template with all sections

### GitHub Templates
- **Generic .gitignore** (`template-gitignore-generic.md`) - Common exclusions for most projects
- **Pull Request** (`template-pull-request.md`) - PR description template
- **Bug Report** (`template-issue-bug.md`) - Issue template for bug reports

### Documentation Templates
- **Contributing Guide** (`template-contributing.md`) - Contribution guidelines
- **Security Policy** (`template-security.md`) - Security disclosure process
- **Code of Conduct** (`template-code-of-conduct.md`) - Community standards

## 🔮 Planned Templates

We aim to create specialized templates for:
- `template-readme-application.md` - Tailored for web/mobile applications
- `template-readme-documentation.md` - For pure documentation repositories
- `template-license-mit.md` - MIT license option
- `template-license-proprietary.md` - For closed-source projects
- `template-issue-feature.md` - Feature request template
- `template-gitignore-node.md` - Node.js specific exclusions
- `template-gitignore-python.md` - Python specific exclusions

## 🛠️ Using Templates

1. **Download** the template file
2. **Rename** appropriately (e.g., `template-license-cc-by-sa-4.0.md` → `LICENSE`)
3. **Replace** all `[PLACEHOLDER]` text with your actual content
4. **Remove** sections that don't apply to your project
5. **Delete** the HTML comment instructions at the top

### Naming Conventions

Templates follow this pattern:
```
template-[type]-[variant].[extension]
```

When implementing:
- `template-license-*` → Save as `LICENSE` (no extension)
- `template-readme-*` → Save as `README.md`
- `template-gitignore-*` → Save as `.gitignore`

## 🤝 Contributing

To add or improve templates:
1. Follow the naming convention
2. Include metadata in HTML comments
3. Use `[PLACEHOLDER]` for replaceable content
4. Submit a pull request

## 📄 License

These templates are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) - see the [LICENSE](LICENSE) file for details.

---

Built by [DePalma Workwear Limited](https://github.com/depalmaworkshop)