# 🚀 GitHub Setup Instructions

Follow these steps to publish your Codex-Claude skill to GitHub.

## Step 1: Create GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `codex-claude-skill`
3. Description: `A Claude Code skill that integrates OpenAI Codex CLI for independent code reviews - enabling proposer-checker-maker-checker workflows`
4. Set as **Public** ✅
5. **Do NOT** initialize with README, .gitignore, or license (we already have these)
6. Click **Create repository**

## Step 2: Push to GitHub

Once you create the repo, GitHub will show you commands. Use these:

```bash
cd "/Users/adam/Library/Mobile Documents/com~apple~CloudDocs/Claude Projects/codex-claude-skill"

# Add GitHub as remote
git remote add origin https://github.com/adampaulwalker/codex-claude-skill.git

# Push to GitHub
git push -u origin main
```

**Replace `adampaulwalker` with your actual GitHub username!**

## Step 3: Update README Links

After pushing, update these placeholders in README.md:

1. `adampaulwalker` in the badge URLs (lines 4-5)
2. `adampaulwalker` in installation instructions
3. Commit and push the changes:

```bash
# After editing README.md
git add README.md
git commit -m "Update README with actual GitHub username"
git push
```

## Step 4: Configure Repository Settings

On GitHub, go to your repository settings:

### Topics (Recommended)
Add these topics to help people discover your skill:
- `claude-code`
- `codex`
- `openai`
- `code-review`
- `ai-agents`
- `skills`
- `developer-tools`

### About Section
Add:
- Description: "A Claude Code skill for OpenAI Codex code reviews"
- Website: Your blog/portfolio (optional)
- Check: ✅ Packages, ✅ Releases

### Social Preview
Upload `screenshots/04-review-results.png` as the social preview image for nice link previews when shared.

## Step 5: Create a Release (Optional)

1. Go to Releases → Create a new release
2. Tag: `v1.0.0`
3. Title: `Initial Release - Codex Review Skill v1.0.0`
4. Description:
   ```markdown
   Initial release of the Codex review skill for Claude Code.

   ## Features
   - Review uncommitted changes
   - Review specific files
   - Review implementation plans
   - Seamless Claude Code integration
   - Production-ready assessments

   ## Installation
   ```bash
   mkdir -p ~/.claude/skills/codex
   curl -o ~/.claude/skills/codex/SKILL.md https://raw.githubusercontent.com/adampaulwalker/codex-claude-skill/main/SKILL.md
   ```
   ```
5. Click **Publish release**

## Step 6: Share on Social Media

Now you're ready to share! Here are some suggested posts:

### Twitter/X
```
🚀 Just released a new skill for @AnthropicAI Claude Code!

Integrates @OpenAI Codex for independent code reviews - enabling proposer-checker-maker-checker workflows. No more copy/paste between terminals!

⭐ Star: github.com/adampaulwalker/codex-claude-skill

#AI #DevTools #CodeReview
```

### LinkedIn
```
Excited to share my latest project: A Claude Code skill that brings OpenAI Codex reviews into your development workflow!

This enables a "proposer-checker-maker-checker" pattern where Claude Code implements features and Codex provides independent review - all in one terminal session.

Key benefits:
✅ No context switching
✅ Independent AI review
✅ Production-ready assessments
✅ Seamless integration

Perfect for teams that want to catch issues before deployment!

Check it out: github.com/adampaulwalker/codex-claude-skill

#ArtificialIntelligence #SoftwareDevelopment #DeveloperTools
```

### Reddit (r/ClaudeAI, r/programming)
```
[Show HN] Codex Review Skill for Claude Code - Proposer-Checker Workflow

I built a Claude Code skill that integrates OpenAI Codex for independent code reviews.

The problem: When working with Claude Code, I wanted a second AI opinion before committing changes, but switching between tools meant lots of copy/pasting.

The solution: A skill that lets you type `/codex` and get instant Codex reviews inline - no context switching.

Example workflow:
1. Claude implements auth feature
2. Type `/codex`
3. Get detailed review with issues
4. Claude fixes issues
5. `/codex` again → approved!

Screenshots and installation: github.com/adampaulwalker/codex-claude-skill

Would love feedback from the community!
```

### Hacker News
Title: `Show HN: Codex Review Skill for Claude Code – Independent AI Code Reviews`

Link to: `https://github.com/adampaulwalker/codex-claude-skill`

## Step 7: Monitor and Respond

- Watch for stars, forks, and issues
- Respond to questions
- Consider feature requests
- Update documentation as needed

## Need Help?

If you run into issues:
1. Check if remote was added: `git remote -v`
2. Verify you're on main branch: `git branch`
3. Check for authentication issues: Make sure you're logged into GitHub
4. Use SSH instead: `git remote set-url origin git@github.com:adampaulwalker/codex-claude-skill.git`

---

**Ready to launch! 🎉**

Your skill is packaged, documented, and ready to share with the world.
