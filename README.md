# Repolex Knowledge Graph of modal-labs/modal-devin

RDF knowledge graph data for [modal-labs/modal-devin](https://github.com/modal-labs/modal-devin), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/modal-devin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d6753c40eb71c026d8a3911b5fecd7de73b19eac
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d6753c40eb71c026d8a3911b5fecd7de73b19eac
│           └── chunk-001.nq.gz
├── blob
│   ├── 032ed820d0f613355de4ad311e244d21c20b42f5.nq.gz
│   ├── 0eaa6539039708c2fc286647d28b569f40cb1e87.nq.gz
│   ├── 0f5b85e0bacabc3719a56a8c4bc8c10e6e1a7097.nq.gz
│   ├── 15289536640af4578be453d068530e32cd03f23e.nq.gz
│   ├── 1b71247c727ec746dd29feb290432cb2d76bba63.nq.gz
│   ├── 208094ec6510573015a9bea8495b677dae62cf98.nq.gz
│   ├── 2f8bc72d846367ce1d8aacc3e2973c85e1e18baa.nq.gz
│   ├── 2fc04cb7d18e558a1001ed3885051d17786fd815.nq.gz
│   ├── 36889906ca90f929d1195b34ec1a2f59f51eb772.nq.gz
│   ├── 39eba52dbda81ad3a5b523d3fcc51c50669cad64.nq.gz
│   ├── 3da0c1b0ea514e1e642c204b3ce442b03c47db31.nq.gz
│   ├── 3dd6be440289c698f9282c0f9389151bc5bce9b0.nq.gz
│   ├── 46580afc641120d2dd70aa523eb0a7517cff927e.nq.gz
│   ├── 49946e0a51e8413bf9ea0cadd98814b2af34bc23.nq.gz
│   ├── 4a65b5c249ca208d8c164dc7cf1ec95f666dbc83.nq.gz
│   ├── 4b145e8968ba21f7eede12d3de4ea6fab0908531.nq.gz
│   ├── 572004e237cfe7ead77430a271932c9e3d07d67d.nq.gz
│   ├── 5a02e5aac82ce779bab0370adee52bf40f428d8d.nq.gz
│   ├── 5bd44431df8bbae100e21c3091961c98022c2481.nq.gz
│   ├── 5e07fd644ad845d564c6ca2844d69ca83dfed0b3.nq.gz
│   ├── 604195ec90ac49294d9b7a4028291c749ea18241.nq.gz
│   ├── 60c1bd77ff6d6b68ce514cb79af11be5e979251d.nq.gz
│   ├── 651f88a0c2e7c83300f96bf643c55acf3ccfa06d.nq.gz
│   ├── 6a65a90ac12032a817359cab71f0acbd8d334113.nq.gz
│   ├── 6c2958d873c04f8d52c395a990262c3c3e06a071.nq.gz
│   ├── 7428c44931dbcaf81415f64525cefd21330de7aa.nq.gz
│   ├── 747eaa15014d7dce190125eb32202824a470bcd1.nq.gz
│   ├── 78eb417184c2700babe6c9c3fd9f4f8c98634c37.nq.gz
│   ├── 7948875dea78d158de8534f6fd499bab0785e561.nq.gz
│   ├── 7970dbc274df584e0e56af6bedca906eeae17990.nq.gz
│   ├── 7c3d2bddd82cdbc5e83eb5e248b3d7ce2988b4a7.nq.gz
│   ├── 85730bac8550c659d3d250538179340dd512fec6.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8fd9b37c5562faabc77361875c22b31d0e58151a.nq.gz
│   ├── 9519dd473983cccd94a77ddd77bc6ac895cb4543.nq.gz
│   ├── 966ba7b98c3ac5ef7ea78c8950c9f173009c0b91.nq.gz
│   ├── a653f0b55f0664c9df2ae6fd80ed2ce17f1011cd.nq.gz
│   ├── ab1f8590d10e2beb0ffca59ab292f4f7eaeeb8b3.nq.gz
│   ├── ad2af11751da8b8eb26c53459e647535186b40dc.nq.gz
│   ├── afcc78b44ee1f3209c35c00cdb74ac0bbaffa902.nq.gz
│   ├── b0faf4c2b8b711c1adbbbd7a145dc8abd6bf0897.nq.gz
│   ├── b369521d051a079358919f1aaf32409ac6fb0343.nq.gz
│   ├── b63605f5604a77e5b48f7a153fa98ee705562277.nq.gz
│   ├── b8ebf56f294430c8072578bf9ea2ad8561aaa5eb.nq.gz
│   ├── ba66ac62b2eaeb912434056e9394da726568533d.nq.gz
│   ├── bbe27ee9a693750ceb903701d209f6bbf8a7c990.nq.gz
│   ├── bd62e87a0dd8a0f574a38d64652d47e47bdfc156.nq.gz
│   ├── c0eff3ba7a5ba201d6016bcea315254b13aa98e3.nq.gz
│   ├── cdcf2a723244fb13872a1caa62f45b102da6025f.nq.gz
│   ├── cfa8f077cc81292d58a1f8391edcea55c67375b5.nq.gz
│   ├── cfd09997eef418884cdeb8e55824a100a241175d.nq.gz
│   ├── d9f9327a27689b598d26c170caa40f7b666259ce.nq.gz
│   ├── dfe0770424b2a19faf507a501ebfc23be8f54e7b.nq.gz
│   ├── dffe44048a4815d9e7b3a500cdd9ea037579ea6b.nq.gz
│   ├── e1378c5234b610981330d434c0547f30d0456736.nq.gz
│   ├── e29678803dcf218371cf17faabacfae024c10bd0.nq.gz
│   ├── ea37ccc1e2b76c35939c918cd2b866f0d58acc76.nq.gz
│   ├── eb4b6b4ffd7dd3e26a952834706867b3ba06f4bf.nq.gz
│   └── f958233a96c9f4bab7574d6286b7433b71adbec0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d6753c40eb71c026d8a3911b5fecd7de73b19eac.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 66 files
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

[modal-labs/modal-devin](https://github.com/modal-labs/modal-devin)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
