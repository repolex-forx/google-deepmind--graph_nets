# Repolex Knowledge Graph of google-deepmind/graph_nets

RDF knowledge graph data for [google-deepmind/graph_nets](https://github.com/google-deepmind/graph_nets), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/graph_nets
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── adf25162ba21bb0ae176c35483a74fb0c9dff576
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── adf25162ba21bb0ae176c35483a74fb0c9dff576
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c07f564d1f7e40c6ab78dc736f15d14c606127.nq.gz
│   ├── 089e31240bc4ddf5d56a1ffb5d51475f72ea4f9d.nq.gz
│   ├── 0d6185e1f9a9296492a0fc439a286d56932ff7e9.nq.gz
│   ├── 10a0b0382d8ca78a25b79364ffabbcf08b59a908.nq.gz
│   ├── 15939fed1784105c9b0921d50a7035f19557ac66.nq.gz
│   ├── 1a6a0c846377067a308c7041f8166b3a2a909e24.nq.gz
│   ├── 2dddc0c4ccc72bc78019cc73b3476a0b79627f71.nq.gz
│   ├── 3e67ce462f1276e699cbe4f8ca6e34a3608823c1.nq.gz
│   ├── 44f80223713b5a8a38aff80ee47e55bcc4b41296.nq.gz
│   ├── 451363c4b2c09f7e2a59520b8ac3fb6e09ae8f53.nq.gz
│   ├── 4ca34f1ffaa0b337bc65c5d5000825245b6c47b7.nq.gz
│   ├── 4d80c48a0ae90b8bfb009056d229e093581788b1.nq.gz
│   ├── 4e87afbb01598191192f07b5f84f1da513d7a107.nq.gz
│   ├── 559c2a9ad6e84cb49f70df1acb4e859f82d3caf2.nq.gz
│   ├── 59e8d510af4223f1bbc9dd9272f98c427ebf3c9d.nq.gz
│   ├── 5ec5669e2164a7ac30623efaad35d3a846f5448b.nq.gz
│   ├── 64523b003fa9f76566aaf2d9a29c46c67d70cbc0.nq.gz
│   ├── 6b0b1270ff0ca8f03867efcd09ba6ddb6392b1e1.nq.gz
│   ├── 8253a694095d61b40876f8d4ea10d97bb499f972.nq.gz
│   ├── 826e2a3818ee303ada0ff78ce32df4a49715f658.nq.gz
│   ├── 873749113dab2422b29e81a37d56bf2d0c614102.nq.gz
│   ├── 94deec38615bd5b1328286ce01bd6304df9956e6.nq.gz
│   ├── 96c476577fee914e968d37df38dc06741a3207f8.nq.gz
│   ├── aaffb96f3f41b6010900972fef45ab44bc51dc6b.nq.gz
│   ├── ad3d13fbaaae5b226521d33565b5b28c2927825a.nq.gz
│   ├── b16203c9cd3a929be7580b436aee09ae39ef8b9a.nq.gz
│   ├── b16cd68716e6e6e6bddf07f94c593ace50f1ce37.nq.gz
│   ├── b381183fcbab17247933a280f001d325d384edb3.nq.gz
│   ├── be833b1f799bcb725550bcac9f4852457eb8ef26.nq.gz
│   ├── c14138ee6dc5296f3948565de33bf499de90b701.nq.gz
│   ├── c6d6ee011851c4626b0bafe8d4d51fe544724a55.nq.gz
│   ├── c8abb80d128ab323b06009649669de0b7ad49d5b.nq.gz
│   ├── ca8fe61c52bd226bd6dfabac5ce90b50b6c88f93.nq.gz
│   ├── d09fb432674ec4d9e7ca4dfc5180dde28e4b44ca.nq.gz
│   ├── d57e340d833a2d2590a7568c5e2a794d87d3ee77.nq.gz
│   ├── d8cfdfd7f66f3bdf2dc1c5970ee3b5067209bde6.nq.gz
│   ├── db5b67c4b2f66edd249d7f1bf4a178d604061fd5.nq.gz
│   ├── df19cd5b137a270fdfc8eedd52a5c1d7945ec4bc.nq.gz
│   ├── e489c456c50c972714cde69962f2155b9774fb86.nq.gz
│   ├── ef131957bbf3561fc37d3ca248c33b4b632e218f.nq.gz
│   ├── f3d673e5d26b4474aa3579a5f9dd41d0551cbaeb.nq.gz
│   ├── f591275d5c2edd43f4a7f628cf3f3c20be043adf.nq.gz
│   └── ff0cc87286db0459c15ccbb4a774ff71bd2dcb15.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── adf25162ba21bb0ae176c35483a74fb0c9dff576.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[google-deepmind/graph_nets](https://github.com/google-deepmind/graph_nets)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
