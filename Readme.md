# Indented.ScriptAnalyzerRules

Script based custom rules for PSScriptAnalyzer.

## Installing the module

```powershell
Install-Module Indented.ScriptAnalyzerRules
```

## Using the module with PSScriptAnalyzer

Each of the rules is written to be used by PSScriptAnalyzer. Script analyzer must be set to use a custom rule path, the path can either be used on the command line or added to a PSScriptAnalyzerSettings.psd1 file.

```powershell
Invoke-ScriptAnalyzer -Path C:\Path\To\File\file.ps1 -CustomRulePath '~\Documents\Modules\Indented.ScriptAnalyzerRules'
```
