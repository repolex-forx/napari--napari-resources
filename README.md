# Repolex Knowledge Graph of napari/napari-resources

RDF knowledge graph data for [napari/napari-resources](https://github.com/napari/napari-resources), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download napari/napari-resources
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 136b5004a465e1a5edea850740ea666253dc6e71
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 136b5004a465e1a5edea850740ea666253dc6e71
│           └── chunk-001.nq.gz
├── blob
│   ├── 23f54aea70c3ee0dfc2e67bf5f139665d158fa08.nq.gz
│   ├── 27440dab7d017a638027dbf0a6772ea1eb482059.nq.gz
│   ├── 3a17befb2a492e5e38b4f4ec8548e9207865b1fc.nq.gz
│   ├── 46d5b7f3857f1f4c5445b1ae5fa8126d84d886cc.nq.gz
│   ├── 4a9364c4689e7d065ba63fb2322425cc83b45067.nq.gz
│   ├── 4bd5600a0d9e7847b1be4a975fd09a234578022c.nq.gz
│   ├── 504c85d4c5d974bd8be36a3a59ac6d179a23ceb1.nq.gz
│   ├── 5b4a70005c16c13442f408dbda55c8a843afefa7.nq.gz
│   ├── 5c80aab8fdf7baed2508fdc565e0583383b257d9.nq.gz
│   ├── 5e5029101985b05f5944a09cb9891df4a2800d90.nq.gz
│   ├── 63fbd08545a0f6e6e17783b03c7bd2df6f2ad1f5.nq.gz
│   ├── 686ae6be2f8f621046881dd1c95208f3b5d379ef.nq.gz
│   ├── 6e0a433443be386ad2d17b8479426905cae2b75e.nq.gz
│   ├── 7434f739561da780bb63ea0fb73b1868a51fdc37.nq.gz
│   ├── 7487f80af31e69087d330818ab8f4c5e8057e14f.nq.gz
│   ├── 7529155c4d9ea57b4d0b66cb59e4aa4b3e07c723.nq.gz
│   ├── 7c7a028772282f68d63b756879e00af6789eaea1.nq.gz
│   ├── 8200b212b6d6270b35908b28888da31d25579387.nq.gz
│   ├── 827d593107ffdd4324cf1e4bd6c25f4701a47a35.nq.gz
│   ├── 84456ecc56d904c5419a6b7e80737c00a6b0b3cc.nq.gz
│   ├── 8533e4deb1bea99927c2b98564d70a7fe5fee1e4.nq.gz
│   ├── 86360e9398effdf2ae11b79e81258ea1755935a0.nq.gz
│   ├── 8b5a2915e101b0a0864d1cba07c1a1117c2bacba.nq.gz
│   ├── 8d0b61a2a87546be4e5bf8fce7702c6263ba01f1.nq.gz
│   ├── 9069bafd4bd1ef3a50317aa8c08801285ece4dde.nq.gz
│   ├── 974588f14a2bffb7e12a46b74a4ecea0bd5f6e90.nq.gz
│   ├── a20f39194adfed49d1969bb18d96dfa00160be13.nq.gz
│   ├── a2b4282314264f049e6603ae905593005b380ad2.nq.gz
│   ├── c8855e09ebab36a046e2ed97ab5bef2157806e9c.nq.gz
│   ├── c9f1ee55f94df5e8a4ecca54c8c993cc8ea3312d.nq.gz
│   ├── d3f381a5306fd2b0cb6337793da38e7a35e3c2b1.nq.gz
│   ├── de83797357ddb3aa215d3b5ec1d75417d5bf6390.nq.gz
│   ├── e0893153ccdbb41282e1505cdbf5241d731b57e7.nq.gz
│   ├── e1d3292bdd37ca6c3a7efa9569c4b04e2be83f64.nq.gz
│   ├── eaee3ec149dbba135f8611df49596f123b1bd4ea.nq.gz
│   ├── eda8c78276d65401430bcf9c6cf9307df6b3fb6b.nq.gz
│   ├── f15da3c3ddab9255b3ccaaaf98b533f2507d270d.nq.gz
│   ├── f2396d7e29b9627046326b024b8e511e9d3afcc7.nq.gz
│   ├── f561cb857c98bf0098875d4cea63431cade1fe58.nq.gz
│   ├── f8d205f3972c6df0cbd979d07fce6e14736e1f74.nq.gz
│   ├── f9a235e29c36265f524dbd963cd3021944f681eb.nq.gz
│   └── fb9ed2a13047247514c0cd1ecb5c64fd2befc852.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 136b5004a465e1a5edea850740ea666253dc6e71.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[napari/napari-resources](https://github.com/napari/napari-resources)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
