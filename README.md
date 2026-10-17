# Repolex Knowledge Graph of ClickHouse/clickhouse-connect

RDF knowledge graph data for [ClickHouse/clickhouse-connect](https://github.com/ClickHouse/clickhouse-connect), parsed by [repolex](https://repolex.ai).

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
rlex download ClickHouse/clickhouse-connect
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d5a1d85c8c4ae119d6a65af219533e4cea059af3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d5a1d85c8c4ae119d6a65af219533e4cea059af3
│           └── chunk-001.nq.gz
└── blob
    ├── 00169dbf63c292d69dfd753ed0f0742e515e190e.nq.gz
    ├── 00527c025845fe165f87e5f6a0cba7fb4c66eab7.nq.gz
    ├── 00ddcf6cd53a7567fc6a8ecf642c4a85c55709c7.nq.gz
    ├── 020027ae5e735211527c51e002f24d7c5a87a6ea.nq.gz
    ├── 02567ed3d5dfb1e476471647e9bef639bbeed622.nq.gz
    ├── 02b9a4b96c452fdc02b93d60f57617c371b7e52c.nq.gz
    ├── 02f8949207a6318959d5e30ddb47de814dbb02db.nq.gz
    ├── 032cb231afe1efbbf00baf90583937a781984051.nq.gz
    ├── 057706a2a04d644acc0a12fddae6b1e1fb89bf69.nq.gz
    ├── 05866c6722d54674c2424df04e07e3eed051b342.nq.gz
    ├── 05bfb74f51337457b395c9f0ca5a72e6aa0078de.nq.gz
    ├── 065315226134afb5357807cb832011acdfa53ca6.nq.gz
    ├── 07507edd75259501791ce2e9e9d39924c55e7da1.nq.gz
    ├── 07d58e32b097f1218b7cf616350214ad51b261ee.nq.gz
    ├── 09ff8c2f9214b1a97c5d8d8fa6bb3323993e0dda.nq.gz
    ├── 0a1895d4cb1c3c2ee97cad6d7962db3f7166f7cd.nq.gz
    ├── 0ab3728dfe9426384a923634657a3f3f4baa6b9f.nq.gz
    ├── 0ab46a840c781acb4fa3c7fe3d095f1614ecf29a.nq.gz
    ├── 0b748a93a257aa677dbdd3b1c329a469cb650469.nq.gz
    ├── 0b9a1a9367150d44e0609436bd05a6d874abe5ae.nq.gz
    ├── 0c60ec5f4490f7ddc9859cd4ee9fc5047c5cb9b7.nq.gz
    ├── 0c8b28fefb0bb01ab3fc59006d4d85742d7b0ad2.nq.gz
    ├── 0d42a457f03f06c805691f79c0756540504eafaa.nq.gz
    ├── 0e66571b4bd27c49722644aafde4f3f72be43d68.nq.gz
    ├── 0eaf39906a03db74c7a09a7c4f81dac89fa69e10.nq.gz
    ├── 104f8c0b2afe782ebd59b8d0383aa6cbf95cf285.nq.gz
    ├── 11986a4b68d885704a8b61ab5d37bdfd22e7ba5c.nq.gz
    ├── 11e9cb5b2ce7f187b7c52321807176626537577c.nq.gz
    ├── 120db6638f55cdc066db165b23293c84e18300c2.nq.gz
    ├── 1392989e93414619d8278ff7c8563e1cda4cb54a.nq.gz
    ├── 14778e9331a57a6683ef64c0514c5535aa6056d5.nq.gz
    ├── 14990bf4e609724038ddfadb002a0b39560a852d.nq.gz
    ├── 1550342f398a78b57b70499bdc8bc0a66a2553a9.nq.gz
    ├── 15560829551489514ecaa444316b794351d97fce.nq.gz
    ├── 155e9e846664dc0d2cf1a6ffcad6433bc2b9daf4.nq.gz
    ├── 15d98b72b7a504e447ff4a798546084030c3142a.nq.gz
    ├── 17e5a8880e04b5e5f372a07d4bf8dfacf87583e1.nq.gz
    ├── 18ada1ccbb6f755402a480a310e0f757a442209c.nq.gz
    ├── 19acdfc91d842d6dd34043d18a4fd1922cd92d6c.nq.gz
    ├── 1a413c6f20facdd1c742ddd05f08005200671344.nq.gz
    ├── 1aa19d98b27fe39f0cfd1e9c997be758b97cc06c.nq.gz
    ├── 1ac8466cc9e898e65473c5cb43f6391373453ff6.nq.gz
    ├── 1aea4182ae41ff1893fe7fded75ac1ec0f253fda.nq.gz
    ├── 1d354dc55d359f7cdb0a7a16e5022475bec58d63.nq.gz
    ├── 1da6c8eb0788613f13f341762758477cfaf1b2b9.nq.gz
    ├── 1ecba9385dec998de2597c46d6b311ab21fb9d7d.nq.gz
    ├── 1f31f614bb5cab53e8ef794d73e923138b6a3978.nq.gz
    ├── 202b4291565bed1d7d81c13ef63ee704f6d050e4.nq.gz
    ├── 20c78867f7cef3f14877b89ef99a93047d119994.nq.gz
    ├── 217bfd8ec566c04e11eb3aaf58074b7bfc38caa6.nq.gz
    ├── 2197a69ce99c63e50647b20ddf5649044c7dd7a5.nq.gz
    ├── 21a43b8694ae6d74444fd66d08c2b5a55e10833b.nq.gz
    ├── 226c54fe7a107cbf75811c35c81942d0fb84542f.nq.gz
    ├── 23494405a80da2f08adf8a8ce360b7859a5253de.nq.gz
    ├── 2423369434051e80deefc53504720d248749b3e7.nq.gz
    ├── 24a4bbeb206c431a8858388d02e8496ce94ca804.nq.gz
    ├── 24b23f3fe6dc969e34e612395389736cd9d0b138.nq.gz
    ├── 2595fa084ea059db741d9d0061172a4a1f5043e0.nq.gz
    ├── 25ef68900cf79a32a3eabb91a30b983e40a7a688.nq.gz
    ├── 26202227a704f0b0456b56adbe12bbb22efa5fc0.nq.gz
    ├── 26ef7d2a87ba30fdb2b92f7bec33b22b441b256a.nq.gz
    ├── 275c9b00e8a48ac2437f5212f0e93ef853f076ae.nq.gz
    ├── 286bf6b4547f7889b66b8bd5dcb3378b1d15d21d.nq.gz
    ├── 2aeccfedc9181188457e366859be579f63dcbaca.nq.gz
    ├── 2b1fd04bb851a3edce54d1d8f1677a3954b0da75.nq.gz
    ├── 2b42ba108f2ae861199a7626654cdeb3c488d721.nq.gz
    ├── 2bb7905b9705e4f96a7cfe1694b6b09df1f4d9a3.nq.gz
    ├── 2bc216ce27314dff7961609cb41176502f3af53e.nq.gz
    ├── 2c5df37dd132ec0160e541e334f9d06d7de147ee.nq.gz
    ├── 2cef059a070d3b2bd05fbd2c8e888a4a7b2148af.nq.gz
    ├── 2d908cf5b2d807643b098f3a094509b834aadf75.nq.gz
    ├── 2e7187ed6d60dd168a4571ddde573006a1372baa.nq.gz
    ├── 2f42173efd59722be7a929fe5a1c3a6615ba25ce.nq.gz
    ├── 2f53752676d657397e68b675f105fd0a27d28f8a.nq.gz
    ├── 31ff6a6efaa51fc2d6f0283a4a8c976ff0588b4b.nq.gz
    ├── 32c30ea58615fdf45eff385ec93aa3a508056060.nq.gz
    ├── 33630d6d343d47a8b80f2ddaa89d89248968ab37.nq.gz
    ├── 364da7b8cf2fb6708f0b11ef9a3d60858865a102.nq.gz
    ├── 3698f97079fc433e344a6248931275f8889dc5c7.nq.gz
    ├── 36a53165bfad033fede461f500f52826630ce526.nq.gz
    ├── 37a50307c8cb15c490d27168c756f0b5222c5e95.nq.gz
    ├── 385af02a6974154af3d2ff37d99bccd34e22a1e7.nq.gz
    ├── 3862950adf48159ce6d8346a2dab3a912f65e30f.nq.gz
    ├── 38ef2ec711df34efd5f8a1af63befd6bb2c6efe5.nq.gz
    ├── 3a3d32637a61dcb3776da78506b4f40a32f33f3f.nq.gz
    ├── 3a7d9511f247e8dfcf4c7f792ea0ae782db03cf1.nq.gz
    ├── 3a9b2dd4c3d3bce3ac2b158b561b76ebbdc1ed73.nq.gz
    ├── 3ce68be7f8707f3d51e111b804f1ee83f7f54b1a.nq.gz
    ├── 3d1c277ebd6ca5112d2c137f84dc58d20f08b4b5.nq.gz
    ├── 3d412ea0d1146c47db19e08288622355326358f9.nq.gz
    ├── 3d98b6dd394bb3e8d80de80d3c0efd09fecadf03.nq.gz
    ├── 3d9e2cdfb331e571cde0a163fdd9310680781812.nq.gz
    ├── 3e4e4157f363cc0ea5503b68ed3a45e2786aa7e5.nq.gz
    ├── 3f737df217f27cfa21e0f3301c1e94821f2ffc55.nq.gz
    ├── 40f8e6831f7f378ef12618267f038bfc6cbef860.nq.gz
    ├── 421d29272369c997b22ff9ecf435e4621b784f68.nq.gz
    ├── 426faa0689c4b114c3a15fa711670d5c35310311.nq.gz
    ├── 4271b278643b64fbe28b52dfe5998d75689ba1fe.nq.gz
    ├── 42f5c3fa96dbf390d79d8750329ed252da1f9839.nq.gz
    ├── 438f251ff725984c532eb35522add9874438c5bf.nq.gz
    ├── 45078497ef4cf75bdef26ee49e50e5bb2163e086.nq.gz
    ├── 4679424d2531f6176ff74ea90e45872e82c1ca07.nq.gz
    ├── 46f4fe6bd59cc3e593ab6e2902791bac9bf0dfe1.nq.gz
    ├── 47ad4fe66d663cecb2382b1eda8392da249e828e.nq.gz
    ├── 4808547ce31eb6297c6fcb22e70ff11ca6b39af0.nq.gz
    ├── 481bdc3f7c6dd978f6f95759db6a54cfb299fe35.nq.gz
    ├── 484888747eb4920ff7581fc0f2df20320b01ff61.nq.gz
    ├── 49dab45d62409517f75d148a3a2fe8964d0a13ef.nq.gz
    ├── 4a2cb880d4fa965f7941fda6ddf436d343adc65e.nq.gz
    ├── 4a695132e39418b1950ffd2e4fa77fc8156226d4.nq.gz
    ├── 4b5bdc4c3ef6d96a732f4de9ad8d14aad34041d0.nq.gz
    ├── 4b69f4232d04b2e774a14baced9cd4707e682cf0.nq.gz
    ├── 4be8c52cbc356f3eb035f8e9d4657753065e29de.nq.gz
    ├── 4c37223f8089f3e03a3f68e75df4f639995606eb.nq.gz
    ├── 4c60d0933ff35a607b3c30f7965673945a32f768.nq.gz
    ├── 4d104401052867c2a403af23c1e519087362de3e.nq.gz
    ├── 4e2c1109acb281578934bad943f7d86b5120ca07.nq.gz
    ├── 4e627acb89d2e7d88639d13c187f76540d39c838.nq.gz
    ├── 4f0feb37ece58052e166ba45e8c67d88b4cbbc39.nq.gz
    ├── 4f5635adbc6c90ef0b7171abd07b2d26ece2c2e5.nq.gz
    ├── 4f6cfe20e0314f6c924c04f87519c16da92e4f42.nq.gz
    ├── 504b027a53072272cee71c0f85a4c687fe365a80.nq.gz
    ├── 519c3ea77239146bc64eb6a05f5df0d6cb3b84ce.nq.gz
    ├── 51f11c54c0153d3a9295e27089adc2bfda28cad6.nq.gz
    ├── 526e662a71533fea1926ce6230c7c8f6e2e9f2b7.nq.gz
    ├── 528bff451beb2a55d2a46454530359ecc07b77bb.nq.gz
    ├── 53fe929a943485c1b09a40c2817e377e60bcf13e.nq.gz
    ├── 5406520f99ac7f89fffbfb9952953dc3715513bb.nq.gz
    ├── 54f4441179cc623ee4cae4d897e55a7da2d4945d.nq.gz
    ├── 55d0ef07c22031f62ecea6a9935891da542ea1ee.nq.gz
    ├── 55d823c96ac0f192b54dc3c4266d1a94e355829e.nq.gz
    ├── 55f57990f0c2c1be60e505b53d4487c9116579e6.nq.gz
    ├── 5603f77f714342e9d9e9f2abf3039de02008b5df.nq.gz
    ├── 56aa05304749f191ddbad2c031d6bb138ee78862.nq.gz
    ├── 59064102a7ee0e734fdff5cdda0c08d2535fa11e.nq.gz
    ├── 59214b911b78a4e2f6939f2cc5468a91fc392eca.nq.gz
    ├── 59313f4cdfc70e5f96e6d2626e314936e281a3f6.nq.gz
    ├── 59a29c095a1b1f35148c21755bcdc1b16ab6f83c.nq.gz
    ├── 5ac07d61c9843290bcabf4a3734a42ecb6e4437b.nq.gz
    ├── 5bd35df14deb81e42f960b47fc39473c6cac98c4.nq.gz
    ├── 5ca29afb56ed10ae5aae0f5c8139c9b57c5f0c32.nq.gz
    ├── 5ce6ec6e92a8f055bab1738a2d8232d3d72ce4d9.nq.gz
    ├── 5d0521cf50a9b2f13bb9990fca5036f593cd4a9b.nq.gz
    ├── 5d1c585f94ea5c00d290175c8dc003a2e1ce85c1.nq.gz
    ├── 5d8f4fd754217d23325d2512a5db7e4f3e3fd6ce.nq.gz
    ├── 5de83f4c09a3e4a369d1a6735607220ad35ca7b4.nq.gz
    ├── 5e100e74f1024e31408a34732b63f42fce2e960e.nq.gz
    ├── 5fa5925acc747452062bbbb9edf1d0df6bc8f555.nq.gz
    ├── 602aae371050b46df7e85dd4fb274bec429fd1b4.nq.gz
    ├── 62992a2b0ea90861a23624a6fab20be2b660d907.nq.gz
    ├── 63040b7ebb2508a1dc727acc90b0e94d212fa7b9.nq.gz
    ├── 639becb96d4039ae4242d6e6f9f866aa5a7ad182.nq.gz
    ├── 641fbc39de09e0a41ac08f7d549396f70e0c65ba.nq.gz
    ├── 64a7e3ac908a3d19aabbfb63c8f76afcb47874f5.nq.gz
    ├── 659adfbb79301b43bfa715419e7094cb5e3b9174.nq.gz
    ├── 66164036d88f65bc50b868a369a263fb655edefb.nq.gz
    ├── 6627bc65ad03a5f20288e1b37674b4edc007e592.nq.gz
    ├── 682a94a1499f60aba82707d75f3b13da209afd5b.nq.gz
    ├── 68376ccc652ff1febf067d02c4d0eb25baaba1d2.nq.gz
    ├── 69f200dd7b9201dea104e99a1b362e280e77dd5e.nq.gz
    ├── 6a17837b0b7a0f3d4134d487785c9015586d8faf.nq.gz
    ├── 6a231ee58ead430266397469dd9d334c6c23652e.nq.gz
    ├── 6a83210ee15d67bf0ee26d3a84d3314fd32a650c.nq.gz
    ├── 6aba7d87b95324bddd4af8985634caa4d1a4cda5.nq.gz
    ├── 6acb134f929d392a4f1e80d1d4bd5d516bf10c6e.nq.gz
    ├── 6afdfe0e65409a72668abfc52e311f0e9f4ea09b.nq.gz
    ├── 6b86f0ac7b3bddaeef43ef0aad0043f5ae7af914.nq.gz
    ├── 6d29d516a2833f434da925bee559704a2b7baaaa.nq.gz
    ├── 6d5f508fde1beef05ec2083078c66c0dd9086517.nq.gz
    ├── 6e3640bdfdc7c8bd1d3b2d154e0f7c451bb4dfeb.nq.gz
    ├── 6e36b3159c7a5e611394219685580efb0e6e33b5.nq.gz
    ├── 6e5f26d580b4f7a49aa8b2bd3a34c7ea00983599.nq.gz
    ├── 70298077a4548962d023071b3659907e7861f4c5.nq.gz
    ├── 703ef779aa0ab57154d226db4abd2644c898fa25.nq.gz
    ├── 7148fecef4916b07122f5113757052e9c8528b67.nq.gz
    ├── 71541a03734ae8346c7429e6cedd50da39878566.nq.gz
    ├── 72c6dfa1b13d200f45b4cf3e5fcd2a8dd77812d2.nq.gz
    ├── 7396a9dcf85c73a4e1afdc7c6fd3926c279227ba.nq.gz
    ├── 73ab1b2648e35a79b3a1e97080c316b3c2118817.nq.gz
    ├── 73da3ca703bc04126901bbc18498404881615fe6.nq.gz
    ├── 74764b5dcc79a15e829f0a5cfea20fd335e928ee.nq.gz
    ├── 7496f877438f2e98adcd2d541665baa15a1dc1cd.nq.gz
    ├── 74af910e9a3647f0e776d6e7c601b39fbff83e58.nq.gz
    ├── 74dab61464995cb3c8ac9b53bd3c6fde7f339c7f.nq.gz
    ├── 750c2bca4a6672079c24a6b6fdc4a66ab8c4e4f7.nq.gz
    ├── 75b6856e32b776ac0c4828d858f8366548d0eefd.nq.gz
    ├── 763137b77f77178fb479b225b96b780e1bdd8c58.nq.gz
    ├── 763cbeb9f0e04b3eaeedf66f6527369c5cf5d122.nq.gz
    ├── 76b99944e24223b55e5ab31621b2983e8434961c.nq.gz
    ├── 7728bce89309ddd7b73d74f7be64ee84f0d7162f.nq.gz
    ├── 7a15f3a4a4dbba3c4ef618ce7fa3d9c7471628ae.nq.gz
    ├── 7a5c905bc0a1a6aad418e521181813337744732a.nq.gz
    ├── 7a69bb59ad50bc2442d1aeda25f1557066097b9a.nq.gz
    ├── 7a9656dedf31ae2ddd5b7563299e8e1e91a86573.nq.gz
    ├── 7bcf0bc3f80cd961f655269639cc65b243af7284.nq.gz
    ├── 7dabb8c190fd5007d95cc307307f62639c160a78.nq.gz
    ├── 7e69503c70d60075b60b0040ea7cf2c6e68ae358.nq.gz
    └── 7e8aed735650da21a26f0d6334f391fe986926ee.nq.gz

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

[ClickHouse/clickhouse-connect](https://github.com/ClickHouse/clickhouse-connect)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
