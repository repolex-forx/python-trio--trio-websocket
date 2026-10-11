# Repolex Knowledge Graph of python-trio/trio-websocket

RDF knowledge graph data for [python-trio/trio-websocket](https://github.com/python-trio/trio-websocket), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/trio-websocket
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e828e54cfcfe425d53688aac7acd14dd695560a5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e828e54cfcfe425d53688aac7acd14dd695560a5
│           └── chunk-001.nq.gz
├── blob
│   ├── 188e2bf496054c4dbaf08e90c1ce1b85996fdc9c.nq.gz
│   ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
│   ├── 2133e5bf6dfb6da5da521ec0f146c7ce62865196.nq.gz
│   ├── 26ec94be4e417c24ee2676800558946913b169a5.nq.gz
│   ├── 27f573b87af11e2cbbd9f54eb1ee285a58550146.nq.gz
│   ├── 346a4c9f91cf354575673c86c3284526cb44e250.nq.gz
│   ├── 382e42aadfbdf36a4be710d193f6e2a865a5cb5a.nq.gz
│   ├── 39e42af96fd3c90e34f7153962f130ba31d4571e.nq.gz
│   ├── 48661fd1192e722358a7768d6d1c68cd8be6f928.nq.gz
│   ├── 4a29d602237581abaa7f4ee6c57163a0d73eeef4.nq.gz
│   ├── 5274013160f9e0ba0c5a4aa9a80e738523144087.nq.gz
│   ├── 5759baa0a5205ceac6d0cc1596f814bff90b016c.nq.gz
│   ├── 5c94b56f5145d2d0c45c5d97de1ef603d0ea7270.nq.gz
│   ├── 5f4a13a225db317dbb3f4cb3ca1e5dc5b10eec2a.nq.gz
│   ├── 689741e94cb615d7a83103290eeb4db3faa980cc.nq.gz
│   ├── 6a84de473b31dea3a3321337ff7098617b10ceee.nq.gz
│   ├── 72e8ffc0db8aad71a934dd11e5968bd5109e54b4.nq.gz
│   ├── 7306a5c92326095302306fe0e5131caca3db273d.nq.gz
│   ├── 76b970ab3047e4e822482bac07427fed4ef708ec.nq.gz
│   ├── 7b5859ec11fb2ff151b332fcc3347a205ea5b1b0.nq.gz
│   ├── 7d59191589c349d2a4d4540e768c82ea532e1646.nq.gz
│   ├── 7e5ca3316306a351c3fddc04cdbe82be82c59b94.nq.gz
│   ├── 8cc9be2c70bae39e304f2e6f9320c2d36673b17a.nq.gz
│   ├── 8f49fa73d269fbf1a3d747ea60d9c2c7968e1900.nq.gz
│   ├── 922fb764fef4fb34c1f1383deee57605efb5961d.nq.gz
│   ├── 94daf29f81254aa7e6cf060fb96ce0cee62e6c14.nq.gz
│   ├── 95d5ff9b2464e7eddbc13958a299a6cdacec42bb.nq.gz
│   ├── afa944c7100215a90736bf53eec4c35e61e0c562.nq.gz
│   ├── ba5311c4973ebabfdf86a00d1d627b4f11c46a4a.nq.gz
│   ├── bc6479694fbb09cc46aed8cc3c68ac2c7f25f020.nq.gz
│   ├── be4445dcb7d3d868375eef3012d2c6c980f64840.nq.gz
│   ├── c58d4183c4ed2dabf00f396def9e309806fa0be3.nq.gz
│   ├── c6abb07dccfa02f433b22b7de540e7e00510ba9a.nq.gz
│   ├── c7c6cf21a125bc71baba3a6e5e3581ac86d4d52d.nq.gz
│   ├── c91c783cd6f62e4f26c10e8bf0d41fbb66549c35.nq.gz
│   ├── d00c8e457cd6337ff097bba8d62fba42dae1b436.nq.gz
│   ├── d37d1f6d448141f0851dc121c14adec4bdf9de67.nq.gz
│   ├── d4e11e5ea03f17b7e84ab1d5bed9bddb9ac6ca95.nq.gz
│   ├── dc3a14f02df84463d29cfcb67d0f89f718813a61.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9195f7ca4aa87bf7d50bca437f53b6549bffdc8.nq.gz
│   ├── eb2cd307a2a5f63e67d4e04547ee040ea4cab4d9.nq.gz
│   ├── fcb36bd2ff4df52dc37dffa3da117ad4e14cced4.nq.gz
│   └── fea31deef70a137cfbf1f45abb3e38ccdf108f80.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e828e54cfcfe425d53688aac7acd14dd695560a5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[python-trio/trio-websocket](https://github.com/python-trio/trio-websocket)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
