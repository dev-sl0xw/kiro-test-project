# Project Structure

## Root Directory Layout
```
kiro-test-project/
├── .git/                 # Git version control
├── .kiro/                # Kiro configuration and steering
│   └── steering/         # AI assistant guidance files
├── README.md             # Project documentation
└── index.html            # Main web page
```

## File Organization
- **Single-page application**: All content in `index.html`
- **Embedded styles**: CSS included in HTML `<style>` tags
- **No external dependencies**: Self-contained HTML file
- **Korean content**: All user-facing text in Korean language

## Conventions
- Use semantic HTML5 elements
- Keep styles embedded for simplicity
- Maintain responsive design principles
- Follow Korean typography best practices
- Use meaningful class names in English (e.g., `.container`, `.button`)

## Adding New Content
- Extend `index.html` directly
- Add new styles to existing `<style>` block
- Maintain the clean, minimal design aesthetic
- Ensure Korean text rendering compatibility