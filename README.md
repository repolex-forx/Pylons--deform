# Repolex Knowledge Graph of Pylons/deform

RDF knowledge graph data for [Pylons/deform](https://github.com/Pylons/deform), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/deform
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3977582583d8982d3931b1eacf63c4de4841726e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3977582583d8982d3931b1eacf63c4de4841726e
│           └── chunk-001.nq.gz
└── blob
    ├── 006f2ee4d4a9670fe9bc38cc5186c5fd4aa5ea3a.nq.gz
    ├── 008382c5cf180b5441b99d6d83bf3a954112957e.nq.gz
    ├── 0173e6135c54b0d8de0294e974b687d358206f23.nq.gz
    ├── 018cc25d35295f28a9ce4e7d175fd5370493a985.nq.gz
    ├── 01b32f15ce48465dee44f42c4217257261dff531.nq.gz
    ├── 01dd9f15ab9fcb81b6e02b07f992eb67938c03ba.nq.gz
    ├── 0200d1385033c64a60c7874991b441af704944f9.nq.gz
    ├── 021c0c78fa0da5e1ee7c8149391e3afdb807c345.nq.gz
    ├── 02f9a0590bd0acda1a2d1370c2b70e545a88e444.nq.gz
    ├── 032798019a5779725de27167a51cd710b026d1d2.nq.gz
    ├── 03cf417a7389c92709b65bbd71774f57f44ed403.nq.gz
    ├── 04865049484f403e5688635ca4652dc3db520b99.nq.gz
    ├── 05d9f200104cb22df9a8393730faef3e8b6a51a7.nq.gz
    ├── 06aef1413f11f0e14c7685da09fe58e7b7c178c9.nq.gz
    ├── 06ced185be28c394f81d8ed959eba42de1d36c8b.nq.gz
    ├── 06e3e5fad2f45ccdea7c04572265f3185eacdbc8.nq.gz
    ├── 073592cd1a41682ae47d6e471897c1113b72ac59.nq.gz
    ├── 07f15d8d4d19b95572e634df40f08896ed14a514.nq.gz
    ├── 0829b30875adf2aacc0e2cde906cf9aaf5cde204.nq.gz
    ├── 08c641344a905d6ba619f8f3c386c047b5bb8c98.nq.gz
    ├── 092c73ad6ab2239717280251b1e6b0508ced6cd4.nq.gz
    ├── 09caa8655b943e6e83cbf8777f8a85f03e986867.nq.gz
    ├── 0a1cf2038a3dacd63ac57feb7dbdc0d9505f248f.nq.gz
    ├── 0b29757726f19b33266d16021905bffbfb74762a.nq.gz
    ├── 0bfaefd36f4da7f7c9d246900b05ed5532a8ece3.nq.gz
    ├── 0d4637e402de5b5ac10a59282b4b105ea411e6cc.nq.gz
    ├── 0de727c0a6ae48387ab2428a739c762979ce9ee6.nq.gz
    ├── 0dfa5ab2f1bb4f953c8d5c26a1ae54b76f1bd6ed.nq.gz
    ├── 0ff61626b3321da562faaeffeb9134f69e2220c4.nq.gz
    ├── 10256ea66d61c1176a5db12bc3da7ae947d43773.nq.gz
    ├── 107b67ffa7fb3636cbae44d137567a56555c4410.nq.gz
    ├── 10a5deb0f17aaebad72b74fb294c3df6d2c33cfa.nq.gz
    ├── 11041c78340067274f8ecb1e9c7ac1953f72b746.nq.gz
    ├── 11fddecd9bebd9f93f47ee11ec6a5d0c502f9df0.nq.gz
    ├── 12895602da9e02bcd25d0cda8115107ac8238f69.nq.gz
    ├── 12b28badd1d833500759e94f98333e88e582501c.nq.gz
    ├── 130ec9062fea8eb3f504bff9a053fc85f9fd3a34.nq.gz
    ├── 13a16738c5f3c7b040f4b1cc89ccce11d51651ee.nq.gz
    ├── 13f5e1a72e7744961029973eccb0f1454df40742.nq.gz
    ├── 1416357a19e009b955820030f501b9e58094ba53.nq.gz
    ├── 1485fcfc6bbfe6f804b583c284fcf3536776b0db.nq.gz
    ├── 14bdbac4589422f6d1216ac4c56e7cb35bd19810.nq.gz
    ├── 15427029d29aeafbaffc531cb5e2376125d1550e.nq.gz
    ├── 16440c0e75ecb580459111089cee1e7bab6840f4.nq.gz
    ├── 166c549765cb1b2d32a63a40513f4e5e35085ac5.nq.gz
    ├── 16704a00a7e15fc3691eb66656b0f66330690694.nq.gz
    ├── 1699896828dc2ea12a193d1080b763054324a0df.nq.gz
    ├── 18134528ead3dab8ba61a7c3d85be30e1b410252.nq.gz
    ├── 187c188d9c60d72d9e2b0de541faa21a4fcddb85.nq.gz
    ├── 1984ea6a519118cebf476d6021303f97f1401d67.nq.gz
    ├── 19febc758cbc34386a4cde4cd56a381b8996a579.nq.gz
    ├── 1cc7973416d04dff4fecd58c4b9dfe8270c76820.nq.gz
    ├── 1ccf81300c55ba9b9c8f3c0aa8aaa2f1556d05eb.nq.gz
    ├── 1e412f35945db3633b675c0da9efff2369e2ce19.nq.gz
    ├── 1f77c35c117991edb52721f65ef6ad2009ee51b3.nq.gz
    ├── 1f88e55d23420176a401cd531461a5c6e7ac5b60.nq.gz
    ├── 1fa411248dc2a80f6fed48ca5d4921f527ba8ccd.nq.gz
    ├── 20cf5cf0aa56d3aa5a056bde78b95209c9834118.nq.gz
    ├── 2133b69a025711980de0a38b6d227732730b5066.nq.gz
    ├── 213930e9350b45a4e0d677b7c9bc970b4f1f240e.nq.gz
    ├── 21908cdf8cb02741932064ab98ed10f594a897cf.nq.gz
    ├── 21928e4bd6681c42c7e062ebcd4e75c2fcd21c4c.nq.gz
    ├── 21b779f277716c71e7615fd39ac0bd7a69b8b192.nq.gz
    ├── 220bcd21375e18a60b71bf54b1cbf48035d839c6.nq.gz
    ├── 228d53df8d30a32313b48d19bd5357f430a23086.nq.gz
    ├── 22a7f6e194963b715d0f4281163528d1f27e43c5.nq.gz
    ├── 22b64a3c28666eab3d8d94592a149f705c71b035.nq.gz
    ├── 22f07a193f82582eacf5bb861768ca7845379aee.nq.gz
    ├── 2376d6f7aa36f5765d84a9a60841c6ab38bd7cf1.nq.gz
    ├── 240f7ddda86e36301580c39d4eec6a1c70de260c.nq.gz
    ├── 2449a90c76e387378864fee482ffdc474159ca2e.nq.gz
    ├── 246e5200a85e43e9172457e5ee7ad939b0c873d3.nq.gz
    ├── 24a0151a8a1bbc004bcbb54d1dc3b91448edc9bb.nq.gz
    ├── 24f708cbef593b740192797ed94c2aef0af71bb2.nq.gz
    ├── 25b0a3710d63578b807dcfaa9a0b886820862de4.nq.gz
    ├── 261d5c99ab272025ef32966652edb656db904c28.nq.gz
    ├── 263c9b8785298c4b082320c4577c4c86d567120b.nq.gz
    ├── 264ec7a08c474a6436dcb8e56cccb38de51e3213.nq.gz
    ├── 26b3dd26863917008ec4fbed75074d255b1dc385.nq.gz
    ├── 27906617210b8e169ed14fe94f2f48a68e0db51c.nq.gz
    ├── 2791e151cd08c868f7a430f5927de46123d7bf9a.nq.gz
    ├── 28071d49a518a16e7396681382488c5de7aaf126.nq.gz
    ├── 2ad80b4b6e558b5d6d78b8445e9975aeef4c2382.nq.gz
    ├── 2b0c119473408f8b5b11f111d957ebf155220fe6.nq.gz
    ├── 2d556b62f59c86342cfdaac0d3220541b3c71133.nq.gz
    ├── 2ded00776a5777b9a5b922c5ab6956c8054df7f8.nq.gz
    ├── 2f7cf001c7a7bcb258ea832a3c994ba8ca772e95.nq.gz
    ├── 2ffaab32418af0b2969514886d7247eb0f96e7fa.nq.gz
    ├── 319074ec67a6dd5200bcc5d5ab09a2fa8259df12.nq.gz
    ├── 32bd847eeb9d9baca31dd6cb2a2c5a032d9eb8da.nq.gz
    ├── 332a765e8afc7cb83dc49daf42528eb56a2ff3b9.nq.gz
    ├── 358572a6576bb33f5a4a16763803c2769d48f278.nq.gz
    ├── 35b3e6ca789f6160dd7333d9bb3192125815ed65.nq.gz
    ├── 365b31b1ff5c18426b837d3c123e8918cb6bfd36.nq.gz
    ├── 36794bb990996968600ad869d78ecd90138c6087.nq.gz
    ├── 3727294e9c98167b659e53e7d880bea3a7adf2e3.nq.gz
    ├── 37876d5a8a291961f448943600db200d37f132a9.nq.gz
    ├── 382375b007bc115bcf0d632670407778fd3233b2.nq.gz
    ├── 383b3d25f22fd2ae713acdd3ff642457916a2a3b.nq.gz
    ├── 389aaeeebc564a0f9938496d24f4a620405ecc54.nq.gz
    ├── 39ff5a32b9673aabccb472ae077fd3c8075469f2.nq.gz
    ├── 3a49f66fd2a967ea719807a0fc05cb1fc0e165d7.nq.gz
    ├── 3c1f833ab1c48f9f7de698603dffdc7d82a9dbfa.nq.gz
    ├── 3c579d34bb03f324096aa4762ad520e883a0cb48.nq.gz
    ├── 3e434a2855c56afcca223a0e92a13b2a577f2f14.nq.gz
    ├── 3e733d301793e781c5e984f41a73605cacc524ea.nq.gz
    ├── 3e9ef8cf7b49db80d924440da930e5f70b8bae7f.nq.gz
    ├── 3eb87bb95453bef7b7d01f4702219ae9bdcc1672.nq.gz
    ├── 3efb84a6e8084a66c17b3e213f5c698cf6efc28c.nq.gz
    ├── 3f449f2a6c83e5560ef50b725cb19458e5ee6ec4.nq.gz
    ├── 3f4f35a745e9ec120b15f5df3166a4cf1edb436a.nq.gz
    ├── 40ddee4081bdf525a819e9404c6c1dc78f6dc73e.nq.gz
    ├── 41378ee0df35dbdd38d1636e1fce23f5f39f79b0.nq.gz
    ├── 4170b6c59e05d580bc15cb4bfde4c3212ced760d.nq.gz
    ├── 41fe62c35cae857fbe46d499e7457da105724440.nq.gz
    ├── 422d5066e33e85a2be14d8891e041b952e5ef57e.nq.gz
    ├── 42e2fccb5fe60fc79a9b15aa23a45b0715f50060.nq.gz
    ├── 43078242f7a474bf82a9dd704666ca29a1526dbd.nq.gz
    ├── 43862c4880990b8cd696a369b7ecb407ee27a07b.nq.gz
    ├── 44aca8b1b14dc6844efe8f723d249be228f14303.nq.gz
    ├── 450a34a6158e1d94960a49660ad43f1c88fe5076.nq.gz
    ├── 456c2c772e526c29ef77acd743900bb0e77c8ce3.nq.gz
    ├── 45958c4de0afddaedafeb18d9c6e138622487576.nq.gz
    ├── 45fb60ee5d8eee57e236850b4fa8824faef2429f.nq.gz
    ├── 47663ea455528bb9238bd1e0eb654ae10f78fa1b.nq.gz
    ├── 49490ea28daeb86abe7ed1d2c6c27f5370ffa6c5.nq.gz
    ├── 49718ed4709f7cf4ca4541e2955b9e31803f087d.nq.gz
    ├── 49b7818dfe52e344c5dee0398516b1a4762afba5.nq.gz
    ├── 4a2ece3568778a1a6a4b6f129263b8e6af2c4057.nq.gz
    ├── 4b7e335b6a84d662ec33f64a4ca9cd66f44b6ac4.nq.gz
    ├── 4be30ed04b598c46a3e29dc0f46b30a4fff92112.nq.gz
    ├── 4ceba54be72f1fc5ea45928e300c22d249b39089.nq.gz
    ├── 4dd7c461d06fd1d7c7c1008366b7a806f331e331.nq.gz
    ├── 4e4f794c53d2fef57383aa51c2ee6e47aec40b11.nq.gz
    ├── 4e8e817b33f58e1fea3687902393d04955477576.nq.gz
    ├── 4edcf900fc5c0fdf603bcb653a906e596a3c961a.nq.gz
    ├── 4f9fd0c9a41a855347d41f03a7f371137d94a777.nq.gz
    ├── 5018badf30e0738f070958c979cb7fd71c7b44c8.nq.gz
    ├── 505da15711b8d714f0ccb29ecdd05b347dc17015.nq.gz
    ├── 506cb9dbe1368c195bc87da1977cc274eaa6f59d.nq.gz
    ├── 5075df0d244ac753206b746b151f8c872baea451.nq.gz
    ├── 50c1371dc1d35a0053348c8c82d5b791a1275bff.nq.gz
    ├── 514953a68eba0e1ad651a3a4c8d9ef8640a500ba.nq.gz
    ├── 51cb8fcc1ffbed21c6d9e241aa1db62e9a9774d2.nq.gz
    ├── 53f6c30fc53c373260492d632249689cf9bf3c91.nq.gz
    ├── 553a0af9d2804a2b7e853cfa7ce28e19f6e78674.nq.gz
    ├── 55e49c6b306073e411e9c776d2428896bfb1bd6a.nq.gz
    ├── 571675fa48ac058304898dae206dfe011f558e7a.nq.gz
    ├── 579ab493587a6d0999c9c1f66d95880d4f973671.nq.gz
    ├── 58215deb28c7b4ec48fb9a30708dfaa38afcec1a.nq.gz
    ├── 584085aaacf5d4c9065ea051a32a7cd2b7bdd700.nq.gz
    ├── 585a7fafd176a78fa50c04e29714da549279af63.nq.gz
    ├── 58f8f73f4f74de4b8c81d38e4b63572a814ecab5.nq.gz
    ├── 59c7ac03059e8f8087a28f7baf59d420278cf323.nq.gz
    ├── 5a1789934aeb1299b5d28cb483451c657d114e03.nq.gz
    ├── 5b8cb0e8660b1692542b345ae8eb7bf9a8c0a7ac.nq.gz
    ├── 5c601e4ef6850338e2d50b084180c5f5e1e57eb4.nq.gz
    ├── 5cc50b50b5a555d703097f1f3a39e5468c4ba735.nq.gz
    ├── 5cd07444cce0dc8134be4a1348403c87362ba9ee.nq.gz
    ├── 5ddee71697555e79224f11e53b59f415ff6640aa.nq.gz
    ├── 5e55937a4b865583dfca9c55e8c2b85c342de78f.nq.gz
    ├── 5e5bae746d6148d7d343abc7f101e8894a3e3c40.nq.gz
    ├── 5ec41082bfd241188d180a56ad888596421bc95e.nq.gz
    ├── 5f11075a217910247eda1a78390033647fc05e38.nq.gz
    ├── 6011ae513d520d0b66330f409088228d5ded244c.nq.gz
    ├── 60c0bfe7c7a5a9668f20237e864a11dea865c885.nq.gz
    ├── 611687c4ff81001d999f481daef6d9d73f2b28c0.nq.gz
    ├── 6141e3bfb1cec69c0fbbb2a0ec5ad03d6a5aa6ce.nq.gz
    ├── 61559ff30d08408ae6b22f48a546a115be051291.nq.gz
    ├── 624a75494957b98653a531052acb139ddabd6284.nq.gz
    ├── 62efbcdedca108b9c901f063414db2586956d11f.nq.gz
    ├── 63357247e5fa4d0cfd9057f23f4f6444e8aedd10.nq.gz
    ├── 636cf07ef144fa05c5de621d77a4080f75c97313.nq.gz
    ├── 637a3894e522fc1115e9553553f68c7f7918d99a.nq.gz
    ├── 6542adf53597051fbf2c978128a2482ff4627d1f.nq.gz
    ├── 661ce4e659d297f9308ee0f6e4627563eaf7e2f6.nq.gz
    ├── 66648728a4c8cd4c89bf376a311898ac7aac8b1b.nq.gz
    ├── 6a67c4a9a81d8ae5f1da34a17814271422beba07.nq.gz
    ├── 6a993bfcc318b3ebdbad11b15209506cbe3f3117.nq.gz
    ├── 6ab0e126f8ed165e7d621117bfe01f338377b4df.nq.gz
    ├── 6af504e06ef25ba8d89f668bf6ed7e4967d19085.nq.gz
    ├── 6b4e26329c0f0e553f5f8eebe756b70c7f496ff3.nq.gz
    ├── 6b944f68ecd73bbc75e232ed4dabaaf089f7846f.nq.gz
    ├── 6bae7e0183a293669a44480a4b2593ecace19fb9.nq.gz
    ├── 6c875f6500e9e1908342db3d18dbdbbeafd2465b.nq.gz
    ├── 6ced7806760114b9b1613d80f9a6257980e1babc.nq.gz
    ├── 6d755ff84cadbc2bcf6917403510ac2c910b074d.nq.gz
    ├── 6d9ad54a5b64d1d0f44ff4084471f849fc6270f8.nq.gz
    ├── 6de31575f1315fb7f8a463539b20925f240e2102.nq.gz
    ├── 6de482022f5ab2a70c4304b132a297d79d62e055.nq.gz
    ├── 6e8d593daf73916ca647f132ca8f437f84861126.nq.gz
    ├── 6f698da84ec1e278462366df8e9efff1fe1fef14.nq.gz
    ├── 6fcec717ab2c466beef5b3071fc565da4c836e05.nq.gz
    ├── 72437bb1c08d7ac100ebe5634288ff3f0e04991f.nq.gz
    ├── 728b766100d6250dcc100e2694fd0f47c2cbeffd.nq.gz
    ├── 729208291799bf437039bd223436c634e1576286.nq.gz
    ├── 738be9dbe94f8aaa212a5a33bbd5f327d2515f38.nq.gz
    └── 7428d10895e56f48d667207ea1101f8329c63798.nq.gz

7 directories, 200 files
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

[Pylons/deform](https://github.com/Pylons/deform)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
