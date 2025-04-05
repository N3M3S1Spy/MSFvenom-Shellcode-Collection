# MSFvenom Shellcode: Launch calc.exe (Windows x64)
# Generated on: 2025-04-04
# Description: Spawns calc.exe when executed.

## Commands
#### For calc_x64.bin
```
msfvenom -p windows/x64/exec CMD=calc.exe -f raw -o calc_x64.bin
```
#### For calc_x64.hex
```
msfvenom -p windows/x64/exec CMD=calc.exe -f c -o calc_x64.hex
```
