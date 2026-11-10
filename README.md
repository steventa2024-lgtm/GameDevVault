# GameDev Vault

**A private workspace for game development teams.** Share project files, review asset revisions, and keep conversations and design decisions with the work they describe.

[Open GameDev Vault](https://gamedev-vault-staging-qa-zeropulse.vercel.app) · [Desktop installation guide](https://gamedev-vault-staging-qa-zeropulse.vercel.app/install) · [Latest preview release](https://github.com/steventa2024-lgtm/GameDevVault-Showcase/releases/tag/v1.2.1-preview)

![GameDev Vault workspace showing channel chat, asset revisions, and a rotating 3D model](https://gamedev-vault-staging-qa-zeropulse.vercel.app/assets/gamedev-vault-demo.gif)

## Desktop downloads

Sign in with your existing GameDev Vault account to open the same workspaces, conversations, notes, and files on the web or in the desktop app.

| Platform | Version 1.2.1 Preview |
| --- | --- |
| macOS · Apple Silicon | [Download DMG](https://github.com/steventa2024-lgtm/GameDevVault-Showcase/releases/download/v1.2.1-preview/GameDev-Vault-1.2.1-mac-arm64.dmg) |
| macOS · Intel | [Download DMG](https://github.com/steventa2024-lgtm/GameDevVault-Showcase/releases/download/v1.2.1-preview/GameDev-Vault-1.2.1-mac-x64.dmg) |
| Windows · x64 | [Download EXE](https://github.com/steventa2024-lgtm/GameDevVault-Showcase/releases/download/v1.2.1-preview/GameDev-Vault-1.2.1-win-x64.exe) |

[Release notes](https://github.com/steventa2024-lgtm/GameDevVault-Showcase/releases/tag/v1.2.1-preview) · [SHA-256 checksums](https://github.com/steventa2024-lgtm/GameDevVault-Showcase/releases/download/v1.2.1-preview/SHA256SUMS.txt)

The Mac preview builds are ad-hoc signed and unnotarized. The Windows installer is unsigned. If your operating system blocks installation, you can use the web app.

## What you can do

- **Coordinate in channels.** Invite teammates to private workspaces, send direct messages, and use voice, video, and screen sharing.
- **Review a specific revision.** Switch from the channel feed to Studio View to inspect assets, compare versions, and leave feedback on the revision you reviewed.
- **Edit 3D assets in Design Studio.** Adjust materials and UVs, add decals, preview levels of detail, and save changes as a new Vault revision or export a GLB.
- **Keep project notes connected.** Link shared notes to assets and other notes, then explore those relationships in the Brain graph.

## Get started

1. Sign in on the [website](https://gamedev-vault-staging-qa-zeropulse.vercel.app) or open the desktop app.
2. Create a workspace for your project or join one through a teammate’s invitation.
3. Drop an asset into the Channel Vault, then open it in the Inspector or Studio View for review.

## Supported asset previews

Preview tools depend on the format, file size, and browser. You can download stored originals from the Vault.

| Asset | Available preview |
| --- | --- |
| GLB, self-contained glTF, FBX, and OBJ | Interactive 3D geometry and embedded animation playback where supported. |
| BVH motion capture | Play and scrub motion on the source skeleton. |
| Images, audio, and video | Preview supported formats such as PNG, JPEG, WAV, MP3, MP4, and WebM. |
| Animated GIF, APNG, and WebP | Play the animation and inspect individual frames in a compatible browser. |
| Roblox models and places | Inspect supported part layouts, schematic poses, and effect metadata. Use a companion GLB for original meshes or a Studio recording for rendered effects. |
| Lua, Luau, and supported game source files | Read and copy highlighted source. Supported Unity animation, shader, scene, and config files can be read up to 1 MiB. |
| ZIP and TAR archives | Browse the file list in supported archives. |
| Blender and PSD projects | Inspect file metadata or open a linked companion preview. |
