# Shellcode: Launch calc.exe

**Platform:** Windows  
**Architecture:** x86  
**Payload:** windows/exec  
**Command:** calc.exe  
**Format:** raw (binary) + hex (C-style)  
**Generated with:** MSFvenom

## Description

This shellcode launches the built-in Windows Calculator (`calc.exe`).  
Useful for testing code injection or verifying shellcode execution.

## Usage

Execute this shellcode in a 32-bit Windows process context.  
It will spawn a calculator window upon successful execution.

## Notes

- Runs without network or elevated privileges.
- Pure exec payload – no staging or reverse connection.
- Works reliably on most Windows versions with GUI support.
