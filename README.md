# Repolex Knowledge Graph of swiftbar/SwiftBar

RDF knowledge graph data for [swiftbar/SwiftBar](https://github.com/swiftbar/SwiftBar), parsed by [repolex](https://repolex.ai).

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
rlex download swiftbar/SwiftBar
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 97f4f87dc90e668c7829f1ee4a6fb7988c47bc73
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 97f4f87dc90e668c7829f1ee4a6fb7988c47bc73
│           └── chunk-001.nq.gz
├── blob
│   ├── 0239bfcc5abcbadfe0024faae7984a0e0eb6389f.nq.gz
│   ├── 05f20b775e1d96df197bfc3e85a0f25255650fe2.nq.gz
│   ├── 0bdcb2a61c155c9b4e1995f4fbe109226e61601a.nq.gz
│   ├── 0f4b1dcfb76d7f7c230c7c31411e33172300db0f.nq.gz
│   ├── 11558c75e4e4c432cca46b7da512f7515247c642.nq.gz
│   ├── 11819ed1c79b9bce05f17dd00357237c8ef51f3d.nq.gz
│   ├── 11a2d8cb31980b544971894e7cc11a6a2095ce6e.nq.gz
│   ├── 12e617b89aeb96bacf4e2dca8a6e51eb430ad164.nq.gz
│   ├── 140127e406965b1c1458c5b3b967c1cf3aaf72d8.nq.gz
│   ├── 179d7df07ad18db2d965ba2f2a00c59f7c936dc9.nq.gz
│   ├── 1801c4a77850b6e4e68743cf908775dc090e75a6.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1bbc06277c9947dc0acaa7bc7b43626814e932fd.nq.gz
│   ├── 1c1b42c17b39513561e39777a7830094499af367.nq.gz
│   ├── 26043a167fbf13f8d7b1df96a39c8395cc7e73d5.nq.gz
│   ├── 2698dfa7f1ebe79e2f02a5298c3968f02dc3d435.nq.gz
│   ├── 29765f750dc3c0b171e90c05a81cdbb5e3bee7a2.nq.gz
│   ├── 29b2be15a9d6a96133ed5deb998134808e8f6544.nq.gz
│   ├── 2b206cde5652613ec5937567f80c37c82836ad5c.nq.gz
│   ├── 2c2e5854d1bf18488bf32457a86e01ce6467d27f.nq.gz
│   ├── 2c8308a19a934b90bb9812a5390ad3060b0a805d.nq.gz
│   ├── 344aa18df93de250a2745d0607fb9930b978c0e9.nq.gz
│   ├── 35951737fd051b4f846ecd341812f020cce131e7.nq.gz
│   ├── 3cb82fce2dc5ab8dc20c227d0b898c0fbef5d3f8.nq.gz
│   ├── 3f1152090d6d87626b136eef87e8fd0d471910f8.nq.gz
│   ├── 43864b38e3b5e6773ad1b84ad383ee131796a60c.nq.gz
│   ├── 43e820ad83af8510ad44993934cd450e04c8133d.nq.gz
│   ├── 4dd69604ba1367c63195ee92d39d87ad8d97d9e7.nq.gz
│   ├── 4ea154eed4c47340ca824ef8278a79344e220bb3.nq.gz
│   ├── 500f34932da6881d4aac9925dc87c85a20ce7bd9.nq.gz
│   ├── 574983a641f11db9269b6c1d785095d3a63d0d47.nq.gz
│   ├── 57f5ae765d0f0340af3522ff292241939f4ea8e0.nq.gz
│   ├── 5d399bbab711584f5f8ca474b5d0a5ba14a4b8dd.nq.gz
│   ├── 5d66da23ce4c0c792ee36e498e717d3da4c05a5d.nq.gz
│   ├── 62278e1728a479a6629bce0ce9fecb79e02f8152.nq.gz
│   ├── 63fe32496f8a455e3c32d2eddaecaee993249db5.nq.gz
│   ├── 64641b1dc87e352ea7ddf3a2f60b26a1622bbdb6.nq.gz
│   ├── 675b6ae74fa513fec0f9acdd93ade5ba8d7dd221.nq.gz
│   ├── 695651756f0ca647486afc6d5df0b909283ecce9.nq.gz
│   ├── 6fa1f2d17c30b8bfe7d5635fdd88a4a885f495b1.nq.gz
│   ├── 749187ec58d94c34f09a03188d2347cdcbcbcb5a.nq.gz
│   ├── 759caba5177168184cb50b5e2f3bc0a507607d1f.nq.gz
│   ├── 76dc4eda02f672a81ce24bd3274f18e7d30d54bb.nq.gz
│   ├── 78ba5fabdff2c366d3546a6e7a9fa9e9a6807092.nq.gz
│   ├── 78fc0497629b5acbb95126d9cfde515095f37ed6.nq.gz
│   ├── 793eefdd8dd29c6869825d0d202cfe6593b69d89.nq.gz
│   ├── 7b681ee0896433976603e4a497eee2826dcc8dba.nq.gz
│   ├── 7c235bd810537ce896f1a02e2bdb637c16194f03.nq.gz
│   ├── 7c968afe8280371c80b2f15b0e85c6e4d397768c.nq.gz
│   ├── 7ce442353f842f2084d1d6e97b3e095a9e2546fe.nq.gz
│   ├── 818161a5bcfd1ae4234ec30d4de88bdf9d932ef4.nq.gz
│   ├── 857befe70d493f422e7de753be0de1226fcb7a3c.nq.gz
│   ├── 87e22cfca89ee30afcec2b1d48a18a62e7028ec9.nq.gz
│   ├── 8aaa93835a2fd280d068f6ad918145ac4187dcd4.nq.gz
│   ├── 8aada33761eeb8c67266cffb447812a33d6d78a2.nq.gz
│   ├── 90f436725f1dfccc72f12ed391598fb717794dca.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 9231b2b947e91c63be0e36ac299575fc4b4bbd03.nq.gz
│   ├── 9309f78b8d43bee4fc7cb14498fff6f24f7f9606.nq.gz
│   ├── 935bdf08c6aa6266735940fb4f9792edb7aaa97b.nq.gz
│   ├── 937a08fccbbab5163f9fc379cd57e73f2a5c0730.nq.gz
│   ├── 95743e528294b4bf01a2a6f5708c9a2ea9bbca5e.nq.gz
│   ├── 9730bf125615a8143fee19faa7486509db8820a7.nq.gz
│   ├── 97b724eabff2951f644bd96a37b664418f62a96c.nq.gz
│   ├── 992b73fa16ebf6f88ad3ce7f04770dbd12a5236d.nq.gz
│   ├── 9b7475259ee70a8d83ab4790ed884a75ced2f500.nq.gz
│   ├── 9d8b7ccf48314fe3fe45b9211d3f508f22649a2d.nq.gz
│   ├── a024bcf5a88d7e61703bd7622ca2a61814dd70bc.nq.gz
│   ├── a1cbc50a38cb956358680d4028718f99b8396581.nq.gz
│   ├── a288718dd1943098d5e3de349a6eddcb0aad9053.nq.gz
│   ├── a41b7a32bb9434cc623674367b0eda2fa8793bb3.nq.gz
│   ├── a4ff84a6e5f188db4e097b6b89fcf557763599f0.nq.gz
│   ├── a56ac5b554328fca1b4a1a2da767e10e9543f997.nq.gz
│   ├── a5ccc1f8b660c6052f0928a7777df40eaf58c06c.nq.gz
│   ├── a9c4e527ff36bc89a3033eb1f9804fbcb5ec8737.nq.gz
│   ├── aa534263513d5a2f102a4c9afc85e922a1c8ede5.nq.gz
│   ├── abbb4c814acb4d487159ba9e0578c9ce5d33b168.nq.gz
│   ├── af0c898c877722cecef41cbe6b503c190c96949b.nq.gz
│   ├── af52615d2922b23d426f5005d253b5d258d29c68.nq.gz
│   ├── b46254f98993bf76d0e5c8f5ff4bd81f43639808.nq.gz
│   ├── b71fae1421c9794fe07bd21be26b72252eee9ecb.nq.gz
│   ├── b882890a0fcd0ffa4a5b93c1e409369ac0a0788b.nq.gz
│   ├── bcb19b32a301a656dee15f7b5c1d2156edf608ee.nq.gz
│   ├── c0131a717a9d71ed4acfe035ddf57b50ee1b76d2.nq.gz
│   ├── c3c0f0e41cbdc6811c1206914c7f69295f6fd436.nq.gz
│   ├── c8a285dcfedde49086eaa761482d034b8617a7b6.nq.gz
│   ├── ca0d53c608e6b9dc0e8949733cecadf2016935cc.nq.gz
│   ├── cb5c46d24ca1866c5a1f0bf3e0bdad6f67ecc11e.nq.gz
│   ├── cb93382330e4f3bf018aa42f20f360a81344384d.nq.gz
│   ├── ccbe6ad07467f253dde3a9d8416f2e829afbcc23.nq.gz
│   ├── ce646d65c66504b880aa03d1f1c77ff2dc9d27bc.nq.gz
│   ├── d1262f13751bad11972aac798880b7b2522b874f.nq.gz
│   ├── d187812b9745903cd0b90505b739930b4536b300.nq.gz
│   ├── d3bc6da066d97c92b3c43186024ec0f8a41a7d91.nq.gz
│   ├── d403c54e01b9848eb50a8c45c12b7cdde4f4a12e.nq.gz
│   ├── d9b8000a20d8d7dfa997f5c6d872fcee47ee71c9.nq.gz
│   ├── db350494e52209e4d1b6e5c5dbc00af4ac0bfea8.nq.gz
│   ├── db6ef12a3700e5b2271e44dc083de558ab483b4a.nq.gz
│   ├── dc0aceb427d8a684e9fd303142e55f43b67f4dc3.nq.gz
│   ├── dd193091c69048621e3ad38c00ac530341abc48c.nq.gz
│   ├── dd8ea849b38dd57dd3ec47d2ac785c30cd927491.nq.gz
│   ├── dd9f185ab64097c7e0f2093d05ee7bd89e022b40.nq.gz
│   ├── e1dad3054d8d4f233684b35cf1a23398febadd2c.nq.gz
│   ├── e4cba2536275341f5828ddb1942508792529617b.nq.gz
│   ├── e9e731ceb88d7746a3150ee26549884ab755eedd.nq.gz
│   ├── ec1d4f0381fc4d4008a467f6b3a3105d2093624c.nq.gz
│   ├── f0112f479da9d7cacbfaa2f838f5c5654a3d1f0d.nq.gz
│   ├── f0c3806c6e329e1f2c6cac313cbea5ff38ac5b4d.nq.gz
│   ├── f1109cffe050a62b707b03db4216dffa25fc01d7.nq.gz
│   ├── f249c4041f30b1ffe20931dccf061efc32edf258.nq.gz
│   ├── f2c2c0ef320103492b6cdabe06d0e346801e76a5.nq.gz
│   ├── f51f98e5086c57acdfaf3dcca96912dd8e8d8c67.nq.gz
│   ├── f61874cacf2b3921b9d46677e4a811b327b00680.nq.gz
│   ├── f670629f6e9fd3ef9a0d2a99b664ef6f17903986.nq.gz
│   ├── f6aeaa33349a4d896729142b2443ad7350cd378e.nq.gz
│   ├── f98e2ef9c2eab784d9226c8d0843c18014f73caa.nq.gz
│   ├── f9cdda02a1935305dc5798bd091036d70e9caeca.nq.gz
│   ├── f9cf7af4aeef56602b517593c509d5cf12e24d66.nq.gz
│   └── fe6e648bd50960eb3eed373f1eab0b5df8f83bf9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 97f4f87dc90e668c7829f1ee4a6fb7988c47bc73.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 127 files
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

[swiftbar/SwiftBar](https://github.com/swiftbar/SwiftBar)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
