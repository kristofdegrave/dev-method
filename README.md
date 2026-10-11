# dev-method

Analysis-first development method for Claude Code, shipped as a plugin marketplace.

## Plugins

| Plugin | What it holds |
|---|---|
| `method` | The contribution workflow (issue, implement, review, fix, clean up) and the `init` skill that installs the method into a project and upgrades it later. |

## Install

`method` depends on Matt Pocock's `mattpocock-skills` plugin, so both marketplaces are added:

```
/plugin marketplace add mattpocock/skills
/plugin marketplace add kristofdegrave/dev-method
/plugin install method@dev-method
```

## Develop

Load the plugin from a working copy instead of the marketplace:

```
claude --plugin-dir plugins/method
```
