# Contributing to Sales Insights Dashboard

First off, thank you for considering contributing to this project! 🎉

## How Can I Contribute?

### 1. Reporting Issues

Found a bug or have a suggestion? Please open an issue:
- Use a clear and descriptive title
- Describe the expected vs actual behavior
- Include screenshots if applicable
- Mention your Excel version

### 2. Adding Sample Data

You can contribute additional sample data:
- Maintain the same data structure (see `docs/DATA_SCHEMA.md`)
- Add realistic, diverse scenarios
- Ensure data quality (no missing values)
- Document any new fields in DATA_SCHEMA.md

### 3. Improving Documentation

Help make the documentation better:
- Fix typos or clarify instructions
- Add tips and tricks you discovered
- Translate documentation to other languages
- Create video tutorials or guides

### 4. Sharing Your Dashboard

Created a great dashboard using this data?
- Add screenshots to the `screenshots/` folder
- Write about your design decisions
- Share tips for creating effective visualizations
- Optionally include your Excel file

### 5. Enhancing the Guide

Make the dashboard guide more helpful:
- Add more detailed steps
- Include troubleshooting tips
- Add examples of advanced techniques
- Create beginner-friendly explanations

## Development Process

### Getting Started

1. **Fork the Repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/sales-insights-dashboard-excel.git
   cd sales-insights-dashboard-excel
   ```

3. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Making Changes

1. **Follow the existing structure**
   - Keep file organization consistent
   - Match the documentation style
   - Use clear, descriptive names

2. **Test your changes**
   - Verify data imports correctly
   - Test any formulas or calculations
   - Check links in documentation

3. **Update documentation**
   - If you add features, document them
   - Update README.md if structure changes
   - Keep DATA_SCHEMA.md current

### Submitting Changes

1. **Commit your changes**
   ```bash
   git add .
   git commit -m "Add: descriptive commit message"
   ```
   
   Use these commit prefixes:
   - `Add:` for new features
   - `Fix:` for bug fixes
   - `Update:` for changes to existing features
   - `Docs:` for documentation changes
   - `Style:` for formatting changes

2. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

3. **Open a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Fill out the PR template
   - Wait for review

## Contribution Guidelines

### Code of Conduct

- Be respectful and inclusive
- Welcome newcomers
- Give constructive feedback
- Focus on what's best for the community

### Quality Standards

**For Data:**
- Follow CSV format with proper delimiters
- Maintain data consistency
- No personally identifiable information
- Use realistic but synthetic data

**For Documentation:**
- Use clear, concise language
- Include examples where helpful
- Maintain consistent formatting
- Check spelling and grammar

**For Excel Files:**
- Use standard Excel features (avoid obscure add-ins)
- Document any macros or VBA code
- Test in multiple Excel versions if possible
- Keep file size reasonable

**For Screenshots:**
- Use high resolution (min 1920x1080)
- Ensure readability
- Use descriptive file names
- Show realistic data scenarios

### File Organization

```
sales-insights-dashboard-excel/
├── data/              # CSV and data files only
├── docs/              # Markdown documentation
├── screenshots/       # PNG/JPG images only
├── *.md              # Root-level documentation
└── *.xlsx            # Excel dashboard files
```

### What NOT to Include

- ❌ Actual customer data or PII
- ❌ Excel temporary files (~$*.xlsx)
- ❌ OS-specific files (.DS_Store, Thumbs.db)
- ❌ Very large files (>10MB)
- ❌ Proprietary or copyrighted content
- ❌ Unrelated files or projects

## Ideas for Contributions

Not sure where to start? Here are some ideas:

### Easy
- Fix typos in documentation
- Add more sample data rows
- Create a FAQ document
- Add tooltips/comments in guides

### Medium
- Create video tutorials
- Design alternative dashboard layouts
- Add more chart examples
- Write troubleshooting guides
- Translate documentation

### Advanced
- Create advanced Excel features (Power Query, Power Pivot)
- Build automated data generation scripts
- Develop VBA macros for automation
- Create Python/R analysis scripts
- Build web-based dashboard version

## Getting Help

Need help with your contribution?

- 📖 Read the [Dashboard Guide](docs/DASHBOARD_GUIDE.md)
- 💬 Open a discussion in GitHub Discussions
- 🐛 Reference similar issues or PRs
- 📧 Reach out to maintainers

## Recognition

Contributors will be:
- Listed in the README (if desired)
- Credited in release notes
- Acknowledged in documentation
- Given a shoutout on social media (with permission)

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

Thank you for making this project better! 🙏

**Questions?** Feel free to open an issue or discussion.
