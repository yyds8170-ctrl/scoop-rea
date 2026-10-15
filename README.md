# scoop-rea

A personal Scoop **bucket** for [rea-ghidra-setup](https://github.com/yyds8170-ctrl/rea-ghidra-setup) — a
cross-platform, noncommercial installer/orchestrator that sets up [Ghidra](https://ghidra-sre.org/) and
[rea-agents (REA)](https://github.com/morluto/rea-agents).

## Install

```powershell
scoop bucket add rea https://github.com/yyds8170-ctrl/scoop-rea
scoop install rea/rea-ghidra
```

Then:

```powershell
rea-ghidra install   # fetch Ghidra/JDK/Node at runtime
rea-ghidra verify    # end-to-end checks
```

## Updating

```powershell
scoop update rea/rea-ghidra
```

The manifest uses `checkver: github` with `autoupdate`; maintainers can run
`scoop checkver -u` to refresh hashes after an upstream release.

## Legal / Trademarks

Maintained by **洋洋 (yyds8170-ctrl)** under PolyForm Noncommercial 1.0.0. This is an **independent
third-party** project; it does not bundle or redistribute Ghidra or REA binaries and is not affiliated with
or endorsed by the NSA, the Ghidra project, or morluto. "Ghidra" and "REA" are names of their respective
owners. See upstream [NOTICE](https://github.com/yyds8170-ctrl/rea-ghidra-setup/blob/main/NOTICE) and
[TRADEMARKS](https://github.com/yyds8170-ctrl/rea-ghidra-setup/blob/main/TRADEMARKS.md).
