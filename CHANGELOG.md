# Changelog

## 2.5.5

### Improvements

- **Performance**: Improved cache behavior for faster repeated analyses
- **Better file exclusion**: Exclusion patterns now support glob syntax, making file filtering more accurate and flexible
- **Clearer status indicators**: Severity icons in CodeLens and the Problems panel have been simplified for easier reading at a glance
- **Help links**: Quick access links to documentation and resources are now available directly in the sidebar


### Fixes

- Fixed parsing issues with dependencies that have null or empty versions
- Improved detection of dependencies with non-standard formatting
- Fixed edge cases in dependency detection across all supported ecosystems

### Patches

- Updated internal dependencies for improved stability and security

---

## 2.5.0 - Initial Release

First public release of Dep-Man on the VS Code Marketplace.

### Features

- Multi-ecosystem dependency analysis: npm (`package.json`), pip (`requirements.txt`), and pub (`pubspec.yaml`)
- CodeLens indicators showing dependency status inline
- Hover tooltips with version details and update info
- Diagnostics integration with the Problems panel
- Inline warning decorations for outdated dependencies
- One-click dependency updates via CodeLens actions
- Bulk update all dependencies at once
- Workspace-wide analysis across multiple package files
- Sidebar webview with analysis overview and statistics
- Configurable folder exclusion patterns
- GitHub token support for enhanced API rate limits
- Auto-analyze on file save and open
- Keyboard shortcuts for quick analysis and updates
