# Video Summarizer Extension - AI-Powered Platform

## Project Overview
Chrome extension for AI-powered video summarization using transcripts and visual analysis

## Technology Stack
- **Language**: JavaScript
- **Build Tool**: Webpack
- **Deployment**: GitHub Pages

## Key Features
- Modern responsive web application
- TypeScript for type safety
- Chrome extension integration
- Browser interaction capabilities

## Core Dependencies

## Development Commands
```bash
# Production build
npm run build

# Development server
npm run dev

# Run tests
npm run test

# Lint code
npm run lint

```

## Project Structure
```
video-summarizer-extension/
├── src/                     # Source code
├── manifest.json            # Configuration
└── package.json             # Dependencies
```

## Deployment
- **Platform**: GitHub Pages
- **URL**: 
- **Build**: Static site generation
- **CI/CD**: Automated deployment via gh-pages

## Development Notes

## Chrome Extension Features
- **Manifest V3**: Modern extension architecture
- **Content Scripts**: Page interaction capabilities
- **Background Service Worker**: Background processing
- **Popup Interface**: React-based popup UI
- **Storage API**: Local data persistence

## Extension Setup
1. Build the extension with `npm run build`
2. Load unpacked extension in Chrome Developer Mode
3. Configure permissions as needed
4. Test functionality in target websites

## Testing & Quality
- ESLint for code quality
- Jest for unit testing

## Future Enhancements
- Cross-browser compatibility
- Advanced extension features
- Integration with more platforms
- Enhanced security features
- Offline functionality



## 🧭 Claude Code Navigation

### Quick Commands
**Development Scripts:**
- `build`: webpack --mode=production
- `dev`: webpack --mode=development --watch
- `test`: jest
- `lint`: eslint src/**/*.js

**Key Files:**
- `package.json` - Dependencies and scripts configuration
- `CLAUDE.md` - Comprehensive development guide for Claude
- `manifest.json` - Chrome extension manifest

**Key Directories:**
- `src/` - Source code and main application logic

**Claude Code Files:**
- `.claude/project-context.md` - Project overview and structure
- `.claude/coding-standards.md` - Development guidelines and patterns
- `.claude/commands/` - Custom Claude commands for common tasks
- `.claude/context/` - Domain-specific development context


### Quick Reference

**Common Tasks:**
- Start development: `npm run dev` or `bun dev`
- Build project: `npm run build` or `bun build`
- Run tests: `npm run test` or `bun test`
- Lint code: `npm run lint` or `bun lint`

**File Patterns:**
- Components: `components/**/*.tsx`
- Pages: `app/**/*.tsx` or `pages/**/*.tsx`
- Utilities: `lib/**/*.ts`
- Styles: `**/*.css` or use Tailwind classes
- Tests: `**/*.test.ts` or `**/*.spec.ts`

**Development Tips:**
- Use TypeScript for type safety
- Follow existing component patterns
- Utilize shadcn/ui components
- Implement responsive design with Tailwind
- Test changes before committing

