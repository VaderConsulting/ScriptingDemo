# ScriptingDemo

VB6 Scripting Control Demo (`ScriptingDemo`) that hosts `msscript.ocx` to load and run VBScript samples (`ASimpleScript.vbs`, customer enum/update scripts) with optional argument list and output pane; includes NorthWind-style `cCustomer` / `colCustomers` helper classes and ADO/Data Environment references. Open `ScriptingDemo.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ScriptingDemo` (`ScriptingDemo.vbp`) | VB6 | WinForms exe | Demo host for Microsoft Script Control + sample VBS |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `ScriptingDemo.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `msscript.ocx`
  - Microsoft ADO 2.5 / Data Environment as referenced by the project

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/ScriptingDemo`.
Company names in `.vbp` files: Somewhere.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
