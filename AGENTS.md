# non-functional-requirements — Agent Guide

This file is auto-seeded so agents are aware of the global `repo-index` tool. Add repo-specific guidance above this line.

## Repo Index Tool

- `repo-index` is installed globally on this machine and caches per-repo metadata in `.repo-index/`.
- Use `repo-index find-mirrors <Symbol> --root <repo-root>` before changing C# enums, TypeScript enum mirrors, DTOs, TypeScript interfaces/types, or cross-surface contracts.
- Use `repo-index find-route <route> --method <verb> --root <repo-root>` before changing ASP.NET route templates, frontend API callers, or endpoint contracts.
- Treat output as navigation evidence and inspect the matching source files.
