# Contributing to PowerPoint Template Repository

Thank you for your interest in contributing to this PowerPoint template repository! This document provides guidelines for adding templates and improving the repository.

## 🎯 How to Contribute

### Adding New Templates

1. **Choose the Right Category**
   - Review the 14 existing categories in the `templates/` directory
   - Select the category that best fits your template
   - If no category fits, propose a new one via an issue first

2. **Template Quality Standards**
   - Templates must be fully editable (all elements unlocked)
   - Use vector shapes when possible (avoid rasterized images for shapes)
   - Include placeholder text that clearly indicates what should be replaced
   - Test compatibility with PowerPoint, Keynote, and Google Slides
   - Ensure professional design quality with strong visuals
   - Use standard slide sizes (16:9 or 4:3)

3. **File Naming Convention**
   Follow this format:
   ```
   [category]-[type]-[variant].pptx
   ```
   
   Examples:
   - `timeline-project-horizontal.pptx`
   - `dashboard-sales-quarterly.pptx`
   - `orgchart-hierarchical-3levels.pptx`
   - `funnel-marketing-5stages.pptx`

4. **Documentation Requirements**
   - If adding a new template type, update the category README.md
   - Include brief description of the template's purpose
   - Note any special features or usage tips
   - Specify any industry-specific considerations

### Updating Category Documentation

1. **README Updates**
   - Keep instructions clear and concise
   - Add new template types to the overview
   - Include practical examples and use cases
   - Update best practices based on user feedback

2. **Main README Updates**
   - Update category descriptions if significantly changed
   - Add new categories to the table of contents
   - Keep the structure overview current

## 📋 Submission Process

1. **Fork the Repository**
   - Create a fork of the repository to your account
   - Clone your fork locally

2. **Create a Branch**
   ```bash
   git checkout -b add-template-[description]
   ```

3. **Add Your Template**
   - Place .pptx file in appropriate category folder
   - Follow naming conventions
   - Update category README if needed

4. **Commit Changes**
   ```bash
   git add .
   git commit -m "Add [template-name] to [category]"
   ```

5. **Push and Create Pull Request**
   ```bash
   git push origin add-template-[description]
   ```
   - Create a pull request with clear description
   - Include screenshots or preview images if possible

## ✅ Quality Checklist

Before submitting, ensure:

- [ ] Template is saved in correct category folder
- [ ] File name follows naming convention
- [ ] Template is fully editable (no locked elements)
- [ ] Placeholder text is clear and descriptive
- [ ] Colors can be easily customized
- [ ] Template tested in PowerPoint
- [ ] Template tested in Google Slides (if possible)
- [ ] No copyrighted content without permission
- [ ] Category README updated (if needed)
- [ ] Template includes multiple slide variations (if applicable)

## 🎨 Design Guidelines

### Color Schemes
- Use professional, business-appropriate colors
- Provide color palette that can be easily customized
- Ensure sufficient contrast for readability
- Consider color-blind accessibility

### Typography
- Use standard, widely-available fonts
- Minimum font size: 18pt for body text
- Minimum font size: 24pt for presentation text
- Maximum 2-3 font families per template

### Layout
- Maintain consistent margins and spacing
- Use grid alignment for professional appearance
- Include white space for visual breathing room
- Ensure logical visual hierarchy

### Content
- Use placeholder text that guides the user
- Include example data where appropriate
- Provide multiple layout options when useful
- Keep designs clean and uncluttered

## 🚫 What Not to Include

- Copyrighted images or graphics without permission
- Low-quality or pixelated images
- Templates with locked/protected elements
- Files with macros or embedded code
- Templates promoting specific products/services
- Offensive or inappropriate content

## 📜 Licensing

By contributing to this repository, you agree that:
- Your contributions are your original work or you have rights to share them
- You provide necessary licenses for any included assets
- You understand templates may be used by others per repository license
- You retain copyright but grant usage rights as per repository terms

## 🤔 Questions or Suggestions?

- Open an issue for discussions about new categories
- Use pull request comments for specific template feedback
- Check existing issues before opening new ones
- Be respectful and constructive in all communications

## 🙏 Recognition

Contributors will be recognized in:
- Pull request acknowledgments
- Repository contributor list
- Category documentation (for significant contributions)

Thank you for helping make this template repository more valuable for everyone!
