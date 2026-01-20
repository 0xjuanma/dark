# Dark: One Dark Theme to Rule Them All

A collection of high-contrast dark themes for VS Code with vibrant neon accents and minimalist design for an immersive coding experience.

## Available Themes

- **Dark Neon** - Red/cyan neon theme with bright accents
- **Dark Purple** - Purple/magenta accent variation
- **Dark Lime** - Green/lime accent variation
- **Dark Sunset** - Orange/blue accent variation

## Installation

### Option 1: Install from VS Code Marketplace (Recommended)

Search for "Dark: One Dark Theme to Rule Them All" in the VS Code Extensions marketplace and install.

### Option 2: Install from VSIX (Local Development)

1. Download the `.vsix` file from the releases
2. Open VS Code
3. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
4. Type "Extensions: Install from VSIX"
5. Select the downloaded `.vsix` file

### Option 3: Manual Installation (Development)

1. Clone this repository
2. Copy theme files to your VS Code themes directory:
   - **macOS**: `~/Library/Application Support/Code/User/themes/`
   - **Windows**: `%APPDATA%\Code\User\themes/`
   - **Linux**: `~/.config/Code/User/themes/`
3. Reload VS Code and select theme from Color Theme picker

## Usage

1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
2. Type "Preferences: Color Theme"
3. Select your desired Dark theme from the list

## Development

### Prerequisites

- Node.js and npm
- VS Code
- VS Code Extension Manager (vsce)

```bash
npm install -g vsce
```

### Building the Extension

1. Install dependencies:
```bash
npm install
```

2. Package the extension:
```bash
vsce package
```

This creates a `.vsix` file that can be installed locally or published to the marketplace.

### Testing Locally

1. Package the extension:
```bash
vsce package
```

2. Install locally:
```bash
code --install-extension dark-theme-collection-0.1.0.vsix
```

3. Test all themes by switching between them in VS Code

### Publishing to Marketplace

1. Create a publisher account at https://marketplace.visualstudio.com/
2. Login to vsce:
```bash
vsce login <publisher-name>
```

3. Publish:
```bash
vsce publish
```

## Theme Features

- **High Contrast**: Black backgrounds with bright neon accents
- **Minimalist Design**: Clean, uncluttered interface
- **Syntax Highlighting**: Optimized for multiple programming languages
- **Consistent Experience**: Unified design language across all variants

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

See [LICENSE](LICENSE) file for details.