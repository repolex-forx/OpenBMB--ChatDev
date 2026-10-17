# Repolex Knowledge Graph of OpenBMB/ChatDev

RDF knowledge graph data for [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev), parsed by [repolex](https://repolex.ai).

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
rlex download OpenBMB/ChatDev
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a2ea4a263cebe9a7abd01ee3b5b0bf95698ed328
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a2ea4a263cebe9a7abd01ee3b5b0bf95698ed328
│           └── chunk-001.nq.gz
└── blob
    ├── 00120fe72868f2245fe6a483796d64ed24a64208.nq.gz
    ├── 0172e2df3c1016699fb8a999074a56f3546f8c2c.nq.gz
    ├── 017b2e3abcbbe67effadefdf17f30effcda5b21c.nq.gz
    ├── 01fc2484808ddec5206c9751f12fc3180e878619.nq.gz
    ├── 0215d2966d8b2ccc09dd8d3b4ccc6f565ed16ca5.nq.gz
    ├── 029fa1994679ea8053442abde9685e2e89112acb.nq.gz
    ├── 02c091b41d728c3c62e32fb94ec1f6fafa42114e.nq.gz
    ├── 03a0ecfa6a2bdfef3c27c9430faae59f87e6cb40.nq.gz
    ├── 04beef5be92b783a39fa6853be71e947c8806814.nq.gz
    ├── 053185e5d299739eee7218f2e93876f0c3a5463a.nq.gz
    ├── 056de20be37e840852a6a8ed86327467e2a29be3.nq.gz
    ├── 05ea8ade057b1a1144bc1ac2dbb6f877f667ea25.nq.gz
    ├── 06b2622c0e2df04d0c538ebd631e4572f5e06785.nq.gz
    ├── 0724a8bdfa609feeabe1d7e75e1585743b141de7.nq.gz
    ├── 074a1747723f5ae5b2b3b03950ac388eb048f989.nq.gz
    ├── 0770560e551e0052342b6b0dca7433f003cf613c.nq.gz
    ├── 07c049b780c1022a812d98b376605b8447decc1a.nq.gz
    ├── 0903d4dab7a260562dcf88e50dbdd0f29a105282.nq.gz
    ├── 0a945dbeafa7f25922c04ab73851029c10fceeb7.nq.gz
    ├── 0cf6aa54d3c7736bfb2cc0ff202e27d614f49b95.nq.gz
    ├── 0d0c3a6a1edcbc9108ed8ec9226b0bd211712f72.nq.gz
    ├── 0e1d577d7b4d9645ed0af54a6aee7ad187e81eb9.nq.gz
    ├── 0ec20528e08b02dd4d2022ee3c2512aaf299bfdc.nq.gz
    ├── 0f96186c0c3ee6be31366c8482ef0e51ba169f37.nq.gz
    ├── 0fb043dc6977210fd5b6a95c0c5fae14d40f3c0a.nq.gz
    ├── 102e76eb91c448ea4f2f991f6fc072bb5101aa3f.nq.gz
    ├── 104aed310bd3ad6299ee338b4cc07b68317f2046.nq.gz
    ├── 10c05f6b7a726b23d1da59e0727ad0cdf2b178f7.nq.gz
    ├── 10c39ac22998489725b30ce8cd7f3be8cd1dbe5c.nq.gz
    ├── 118c5cb809c8703c0df3371724269bfae1b0f893.nq.gz
    ├── 11a536d4daa2e25c363800f7887491b0f75e98ad.nq.gz
    ├── 11e28110453d243caf5e0d6103b46d257f5181ed.nq.gz
    ├── 11fcf07ada09ed28b0485a456877e18cf58b3386.nq.gz
    ├── 12dcd6aa6c3e6322632ddbe1be2ecbc59362663f.nq.gz
    ├── 12e3ac6d144f0c441f364378962d024caae73786.nq.gz
    ├── 13459560251473631b4f612e8b1e4c5583b5851e.nq.gz
    ├── 134e8372f4a8aeb117168da37c06c9a1e4abd503.nq.gz
    ├── 1360dda65430de46ab95213633be33a26201e61c.nq.gz
    ├── 1385605083aed488014a55ed6e3deb900771bf28.nq.gz
    ├── 1428902d06b08aae2368595924d80cbddb095326.nq.gz
    ├── 14d3595bc7260c30d8dcd777b1d7d5c2b9dfa241.nq.gz
    ├── 14db99406ac15c12da63fd436e172e626fca4e5e.nq.gz
    ├── 1503b431955e7bfa0957c4121a5b159e6dc09d32.nq.gz
    ├── 153dc1e07ce048607e987fa6b89e2a166d18425b.nq.gz
    ├── 15c4aac527ae84a15fb35bdb2886461401ad2c01.nq.gz
    ├── 16c98eabed1143ed4ed945688cb6f003a568d09d.nq.gz
    ├── 17942b85e06555396b0001b64f39a8c9aa2edb1e.nq.gz
    ├── 1967566219286dec1369fa790442496d31209f97.nq.gz
    ├── 19dee4d9ed81f3cae4c18def0e087f93fbcd7451.nq.gz
    ├── 19f89d49b227ccba84e746d44323e636d24cdaf3.nq.gz
    ├── 1a0288e6949b126e4a77fb8a4504c89cfed56d54.nq.gz
    ├── 1a1a999251df245b7d4afe48f44d81c410a60564.nq.gz
    ├── 1a2a6f252d75104b822141ee84d2d7f89edd0944.nq.gz
    ├── 1a56735903475ae1011b66ab1d9fee7d7c0b3789.nq.gz
    ├── 1b619bd5092a2702aed6bac40c5ce7aff412958b.nq.gz
    ├── 1c31bd4ed4e7f41bfed1ed52ba6426a71387c6a4.nq.gz
    ├── 1c3d251c0c623dd55627cd7634a25ddb1a9ebc39.nq.gz
    ├── 1cc37c9e490dc9d134af5981be8b19cb2b4ad43a.nq.gz
    ├── 1de5f6dc79208ddda34c94db7643cad9cfbbf3fc.nq.gz
    ├── 1ed9793627912f59f2610c2d782cf90413be0e71.nq.gz
    ├── 21ab6c83ee04f456ed068a6ecff2f515828a6325.nq.gz
    ├── 2243289313b67eeafd6ac47ff910cf15bd283df4.nq.gz
    ├── 2248d9efc349aab78621df6658b4b9c27aa0f71c.nq.gz
    ├── 2266c2a180254f275b03d112e021ba0a390d04a3.nq.gz
    ├── 22e486d91e25ba559fecc56931e541dccf610acc.nq.gz
    ├── 236d032deaff2068635a08280fc392993f3c9a4b.nq.gz
    ├── 239807158a85bccc3acb5d48e0d34f4b0616248c.nq.gz
    ├── 23ab42872dfddc675bc6ebbb5540778cbdd9858f.nq.gz
    ├── 260c04f86b869e804dfdc8a9294f71f723b2a94c.nq.gz
    ├── 26b652a890282c02aeb87204f2f207ab469f0794.nq.gz
    ├── 275f305e27f250c77f0e30bd6eacd1d629e97958.nq.gz
    ├── 285a36595acc157fbb1d927899b694817c7b0090.nq.gz
    ├── 28853131cea444b220cf6e1c4068ddb6cb1edcba.nq.gz
    ├── 2910f8f0a73a0931c53e77f51a40099f06ba5f6a.nq.gz
    ├── 29afe4f6d810df69666890b857d29b5794a41442.nq.gz
    ├── 29bd87b46cca890fde00b4c846f9a8a45febc89e.nq.gz
    ├── 29f74ff2d2e02d61cd15b51d37ea4ac233a3d34a.nq.gz
    ├── 2a435dcbc767e7379a5c7e5f229d8ff0748ecbe7.nq.gz
    ├── 2abb92b4b34a62ac51e4eedb0289812d4793d20f.nq.gz
    ├── 2b12d30c5a5ee7831ffe9e8d9ecaeda991e6426b.nq.gz
    ├── 2b7a0289a9af88dec997b81a136b3d8e2af07de2.nq.gz
    ├── 2b94821cd7b72154c708b4f704c1238367f1c294.nq.gz
    ├── 2be636e3486e94d13af8aee6edff49daf34aab57.nq.gz
    ├── 2be6fd72d39ba9012dfdd9ee9ec0dea5992c7b7a.nq.gz
    ├── 2c17ccc28378da3ad5119589811cfb21f918fcd1.nq.gz
    ├── 2dad50302c553b04bf8abef385499462371a14f3.nq.gz
    ├── 2e22c5ac2155de62fef33769f8de55bddb808054.nq.gz
    ├── 2e5ebc53b16adedf68c096709902e4bfb52b96bc.nq.gz
    ├── 2ec6ca3fe4eb5e80faacbcd79c1632106fb94dad.nq.gz
    ├── 2f7a8d2a799add92fac0a4e94feefc99541ac1dc.nq.gz
    ├── 2f9d63fe496fc6414b7d4df5d5de70c856a87735.nq.gz
    ├── 2fcd377a324e3d1b07af864ca3c86593ba27613e.nq.gz
    ├── 30f59fe0013fba25473fa1f9000eff587c8313b2.nq.gz
    ├── 314275cec27b3206d8a27b9d9d99472d541906fb.nq.gz
    ├── 3192f99cc7018dd085e637b313e0a2ab536fa1f9.nq.gz
    ├── 31a92493d722ffcc03bd06ac4f65a50371ee46bd.nq.gz
    ├── 31c9b69458347c68ab72429b7c7db2c73bd951d1.nq.gz
    ├── 330d63be863f49796197ea43966519789052d2e0.nq.gz
    ├── 3461a928f439027a0971cfdf0a9bac6281510257.nq.gz
    ├── 3505b357ea8baf30989cc85a47db6150610d08a0.nq.gz
    ├── 3512b4f4ed3bb9b07e914a4e33214965468a6e99.nq.gz
    ├── 35df4ff1c6574e70e033b88f82f8c866811ae92c.nq.gz
    ├── 362974569d99b5b7e5506cd926a35d4cbdd41e58.nq.gz
    ├── 363e4359f95d50153665573d3b18382bb7b53a09.nq.gz
    ├── 365611e5954f824b87f8b8ac592cf1d8a4b91f13.nq.gz
    ├── 36c75a4156b252ada1fa0489b6a702d8ad7880c8.nq.gz
    ├── 371b85e9374e72fe223bb2469c39b063bcc8594b.nq.gz
    ├── 37485b00c0bd6128bb1cfadce7bc22ee79f48453.nq.gz
    ├── 37ae5999dcd96ac23cc5d081ba3cc09c8ea11a83.nq.gz
    ├── 3852b9e3ea36587e17d08159cb3097faf9d93aac.nq.gz
    ├── 385cbf0528e2108ce691575a9c47f66f4bc060ca.nq.gz
    ├── 3891b73a703afc1186548748b4dbc6a72fc5ba14.nq.gz
    ├── 39f74f66910a1c3597631c420bae63fc2d985146.nq.gz
    ├── 3a9a905831bacff5cb85ae80bbb07273454d1cb7.nq.gz
    ├── 3b3754fe43337f48e137136582348d0e3765c3be.nq.gz
    ├── 3b5b566beb986c895944a6f9e93758e91da31f0c.nq.gz
    ├── 3c8fdf9686d1bd53177cf59a07637b69dd0fdafb.nq.gz
    ├── 3ccdc10cada523e85d3206040ba481b0e51f7e27.nq.gz
    ├── 3d1107940e7dd6bdef3dd50099c409b3f07b6c15.nq.gz
    ├── 3e0bf4754bcd5c4091070ed93f13ecc4bf5e065e.nq.gz
    ├── 3e7e97cc27bfeaf0526e006daaa72f9fa04bc881.nq.gz
    ├── 411b4d09f7ccb25064b3ebcab021cfe2ce2e18a1.nq.gz
    ├── 416167afed4f462a58af4c70291709ebace5b2cd.nq.gz
    ├── 41c9357903770e166625deffb8e2f1584043fab8.nq.gz
    ├── 42088cffd0b4a07df3eb636297b953288262cc20.nq.gz
    ├── 4219c762e9b9c9f2deb9e561dea4ee71a9564ab7.nq.gz
    ├── 42524fff4b49f1d714af05cef4eee8561ac6606a.nq.gz
    ├── 42c8d67bf7e4252e5f03c43ce76ef372285eb418.nq.gz
    ├── 4394a9233490dcb235a96e05706be6a1fd6accb2.nq.gz
    ├── 43ed4f5ee6cb01173b448af26edb9d7459f9d365.nq.gz
    ├── 44b62ae56a5ab6f605b19c8d4a6bfe0ab5de90a8.nq.gz
    ├── 44cef9ef4d589673c8349cc90946c03b3ce7f494.nq.gz
    ├── 453e0d4d2e7dc3fc5b1a907c5d56bbc95d59997b.nq.gz
    ├── 4544251e369ff1b530b81e48d68020bf152332dd.nq.gz
    ├── 463923f5e9211748f785eaf3fbd6e4535d2207df.nq.gz
    ├── 47210fd8f09359a02e54be6eaf42d0fda196c574.nq.gz
    ├── 475f0b7662be1e74df43b0c7b56576537f9a4086.nq.gz
    ├── 4773b762179d1102d6d411cf6b8a6e055aabceb3.nq.gz
    ├── 4905a5812ffa8a35d55cdb5f592e6fd445221eae.nq.gz
    ├── 49f9c55375ce3921b5c4d36699c10b74ffafed00.nq.gz
    ├── 4a462e8099c3072ac1ad99964df5a1ac84c2d90e.nq.gz
    ├── 4b32ed73000da8e3e5c750bc869b5447505fc042.nq.gz
    ├── 4b7c39a38370bd914de25f589fff544db0195879.nq.gz
    ├── 4bc9640f41dd9d371b45ba63589c0742c601282d.nq.gz
    ├── 4c6e61e01a403f9ad765b98b0d4074b3c55615b7.nq.gz
    ├── 4c812dd3ab8ed8e7460fbb2202c09e107a114f40.nq.gz
    ├── 4ce5f7db96b6f9581a9448c8b16cfeb7fd976a2d.nq.gz
    ├── 4d7781e0a35203238cfa0858b3ab6f3f9900fef0.nq.gz
    ├── 4de0e194abd86cc060ae9bd582ad070fda96795e.nq.gz
    ├── 4ea9bc2e0d888dd8bcb92c878fd53946bc75636f.nq.gz
    ├── 4ec830f137f86c36bfc0d5681c56c2585355543f.nq.gz
    ├── 4eca8f3ecae5b3fd4f97edc4e28b341563dea089.nq.gz
    ├── 4fdb9c1b478dd703ac814f0d613d702a6b548450.nq.gz
    ├── 4ffffc9ca4a2409204e0fb037f52d9da4cc4fbcd.nq.gz
    ├── 50a4165363f71fb7b47e183a3d36d45e50c67d41.nq.gz
    ├── 50df48b94cf9478939aec20756e9b72a85bfe3f5.nq.gz
    ├── 513b55e35d22a334580ab5b6e8f09631bd8f30f8.nq.gz
    ├── 51c354028309e782604fdc87c435af049d962035.nq.gz
    ├── 52b774c32b0c4c3deb0f18145b7c2ef314b002db.nq.gz
    ├── 52c6cd28c666edd3b25b7666367d152a0c8b8719.nq.gz
    ├── 533bde33c26503bbb6b998f134d973eb173471f2.nq.gz
    ├── 540ba911c02c284c2552ad914a2a5276bcf8161c.nq.gz
    ├── 541b741a9ea2fc0613302dc33b5f3beb045f816c.nq.gz
    ├── 545f89519922a37e72985693a001a953ea9f6c87.nq.gz
    ├── 5516d9e45eba19abfb0dff3dd411791d993d4837.nq.gz
    ├── 555d56d4c7396e2d4341a19d0524fbe290734b82.nq.gz
    ├── 556a19003f3730f77442c0833dc9b2c6524359a7.nq.gz
    ├── 55cb0220fdd5c613ba11046596c3b6ac51ff0662.nq.gz
    ├── 567bf282c2c8251e5f70a285ca44b7e4fc770fa3.nq.gz
    ├── 56a000211e9e3c8068bcd72741a05a2668b5beec.nq.gz
    ├── 57704d104c8b56b90459a7d0697feb5e70f07b04.nq.gz
    ├── 5785cbc59968bf7e96c99c0386bd9ef169998b0b.nq.gz
    ├── 58bf0685062b878d7a20d0b71a47097ab1123bd1.nq.gz
    ├── 5982194da5ba1c17309d4c20e654c9f3e548a675.nq.gz
    ├── 5a969bcb3dd09f97cf792eb298086b02623084ec.nq.gz
    ├── 5ac59a97f52f2d152534334a28bc395789a062af.nq.gz
    ├── 5b98125c558e606ef9d5935cd7891b87f0511961.nq.gz
    ├── 5bee76194a272638e86ff2ff9a8bc4678f52e24f.nq.gz
    ├── 5c2b8395171f34fb1694e004d82da8c4da22359b.nq.gz
    ├── 5c88739bdf1b4aec798fb58c873483a08a538b2a.nq.gz
    ├── 5cf64d35e248d3b4e60c55ffa65e3ca42434d4da.nq.gz
    ├── 5e36232bdc18216df65eb5df2507340683fd369e.nq.gz
    ├── 5e87404ca3a3b4c475c5ebb30708c4f653237ca2.nq.gz
    ├── 5eddfe8a237b1c9be79253741f724f84bbfb6cdf.nq.gz
    ├── 5eeff3a594a7fea76b4affb88e5029670d61e98e.nq.gz
    ├── 5f0770cc20b150edcc888ecc3d7b2c064724b1ef.nq.gz
    ├── 5f08fa214fb7018d3d031fb3e16599cd56944423.nq.gz
    ├── 5f543861eb62189f71ef021d9b42336f30007250.nq.gz
    ├── 5f93a9760ba4a7ead58fc2ce352fa0ffe6fd7697.nq.gz
    ├── 5fcd6462cd232ee0c06f1070522788fd719afb93.nq.gz
    ├── 6088724472074e9c7a592a8262f62e34ec853c1e.nq.gz
    ├── 609f0cee019c7c3d67b60af06248a66c1cd37568.nq.gz
    ├── 60f0186c2cf47dd207cd680ed9e606648f4ca339.nq.gz
    ├── 611d315eb75ceaf2b4c6334bb6d3d0146bd334ec.nq.gz
    ├── 61c5905987ea60fc7e3cad0c81e5992f2959262a.nq.gz
    ├── 623f25ed92447b51175f8ce358e6effe691361c3.nq.gz
    ├── 62d63e565ca597d96247e76ade8be258186dd8c4.nq.gz
    └── 62ff4fa8879f38e1730a163d7199c6ed73a423bf.nq.gz

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

[OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
