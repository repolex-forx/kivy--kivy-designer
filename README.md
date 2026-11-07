# Repolex Knowledge Graph of kivy/kivy-designer

RDF knowledge graph data for [kivy/kivy-designer](https://github.com/kivy/kivy-designer), parsed by [repolex](https://repolex.ai).

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
rlex download kivy/kivy-designer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 20343184a28c2851faf0c1ab451d0286d147a441
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 20343184a28c2851faf0c1ab451d0286d147a441
│           └── chunk-001.nq.gz
├── blob
│   ├── 04c4752285f27e0182ba0587ee3a9f15d0624cd6.nq.gz
│   ├── 0a92b5e1fc1f9b1e2c873b013a6fbf727af0485d.nq.gz
│   ├── 0e7e679d91952affa4e9d33cce8dc3e573e48a6e.nq.gz
│   ├── 0eff2e925918421dee3de27587e8bf06cf33ee59.nq.gz
│   ├── 10d004338de254f8bf4dc9224e80cd811b18a6a1.nq.gz
│   ├── 1431da00671da4dac0b5b6a160a01def25578eed.nq.gz
│   ├── 167aaa736d695459547d016f9fbfe57d95a454d3.nq.gz
│   ├── 1811f8493cea9bd0053d197ff0ac646d81ffd556.nq.gz
│   ├── 1f7f9df069930af5bcf2d3417d12cfd3a2521a9c.nq.gz
│   ├── 205792802b5cc3cff5026be2f578fdffa5f56784.nq.gz
│   ├── 217d7864f9af61a0d39e987ebcc4f188168e6e96.nq.gz
│   ├── 23ed684593be8b06152464d098d64f4ee220c553.nq.gz
│   ├── 252356195ddac44414530b95d365d9a787188982.nq.gz
│   ├── 2707be62ffc9b556a0d7eead77158583c06786c6.nq.gz
│   ├── 290d4b7a0060885908bee56c1ea3ad5213d3668e.nq.gz
│   ├── 2c91aae876dddd4c01695a4ce7720ab8a6950ce9.nq.gz
│   ├── 2d7d9606cee6a0cc17653913f706ea5296b25591.nq.gz
│   ├── 2d871d4a69185e55bbef83d9d450e78f7cb48fe0.nq.gz
│   ├── 2fd5e5f4fc4b51f449160638cc179d5f12420f42.nq.gz
│   ├── 32f023a7c2bffa5aa1b64d4642011da585379f7d.nq.gz
│   ├── 35e191b7537513d83fec7651eb8777a8db37a79d.nq.gz
│   ├── 36b14ae41255f4aca041943497334cb416be5c4b.nq.gz
│   ├── 36df0deb79d570876327debfa25220a2bc5d7f0a.nq.gz
│   ├── 37b695085fba878acc57da2a7e38379990be11fc.nq.gz
│   ├── 3900c0c6ab2f61d54c786df84dfbdad8d130dc62.nq.gz
│   ├── 3982e3e68e26dedb6c7ca1f2ea0b9cb2d81742a3.nq.gz
│   ├── 3d780c51b1e22eb10c3e967d03d76908c5477a89.nq.gz
│   ├── 3d9e9af85d896f74b120f7245575533b2b55671f.nq.gz
│   ├── 3e6a2838e62ec79278a1f7ff9c6dcfb967a54a8e.nq.gz
│   ├── 3f1565e8e654ce6647d32f12f9cc370f60f4b958.nq.gz
│   ├── 4163c289345c25343eb556a756c4e7ba997655c8.nq.gz
│   ├── 43b20e38940af28ce26f45417abd193e2961c3c3.nq.gz
│   ├── 43bae7e6ac7fee5139bcb4209e7b8651a1f71d9c.nq.gz
│   ├── 43f720d2d2d7e3fad3a33f432a98636b1e2abdc5.nq.gz
│   ├── 4c60f03bf5f11ff2a5cf6074e777d1c3187d25c6.nq.gz
│   ├── 4caec023a57acf33294ba8d10d94c658c1125d48.nq.gz
│   ├── 4d660dc79e3c0b917cc0fd05f8ac76dec0efede6.nq.gz
│   ├── 4dc7455bada3f21f8d3024280600552c5eba7a22.nq.gz
│   ├── 4fa6c3ae55c2936b7ce00bfaa20180dd8d7a0201.nq.gz
│   ├── 546187910a655766bec99218a230aaa6ea9a595f.nq.gz
│   ├── 55e7c95e964e7c1adef371a38d6e29d597f557bd.nq.gz
│   ├── 5730e4db9e2cd1ed70e5898c6e22796c9342a1e6.nq.gz
│   ├── 57e67068992de8f790a030197210ac93cca34b99.nq.gz
│   ├── 59cd744836020d3dcd5c23de534db19d864c0378.nq.gz
│   ├── 6080a3d61c804aaac8c430e32b5bbf605f377708.nq.gz
│   ├── 60f2c2459186eb3faf0c97da071009100bd8fd26.nq.gz
│   ├── 6327ef8b44efb9a6d6a68d7b6ae649a3acb98700.nq.gz
│   ├── 635c3e1b0da085489ecefc80761156ba420dc3ca.nq.gz
│   ├── 63a78e2599f34f26ef788f8c2b5d2457c668f817.nq.gz
│   ├── 6504f6f37074c623b0b4b93e7ca2df3dcd650c56.nq.gz
│   ├── 6718f2cfebd1b23665d5ea24c044dda98246b0f2.nq.gz
│   ├── 684bd11007db7beb4e951a0c3e7958523231e2e9.nq.gz
│   ├── 73db19e842d71b8c535180bbd63b15823605ed09.nq.gz
│   ├── 74aed9376cf63173c8bbec55e8c67debc425a7ff.nq.gz
│   ├── 774a30ac02c413a34db7e952113b55ed626659e6.nq.gz
│   ├── 7a1663f328a078349e6f77b09c68747926e74ba6.nq.gz
│   ├── 7c2f1e86960dc0bd64ddeb914fd35d564647f25f.nq.gz
│   ├── 7f27766ee67e242d9af467932bb0bc778d9cbda4.nq.gz
│   ├── 804737b91907b18e28b476c37866e8ccb3e7b8fc.nq.gz
│   ├── 81416ba046422110f832934412e0256254db5ef7.nq.gz
│   ├── 84c2dca64992156b239a01f4dcc6941ee9a64133.nq.gz
│   ├── 859f31bd7700a84b5e4cd7cf974a13b9783d27ff.nq.gz
│   ├── 85fe386e25181bb829618eb809c1a859aa6bfcfe.nq.gz
│   ├── 8657bf6a3210a7ab7cd509c13ab318f8d8efc100.nq.gz
│   ├── 86ba26b1c618d9631802714c65359303813d0b49.nq.gz
│   ├── 894867ccbf62b6740079d8a2578c8cdb8c425526.nq.gz
│   ├── 8970055bc97f68ff0a6d98dd543f79a160abac5c.nq.gz
│   ├── 8af04dd1fd1305cc1abe29eec01b702bcc41eb3b.nq.gz
│   ├── 8b896c7383570edae6308b7fa83d8479ab848382.nq.gz
│   ├── 8bc823699c03f0597bf10dcf40b3bd2ba05d3487.nq.gz
│   ├── 8c3176e5a497d794d5b4cf2a23178c98f4d137b9.nq.gz
│   ├── 9266a4258c078608467cf75e82843deade83977a.nq.gz
│   ├── 926d66374b83ed01ab885d2403fdf8341f6cf47a.nq.gz
│   ├── 9838938a8e60028af3f867bf2f809d45925d5dec.nq.gz
│   ├── 99531c7c49a1f25c3673cd8a133359829810cb73.nq.gz
│   ├── 9a734b29b3040ddb3ae6fdf53853dc192e3357bb.nq.gz
│   ├── 9a82ca0ccd3bf990cdaf9557920f1a84f6913b78.nq.gz
│   ├── 9b7a3e8eb37d1ece8f528daf2c4d3de10d7f48bc.nq.gz
│   ├── 9b90e97cf90cc12bf66a25f85ca6e6f1d418cc85.nq.gz
│   ├── 9d0705f00fb3bffbec67efb3cba97704d983ab4a.nq.gz
│   ├── 9df4c879ee99d8f15f94223ae2970d31fc77854f.nq.gz
│   ├── 9e50e45b1318986ee97f289bed225b5668445c56.nq.gz
│   ├── a07fed52fbf9ccee508c45bbd0f187cf3b5c564a.nq.gz
│   ├── a2447f45f4d455b3f9f690e162725a8b481e2a33.nq.gz
│   ├── a2c1672579fdd9069356b16f4a993fe66a56d754.nq.gz
│   ├── ad8acd662885c4aab4d3232bb9ff65921eb5c795.nq.gz
│   ├── ae59825a1f5fc9f5acfd35d01c5e67ae76c24491.nq.gz
│   ├── ae659afa1b3e35ea3ff6de75249e8d98753c5e59.nq.gz
│   ├── b0c1c66288f923d626363c4e6d1ad6ac62e09909.nq.gz
│   ├── b1901ca89af53eda56cbc5e3ebf10562ce2d9b0a.nq.gz
│   ├── b2582c272795a0bc30b7e5b6f496fcb27391a4c3.nq.gz
│   ├── b268e09df4e10c5433116d4279184536b7226581.nq.gz
│   ├── b890aeddc065998119bea1864898bafb4188bd47.nq.gz
│   ├── ba69723cc419f91e7e182d1f667588b33da7fa91.nq.gz
│   ├── bee4d1724f7c81e503b7ff5186a0589c805989a8.nq.gz
│   ├── c23c52e35691268b9311e7b47a12375791a836eb.nq.gz
│   ├── c5d56b63ee56fd4dac5bfb59ff1083c6a54aa868.nq.gz
│   ├── c802bce6e831d974127635b8ebef1b5734fa4a4c.nq.gz
│   ├── cac9103860f89c22b3623afd4d60a836a528b216.nq.gz
│   ├── cdd6b79fd2bb5d45d2b47634dbd38315257cdefe.nq.gz
│   ├── cfe13a27d3b705eb261f7cf74a246229085690ab.nq.gz
│   ├── d084dab7306a124eb4fb4e779cdd7283c6b7cc0e.nq.gz
│   ├── d3ea91bf4a49e85c6176c0eb0be2cd85c5e75fc8.nq.gz
│   ├── d5d6b13c8523290257544a9fc3b75abf911b367d.nq.gz
│   ├── db3c76dfa18843d55ac5e2b68e0d7dbe48dcfe65.nq.gz
│   ├── dc194049c4f76de7f3ca8d46e83721fe8cc64f56.nq.gz
│   ├── dc89f3ccd2ce36933c7d1de93349b56e40392275.nq.gz
│   ├── dcbd5de91d15a74030495c53834d72612cd93a20.nq.gz
│   ├── ddc82f19b0d43e1e1752cbcbdfbb5797b008c355.nq.gz
│   ├── ddd1fedd6f45bb407b99c0b28d18cf1f05d3986a.nq.gz
│   ├── dec80b1b1792f1f067597f8a66f52b4ca573bb5b.nq.gz
│   ├── e3c2a78b59169d70f572183c7db8cc9821a99ec9.nq.gz
│   ├── e448ae61d3c3ef9700c22e459abe1c9085343094.nq.gz
│   ├── e49a07a97d66a7ab7b2d56f6630373e14c86190a.nq.gz
│   ├── e56bd6d65dbc2e4d355ba48aba8a0136e7152c94.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e891c1a9d6954f44909398b98d7f5d1a42a5912b.nq.gz
│   ├── e92dbbbcce261ec643c40316717a70593ec3b48d.nq.gz
│   ├── ebc5c8213c903c8029614a34129fb6ed24451650.nq.gz
│   ├── f5c4e056c152cf05b8e4fabf655ab4c188b05bc8.nq.gz
│   ├── f6a21d37b9c0d0da501c90d4a813c8c46080cef4.nq.gz
│   ├── fc5a714622adc13120577681ca20546cdf3ffb1c.nq.gz
│   └── fe62ded162a322ac6cbff4cd7257683730dffa05.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 20343184a28c2851faf0c1ab451d0286d147a441.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 131 files
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

[kivy/kivy-designer](https://github.com/kivy/kivy-designer)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
