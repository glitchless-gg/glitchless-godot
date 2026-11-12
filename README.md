# Glitchless for Godot

**Coding agents can build a game. They can't see anyone play it. Glitchless lets them.**

Glitchless is game observability for coding agents. This addon times every frame on every player's device and names
each hitch's likely cause, groups errors and crashes with what the player did just before, and shows where players
quit. Your coding agent (Claude Code, Codex, Cursor) reads it over MCP and fixes the next build. For Godot 4.5 and
later; this is version 0.6.7.

This repository is the addon alone, copied from [glitchless-gg/glitchless](https://github.com/glitchless-gg/glitchless) at each release so the Godot
Asset Library can install it. Report issues and send changes there.

## Install

1. In the editor's AssetLib tab, search for Glitchless and install it (once it's listed there), or copy
   `addons/glitchless/` into your project's `addons/`.
2. Turn on the plugin under *Project Settings → Plugins*. It adds the `Glitchless` autoload.
3. Call `Glitchless.init(...)` when the game starts.

Or let your coding agent do it: [the setup steps](https://www.glitchless.gg/godot.html). The
[addon's README](addons/glitchless/README.md) has every option, and [PRIVACY.md](addons/glitchless/PRIVACY.md) lists
what each privacy mode sends (anonymous by default).

Free on [Glitchless Cloud](https://www.glitchless.gg/pricing.html) (5,000 play sessions a month), or run the
open-source server yourself. MIT licence.
