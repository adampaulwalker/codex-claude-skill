# Contributing to Codex-Claude Skill

Thank you for your interest in contributing! This project is community-driven and welcomes contributions.

## How to Contribute

### 🐛 Report Bugs

If you find a bug:
1. Check if it's already reported in [Issues](https://github.com/adampaulwalker/codex-claude-skill/issues)
2. If not, create a new issue with:
   - Clear title
   - Steps to reproduce
   - Expected vs actual behavior
   - Your environment (OS, Claude Code version, Codex CLI version)
   - Screenshots if applicable

### 💡 Suggest Features

Have an idea? Create an issue with:
- Clear description of the feature
- Use case / problem it solves
- Example usage (if applicable)

### 📖 Improve Documentation

Documentation improvements are always welcome:
- Fix typos
- Clarify instructions
- Add examples
- Improve screenshots

### 🔧 Submit Code

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Test thoroughly
5. Commit with clear messages
6. Push to your fork
7. Create a Pull Request

### Code Guidelines

- Keep the SKILL.md under 500 lines
- Maintain compatibility with Claude Code and Codex CLI latest versions
- Add comments for complex logic
- Update documentation for any changes

## Development Setup

1. Fork and clone the repo
2. Install the skill locally: `cp SKILL.md ~/.claude/skills/codex/`
3. Test in Claude Code
4. Make changes to SKILL.md
5. Copy changes back: `cp ~/.claude/skills/codex/SKILL.md ./SKILL.md`
6. Test again

## Testing Checklist

Before submitting a PR, verify:
- [ ] Skill loads in Claude Code without errors
- [ ] `/codex` command appears in autocomplete
- [ ] Description triggers correctly ("review", "check", "validate", "codex")
- [ ] Reviews work for uncommitted changes
- [ ] Reviews work for specific files
- [ ] Error messages are helpful
- [ ] Documentation is updated
- [ ] SCREENSHOTS.md reflects any UI changes

## Pull Request Process

1. Update README.md with details of changes (if applicable)
2. Update SKILL.md version number (semantic versioning)
3. Update SCREENSHOTS.md if workflow changed
4. The PR will be merged once reviewed and approved

## Community Standards

- Be respectful and inclusive
- Help others learn and grow
- Assume good intent
- Focus on constructive feedback

## Questions?

Open an issue with the "question" label or reach out via discussions.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for making this skill better! 🙏**
