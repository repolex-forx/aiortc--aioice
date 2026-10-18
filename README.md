# Repolex Knowledge Graph of aiortc/aioice

RDF knowledge graph data for [aiortc/aioice](https://github.com/aiortc/aioice), parsed by [repolex](https://repolex.ai).

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
rlex download aiortc/aioice
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d17b5378249c8fd119b88d2713de378b2cd13995
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d17b5378249c8fd119b88d2713de378b2cd13995
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a66ad14c3450861a573e2b0ce89e1e83f266c27.nq.gz
│   ├── 12981f425a746ef482e4e39e5e67c336a51922f8.nq.gz
│   ├── 16a266ac142518a71d2853ac8fcf4898c8de121c.nq.gz
│   ├── 17d62eef6c88b7a0a1f3f686195d6f759468d59f.nq.gz
│   ├── 1c9fcb492825029fa7dad6180c67b8c89fcafff1.nq.gz
│   ├── 21fe17e8b3de475af369bfe35051445d73666a4b.nq.gz
│   ├── 2bb9ef0b9b729830a6b8db4da4ab52a6e1e07687.nq.gz
│   ├── 2ecc7dc7a51c52289d733bf287596864bf73b817.nq.gz
│   ├── 2f1b98d2d3a903e208ae2387b77d26f4aaf85f11.nq.gz
│   ├── 2fea70ed68cb52d7d168cafb8f49065f38596b9f.nq.gz
│   ├── 41bc35457ed432565969dacaa021a7d124e43fe6.nq.gz
│   ├── 471188e90b98b10fa3d5df9ac62f847249cea62d.nq.gz
│   ├── 4b370cb2063d3ea3c7b3428018f4c122e459b6e5.nq.gz
│   ├── 4ccb0ca3a8a2a29c32f0f52dd1969084795838e1.nq.gz
│   ├── 522c14c7bd9f7f4786a48a517f237b9554cd6e3b.nq.gz
│   ├── 5309018e2f381992934ac7e8661b3295bc483617.nq.gz
│   ├── 55ac86af175875b4986a97a142f1b4dd4f2acb8c.nq.gz
│   ├── 5c7d50a58d143b24ac152c78e409be57bed7eb45.nq.gz
│   ├── 61dff18f1b616d109a38d670529df467e4bd8ad6.nq.gz
│   ├── 6e401350cfc24514820b333e7cabb4f82e632a0a.nq.gz
│   ├── 7018a5e4492372ed2404541f55edd3b9744a2379.nq.gz
│   ├── 724df59ee4d8bb0ff5a3bbadfa042ae2a4f7361d.nq.gz
│   ├── 76186827ee11c7c15ebd779d7c974e23c4a1251f.nq.gz
│   ├── 774673dd70a9273bc910a60f9d665308a84fd9e4.nq.gz
│   ├── 7ba61bb310b7dbb70ea1170be54712394cba89ad.nq.gz
│   ├── 7bb6870b1a5c8223ff6f2b0d4d64779c1048e128.nq.gz
│   ├── 80db43c95e22f2d319979deac975ea5e945d7096.nq.gz
│   ├── 842d3b07fc93f647f3fd08e65b4b4faddcf33afa.nq.gz
│   ├── 90b4c6ed1e5e3629b25671b4238355116f315d27.nq.gz
│   ├── 92967f7344fbb1c8e03e0a818aecbcc0e89eede7.nq.gz
│   ├── 93ab63caf9459fdfe729d31a1edc24ca37a764c7.nq.gz
│   ├── 96f33e71d3dde4dce8106762fc5377011332f7dc.nq.gz
│   ├── 9e8758a2a0196220228b4914619b0c6a76f90672.nq.gz
│   ├── a292edf711646efa16dd71cfd80662404cf65a6f.nq.gz
│   ├── a9d02d28e4ad71f35422f86b20bfdac9e1e1ab1d.nq.gz
│   ├── b3c1dc48cb12fb942937a660a3f968e992ca8693.nq.gz
│   ├── b908cbe55cb344569d32de1dfc10ca7323828dc5.nq.gz
│   ├── bf8751aa8c892bbdb1a02d0615130ca3fb0a6201.nq.gz
│   ├── bff78258149500edc4a5f2c55fb71859165b3276.nq.gz
│   ├── c6c0f81463359500c3b1c000cb08f9e3d642f794.nq.gz
│   ├── cc5a81954a766c6abbf3e71a609f34b47d6e683d.nq.gz
│   ├── cf790ed6a701c1098c2c95b93674d7ab33f4f630.nq.gz
│   ├── cfdb907748a7396c1bb7e6bb2183ac155510d1ef.nq.gz
│   ├── d64e39d34e0e53e059df35939ec2cd665c99c987.nq.gz
│   ├── df06e6c1cc3da52ad3c12a5ad60423fdb7372f61.nq.gz
│   ├── e672ec7f73a3d96f3e6a861d6a8dfd98a6ca6c90.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee8a6884b9666b3a8f61ecd8af3ff8ad0278fb4d.nq.gz
│   ├── f5642f79f21d872f010979dcf6f0c4a415acc19d.nq.gz
│   ├── f6f9200ac195cce25026a30028ca9e9ae93ae091.nq.gz
│   └── fabf31e2ff89f73bb939c9ffb7fa4c27c78cb263.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d17b5378249c8fd119b88d2713de378b2cd13995.nq.gz
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

[aiortc/aioice](https://github.com/aiortc/aioice)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
