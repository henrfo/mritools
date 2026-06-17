# Contributing

Three ways to contribute:

**1. Use the form** — go to [openmritools.com/contribute](https://openmritools.com/contribute). Suggest a new tool or flag an edit. Takes 30 seconds. No account needed. Your submission becomes a public GitHub Issue automatically.

**2. Open a GitHub Issue** — go to [Issues](https://github.com/openmritools/openmritools.github.io/issues) and create one directly. Use the `suggestion` or `edit` label.

**3. Open a pull request** — each tool is a YAML entry in `_data/tools/`. Add a new entry with:

```yaml
- name: Tool Name
  description: One sentence. What it does, not why it matters.
  url: https://...
  language: Python
  modality: multi        # fMRI | structural | diffusion | ASL | multi
  github: owner/repo     # optional — enables health tracking
  date_added: 2026-06-17
```

Place it in the right category file. `url` should point to the most useful page (docs > repo > homepage). No marketing language.
