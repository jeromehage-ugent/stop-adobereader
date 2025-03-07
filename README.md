## stop-adobereader.hook

Prevents Adobe Reader from being installed with chocolatey. It is just a one line `Throw 'Installation halted.'` pre-install script for the package ID `adobereader`.

## How to use it

1- Copy the folder `stop-adobereader.hook` to `C:\temp`
2- Run this command in PowerShell with as admin:
```
C:\ProgramData\chocolatey\bin\choco.exe install stop-adobereader.hook --version="1.0.0" --source="C:\temp" --force
```

## References
- https://docs.chocolatey.org/en-us/features/hook/
- https://docs.chocolatey.org/en-us/create/commands/pack/
