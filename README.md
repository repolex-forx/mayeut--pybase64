# Repolex Knowledge Graph of mayeut/pybase64

RDF knowledge graph data for [mayeut/pybase64](https://github.com/mayeut/pybase64), parsed by [repolex](https://repolex.ai).

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
rlex download mayeut/pybase64
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 10639d9232cad3702431d7f2211e1fd2e36be5d8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 10639d9232cad3702431d7f2211e1fd2e36be5d8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0167da089848b2b2301c192fbd7811e05d066c3f.nq.gz
│   ├── 02cdacceaafb22f97ba1ef675b16495c8ee07841.nq.gz
│   ├── 052531c94df5acd26672ba874a100f1003e0d180.nq.gz
│   ├── 095dcf2499b3d3a12e0e0bee55701a6284cc27ed.nq.gz
│   ├── 10c936db64ddcebc6d684d604fccef225412d01f.nq.gz
│   ├── 14886610d05b3b33d2455463745bc71d6a2b58f3.nq.gz
│   ├── 15b3d20eefa68e43442038fc2718eec840b79d81.nq.gz
│   ├── 189dfb1cae640ea4fbf720c158dcd6ab08839844.nq.gz
│   ├── 1c7aa820d94a8f8f6483395b33087adc8885c837.nq.gz
│   ├── 1d9f4d6afcc3be2f92a4e5df7221235f8c9efc18.nq.gz
│   ├── 27e0c5ba2d2151ed7f7d5a95eadfdb0ffa5998df.nq.gz
│   ├── 2c0f700e2204daee533293594e1e39dd7d57d5ad.nq.gz
│   ├── 33071a627afe4abbcd3864541c9edf479a8c6fd6.nq.gz
│   ├── 39c5306deb9ad492151295142fccbf1deec495d0.nq.gz
│   ├── 3b3c03a9ec0ef2ef12f22835550fda61404e6240.nq.gz
│   ├── 51f2c3d95d551f02c16ba45b27714b28d1b11661.nq.gz
│   ├── 5cbc123b2e6ecf1c7a043c33ab0f3ffc5fc61c33.nq.gz
│   ├── 603e61e69a079eee39c3ec0e1c1e0b0ebc24d436.nq.gz
│   ├── 63c66f785a13ae5c70ebcf51c7dee24571f16722.nq.gz
│   ├── 64d9f90a9136381f87c7e490858162609a942802.nq.gz
│   ├── 673e9c016d91655e2575fe1841bb011f2eeb6264.nq.gz
│   ├── 69da1777551faa21ec68e2f76b7709439e8abfd9.nq.gz
│   ├── 6acdb762f2e823eaacbc5bada7cceac5a08f7f5d.nq.gz
│   ├── 72df85db80e3c38481e19d8fa2ed1913aeb4d5c2.nq.gz
│   ├── 7406f47856ada917d22f8e4ab7dc4c070ca39b42.nq.gz
│   ├── 777a528306f9cf61b4a2a09e5d2341891ec7d79d.nq.gz
│   ├── 7944c74cf238630175ff85a800cdf261c9999219.nq.gz
│   ├── 88869619ebd1168accf5103c759e8047d330fa7e.nq.gz
│   ├── 8929b6b893e6b0cdee315d229a1092c2a7ea1d56.nq.gz
│   ├── 8a7c9db973a01d4e4a3daae6dd6d23f6a5169484.nq.gz
│   ├── 8adad22973de9e93ed6e03e03bd419ef506ef9e0.nq.gz
│   ├── 9d165cbcd86d02601e7b21ad4e71ed3e238440c1.nq.gz
│   ├── a406d0ec7a55e153fe0bf7f425fd2a01ea421e9f.nq.gz
│   ├── ac156edcef9424b1a873f34263427eb40ee0b254.nq.gz
│   ├── b1f49ce47f9a334f53248e03c4e4b272bbb804da.nq.gz
│   ├── b6acd53a20e1cdcfba735bfa8666586ca04d4ada.nq.gz
│   ├── ba51e3ef16409531f95c5816dc27b212375b2867.nq.gz
│   ├── d27609e5e376a86092a9b16f2ad64842463a578d.nq.gz
│   ├── d780061a48eb47c5b0e07c6db49026d3336d2065.nq.gz
│   ├── d9d96d67585504ac60f80e4d00f71f76ee7b1e42.nq.gz
│   ├── dd8a3779b2b33fe1b0f7244f3051fb44f878cad5.nq.gz
│   ├── df900bfd4da9061dfdb25014783f39cfdb0c9534.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6fe02ee822c5babd8a34170fdc4353773425e46.nq.gz
│   ├── e8ef7a13819b150f6314670c91007f1b5f3a2bb6.nq.gz
│   ├── e925adbd630b59c56f7cb7826687857119342012.nq.gz
│   ├── f24638f8fdf50fe79d4c434c4c866b71fcbadd22.nq.gz
│   ├── f5a99812032d70fbdcaed0464b03afbd590ffbd6.nq.gz
│   └── fa82997a13576b10362ea932f25c8eb89bc969ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 10639d9232cad3702431d7f2211e1fd2e36be5d8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[mayeut/pybase64](https://github.com/mayeut/pybase64)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
