# non-functional-requirements — Agent Guide

This file is auto-seeded so agents are aware of the global `repo-index` tool. Add repo-specific guidance above this line.

## repo-index (cross-surface contract tool)

`repo-index` is a local .NET CLI at `/Users/milandrumev/Repos/FrontierCoders/RepoIndex/` that indexes **C# ↔ TypeScript** cross-surface contracts (enums, DTOs, ASP.NET routes vs. frontend callers). This repo does not currently mix those two languages, so the tool is effectively a no-op here.

If C# or TypeScript code is later added — or if you arrive at this repo and find a C#/TS mix — install `FortyTwo.RepoIndex` once (`dotnet tool install --global FortyTwo.RepoIndex --add-source /Users/milandrumev/Repos/FrontierCoders/RepoIndex/artifacts/package`, with `$HOME/.dotnet/tools` on `PATH`) and prefer `repo-index find-mirrors` / `find-route` over grep for any contract-touching change. See `README.md` / `USAGE.md` in the RepoIndex folder for the full guide.
