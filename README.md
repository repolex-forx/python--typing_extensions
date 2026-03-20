# Repolex Knowledge Graph of python/typing_extensions

RDF knowledge graph data for [python/typing_extensions](https://github.com/python/typing_extensions), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download python/typing_extensions
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 583f9f6e6175f891a0ebd56dfe41ad9411b233b9.nq.gz
│   ├── 5c21a6df8966b2de3d3c9a62280803321fe2ea20.nq.gz
│   ├── 62d1e46c7217d63f11200ae74d2c7519aeee1cef.nq.gz
│   ├── 637292647b927a66c3fa4a0c32230ca94855c8b8.nq.gz
│   ├── 7b1611cb8b0285fa82a7dca04a6531d8b938af93.nq.gz
│   ├── 7bb6156d733673578fc147a2f3f2de571a380663.nq.gz
│   ├── 82d1c2dc2c406f14214a75172d97d74f1fd03a1d.nq.gz
│   ├── 98f6213580d3e66f67ebd6fe81ba167327865561.nq.gz
│   ├── e2889ce0ebb5f12a25b4c09fe99b6d961f0edac5.nq.gz
│   └── feda4cf1e4446aa94cbbf292528c369964eee1f7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── faa7ce22752123e616a08c9e4fe81c3b234c1354.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 16 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[python/typing_extensions](https://github.com/python/typing_extensions)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
