# Repolex Knowledge Graph of ansible-collections/openvswitch.openvswitch

RDF knowledge graph data for [ansible-collections/openvswitch.openvswitch](https://github.com/ansible-collections/openvswitch.openvswitch), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/openvswitch.openvswitch
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a1adb384d6192e51dd30ebe8c0555259829483f8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a1adb384d6192e51dd30ebe8c0555259829483f8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0583900f09689d403f6f85e478344a9483c72df6.nq.gz
│   ├── 1bf28d2f1ce7e056baa7adfcf01b1a0257c90519.nq.gz
│   ├── 2bc9ddea081c49478a842ed59210132313584da7.nq.gz
│   ├── 2e7f08121fb07f28a0e727fa00f9ae690a25ceca.nq.gz
│   ├── 306379d4e372a39fba21c8cdbf62a0c45b43ae0f.nq.gz
│   ├── 38bf3dc0e581197e06f25de1a345f7584832786b.nq.gz
│   ├── 3c11a96c946c21813121ed8040f4ddfab0549ff1.nq.gz
│   ├── 3c9dafc69e2bdffb09785ad7933c986281f5905e.nq.gz
│   ├── 3d86ec6498f3f2c00a73220120de77934b185d8d.nq.gz
│   ├── 3ef8193aba5c760df26961ddd6dcf063208089ef.nq.gz
│   ├── 41f91a02edf10b8a1bbbe76eb5efb7e3abdd1b1f.nq.gz
│   ├── 47d2df08bf6486cc22f8f1f5e99f557d2b4315c0.nq.gz
│   ├── 482c59adb1600fc7f9921fe2ac614392aa2a842c.nq.gz
│   ├── 4b9f3a799f1aab9bb33755fc9d2e7160bcb84421.nq.gz
│   ├── 4dead068639e7b0f05166766b3aed49f12743477.nq.gz
│   ├── 52143608d38a33749bebf7262829cb931c9fb7ba.nq.gz
│   ├── 573541ac9702dd3969c9bc859d2b91ec1f7e6e56.nq.gz
│   ├── 57d464395c63b00e64d11e1c5d43824ec61c9b10.nq.gz
│   ├── 5b2c148f4701238f7d35f0d5c106dc9b7aa1617e.nq.gz
│   ├── 5ebc2edfa104b61603927359fb9c92229b1e2592.nq.gz
│   ├── 5f8f9717f99b274e9f2dd291a1889feba9715165.nq.gz
│   ├── 5fbc1b8c80a49313c8908e88f26c5620849899ae.nq.gz
│   ├── 615bf35a7cea83172fda5c9c0840b63d7beb8773.nq.gz
│   ├── 6432d61f1cd43b1c1a5dcfa16ca3545354c527e4.nq.gz
│   ├── 64796f72cd0976d3c338d4de57fcc8d296595963.nq.gz
│   ├── 6482ea1d9e9f63e88b1796c6e2af9b2d0a324eed.nq.gz
│   ├── 660fa5ae173db4b586267ea6b7a62f6f90d84b0d.nq.gz
│   ├── 6827d9fdf52caf41cd631f87284cd8f549c87df9.nq.gz
│   ├── 74d0a43fccfe158623340e102f0357d221271fe5.nq.gz
│   ├── 7a55a1ec7b0c86f13d449be81297cd38817175e8.nq.gz
│   ├── 7e88254c44cb7a82ead98cd0bfae28bb6df30613.nq.gz
│   ├── 816cb44098cc8881b333f2ca0a8f8a1d8f57df8f.nq.gz
│   ├── 846a02ba2c503deb233e79cfc97923c503969d28.nq.gz
│   ├── 85c57212cfe1488c66b254af4f75275491087f3c.nq.gz
│   ├── 86a3150d8e9f6ea9bee6fc725600ec9385bac9a6.nq.gz
│   ├── 8e6a19b29283d9c558c9fa057925db5357ee55b0.nq.gz
│   ├── 90f5c36390cee6c22bc67c792e601aaf05b03627.nq.gz
│   ├── 92a5e11d1bb035274dc5636d44f9c41fe006bdc0.nq.gz
│   ├── 9b068cbd9e068311371124924a11051d6f1f2c78.nq.gz
│   ├── 9ef5ba51651119181521e5925f8ee03e49376728.nq.gz
│   ├── a141c25a7bb0b2d4df05652474b4d9fad3a1eed1.nq.gz
│   ├── a39e55e196d0a56116d0eaba6ef22b287d2e68a3.nq.gz
│   ├── a51f9c505f22967ea2263bd09331b848f7e82305.nq.gz
│   ├── a68e0203ef31a1fbe1c8e4d0066423f6aedcf21d.nq.gz
│   ├── a84fb5070d50d1047999fff1942da4c6b5e97767.nq.gz
│   ├── a8b2ccc40a412f499d5fe7b115077c7216e3fd52.nq.gz
│   ├── a908f0da4515797babf1bfd2382b26f81bfda59c.nq.gz
│   ├── b20413565d1ca54c49583783e956b10b960e5a87.nq.gz
│   ├── b425edcc2da5002c0ac2cf1264e93775ff17a81b.nq.gz
│   ├── b5248a975e1ac4dfece01af8b7f3bf08802a1192.nq.gz
│   ├── c517ce65f7f9d78b8661215f39c490ec7a799459.nq.gz
│   ├── c54d4f5e57df475afa2be63366b781ea40de750a.nq.gz
│   ├── d12c1efe28855cdc80e307a52f723a465d57920b.nq.gz
│   ├── d8bf4ae72a60de8006bea2e342e5a9f20cd8f8ac.nq.gz
│   ├── df3379b820907ce6b2bfb0550e59537ad135b8af.nq.gz
│   ├── e2b9e9d59f898e983b6228f7f97da78b122d8a5f.nq.gz
│   ├── e64394290ab81cb1f64dc6063dff9c19608c4fb0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6be0adb330cbef52fa7d2f54ce4218e9e141d04.nq.gz
│   ├── ea1472ec1f38b2d1410951194a02f8fb9f1c820a.nq.gz
│   ├── ed0eabfbaf172292733d6512db883a18787b92da.nq.gz
│   ├── ef62fb5bd982e62e60f97d7474fbd4b7a74ec264.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f43ae9b13852329df7221f315e4950ec86097337.nq.gz
│   ├── f599e28b8ab0d8c9c57a486c89c4a5132dcbd3b2.nq.gz
│   ├── f62a66faaca945960715d0ef06e7fabcf840b1a4.nq.gz
│   ├── f6cbd7e9c7fd6a56c0aeb11719a72c7cec6a9901.nq.gz
│   ├── f6f3c1fa9b8466d4f8bdc4d5a9efd84319d87153.nq.gz
│   ├── f91dc952a0aa68d1350c56cbdea2e23efa19f8d8.nq.gz
│   ├── fa4225f3eddd267a91bdd4c2d2ccee679c90ca97.nq.gz
│   ├── fe51488c7066f6687ef680d6bfaa4f7768ef205c.nq.gz
│   └── ff821e8af028009a7c1ba87c0a3b1cea04b7ad09.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a1adb384d6192e51dd30ebe8c0555259829483f8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[ansible-collections/openvswitch.openvswitch](https://github.com/ansible-collections/openvswitch.openvswitch)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
