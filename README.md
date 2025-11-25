# Percify Documentation

Comprehensive documentation for Percify AI - the creative AI platform for generating avatars, videos, and voice content.

## 📚 What's Inside

This repository contains:

- **Core Feature Guides** - Detailed documentation for Avatar Studio, Image-to-Video, and Voice Cloning
- **API Reference** - Complete REST API documentation for all Percify endpoints
- **User Guides & Tutorials** - Step-by-step guides for getting started and advanced features
- **SDK Integration** - Examples for JavaScript, Python, and other languages
- **Webhooks** - Real-time event notifications setup and handling

## 🚀 Quick Start

### View Documentation

Visit the live documentation at [docs.percify.io](https://docs.percify.io) (or your custom domain)

### Local Development

1. Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

2. Preview the documentation locally:

```bash
cd /path/to/percify-docs
mintlify dev
```

3. Open your browser to `http://localhost:3000`

## 📁 Documentation Structure

```
percify-docs/
├── docs.json                 # Mintlify configuration
├── index.mdx                 # Homepage
├── quickstart.mdx           # Quick start guide
├── percify/                 # Core feature guides
│   ├── avatar-studio.mdx
│   ├── image-to-video.mdx
│   ├── voice-cloning.mdx
│   ├── credits.mdx
│   ├── api-auth.mdx
│   └── ...
├── api-reference/           # API documentation
│   ├── introduction.mdx
│   ├── avatars/
│   │   ├── overview.mdx
│   │   ├── generate.mdx
│   │   └── list.mdx
│   ├── video-studio/
│   │   └── overview.mdx
│   ├── audio/
│   │   └── overview.mdx
│   └── user/
│       └── overview.mdx
└── guides/                  # User guides & tutorials
    ├── getting-started.mdx
    ├── prompt-engineering.mdx
    ├── sdk-integration.mdx
    └── webhooks.mdx
```

## 📊 Documentation Coverage

- ✅ **11** Core Feature Guides
- ✅ **7** API Reference Sections
- ✅ **4** Comprehensive Tutorials
- ✅ **38** Total Documentation Files
- ✅ **150+** Code Examples
- ✅ **Multiple Languages** (JavaScript, Python, PHP, Ruby, cURL)

## ✨ Features

### Core Guides

- **Avatar Studio** - Complete guide to AI avatar generation with prompt engineering tips
- **Image-to-Video** - Transform static images into animated videos
- **Voice Cloning** - Clone voices and generate natural speech in 30+ languages

### API Documentation

- **Avatar API** - Generate, manage, and publish AI avatars
- **Video Studio API** - Create animated videos with motion and effects
- **Audio & Voice API** - Voice cloning and text-to-speech
- **User & Credits API** - Account management and usage tracking

### Tutorials & Guides

- **Getting Started** - Complete beginner's guide from signup to first creation
- **Prompt Engineering** - Master the art of writing effective prompts
- **SDK Integration** - Official SDKs and integration examples
- **Webhooks** - Real-time event notifications setup

## 🛠️ Contributing

### Adding New Documentation

1. Create a new `.mdx` file in the appropriate directory
2. Add frontmatter with `title` and `description`
3. Update `docs.json` to include the new page in navigation
4. Test locally with `mintlify dev`
5. Submit a pull request

### Documentation Standards

- Use clear, concise language
- Include code examples in multiple languages when applicable
- Add visual elements (Cards, Accordions, Tabs) for better UX
- Follow existing file structure and naming conventions
- Test all code examples before committing

## 🔧 Configuration

The documentation is configured via `docs.json`:

```json
{
  "name": "Percify Docs",
  "theme": "mint",
  "colors": {
    "primary": "#FFD700",
    "light": "#F5B544",
    "dark": "#1A1A1A"
  },
  "navigation": {
    "tabs": [
      { "tab": "Guides", "groups": [...] },
      { "tab": "API Reference", "groups": [...] }
    ]
  }
}
```

## 📝 Publishing Changes

Changes are automatically deployed when pushed to the main branch:

1. Make your changes locally
2. Test with `mintlify dev`
3. Commit and push to GitHub
4. Documentation updates automatically via GitHub app

## 🐛 Troubleshooting

### Development Issues

- **Preview not loading?** Run `mintlify update` to get the latest CLI version
- **404 errors?** Ensure you're in the directory with `docs.json`
- **Build errors?** Check `docs.json` syntax with a JSON validator

### Common Problems

| Issue | Solution |
|-------|----------|
| Broken links | Verify all file paths in `docs.json` match actual files |
| Missing images | Check image paths are relative to the docs root |
| Code examples not rendering | Ensure proper code block syntax with language tags |

## 📚 Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Percify Dashboard](https://percify.io/dashboard)
- [Percify API](https://api.percify.io/v1)
- [Community Discord](https://discord.gg/percify)

## 🤝 Support

Need help with the documentation?

- **Email:** support@percify.io
- **Discord:** [Join our community](https://discord.gg/percify)
- **Issues:** [GitHub Issues](https://github.com/Suhaib3100/percify-docs/issues)

## 📄 License

This documentation is licensed under [MIT License](LICENSE).

---

Built with ❤️ using [Mintlify](https://mintlify.com)
