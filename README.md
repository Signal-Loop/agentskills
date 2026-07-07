# Agent Skills

Reusable UnityCodeAgent skills packaged in the standard Agent Skills repository layout.

This repository is compatible with the `npx skills` CLI from `vercel-labs/skills`.

## Skills

- `executing-csharp-scripts-in-unity-editor`
- `kanban-task-workflow`
- `unity-game-player`
- `unitycodeagent`

## Install

Install all skills:

```powershell
npx skills add signal-loop/agentskills --all -y
```

Install for Codex only:

```powershell
npx skills add signal-loop/agentskills --agent codex --all -y
```

Install one skill:

```powershell
npx skills add signal-loop/agentskills@unitycodeagent -y
```

List skills without installing:

```powershell
npx skills add signal-loop/agentskills --list
```

Update installed skills:

```powershell
npx skills update
```

## Layout

Skills are stored under `skills/<skill-name>/SKILL.md`, which is the canonical discovery path for the `skills` CLI.
