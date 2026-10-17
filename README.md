# Repolex Knowledge Graph of intake/intake_geopandas

RDF knowledge graph data for [intake/intake_geopandas](https://github.com/intake/intake_geopandas), parsed by [repolex](https://repolex.ai).

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
rlex download intake/intake_geopandas
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 34b30175ba86f4ce754f4e84d35fa07c91e6db88
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 34b30175ba86f4ce754f4e84d35fa07c91e6db88
│           └── chunk-001.nq.gz
├── blob
│   ├── 02f0e7baa25ef2410a68479543e96ce0c8b9ebc5.nq.gz
│   ├── 05ea7fa4efbcce692dbc95786f4fff101a6090d7.nq.gz
│   ├── 06176cd5f9aa4f485dfcc464c15ac63ccb0d284f.nq.gz
│   ├── 06726a665367486ab8a18bc75a345941e8b2d3aa.nq.gz
│   ├── 06969270b4ec48da291e8a17c172e4dc5669c015.nq.gz
│   ├── 11ca4c6df4cbf86db852a1c029d2d62ad886e639.nq.gz
│   ├── 2d0c73f3e8944d72317a293e73df5325d8c42eb4.nq.gz
│   ├── 2d13f6377f27e225d75a3d6d74b88028ce610c94.nq.gz
│   ├── 37b903f8a2c419dfee0c3b705a9df3009acab3d2.nq.gz
│   ├── 383d773309cdfcc31332efb008c4ae32d19ac2a8.nq.gz
│   ├── 3a83f9be43a9cae1276f709a1485d900d2c24a12.nq.gz
│   ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
│   ├── 411936e186d997a128a6e38de2f5e471f2f05edd.nq.gz
│   ├── 4a788a01dad42913228f213ad78fbb1fb8cb0928.nq.gz
│   ├── 4d1276e34d4f8d26641d17336c57b998c14e82b2.nq.gz
│   ├── 5213003e0e85b7f964e3ec3db26ab86c1ebe05af.nq.gz
│   ├── 56479d5ca4c15cad250704ea9a454c5a4776b8f3.nq.gz
│   ├── 6dd50190354c7b037d03c2b92ce7c335c11110eb.nq.gz
│   ├── 6f21900e1e1f8e9047041ed7b7edfc8650235f07.nq.gz
│   ├── 765ce3ccbe1d86144e48aa318331c9b3f653ed7a.nq.gz
│   ├── 7cd5ba581b0ce7fad9fba6a5ab9425455b1cf2dd.nq.gz
│   ├── 89adffd6a979677bf4bf430380febd22c8b23a76.nq.gz
│   ├── 8e1230d8568d643d49c3712fc4cdb0bd3f62b56a.nq.gz
│   ├── 994a451a778620a3ef119d45639dfc655952f317.nq.gz
│   ├── 9ac1f99e87ee85ab34e8d0d733261c1963a8177c.nq.gz
│   ├── 9f8880bef9963bbd89cd852b7a7d88cb32b5f61e.nq.gz
│   ├── a00ab24c1e3b414fc75d681b9ea2a61b4edbdba6.nq.gz
│   ├── a30c00a55de19be195abf9e942f6cff93bf0a825.nq.gz
│   ├── ac1937a89270f52f72a698822cc71c63ec4f8070.nq.gz
│   ├── ad5584078971c96b8f12b9b2ab15a9b1319649b3.nq.gz
│   ├── afdfc39993bd6107d26050fe4e8ade36ce08b871.nq.gz
│   ├── b593361e38b92b6adce1176393edcd7026d0cf6c.nq.gz
│   ├── d59fe6d6d3a515a6471cfbd72e475ae4b9413507.nq.gz
│   ├── d76f488b6eae2f1e5d31ee19e19e384773e3e00b.nq.gz
│   ├── d7ebf18fe77e26159846e1f6d2f5e1780976c3ea.nq.gz
│   ├── e62e3275c68795cd50472676a374bb7ba072d5fe.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e95824681f6e54f342a03421489beb60f8b50924.nq.gz
│   ├── eab6fbcee82830ad04a4bb53c7d7fd8e1609a555.nq.gz
│   ├── ec9193d1f093c616ec4933de5ededdc728a90221.nq.gz
│   ├── ef9bd9c3b6515970ed11816e5a0e48799463fe40.nq.gz
│   ├── f03658870db75500c82cd459fecdfd407ff9c326.nq.gz
│   ├── f0b8b96fbbebdecdd1d8cfd8c77a74f9440c5741.nq.gz
│   ├── f62f3ea463b9c82cb061c7e370f3ecdbfdeccabe.nq.gz
│   ├── f76691eff67bc9253824282891c2ca4aac3624fd.nq.gz
│   └── fec68db6d811a7952fdc3d5398e8e75bb973c2cd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 34b30175ba86f4ce754f4e84d35fa07c91e6db88.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[intake/intake_geopandas](https://github.com/intake/intake_geopandas)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
