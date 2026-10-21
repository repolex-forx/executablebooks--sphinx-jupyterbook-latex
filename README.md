# Repolex Knowledge Graph of executablebooks/sphinx-jupyterbook-latex

RDF knowledge graph data for [executablebooks/sphinx-jupyterbook-latex](https://github.com/executablebooks/sphinx-jupyterbook-latex), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/sphinx-jupyterbook-latex
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 70c911c74e8e88e24a39e2172a20fa148ea21524
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 70c911c74e8e88e24a39e2172a20fa148ea21524
│           └── chunk-001.nq.gz
├── blob
│   ├── 08a1c85a0baed3c1c5719d09e72fb5a20d833fd7.nq.gz
│   ├── 16c3ca62185cd9c005c7d736a12b7d4e35bb511c.nq.gz
│   ├── 1821b9e4e93d788a0276cdd1cd11b68749b9c8f3.nq.gz
│   ├── 2dc86add81fca54934dfe3d1906e1e5f44d929c3.nq.gz
│   ├── 3385c4d7e084e1c818e80c9f67f2ca05bd55ce31.nq.gz
│   ├── 360d8e241736ab334e44613fb461a9de59b0245b.nq.gz
│   ├── 40c92f932f0ef04b78229ff2fe015a1f50bb5a80.nq.gz
│   ├── 4ba64453ab2c9e92b01dfa29f5f9b7c59c2caf4d.nq.gz
│   ├── 51d00f7be05b9eb4b669961230aa77e09904fe4a.nq.gz
│   ├── 56f7541ac9abe93fca4ceb1089a6364d5781eceb.nq.gz
│   ├── 59aff6ceffd5e1c53b8d56f6d49a69bc8b0b452e.nq.gz
│   ├── 5a7852dc970d64cedf509e43ccc83e250e930a85.nq.gz
│   ├── 5fa28023c6574beb6649a6179b22afa31a6171a1.nq.gz
│   ├── 65507d225c5f79a37148a44b9d061e282bce8f63.nq.gz
│   ├── 65d0c882ef066f8cf9340d6a22107fc7455dc073.nq.gz
│   ├── 661764d767b978f7f5d455215f8ee5c0fe95e6e1.nq.gz
│   ├── 687d39b5161a684514b40444fd414c45ae87e7a4.nq.gz
│   ├── 6b4d4df4ee8087d809ec2cc1ed298346d5518ec5.nq.gz
│   ├── 6f02d4802858b7144673df7c1235d6eac523c68a.nq.gz
│   ├── 723bc777544a893383be4dcc28d1ffdeea19329c.nq.gz
│   ├── 74b29cbbf70ed1369927380e81c1b0ad244156e3.nq.gz
│   ├── 75fc91d3c2fe12931552f0c5d4703ee371292f32.nq.gz
│   ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
│   ├── 8038fd88616fba9c4cbc75119f6c07eb8cb8444a.nq.gz
│   ├── 8606160e3585ccf8ed6f22c915d090cf0f5dd678.nq.gz
│   ├── 929b95bee71c09444840d8b50ed4b6bf01d5cc70.nq.gz
│   ├── 9601bcec30bb84fceaa06569c948cfef3289f317.nq.gz
│   ├── 98b6835845fe488b20765d7c0f65e8486fce488b.nq.gz
│   ├── 9e42c417615c90da652750daa6f3935edb879d8d.nq.gz
│   ├── a1115d7414320ccd894a999596ee46374512b437.nq.gz
│   ├── aa3ef0ec5fc7a3069b56447c636b83c4eb401633.nq.gz
│   ├── b147e6a602db07cd8d00cda07ec76e9982c52c4d.nq.gz
│   ├── b16b4c798a6522be44609202d173d9f9c4a0656f.nq.gz
│   ├── b1f4b37fff0cf5aeb93dfd7c6e7d86b7e67977ab.nq.gz
│   ├── b2b443bf5c332ffba81763a064d6b8f9d9a498ab.nq.gz
│   ├── b2c42fb2f18870291ec20ed4da930eab8bb59f5f.nq.gz
│   ├── c0107a5dc4cb1a35d425c0963be7ab7b4f87983c.nq.gz
│   ├── ca5d80d6a628e83072682fac8cb98e2be72383d8.nq.gz
│   ├── d0cc6346c02c29c7e67e783e99e7bbab6e37dcfa.nq.gz
│   ├── d2e6afd99515eae029f6793370db5e3a6b1df2ed.nq.gz
│   ├── d69a8e1d56df5389cd31f9931e5c06cbb2550a0e.nq.gz
│   ├── d820740785e93eecd81f6b871ef502a2370c3ff1.nq.gz
│   ├── dd1d993ce743d72c1e512b0731ae804421143bd1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec7142b045f8f8fab9503a52fa5d7bf54eb8473f.nq.gz
│   ├── f33ccc79dcf079711a51deea806506b1a124db99.nq.gz
│   ├── f606f02a436cb01432aae0c07c638783b3a8753a.nq.gz
│   ├── fa8d6570c7399ac5669fbf524f24313b28e86ada.nq.gz
│   ├── fcebcb16d7b214f63e895319845afeccc94659c8.nq.gz
│   ├── fdfb8abc2cefeceed65fcfb4c5033adb152705c4.nq.gz
│   └── fec49687412b540a0a94dfd365121d7e8fed6dc4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 70c911c74e8e88e24a39e2172a20fa148ea21524.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[executablebooks/sphinx-jupyterbook-latex](https://github.com/executablebooks/sphinx-jupyterbook-latex)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
