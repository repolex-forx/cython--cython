# Repolex Knowledge Graph of cython/cython

RDF knowledge graph data for [cython/cython](https://github.com/cython/cython), parsed by [repolex](https://repolex.ai).

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
rlex download cython/cython
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2fc896931ef3f47c3b0ea733cd7e81428a96d8d1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2fc896931ef3f47c3b0ea733cd7e81428a96d8d1
│           └── chunk-001.nq.gz
└── blob
    ├── 00cfe4dd8cf6adf5c265e81bc285126448bc6327.nq.gz
    ├── 00e7a3206bacb498f94f6005f98e31f0fd266386.nq.gz
    ├── 0150bee405231aa9233824a34bf693cc126c634c.nq.gz
    ├── 01cc3bc57aeffc5b0e1c6b50afbac0143d8ad4f8.nq.gz
    ├── 01eb41e3b687c5ad56c36ad324f154b86656f456.nq.gz
    ├── 02be71f6fec9fb21210f1ebe18e69a8e5705513b.nq.gz
    ├── 02dddf49216e265eb05f1ce031e4a7ae3c367c5c.nq.gz
    ├── 0397f269a7e50078280a7fb6ca0b2e12b5730554.nq.gz
    ├── 04088a5528da04f478dc983ae481bead4ff8ff68.nq.gz
    ├── 0453e31d030b6f795234b6f0a1f8eca967100b93.nq.gz
    ├── 0524dee0cd289590be2a2466a83839bc027ddcc9.nq.gz
    ├── 0530a682a08c98456cdf076ba2f72004e497e1f9.nq.gz
    ├── 055928013f3a26c452c92660ef6f171c484930ef.nq.gz
    ├── 0559487dbb287ca6971d95f2ca09fbcd5f6a8fbe.nq.gz
    ├── 055de292701e2e7d8d58c27177af28e9195cf30e.nq.gz
    ├── 05754f59172a864f1dd71d1f2f8050329c71d2fe.nq.gz
    ├── 08cfd8651512cc417b8d501f4f4904a850b9b345.nq.gz
    ├── 09a25273ccac67eb9cc2636235c4e80561b8207a.nq.gz
    ├── 09df291f5d76b163adc28ab9c9d1e8e699ab83cc.nq.gz
    ├── 0ad1301b2697727ccc4dfb9b8e11343b5b596814.nq.gz
    ├── 0b62a168937355480d74d216935a4832a35b8b9c.nq.gz
    ├── 0db1ba52c345e050e50e475cd98cced39704b9d1.nq.gz
    ├── 0db5368b48b7e85fc1baeac01af2a530d1b6fc3c.nq.gz
    ├── 0e10907f7f1e673b3e0dd2f6d363c80206b6cde2.nq.gz
    ├── 0e20a6c331c83f5849827a255d6ad03476d6b548.nq.gz
    ├── 10ff2784603d6f438bcafe9044ddad403d44f91b.nq.gz
    ├── 12589c9f87de4d9a2f98f797638e387facd1fbeb.nq.gz
    ├── 1306c1891a0959b36722c562c5c86959f1a73f1d.nq.gz
    ├── 1356f9a2a7902c3e3c58ac8e62bb4995cb9e5f4e.nq.gz
    ├── 136fd04525b5b16b7460d4f6ed2217b3c62f043f.nq.gz
    ├── 147fe3c52abc39f2b80590771f0757b27a536aae.nq.gz
    ├── 1487ac43b33467c66c8c06a7613fa2e491e74688.nq.gz
    ├── 1496690aa9edcee33dec20dfaec9b6125d88c96e.nq.gz
    ├── 14ee440a0c4ab0622c34883fd55ded1d36baf040.nq.gz
    ├── 14f453ba6825e0eb57879fad589ecc21263388a9.nq.gz
    ├── 14f932dac8cf5da073ee647c668578d07d6c671b.nq.gz
    ├── 154dc9cf6b178ee11bad2f0cb7f8535d3561f7dc.nq.gz
    ├── 15b57fd0ede5ede046ab38c5b61e0d84f978bbf5.nq.gz
    ├── 16c7395f0f24231134c12e4f82f296aa494e4848.nq.gz
    ├── 1706b6611006c0a18f794d31450b0e6e2c7bcde5.nq.gz
    ├── 17b93b448c94b0cf061d5ead18271cbe348cbd7d.nq.gz
    ├── 181dc499395479623f4fe286599920c44e8c09c7.nq.gz
    ├── 182ac11d53fa916cc58b517bd0af164c36d41858.nq.gz
    ├── 191fe95461530f6e24bd60f290d605a3f3f8c18c.nq.gz
    ├── 19469f0672a8acc8e843aecfcc90f6bec1d24093.nq.gz
    ├── 19db1e2d2e42f7c457213c0fb210d3e1680f6032.nq.gz
    ├── 1d2fb9f66a151120f691bd77cff63d0bd607d884.nq.gz
    ├── 1de4a879b3383504313b7239a2eead21d5d00d82.nq.gz
    ├── 1de4ea165f77c5b914ac9a0e02b415a929d02601.nq.gz
    ├── 1e29b17cf0bf76880bf87598d9c6f6abc7ea85e5.nq.gz
    ├── 1eef3affd0eeb2a0f09a3cb02ce939ebe9eb2347.nq.gz
    ├── 1f6ff9c72d2e67ce78ea4c612fdc0f993ee93a56.nq.gz
    ├── 1f826690d8f3877414b458dcd8b623940424b5bb.nq.gz
    ├── 1fc40f48aa48cfb315b238820a6148b6e474537a.nq.gz
    ├── 203db0c268ea6aec1719466652cb6694232ba6fb.nq.gz
    ├── 20f0785967e4472ad4ff573cd88e3ef75209f630.nq.gz
    ├── 210c526406fb33ee9223a703078ecb644b1105ef.nq.gz
    ├── 2168b86967843ecc7c51a6ba599d3c31db5ab8c6.nq.gz
    ├── 22d0d5940f9b27f0b9a2bf6d0a7fa851464c90b1.nq.gz
    ├── 23412dceac9cca7302d2b423b6ea4d4bc2fbbbc4.nq.gz
    ├── 23ea01bc8edf2b8ce078960cafa1104c5f8c95fa.nq.gz
    ├── 23fbce0ea9840d642e71daef12421b2eb3d0805f.nq.gz
    ├── 24692624414899bec712a477cb29f024c8b2a811.nq.gz
    ├── 2495d740c272fa84eeadc607a19071465aee95b4.nq.gz
    ├── 24f7b79d3eb30976401487b407dadba247f52ea1.nq.gz
    ├── 257858d2330904aa7318035821374eb727c51647.nq.gz
    ├── 263befb69c7e94e607a8b21e640964d1dfce2fc3.nq.gz
    ├── 2648fc0087070f96cad45dfd044071e7bb4f15bd.nq.gz
    ├── 27ba40061fbfb7dc9f2721ab8ae59bdd0925f9ff.nq.gz
    ├── 28a2783fe49a829cbacd8170e4c9c5326f93c9a6.nq.gz
    ├── 29f4a1d52a0a9e364190aaa9d1d0f6e1ac2bd3fc.nq.gz
    ├── 2b001b5f2112e5b52221a72d32e930569441272f.nq.gz
    ├── 2b260281227e591ba1bd54e66d75aa061ea404ad.nq.gz
    ├── 2b3373c2e3e17ca249628016dd2e6aaf2293a79d.nq.gz
    ├── 2c28757e11c8f31b69edb709d357e3500730df2d.nq.gz
    ├── 2c71e371634cf239ffca29e986eae2f7dc239f4f.nq.gz
    ├── 2ec165421449839d301c436ddad41c23797950f4.nq.gz
    ├── 2eef6946080715796033f153c22119d510235663.nq.gz
    ├── 2f2043ac515f54911fa97c1aa2836132cc5e66f0.nq.gz
    ├── 2f6769a948263298da7b235535eb6196b6b93685.nq.gz
    ├── 2f919dbd49b4f0a453de5bbf5777cb37d8caf7ee.nq.gz
    ├── 2fcc706f8fe76a87efb927e7a2ac01be12044eaf.nq.gz
    ├── 31a8de602783882e0d86377a613a5df565fc1bb3.nq.gz
    ├── 323a89ad504c9afadfbbc10b8185a1ef126ce4c7.nq.gz
    ├── 3311429995e1a75b7c0dcfa1c5ca74ccc138eaf6.nq.gz
    ├── 340b63b8ab92cba1a4fe3f5e552fe3774100a237.nq.gz
    ├── 351fcd065b6966d8c26eebd8b7aa08da585040dd.nq.gz
    ├── 354202af2e6855abebce33a87a2f40e67a836d4e.nq.gz
    ├── 35a9d27d7d8e0c8986670f6c20e96fcec780a436.nq.gz
    ├── 373fedcc070f18ab56338bf9b85e53e298077f94.nq.gz
    ├── 37d90aea8a8fe6fc4dba9bcd3864792e1a3c25a3.nq.gz
    ├── 37efeac7d505f84187701ebaab724cb9d8503085.nq.gz
    ├── 392bef7d64baed6c9b33c8280a4b8536d1146f0e.nq.gz
    ├── 39970979a28178191834cd2be1062b4a05fd7e5d.nq.gz
    ├── 39ac928194dd702632a9f2d24571177554bf71a0.nq.gz
    ├── 3a35d1d8e62acdbff5928a1c7706603dd4b3608b.nq.gz
    ├── 3aad46d8bc3f18145464277dd4d902e8875e39e6.nq.gz
    ├── 3ae85083907738ea86a1f1282530681a712c3401.nq.gz
    ├── 3baf5813604d3e6e49e54adda0cc5b7277236d83.nq.gz
    ├── 3cd6bd7197a2dffeeab9bc35161f516fcb3f53e4.nq.gz
    ├── 3d0f37f87bd62248c13ea038df36b8c993c2cd26.nq.gz
    ├── 3da94b446044ffcda61d20433452dfaa2bd9354f.nq.gz
    ├── 3dcb37c024adaaf616fb20e3b2e064f824b4cb65.nq.gz
    ├── 3e04695fc5ecd132bffbb9c290152a41efcd84a1.nq.gz
    ├── 3e4d4e663222ad1fdf98456a05c30f2d454cea01.nq.gz
    ├── 3f13b91c7c684fc9415e20658d63dc01798eabb6.nq.gz
    ├── 3f5bc34a8ffdac5b26a3213aa727f51cf7f844fa.nq.gz
    ├── 40f2f17a3c8f5f5b8711ac9b883b156036bda3c1.nq.gz
    ├── 419f6dd50fa2419a8767f2f57a516e9168619870.nq.gz
    ├── 4207f00c9ef08f9c8ea9d8114df7755852cbbde8.nq.gz
    ├── 425b7064b09447c5d7260de0bb5a843638409a59.nq.gz
    ├── 428ed2e8e7ad580aba9f4e579618c6b8985a0637.nq.gz
    ├── 434a7cb50733f531153fc4b3bfe7da9b228a2338.nq.gz
    ├── 439d3df6ecbd3a70ae969276df1df49d105abf99.nq.gz
    ├── 43becf59dfa6ef717502baed6a1e0f80a5d9af5e.nq.gz
    ├── 441292acec2968434254355d0d26872d90eab046.nq.gz
    ├── 444b1ce9f38e259ec6847052c914f31c2e958c95.nq.gz
    ├── 445197508ce3e7f5acc0008fe20100a69d779456.nq.gz
    ├── 44d9a9b167cd92067679694d709af68b02c34412.nq.gz
    ├── 453695ebb73228b4f53046f05ec50f1d15c6e317.nq.gz
    ├── 455258c038c18151f7737393263d82bc067c7897.nq.gz
    ├── 458c6fef29a59ef3fb636ad69bc88ce3d483834d.nq.gz
    ├── 47175834ca726de6f8072cb5e41082e98563262c.nq.gz
    ├── 477a2ebb4bb3320eb88d06f36ecb536c5ef92f9d.nq.gz
    ├── 47975067c1ea9ca77baf3b3e5dccffb54685471d.nq.gz
    ├── 488dd16574361ef0fe4cf8f69a4263e7adb6abd3.nq.gz
    ├── 48ceb71e044eaa8c43d93ed36c5304a1d1ae6e4c.nq.gz
    ├── 49d660ebc5c77d082695c67c9fd605a337f3463a.nq.gz
    ├── 4a9858c2af4bb625bbd20dfb7ff415d33481c7f6.nq.gz
    ├── 4bdd9ab98bd6ac2139251238af8934dd524a3ff0.nq.gz
    ├── 4c3b5d26cb6e366447662e758b2a5bc52ce0f46b.nq.gz
    ├── 4cc40ecd9e644361792a64bbc4659136026fb07a.nq.gz
    ├── 4cf943e56530dd2a420400812a2d46dfe1e57ebf.nq.gz
    ├── 4e30cec79456dba77d2be29056255f2e12d1bf34.nq.gz
    ├── 4e41d4bbb61e593aa19187fc241f03225ec0c7dd.nq.gz
    ├── 4ea0593d9c7e2538c661a4849c5a80bd8696f626.nq.gz
    ├── 4ff232b829777eab5d2e28805db152420c270d6f.nq.gz
    ├── 5026415bac3570509e190f09088b970063978356.nq.gz
    ├── 50a453901df264415c8faa563042b1aa7c762815.nq.gz
    ├── 514946b53a4c33477fdf91b184b731cdda6ac372.nq.gz
    ├── 527f16bdf33da3a46df61158a9cddde4c8b21adf.nq.gz
    ├── 52861c209cb646e522aeb0e7ec7fa4184073644e.nq.gz
    ├── 5347ead95c061f96af25ba3a654414187e21c1f9.nq.gz
    ├── 53d39c63cdb23d5700a4c3df01111b4533276b08.nq.gz
    ├── 542ad3996534299a1160b4373a749ca6edf36717.nq.gz
    ├── 54f5ff957d765ed012fc6374d46de514a10c6f78.nq.gz
    ├── 55040aa39506bac5f1521fc13f4648625d176438.nq.gz
    ├── 56f0f685d1da6c4121660c84eec39bc8373cb116.nq.gz
    ├── 5725a8e29bc9cdf68b9460f3c6d14cd969915165.nq.gz
    ├── 57985cc43c0b24022f6bc707b7f98bf07de3e12f.nq.gz
    ├── 57b1155c2bc60d26efc57426daf844dd18edf9c6.nq.gz
    ├── 58d13a15792a73edb1261d4508c297f87c27e583.nq.gz
    ├── 592ce8db798e2c2121cfdffb055b92bb1f169c1a.nq.gz
    ├── 59765f8dd6cac8dbc5e36427b7bbcb31359ad3b2.nq.gz
    ├── 59b5dc9ff288bf7c0409c4f256d771cfa1a8030b.nq.gz
    ├── 5a2ba39932a95b72d3d967e1f51df4f4a5c96806.nq.gz
    ├── 5a62f24f78ed964356f828e493fd0a81836f8e74.nq.gz
    ├── 5a6c92b5069c37e2fb486239dae339aefa1826f9.nq.gz
    ├── 5a9f43f4cb0bd5330f9c9e25f3dfa5bf411146c9.nq.gz
    ├── 5be4876d5ce5c03d2a1cff211dddd7d36d38718d.nq.gz
    ├── 5c0bab6aded5fa18840f169e121442e5029c1b2e.nq.gz
    ├── 5c33c14b4106abb08d8cc6c70c11eac58045b1d9.nq.gz
    ├── 5c4a6d972662b488ddab62bb2593edf096ce84e2.nq.gz
    ├── 5c631532377f96286c8268c68ffb683174de5057.nq.gz
    ├── 5ca615cd45f18292717cb9e698f7d326e1b374ad.nq.gz
    ├── 5cc498c8f01b9b6fa1e7f73ffafeb27d884aa032.nq.gz
    ├── 5cda5246daafc71b66b03d87b8ce519954430b13.nq.gz
    ├── 5d34090cae3e5095f5c06cd3f16f550b73232448.nq.gz
    ├── 5d92947260c3c35e17bdbd24458501c988b0cd56.nq.gz
    ├── 5da5475fd2b778e30c9ebf095720c3cb13573e8d.nq.gz
    ├── 5e0ae35211a38672fb4fa1da83a949160da6f78f.nq.gz
    ├── 5e41285d1ca832d9298b0951cf7b66f9d7ae53ca.nq.gz
    ├── 5e461119abcf0b105b03c0ff94d217234129933f.nq.gz
    ├── 5e972717be8dae2b2be90b57ba230e3fa1c85764.nq.gz
    ├── 5f3a80e723a5e514f654b263dfe9c85650ddd4af.nq.gz
    ├── 5fb4fdb9834d294e61bfe310f7bb0facc690a005.nq.gz
    ├── 600cf3d85dcafb6aab917548aa54928e93046e79.nq.gz
    ├── 604edb2135090f809236522726debd464a0a3b5d.nq.gz
    ├── 6063503c41bc430a5976fdb83e95672990676b46.nq.gz
    ├── 60c96aec0547128bf217608422606893b54b17d3.nq.gz
    ├── 611dd167a839c6253b3fd85201115cb62b5909af.nq.gz
    ├── 6127fa9f1ffa0b67086535f946a602dc86c43d0a.nq.gz
    ├── 623b6311ade2bab2af412d4c8f6bd7fa965f608e.nq.gz
    ├── 625ac2a9d85ecfbf43e9920732f239a633779b46.nq.gz
    ├── 62fa43745d15c7522b9d0f29b36ed4a61839edca.nq.gz
    ├── 638366dd2549770611e4fc2d77b9917cceacd975.nq.gz
    ├── 63f159f1d25b7e06d471a89e4d6dbccb0f16fa4f.nq.gz
    ├── 64239d93687cdc5eac9abb388586a341f0c0f511.nq.gz
    ├── 642bf54aff088159bcd77a9b5a876a209e67df37.nq.gz
    ├── 645919fb9e0602677c595a9392eb661f915d24ff.nq.gz
    ├── 665f09371718314f0105dd3a656d217ef33159dc.nq.gz
    ├── 66631647ac3f2a17d2681c037b403d67034c8d6b.nq.gz
    ├── 66b6158c508bf86ba50c477aa4121e72c58da045.nq.gz
    ├── 670f340a48651a734549f797be7852db9478aece.nq.gz
    ├── 67994e0f976b0ab95f8c9a1e812093fdf807a036.nq.gz
    ├── 67d740672ae3801e1fa4ff52cfd637f293e4a2a6.nq.gz
    ├── 67f6cb2f6926f676f230fcd88e911be52da43e14.nq.gz
    └── 68853f4931293e52599fa1b7a01b5645d68273a0.nq.gz

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

[cython/cython](https://github.com/cython/cython)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
