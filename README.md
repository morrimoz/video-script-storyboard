# Video script and storyboard

**Category: Creative AI workflows | Format: Agent skill**

Script and storyboard a product video around one change, one proof sequence, and one next step. The deliverable is a scene-by-scene handoff a motion designer or editor can build.

This repository contains the writing workflow. It does not render video.

## What it produces

| Input | Output |
| --- | --- |
| A product, an audience, a duration, and the proof you actually have | A script with one job, one hook, and a proof module per major claim |
| That script | Scene cards with on-screen copy, optional voiceover, timing, and motion notes |

See [SKILL.md](SKILL.md) for the frameworks, the storyboard template, and the checks that catch a feature dump.

## Install

For Cursor:

```bash
mkdir -p ~/.cursor/skills
git clone https://github.com/morrimoz/video-script-storyboard.git ~/.cursor/skills/video-script-storyboard
```

For Claude Code, use `~/.claude/skills/video-script-storyboard`. For Codex, use `~/.codex/skills/video-script-storyboard`. Start a new agent session after installation.

## Example request

```text
Use video-script-storyboard for a 60 second feature film.
One audience, one call to action, and a visible proof shot for each claim.
Do not invent customers or metrics.
```

## Tradeoffs

The skill will not invent customers, metrics, or product behavior. A storyboard is not a finished film. Pair it with a production workflow when you are ready to design frames and cut footage.

## Related tools

- [Directing motion films](https://github.com/morrimoz/directing-motion-films-with-claude-design) - Move from an approved storyboard into style frames and rendered-frame reviews.
- [Talking-head clip review](https://github.com/morrimoz/talking-head-clip-review) - Pick on-camera selects after the script exists.

[MIT license](LICENSE)
