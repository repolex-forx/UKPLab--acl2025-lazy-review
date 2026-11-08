# Repolex Knowledge Graph of UKPLab/acl2025-lazy-review

RDF knowledge graph data for [UKPLab/acl2025-lazy-review](https://github.com/UKPLab/acl2025-lazy-review), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/acl2025-lazy-review
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 08b01465c8dde1e9768f6bcc003cd42a6cb4e8ef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 08b01465c8dde1e9768f6bcc003cd42a6cb4e8ef
│           └── chunk-001.nq.gz
├── blob
│   ├── 0026ed3aa0ad509e75d78dbd8c1b5b3012a49dff.nq.gz
│   ├── 00641c3a79ae55ccc365bb0ab205fddb5f617ed3.nq.gz
│   ├── 01b57da23429c5786f66630f0eaa80da15618cd9.nq.gz
│   ├── 04bd358fb627750ffef062bd2d90a56d5d1400da.nq.gz
│   ├── 08c5aac6a5c7fad3e263886b4885597bf7ba0cdc.nq.gz
│   ├── 0b57956c4bf87a47e2221e403ae3825318b5351c.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0e72c87000439ab26bd810c702be8c1f004c9406.nq.gz
│   ├── 0ef9b2195f759e30ac7b9d3a521d86e123db3bdc.nq.gz
│   ├── 104a4d5709e79587dd4764a0f2edc79b9c56ed26.nq.gz
│   ├── 106588b2496abdb7ac1896861285161178a9c9f3.nq.gz
│   ├── 10922aa5f7711a60e61ffd77c5f083732da99dfa.nq.gz
│   ├── 16c1a3e54ec6f95ec124c5c914eec47b9f068c6b.nq.gz
│   ├── 1810122a22400cd748e6cc0f9cb855a7922653c6.nq.gz
│   ├── 1858c795f0776f2f7a90d80c9afb76947ff8730c.nq.gz
│   ├── 1acedbaf89b062246fac4f46cc3f69a44babba0d.nq.gz
│   ├── 1ba67382c354dc20dc0f9a962cb802cb584d3f09.nq.gz
│   ├── 1c4db2ddb2452a602557f68fe6c5517547ba0343.nq.gz
│   ├── 1d43bdaa56c1b3de29f2ab3562532352349c45a6.nq.gz
│   ├── 1fc8490d68ed74302bdb6c9e7fe667fcb6e2969c.nq.gz
│   ├── 208f229aff103160d3bc421ed9def6a2481b6a1b.nq.gz
│   ├── 214880d8ffc80e23ee42ce9f51b65cb5e58eb03c.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 27d250e53f2ebcbe4e0eb77f4daa5da39df71bdd.nq.gz
│   ├── 2c42fb4abe39fed6d4b32fdd954995a1da03b6c4.nq.gz
│   ├── 30c855ddc3bef5efb7d155201e15cfdfd24794de.nq.gz
│   ├── 34f742f5e1d93e97763a7dff78526ed6b7c6482d.nq.gz
│   ├── 3837f2f76af9bfbd963fad0b5da3d6fb5e7b60f9.nq.gz
│   ├── 3aa8b84b9d2e5d2fca6367aca87403da10dbaf44.nq.gz
│   ├── 3aafefcc2c8e1be75ff954b3b066c5589ec2a5e5.nq.gz
│   ├── 3b7312fc8005bc9748bbc7b35a04a9f62eaae348.nq.gz
│   ├── 3b88d6e3ec6cf0d945c2d5a90e3862dad99bdaa6.nq.gz
│   ├── 3ce1852b8d1cc6355ba7cef7d829b85df81557a8.nq.gz
│   ├── 3dac90c5790f390efbb2ebfcddba90cacedda2e1.nq.gz
│   ├── 3db5e4237dac6c422c9a46a072a3c3efefa63c86.nq.gz
│   ├── 3e4034e41ee913cb2bd84715e00a88deff1f8a5b.nq.gz
│   ├── 40e2de301e2bbd84c6c9ad2ae7ea8db429d3c44e.nq.gz
│   ├── 41e51739778be20ba2b9f341cfd9b8502be9befa.nq.gz
│   ├── 4494992e95a890d760734ccf84e8f96ba53b132e.nq.gz
│   ├── 4724ab845490f7f1a5d565eb0b78f03e129b0494.nq.gz
│   ├── 47e662e9a2685a8f0d90adb82abe6cb28e6fe0f2.nq.gz
│   ├── 483a74745de45a61202195b1d5cc64ef53629a4b.nq.gz
│   ├── 4847b3f5fa017a715ae0a33076cd683ab68d3b93.nq.gz
│   ├── 4ba7133264b2ddc1dd2fad4e514a127315dfc82e.nq.gz
│   ├── 4bd034835e66256b3185790ae32192c5ecc36f20.nq.gz
│   ├── 4cfcfb01bc8fa5e68bc9a2e19adc0f832710f568.nq.gz
│   ├── 50708aed43637d5f32728c286beab4b251523bb4.nq.gz
│   ├── 51b6beb87ef6e0742bed8fde245c2a9446cd8630.nq.gz
│   ├── 524906a623a57b308f98359c7c08218afb6e0106.nq.gz
│   ├── 532669bf50e8ff3b306b8d1338ec2e7051f40a2a.nq.gz
│   ├── 5354107d38e596317fd89e9e3f7da1ed62cb939b.nq.gz
│   ├── 53cdacb0b864d78f23371f2c522ea50bd65a2962.nq.gz
│   ├── 547f9373de32542b25b704cf89ce269fef96e242.nq.gz
│   ├── 548cc48215a7b114c73e350693ad2c510cb0f024.nq.gz
│   ├── 5681e0be5680a2b348f94f37ac47cb92c9e64a48.nq.gz
│   ├── 57270df625c755737b463b4d1d400535543fbd14.nq.gz
│   ├── 5767fb0174b0bbe80f04d392c039e7692d6608d9.nq.gz
│   ├── 5790a29a86028489a88257d3bddbd8aa51a7d453.nq.gz
│   ├── 5946048aefe53e1a76a1ae18405baa313c7ae5fb.nq.gz
│   ├── 59776b06733ed1cf31e5cc2df0051057eeaa8e08.nq.gz
│   ├── 59edc8d80544aa2843452cf77afef909e187a990.nq.gz
│   ├── 5b8d108d22fe698c7de1a0767bec3902591a57ea.nq.gz
│   ├── 5cdd06fa6c9f890105f4f97bb20526faa9fde7d0.nq.gz
│   ├── 5e45e8723ff4275fd2913f85845f486fe4ded1fd.nq.gz
│   ├── 5ed960c665b6482ef31672bb0dbbd0415a630c45.nq.gz
│   ├── 603e5039c2354b081a1b93a9a22c9d72b4c9490b.nq.gz
│   ├── 63adbdcb3a9c70d19ad882d352c4c32d829b1259.nq.gz
│   ├── 6a8b4db475fcd14e83f415340c89499931f54160.nq.gz
│   ├── 6b835d9e15b6f99d4c1c0d960c420657f29d23bb.nq.gz
│   ├── 6cf51983a819fca80603aa7cafc95a3544f79eef.nq.gz
│   ├── 6f0d38e488f9c5017cd1b546c8e5a9188133b327.nq.gz
│   ├── 6fe1dfa57c2d6510473f3de80b042727ebdc7567.nq.gz
│   ├── 71c7145424a819cf9ac9ca14b032102082a1882c.nq.gz
│   ├── 794dd21140a99f2a6bb2fea727c0e862df1c8864.nq.gz
│   ├── 799217545a5153bd77295edaf90cad379202cb8d.nq.gz
│   ├── 7d2874406227078c40ff3cf6b05ec799249517fd.nq.gz
│   ├── 81bc541c3664f0a08920d469742e07b09ad86c5a.nq.gz
│   ├── 84d63bb14f58a0439a6b8a8859a40b95e47228d9.nq.gz
│   ├── 87e16753f5f7421341ae1bb37870222a8fd1ad3f.nq.gz
│   ├── 8a3f93b93d3c888fcfe8363edf96786f88c958e9.nq.gz
│   ├── 8b4d7cfccb6bed08d4d82abc6e5c0722efd8b9e9.nq.gz
│   ├── 8ba2c4f5d26cdbcf4560f364131ac04d193a027e.nq.gz
│   ├── 9477909866b59be3688ecaa365cbf1886bcc8997.nq.gz
│   ├── 95d6043e948f26b6e2f18c2a6871d3a968810645.nq.gz
│   ├── 98359b95ca4eabcbebdea65148b9c780a7c7e805.nq.gz
│   ├── 98fa1dd60692235d99008edcd3be85e72b445208.nq.gz
│   ├── 9b4fc3f8aa4f8b016503aae4157b76eb81ec99db.nq.gz
│   ├── 9c44d6d537652077e711b5d74c9cc6e07460f366.nq.gz
│   ├── 9d10c276b5e03b2e12daeba2de216400b2ed54b5.nq.gz
│   ├── 9e903ccde47c86a8c21a42e16d0f953da143c954.nq.gz
│   ├── a03ee83da25305949567914b11095793d643456b.nq.gz
│   ├── a1c942a35c6c85d8cdfdeb7037761048361721d5.nq.gz
│   ├── a3c3cb418b43285f5f9e0fb7b847264bb21668c4.nq.gz
│   ├── a880de7723e7b98a7214ec0c9900b0c4580d2315.nq.gz
│   ├── aba84321a716f61844d5dd8c7d395519eaf70294.nq.gz
│   ├── ad88a3994881afe626bcaac152a142e5c87f1aea.nq.gz
│   ├── add20195362814df3991fe8a4f2c9da45d811b45.nq.gz
│   ├── aecc3b738218e0250cd71300294b9a14ad77cd55.nq.gz
│   ├── b08d2166f156667e772f915d1925366d196c3ab4.nq.gz
│   ├── b34128e6a889fc4c333dc8d06641c98dacef6ae3.nq.gz
│   ├── b7641ef24037183f60f6343d1d447cc6e2f8fa36.nq.gz
│   ├── b854bfc1ea1f31a7afd8a20f2a093dd75072e9d6.nq.gz
│   ├── bbd36055f06097ee3fecd4774827424dba28cb60.nq.gz
│   ├── bde04795fc65ed9754563e510de02c330d6a6546.nq.gz
│   ├── becb0f6c021149bafd6b883d921aacad6922a3b1.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c3af969410c97c5a2aa8219189e68dd4f6c31206.nq.gz
│   ├── c5988802c4490124af2702ae9988fb9379ebb7e9.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── cb105aa03fffb0983a004233ab01ccde0de7b3e8.nq.gz
│   ├── cd223b6d78895dd117088188ffd6b26fa404c56e.nq.gz
│   ├── d0286fef8bd401f1a147ecae7cdde9f6b4598941.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── d6c914f53c567df16192bb54ff7e0e443c61e209.nq.gz
│   ├── d8cc094a4b4ca36660ec833f0dc4d00745148b79.nq.gz
│   ├── d959ab580a445318533280eed8026a7123fe5273.nq.gz
│   ├── daa48665fb34587e709e98ebd26392d54c64cd17.nq.gz
│   ├── dc528a277bfcb9f4f7a47fc407db7647f6c0634f.nq.gz
│   ├── e050126dd1d592fb0097e3309d7a3be9f3ff16a9.nq.gz
│   ├── e161134ae1aeee75769246990ac4038362c66067.nq.gz
│   ├── e17a7a5e6cd04b04e4850b58183ff46976fed4d1.nq.gz
│   ├── e1ca8dad52266fb4c8fd1db03a83b1c19fb5f0a2.nq.gz
│   ├── e7858401db9a8865e7248687358c51cfeb95b491.nq.gz
│   ├── e839a7707cf7da6a6ddc51835f2cac1cf4601997.nq.gz
│   ├── e86daed7b1797b01d3d6e7f0609728043e0b5c5b.nq.gz
│   ├── eaf9eb38bd229973ce5b19726938fd1a8d3046fb.nq.gz
│   ├── f08a660557b74d78b0e11c819badd05818340d74.nq.gz
│   ├── f1b53f3b8d87ad2d89c8d94c856a9addd1966919.nq.gz
│   ├── f38c31faed718d9ec23d52d48efa23affb799645.nq.gz
│   ├── f49a4e16e68b128803cc2dcea614603632b04eac.nq.gz
│   ├── f6059c794f2078de36115dc7d94aa14ba0064954.nq.gz
│   ├── f776bec0d1ef0ccb3303bd6538513232dca99bc8.nq.gz
│   ├── f77808d063ef13016641a5b6d502bb07a1e64b64.nq.gz
│   ├── fa4ddc7c793ec902e760b26f22c0ddb1b49db7b3.nq.gz
│   └── fb3c3a9e376504c94d9c5e7e6f3b6fbd3c47986f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 08b01465c8dde1e9768f6bcc003cd42a6cb4e8ef.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 143 files
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

[UKPLab/acl2025-lazy-review](https://github.com/UKPLab/acl2025-lazy-review)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
