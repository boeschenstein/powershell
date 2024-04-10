# Powershell

## Avoid Screensaver

```ps
$wshell = New-Object -ComObject wscript.shell;
do {
    $wshell.SendKeys('{F13}')
    Sleep 60
} until ($false)
```
