# Contribution Guidelines

Thank you for your interest in contributing to `awesome-opencode`! Your contributions help make this list a great resource for the community.

## How to Add an Entry

**Submit a Pull Request** adding your entry directly to the README.

### Step 1: Fork & Clone

```bash
git clone https://github.com/YOUR-USERNAME/awesome-opencode.git
cd awesome-opencode
```

### Step 2: Add Your Entry

Add your entry to the appropriate section in `README.md` in **alphabetical order**.

Use this format:

```html
<details>
  <summary><b>Your Project Name</b> <img src="https://badgen.net/github/stars/owner/repo" height="14"/> - <i>Short description</i></summary>
  <blockquote>
    Full description here.
    <br><br>
    <a href="https://github.com/owner/repo">🔗 <b>View Repository</b></a>
  </blockquote>
</details>
```

**Sections:**
- **Plugins** - OpenCode plugins and extensions
- **Themes** - Color schemes and visual themes
- **Agents** - AI agents and subagents
- **Projects** - Tools, GUIs, integrations, and utilities
- **Resources** - Guides, templates, and configurations

### Step 3: Submit PR

```bash
git checkout -b add-my-project
git add README.md
git commit -m "docs: add my-project to plugins"
git push origin add-my-project
```

Then open a Pull Request on GitHub.

## Entry Requirements

Before submitting, ensure your entry:

- [ ] **Is relevant** - Directly related to OpenCode
- [ ] **Is public** - Repository is publicly accessible
- [ ] **Is maintained** - Active commits within the last 6 months
- [ ] **Is not a duplicate** - Check the list first
- [ ] **Is alphabetically ordered** - Placed correctly in the section
- [ ] **Uses correct format** - Collapsible details with star badge

## Quick Copy Templates

### Plugin
```html
<details>
  <summary><b>opencode-example</b> <img src="https://badgen.net/github/stars/username/opencode-example" height="14"/> - <i>Brief description of what it does</i></summary>
  <blockquote>
    Longer description with more details about the plugin.
    <br><br>
    <a href="https://github.com/username/opencode-example">🔗 <b>View Repository</b></a>
  </blockquote>
</details>
```

### Project
```html
<details>
  <summary><b>My Project</b> <img src="https://badgen.net/github/stars/username/my-project" height="14"/> - <i>Brief description</i></summary>
  <blockquote>
    Longer description with more details.
    <br><br>
    <a href="https://github.com/username/my-project">🔗 <b>View Repository</b></a>
  </blockquote>
</details>
```

### Theme
```html
<details>
  <summary><b>My Theme</b> <img src="https://badgen.net/github/stars/username/opencode-my-theme" height="14"/> - <i>Color scheme description</i></summary>
  <blockquote>
    Theme description and color details.
    <br><br>
    <a href="https://github.com/username/opencode-my-theme">🔗 <b>View Repository</b></a>
  </blockquote>
</details>
```

## What Happens Next?

A maintainer will review your PR and:
- Verify the project meets our guidelines
- Check for security concerns
- Merge if approved, or request changes

Thank you for contributing to the OpenCode community!
