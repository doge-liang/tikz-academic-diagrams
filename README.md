# tikz-academic-diagrams

TikZ academic diagram creation guidelines and templates for publication-quality LaTeX figures.

## Installation

```bash
npm install tikz-academic-diagrams
```

## Usage

This package provides TikZ templates and guidelines for creating academic diagrams, especially for machine learning architectures.

### Available Templates

- `base-template.tex` - Generic diagram starter
- `neural-network.tex` - Multi-layer neural network
- `attention-mechanism.tex` - Self-attention mechanism
- `cnn-architecture.tex` - Convolutional neural network layers

### Copy Templates

```bash
# Copy a template to your project
cp node_modules/tikz-academic-diagrams/assets/base-template.tex my-diagram.tex
cp node_modules/tikz-academic-diagrams/assets/neural-network.tex my-network.tex
```

### Compile TikZ Files

```bash
# Using lualatex
lualatex --output-format=dvi my-diagram.tex
dvisvgm my-diagram.dvi --font-format=woff

# Or use the npm script from this package
npm run tikz
```

## Features

- **Publication Quality**: Designed for academic papers and presentations
- **Math Formula Support**: Native LaTeX math rendering
- **Precise Positioning**: Fine-grained control over layout
- **Architecture Templates**: Pre-built templates for ML architectures
- **Best Practices**: Includes styling guidelines and patterns

## Claude Skill

This package also works as a Claude skill. When used with Claude Code, it provides:

- Interactive guidance for TikZ diagram creation
- Template selection based on diagram type
- Styling recommendations
- Troubleshooting help

## License

MIT
