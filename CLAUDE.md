# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a documentation repository containing comprehensive reference materials for Claude Code and SuperClaude framework tools. It serves as both a quick reference cheat sheet and an interactive learning resource with memory palace techniques.

## Repository Architecture

### Core Content Files
- `index.html`: Main reference documentation (47KB) - comprehensive command tables, workflows, and configuration
- `claude-superclaude-complete-guide.html`: Interactive memory palace (36KB) - visual learning with city-themed districts
- `Claude Code Cheat Sheet.xlsx`: Offline Excel reference for enterprise distribution
- `README.md`: Project overview and getting started guide
- `docs/`: Comprehensive project documentation suite

### Documentation Structure
The repository follows a multi-format strategy:
- **HTML files**: Self-contained with embedded CSS/JS, zero external dependencies
- **Memory Palace**: City metaphor with districts (Central Hub, Creative Quarter, Industrial Zone, Security District, etc.)
- **Cross-referenced content**: Internal linking between main reference and interactive learning
- **Progressive disclosure**: Information organized from basic to advanced complexity

## Development Workflow

Since this is a documentation-only repository with no build processes:

### Content Updates
```bash
# No build commands needed - direct HTML editing
# Open files directly in browser for testing
# All styling and scripts are embedded
```

### Quality Validation
```bash
# Manual testing across browsers and devices
# Accessibility testing using browser dev tools
# Link validation by clicking through navigation
# Content accuracy verification against current tools
```

### Publishing
```bash
# GitHub Pages deployment is automatic from main branch
# Files are ready for immediate browser consumption
# No compilation or build steps required
```

## Content Architecture

### Dual Learning Approach
The repository implements two complementary learning methodologies:
1. **Traditional Reference** (`index.html`): Structured tables, search-friendly, printable
2. **Memory Palace** (`complete-guide.html`): Visual learning using Turkish "Zihin Sarayı" methodology

### Information Organization
- **Command Reference**: Organized by tool type (Claude Code CLI vs SuperClaude Framework)
- **Cognitive Personas**: 9 specialized AI personas with specific capabilities and use cases
- **MCP Server Integration**: Context7, Magic, Sequential, Morphllm, Playwright, Serena
- **Workflows**: Real-world development scenarios with step-by-step examples

### Cross-Reference System
Content is interconnected through:
- Bidirectional navigation between HTML files
- Context-aware internal linking
- Progressive learning paths for different user types
- Multi-format content synchronization

## File Modification Guidelines

### HTML Files
- Maintain self-contained structure (no external dependencies)
- Preserve embedded CSS styling for consistency
- Keep table structures intact for command references
- Test navigation and interactive features after changes
- Ensure responsive design principles are maintained

### Documentation Updates
- Verify all commands and examples are current with tool versions
- Maintain consistent formatting across all table structures
- Update cross-references when adding new sections
- Keep memory palace district organization logical and thematic

### Content Synchronization
- Excel file should reflect HTML content changes
- README.md should match current feature set
- docs/ folder documentation should stay current with main files
- Internal links must be validated after structural changes

## Quality Standards

### Accessibility Requirements
- HTML language attribute must match content language (currently needs fix from "tr" to "en")
- Table headers require scope attributes for screen reader compatibility
- Color contrast ratios must meet WCAG 2.1 AA standards
- Keyboard navigation must be fully functional

### Performance Standards
- Files must remain self-contained with zero external HTTP requests
- Total file sizes should stay under 50KB each for fast loading
- Interactive features should work smoothly on mobile devices
- Print styles must provide clean, professional output

### Content Accuracy
- All command syntax must be verified against current tool versions
- Examples must be tested and functional
- Configuration templates must use valid JSON formatting
- Cross-references must link to existing content sections