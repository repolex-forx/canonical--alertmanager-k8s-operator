# Repolex Knowledge Graph of canonical/alertmanager-k8s-operator

RDF knowledge graph data for [canonical/alertmanager-k8s-operator](https://github.com/canonical/alertmanager-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/alertmanager-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f77240c3fe1b78778e7c2fdae8200f82704c251
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f77240c3fe1b78778e7c2fdae8200f82704c251
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a88b4435409c5e8c765fb31532d45ebd08c9cd.nq.gz
│   ├── 058d1651e75dabd04e862c995f454ea741a09841.nq.gz
│   ├── 05e0dcc6a2ae16b8bd08e0d67a35e3fd919d98ed.nq.gz
│   ├── 07254507638c60ed3888c624a6cbe29edd1c32bb.nq.gz
│   ├── 08512ee4ef52d4a5d5d1cb187501c7c18458cc89.nq.gz
│   ├── 0aa6f9ad51aca911eb3bd776d8d94179a2e72101.nq.gz
│   ├── 0b319b02dea281d8650e0f67a7cea1bc9c221e1d.nq.gz
│   ├── 0b3cad5894b46058c815eb28e93a1c493d2ba0e4.nq.gz
│   ├── 0bf6589cbe253cb80c2aae7664639e480d3c3056.nq.gz
│   ├── 0ec298c61df5d1afc5bebd23458c7a37146d4d24.nq.gz
│   ├── 0f16506e42b0af4ef4a5e6bcd10503ed36cabc91.nq.gz
│   ├── 100ff0f6456d836faf57fd8cff1483fa56e43966.nq.gz
│   ├── 10d653f962d9da6089b7e61f0fed88b9a8587e01.nq.gz
│   ├── 14cd592e0466bfdd79dcf2003f3bf9310308a98a.nq.gz
│   ├── 1527248b125dabe30867ea3750b2a727c6797536.nq.gz
│   ├── 157b32dec7268ffe9ee2e2972826c863b5587bf3.nq.gz
│   ├── 1619ff2e4b7db976246f79e1803404d9779fd469.nq.gz
│   ├── 168599e54b7503a3b957201947519a5eaa9c4561.nq.gz
│   ├── 169da982099be9a6f21e3603ff134913b68e2fb6.nq.gz
│   ├── 16a35c137fc10ac2e89c989678012817c326c92a.nq.gz
│   ├── 1a5f0e77f4c103012fb323e34faeae62c1132c58.nq.gz
│   ├── 1ad983307da72fdc0dda66d541296606cbf90a41.nq.gz
│   ├── 1bb45e9085b56696c3b53307f0da6268b4b3d16a.nq.gz
│   ├── 21289226ab92acdbf9ae5f66ab82c1b984ce2831.nq.gz
│   ├── 219793a0aa948e6766e7ef5ea130682b05755c83.nq.gz
│   ├── 2ab66ed404b16eff97f3a2cb1184f57000571caf.nq.gz
│   ├── 2bfd9f8d827d57bbc85a6e8619dc9e1507d16a0b.nq.gz
│   ├── 2e21e6568a5796515a276e0a449cd7f319a0531a.nq.gz
│   ├── 2e838f4e70fde6fda395abf7b870d7b4af70e345.nq.gz
│   ├── 32ad9d1b1d6da74d4b9424ce046273ffa80d9f5c.nq.gz
│   ├── 3592459112aa83c5b12b656cdf1c148f3d4556e5.nq.gz
│   ├── 374023d7b222a319468ef5c61cd01f34ab7db9f2.nq.gz
│   ├── 387ac6a47738bcce3f686ea6d43178ab2197e414.nq.gz
│   ├── 39e903656f1c86e434411c0a5078d1585fd05e8e.nq.gz
│   ├── 400ab77a3f268235d2acfccf328e78eb44f728a4.nq.gz
│   ├── 455a28db025a9a571fbd771b10ab2833ef2f32ac.nq.gz
│   ├── 51e12034a5008774f1259e5d4bd216c65767bdd4.nq.gz
│   ├── 522c7a31a0a9c0f75af0d5793466dc366d4813eb.nq.gz
│   ├── 560f34a8f8344704803cf6166c48cf40223eec3c.nq.gz
│   ├── 5c51f66d901d0a30c082a7207a53d19b763acc2b.nq.gz
│   ├── 60e60cb4b0c1b613bc67db3ba19459b46d69065e.nq.gz
│   ├── 6288d5b32061f823c888913e2747b1f0a2b3a99c.nq.gz
│   ├── 646887df1a746773b851e72a6b192f6ed9abde32.nq.gz
│   ├── 652c7d218edf2dc1dcf39f46f745b352c2172801.nq.gz
│   ├── 65f684537daaffedbfe96f718f95b94584b61603.nq.gz
│   ├── 682c561be10511e3ccffe1b270df856dde774591.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 71a097fd86d0c1ecfa69af8cd356f4a08ef69920.nq.gz
│   ├── 7702221faa80b9f2c2b161801de9533c833191d8.nq.gz
│   ├── 8615cd90891ffd8ecd82ec71996124e16f77a2a8.nq.gz
│   ├── 888c85583f72dc67ed997c9868566452e70cf898.nq.gz
│   ├── 88b10ce75a36fb4ad1d05d4f3cde486b3ee38f0d.nq.gz
│   ├── 88ff1492be46a0699eeca8676d36750066c2ac8c.nq.gz
│   ├── 8974ee842149c2458c6e9bf0e354891ba4bcc82c.nq.gz
│   ├── 901f14351bdce339c3fcc6c3b3112c94e4fecb2f.nq.gz
│   ├── 9099f764250a3fe26103b5ddec6336eace2fcb0e.nq.gz
│   ├── 919768f331d419c472182136a98e9195c8ab5f49.nq.gz
│   ├── 9265c2e82237aa1641f8a8cca3020dbf18459cdb.nq.gz
│   ├── 92c00810d4bb67bde1e0cf0ee75d326e662004a6.nq.gz
│   ├── 99e1e0c417d602f445bebbad9327af57837096a2.nq.gz
│   ├── 9eec3b39e0f1947d874412fbe85d70a85e5fafc8.nq.gz
│   ├── a1d47525b03d86691c7c96130ac3fd4ba50f1a7e.nq.gz
│   ├── a3cdb65b974940602b9c6967fa391c77b04c781d.nq.gz
│   ├── a44914d2699d6ccb8f034f99a6a8badaa6c852f7.nq.gz
│   ├── a91cbe0896d93c67bdf387b8a9c5a39b0bfe0dad.nq.gz
│   ├── aadb84f22daa6bd03949ed9966b042f2cea6b99e.nq.gz
│   ├── ad60b546623c02340f4e7eb19bf83031a47b2ea1.nq.gz
│   ├── af596d1c2089811f1fc012b2b352cc4339b405ab.nq.gz
│   ├── aff29f890a081dacb874528f6aa2e9edde9c581c.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── b415af0a8109afa614fe12d8c9d83e095c752d50.nq.gz
│   ├── b5698481e7215b1c64023dfec66d5cea48fb9e66.nq.gz
│   ├── b9e36c248b2d454621e079a61d0456582dbc99e7.nq.gz
│   ├── bd7519d70b565e6b8f72b29783842a8a51ba3f3b.nq.gz
│   ├── c04ffbcdd23447503b16aaa43e47cf1256f7607b.nq.gz
│   ├── c28b8bc52e393e8c591f64d4ef0dd1379eda68e6.nq.gz
│   ├── c7f7558b7f5cda06804923010dcde901538ba656.nq.gz
│   ├── c85b16fe76d0b634d9440772072fd749601f416f.nq.gz
│   ├── cc0246d2ce8446e38c154298af2ef0b8a5b0e2fe.nq.gz
│   ├── d0e26a51ae6975c07fd039919f00ef2e1ad90173.nq.gz
│   ├── d25729588b7ddd229cb0756c0b098ea3709a7a6e.nq.gz
│   ├── d35df0b92bcef0c67532bab64d131d60a43b1ce2.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d6dcb8608f626f59723c48c5fb7ed2b5e4d17ee3.nq.gz
│   ├── de535d0f97c5fd103dfccb173b400b7e71461bd6.nq.gz
│   ├── e4a7e3b551c57b8b6b18af810acb6b26220a50c5.nq.gz
│   ├── e65bc97a07008d21813a4b31c8a1661baceeb484.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed60443dc8f4d1deaed246044a566e0781e88f97.nq.gz
│   ├── f35143eb2ace2ec8c395b78e06459ca40e03caad.nq.gz
│   ├── f93b8632edcddcb5e23f05b83117b0b4d9d3e924.nq.gz
│   └── fc0bd8d783c3576271af6b54826bb979831942c9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4f77240c3fe1b78778e7c2fdae8200f82704c251.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 100 files
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

[canonical/alertmanager-k8s-operator](https://github.com/canonical/alertmanager-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
