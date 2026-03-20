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
├── aggregate
│   ├── ast
│   │   ├── 0c70227e221866b74b5cf6b3e251bc67864781ef.nq.gz
│   │   ├── a9be78c5dcf0ce475b3b561b326637ecca2e8e50.nq.gz
│   │   └── faa7ce22752123e616a08c9e4fe81c3b234c1354.nq.gz
│   ├── lsp
│   │   ├── 0c70227e221866b74b5cf6b3e251bc67864781ef.nq.gz
│   │   ├── a9be78c5dcf0ce475b3b561b326637ecca2e8e50.nq.gz
│   │   └── faa7ce22752123e616a08c9e4fe81c3b234c1354.nq.gz
│   └── repolex
│       ├── 0c70227e221866b74b5cf6b3e251bc67864781ef.nq.gz
│       ├── a9be78c5dcf0ce475b3b561b326637ecca2e8e50.nq.gz
│       └── faa7ce22752123e616a08c9e4fe81c3b234c1354.nq.gz
├── blob
│   ├── 06d4cc40a8b2e753329cf1ee648789f14aa70dec.nq.gz
│   ├── 0bb8845f2760e6c50aaeddf3c5a6116fb9fa909b.nq.gz
│   ├── 187303aa4d2fb853f70954e4b1710701da19df7f.nq.gz
│   ├── 4166510a71aab8e482392f3b19a02f60f4119891.nq.gz
│   ├── 424471f08752f8be5e08b2afcf326efbd54d65c1.nq.gz
│   ├── 583f9f6e6175f891a0ebd56dfe41ad9411b233b9.nq.gz
│   ├── 5c21a6df8966b2de3d3c9a62280803321fe2ea20.nq.gz
│   ├── 5e2adbc68babcb096ab21de66711e2baeca67f2c.nq.gz
│   ├── 6075ee91303de8ce9199b6ee7873eb4fec3b169d.nq.gz
│   ├── 62d1e46c7217d63f11200ae74d2c7519aeee1cef.nq.gz
│   ├── 637292647b927a66c3fa4a0c32230ca94855c8b8.nq.gz
│   ├── 75bdb8ebb1c57b6d88158ab19a8df7f8c5440035.nq.gz
│   ├── 77f1a309681d8a3983e2aaeb7aac354d648bf5a7.nq.gz
│   ├── 7b1611cb8b0285fa82a7dca04a6531d8b938af93.nq.gz
│   ├── 7bb6156d733673578fc147a2f3f2de571a380663.nq.gz
│   ├── 806f8331d2b161598dea9ba11431383bc2aadbca.nq.gz
│   ├── 82d1c2dc2c406f14214a75172d97d74f1fd03a1d.nq.gz
│   ├── 8e84b8826d2b666dec9669ab9e761f5ac701253f.nq.gz
│   ├── 95bb873572e3153ffca4b1148be29d73bb33dc54.nq.gz
│   ├── 98f6213580d3e66f67ebd6fe81ba167327865561.nq.gz
│   ├── a551dcb976641e559dae4698b7c6d045dc850391.nq.gz
│   ├── b3fb143ccf15d9ce7c639e8592d40d6f355cca99.nq.gz
│   ├── ca537456b1c3a54b761b64c816417de169024785.nq.gz
│   ├── cd327aae1cd619b7db0f01d27ef33be8fd837f16.nq.gz
│   ├── d13953f8c0ff495973fcbb3d08cf69a197914269.nq.gz
│   ├── d900036e5144d293bd5f9e287c42396ac302f460.nq.gz
│   ├── d984caa05933b0db415311b15981bd0ac0668654.nq.gz
│   ├── d9f12a9bc42d3ae01e154ebd44a92e7f3fa62131.nq.gz
│   ├── e2889ce0ebb5f12a25b4c09fe99b6d961f0edac5.nq.gz
│   ├── e4d1644047e76a794ac15c2a844998ec846cfc96.nq.gz
│   ├── ea035148ea322405faf78c28b8d474be24440c5f.nq.gz
│   ├── f9ee1af959b3b77c0643ea974178503bf9cd996b.nq.gz
│   ├── feda4cf1e4446aa94cbbf292528c369964eee1f7.nq.gz
│   └── ffce8c82326b37c301fa7d2961c10e167f978918.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 0c70227e221866b74b5cf6b3e251bc67864781ef.nq.gz
│   ├── a9be78c5dcf0ce475b3b561b326637ecca2e8e50.nq.gz
│   └── faa7ce22752123e616a08c9e4fe81c3b234c1354.nq.gz
├── filetree
│   ├── 0c70227e221866b74b5cf6b3e251bc67864781ef.nq.gz
│   ├── a9be78c5dcf0ce475b3b561b326637ecca2e8e50.nq.gz
│   ├── c448a763ad2c28bcc390222122a61a172dae1283.nq.gz
│   └── faa7ce22752123e616a08c9e4fe81c3b234c1354.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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
