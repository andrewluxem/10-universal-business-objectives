# 10-universal-business-objectives

Maps supplied work to ten business-objective lenses without claiming unsupported impact.

It produces:

- **Universal Objectives Mapping or Audit:** a working artifact built from supplied facts, labeled inference, and visible missing fields.

It executes the [10 Universal Business Objectives playbook](https://www.andrewluxem.com/playbooks/10-universal-business-objectives). The playbook teaches the framework. This skill runs it and returns a working artifact.

**Static by construction: no dependencies, executable code, telemetry, network calls, remote instructions, auto-update, scheduled work, or background behavior.** It reads only the files in its own skill folder. Nothing happens until a user or agent invokes it.

## Install

Clone and copy the skill into Claude Code:

```bash
git clone https://github.com/andrewluxem/10-universal-business-objectives.git
cp -r 10-universal-business-objectives/skills/10-universal-business-objectives ~/.claude/skills/
```

For Codex, copy the same complete folder to the Codex skills directory:

```bash
cp -r 10-universal-business-objectives/skills/10-universal-business-objectives ~/.codex/skills/
```

Or install it as a Claude Code plugin:

```text
/plugin marketplace add andrewluxem/10-universal-business-objectives
/plugin install 10-universal-business-objectives@10-universal-business-objectives
```

For clients that install from an archive, use the versioned [10-universal-business-objectives v1.0.0 ZIP](https://www.andrewluxem.com/downloads/10-universal-business-objectives-v1.0.0.zip).

## Invoke it

```text
Map this work to the 10 universal business objectives
Use the 10-universal-business-objectives skill.
```

Naming the skill is always valid: `use the 10-universal-business-objectives skill`.

## Files

```text
.claude-plugin/
  plugin.json
  marketplace.json
skills/10-universal-business-objectives/
  assets/universal-objectives-mapping-template.md
  LICENSE.md
  meta.yaml
  references/objective-mapping-standard.md
  SKILL.md
README.md
LICENSE
```

The complete canonical package is copied under `skills/10-universal-business-objectives/`, including every asset, reference, test prompt, source note, changelog entry, and license file present in the source.

## Versioning

Plugin installation is version-pinned. When behavior changes, update the version consistently in `SKILL.md`, `meta.yaml`, `.claude-plugin/plugin.json`, and `.claude-plugin/marketplace.json`, then add a changelog entry. Reinstalling is an explicit update; this repository never auto-updates itself.

## License

MIT. See [LICENSE](LICENSE). The canonical skill folder carries the same authorization in [skills/10-universal-business-objectives/LICENSE.md](skills/10-universal-business-objectives/LICENSE.md).

---

## More playbooks

This skill packages one playbook from the free library at [github.com/andrewluxem/playbooks](https://github.com/andrewluxem/playbooks). Every playbook is free to read, with no email required.
