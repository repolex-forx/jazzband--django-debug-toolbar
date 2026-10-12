# Repolex Knowledge Graph of jazzband/django-debug-toolbar

RDF knowledge graph data for [jazzband/django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-debug-toolbar
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ac540263ea5a4f0cdecf4e047f19cb13ad919d9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ac540263ea5a4f0cdecf4e047f19cb13ad919d9
│           └── chunk-001.nq.gz
└── blob
    ├── 0216bcae2c7ce531df4469417cf671b6c2185bfa.nq.gz
    ├── 0399974e65b285b725a9be47db56f19bf4af996a.nq.gz
    ├── 03b871964f0bf5017ce83c39a5178addcddca9bd.nq.gz
    ├── 07217f39d7e2ed368fe86fb6ab8e2529607ac2e4.nq.gz
    ├── 07355ad72cb02ef11e9862252c9a451d155f7afb.nq.gz
    ├── 0756a4293f9d779ab267ec710c3d50649c3d040b.nq.gz
    ├── 09c72e582a7a6c28ff1271522cf20c607fcb5cc4.nq.gz
    ├── 0a2a547a4676563e331776cded698da178b43c3a.nq.gz
    ├── 0a3a91ab36c5e436f38196ac9f62db95d61ec6eb.nq.gz
    ├── 0ac9ecbeeaf88fd5dbe618c5614ccf24349c9d46.nq.gz
    ├── 0b772ac39f2b0adc85698227f8fe5000c34d4585.nq.gz
    ├── 0ba9df2bf13b0ab9868fb5b119c3d77cc57810a8.nq.gz
    ├── 0c62e5282d78a1907a43eefaf57a94d3e115b1c5.nq.gz
    ├── 0ee68b2d6c8fc0c57b602dc1d4b05491d3871dee.nq.gz
    ├── 0f3c062903dd17089a17f14c6d3976b1454c85c1.nq.gz
    ├── 0f6a260c793f8a7e038fe2534f7eb98297e26f63.nq.gz
    ├── 0fb46b9990c959adb6d8ace6ecdaf4bda13674a8.nq.gz
    ├── 11676e0955efcc47d8c2bba0fe20dca0b7f9072f.nq.gz
    ├── 11ae526f3738fdfe684bf3396db6b5d90c3e90fe.nq.gz
    ├── 152bc32e1f0ebb2ba39495c6a7060cee9a3c66c4.nq.gz
    ├── 15e624db3d924351490c34b8afac16cb41d4f281.nq.gz
    ├── 169db247a32fadcb17d5d3710fb84d7532034d27.nq.gz
    ├── 16d1fee3ca5e3a464e545464fde4c0e02a0bc927.nq.gz
    ├── 16d87ac14b905a6467388e61838d85a4204525d9.nq.gz
    ├── 178eb29061cce1a279742afbb544f3028f32ca96.nq.gz
    ├── 1927f6dcd13becf6dedb353f2f69ab34e01ccc88.nq.gz
    ├── 198367e3e9335ba84ab57e5dea955ff56cd43719.nq.gz
    ├── 1a5702d08a83c931296a2e8bf0814abc61523d2f.nq.gz
    ├── 1a9ab2d1939c2a39bf7c36d3b66ec2038429c10e.nq.gz
    ├── 1b981c742a61dfd08ca15848eea91294c8dc69a8.nq.gz
    ├── 1c41d04fc2894de141ce1d836c3a65cc6b049018.nq.gz
    ├── 1c80b8e104571ede134b644291c3ebe5a19dc5de.nq.gz
    ├── 1de22cdbcd5f60fac03ed8620562aff3c75cb9a0.nq.gz
    ├── 1ebced724cb1b5b94b0bbbcd784e124795efaa67.nq.gz
    ├── 1f5292b54f8ad47aad0927e821f788c4f75690c4.nq.gz
    ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
    ├── 221d733138be3879cb649da052cc58a875c0da71.nq.gz
    ├── 233da1865eed077eac7ae5c4bc0aa8d54bfc7841.nq.gz
    ├── 25cb0882b589c46572d36f9cdc2a9880a52dbcac.nq.gz
    ├── 278e8630ea50c78af17c95056e282c8d3e571f89.nq.gz
    ├── 27db92a9de3ac3f207060e073b0440cdfe95bb6c.nq.gz
    ├── 281d5197a279470469a68c1a91f6bd724d2fed31.nq.gz
    ├── 289be73f76698d5306fa79003aca74360361070c.nq.gz
    ├── 28c7a0107b98d2e2a91e94c7ad7ac8a056a5a43c.nq.gz
    ├── 2921a456d68bdbf95cbd9a04f826f5a8d7d36b8c.nq.gz
    ├── 2a274fafb76b1fefa074bb2a8c6a230a75f0443a.nq.gz
    ├── 2aec18c34af4e49b2b7c85c1475d3c1a4d61252c.nq.gz
    ├── 2b4fb8ba44b4b0432701f08b419b100d648a1aa9.nq.gz
    ├── 2b7c55626026b3b58f7bdd05cc1a68c345c798e9.nq.gz
    ├── 2b9b8f0174892265b7a42ca72c7d77989204f4a0.nq.gz
    ├── 2c4ca3e12a266e398cf91c1a2e4fd9eec52e7668.nq.gz
    ├── 2cf45ef85ac5867e992e158c55faf0058458f569.nq.gz
    ├── 2ddb7e4496b81098a394c02baa7f491e5e28b754.nq.gz
    ├── 2dff8893bfd89632e44a4e3c04651ebe8922b507.nq.gz
    ├── 2f339f15fe41603f5a8cc1022d3cbeb4a6a55041.nq.gz
    ├── 30ff6a94077af7eb6aebb11b638ab3c2efe1165f.nq.gz
    ├── 31750a7493b1d98cd25cb399749c336e49a0760d.nq.gz
    ├── 320c657ac5c58796bbbf9d3954fe5e7e9bfd55f7.nq.gz
    ├── 3303d87ca33a3612279bed81f709a36112e5c69c.nq.gz
    ├── 331662eb9c221876ace17cde74f6013b034d4d8c.nq.gz
    ├── 333103bcf83c4a4a23726cfb3dd29e9f246fd1b7.nq.gz
    ├── 3443068702fa1efd8492129996b33ab2f906c442.nq.gz
    ├── 347db5878607a878e4d2ec1119d85bb6e4442e62.nq.gz
    ├── 356f78b7c158fa0229ec438c601e987efdd204b5.nq.gz
    ├── 35e1430b3cf226c5b78b7818586a19d66a4b47cc.nq.gz
    ├── 35e99663f80bfca7d148e5a47f6c1a143f852e7c.nq.gz
    ├── 3893c8d49ee2f2decd838ff8e103ec07c46b4aed.nq.gz
    ├── 38f75d520caab91606d1038a894c95e7c8718f3a.nq.gz
    ├── 394bf6747208413fd2dbea69d8ec2d5ff2ec0d2d.nq.gz
    ├── 39af69ee0c7025d6465f3df193ef9679b9b9e3b0.nq.gz
    ├── 3a43f61e9027ec6f1f28704e298a1ed76cb9e14c.nq.gz
    ├── 3a665274e553d45b02e33169cc0a2351488a2a78.nq.gz
    ├── 3baae2b7906861f41df0c44bbd502f37bda880c7.nq.gz
    ├── 3bd8ce037507a1e047fdd31565e55828ecfc72a3.nq.gz
    ├── 3e6c9e74db6b2cb65136b37ec16e9e272fe90723.nq.gz
    ├── 40ad8cf672d8e87a38b1a9d639a30d54f53076cb.nq.gz
    ├── 41c1faf2cd826e0ffa7924543d4c0e2e0f51e755.nq.gz
    ├── 420d86d16485cc2bd03dd1dbf46dd14603982d87.nq.gz
    ├── 422d364746e5c28eff8083781f99f8cf7702eb6f.nq.gz
    ├── 439eb1f7c72a326415a53bd16bfff2312ac1f26c.nq.gz
    ├── 43f0f30ee4a694bc50512f9d8405014a8527bfe8.nq.gz
    ├── 44c4a7c793982fed33a3b208f431f9d648ad03fa.nq.gz
    ├── 469cc4c48a3b3427fa0bf22997119c8ebef60412.nq.gz
    ├── 46c68a3c61efaaa005bee37bad1ea47fcc3bdbe8.nq.gz
    ├── 475a2645c63425e574ba5e35b8381cd140965872.nq.gz
    ├── 4816aee68fa584e0577bb4ff44f8e53fe333e1a6.nq.gz
    ├── 48b2a36f89190e92d33b0eb898ee6fe5fa9f9b9c.nq.gz
    ├── 4aaaa1a62c5ecd6ea0698f9825183e64a1afd654.nq.gz
    ├── 4b389b314e45de3cb799af21ce74c688d5b4bb26.nq.gz
    ├── 4bad81811272743cb0381fafc9fa23733ba95c2b.nq.gz
    ├── 4d4b8c1a20bd67eb9aefdfd5642fe5a378f86d9b.nq.gz
    ├── 4dee5924892c72af6fb61b2f07be3f74e1009842.nq.gz
    ├── 4f39112c5653db2210474c6de284c7d17e9e2900.nq.gz
    ├── 4f632563c5e97f0b029d054f3c55e0dad5d3a107.nq.gz
    ├── 4f680148cb3eaacf0fb24834e6ac82ec168018ad.nq.gz
    ├── 515d65b0e9e6e9ba9058833583a45f5577124a74.nq.gz
    ├── 539980bd325c88551c710b31b7191b2e4fd17257.nq.gz
    ├── 53f373c3d5f4cec01270b60ddec8490824736f6f.nq.gz
    ├── 541131e82bb56be0c6f0269a7a2f11cee2f7a8ab.nq.gz
    ├── 55599d432b3e344e65507fac3a4fae3e74f84ff5.nq.gz
    ├── 5688f2bc68994797f4f5e4bb7a6931ce50d4e52e.nq.gz
    ├── 56b76cb7f6a4c3fc8bebc18048f91154aef63030.nq.gz
    ├── 58d30847ccbea6c60b8d1b44c3eda72f4dd5bec7.nq.gz
    ├── 5a2e0d71acc781283a549a762266440af4a839fe.nq.gz
    ├── 5aa0d69e93712967b6dc689d988f583aa8d5151b.nq.gz
    ├── 5bc334e6cbf7c8a4a65ebede573f82ece94212dc.nq.gz
    ├── 5d745a0050070af6fd01a114ec67dc6a61fdbf1a.nq.gz
    ├── 5d96228e0a684674e55b77b687f62e0da094b7d3.nq.gz
    ├── 5e5daa977cc07bf46f792fefae82928c4ccf722e.nq.gz
    ├── 5fedea529d8b27999fee8c948e7a643608c560d1.nq.gz
    ├── 61e46490d930b08849f354d5e7a3a4efcdbe783f.nq.gz
    ├── 63fee010cb8cd1b6998e1785819f91b18d6a2f5e.nq.gz
    ├── 6436d5f08d84edfd70fbe0126e70291d5a6b7d3d.nq.gz
    ├── 646b6a5ad0882cc6aa5fc2948a3ad62b6e0a6c3d.nq.gz
    ├── 649d10b120816126e85ccc66339e1caebc40679b.nq.gz
    ├── 65698092f3922b55dfa2f14ea4e6c003495debe4.nq.gz
    ├── 67baea32cd36a78a8f1bcc0a27f2674ea912e3fe.nq.gz
    ├── 686ac4cfaaa8e546e769d05f52dd539c2fbe8ad2.nq.gz
    ├── 687b78f13bc076fef6930d8a495833047ba67985.nq.gz
    ├── 6976de4b5d94a8a9919a33c73f20342659585ee3.nq.gz
    ├── 69e112a39637f38d338a382597d342dab1a6fb82.nq.gz
    ├── 6a3c14866cbeb6208e1db341f2e18247f7b48e37.nq.gz
    ├── 6ac678fa34b74d97650b4e1a0b0f37547141d7d8.nq.gz
    ├── 6f6253cef7ff559dea159362e6b9be214138f0be.nq.gz
    ├── 7155d3fcb8ab518f807717fb14c8bdf07427fbe5.nq.gz
    ├── 72d4e3db62203bb3822f1d784d149cb9ed561a7e.nq.gz
    ├── 7326e0d0b5c6e710168b37a0fb19bc7f391dfd63.nq.gz
    ├── 739f2f3144ce068b80c577fb951ff93ecc7e0fa1.nq.gz
    ├── 73c154304b95354d8f0041ec7268b8483bc4b3e6.nq.gz
    ├── 74b4064f49c8ed3c1ecad62aff8ea00af9513e02.nq.gz
    ├── 76ddcbb62f125382a077bb38b9cef8f156357f9f.nq.gz
    ├── 77b6a9b8278156e8110a918ab2c5822bad774de9.nq.gz
    ├── 7868ac3c146ec7193c58201849c4586a12390252.nq.gz
    ├── 79400e93e39113f126d062046358a62c32249f2d.nq.gz
    ├── 7a29bd50b6dfa707bd01bdae26723d46e76d5e47.nq.gz
    ├── 7b65805f3a4a5ac290a377bad4fc4d1150d7ca28.nq.gz
    ├── 7c5c501f63194a4cbdf600faaa4c79beccc5a067.nq.gz
    ├── 7e4d4897857683fcb1f49edf41fbabb131425129.nq.gz
    ├── 7ee2c621ae46d5ec5e4cc992f37f076bfe205e66.nq.gz
    ├── 82626bef007625ca8b2b4bf2b66756f53f4fbb00.nq.gz
    ├── 8302b7bc2505400e42e54cc6f8914ca08e929291.nq.gz
    ├── 88c42bfbdd6e85493f6ef0e2c3aceaae4616ef9f.nq.gz
    ├── 8a8140cd15cab722b0a342495ad01fe36cb4e784.nq.gz
    ├── 8b67970add637c6736fdf90456be480d19fea74e.nq.gz
    ├── 8c1b2d0ab5ad0d3f1400fe41906a7a42ad041990.nq.gz
    ├── 8e3b260771beb825b0b99f9d23200f15ade56c74.nq.gz
    ├── 8e6b939735fa6ecd962d50c25dfd62592406edc9.nq.gz
    ├── 8f01e7630ba2f88ffa1acd90d69f67efb5bd3092.nq.gz
    ├── 8f286c1333b70f8a6e195d9392ec5a1797de46ac.nq.gz
    ├── 8fc48aa56e69860e350a154d8db6d45f40e6d962.nq.gz
    ├── 8fc9905eaa0da27af3b0a7d0f5b2062fa71fa7f4.nq.gz
    ├── 916cb66125a9cd243f7f4f4c8decf331f59e527f.nq.gz
    ├── 918f901088320b5b5e952b21be97bbcfa9826e95.nq.gz
    ├── 926a15ec60398458a6a7ba0e0d210e4ac485385b.nq.gz
    ├── 92f66bac72ebd17209dca926bdaa4f7ef6f00f91.nq.gz
    ├── 940535c31649742f83e37bad21481a30d82cb446.nq.gz
    ├── 9557b3c7387b055f962e2422628fc5d8a0d39d6b.nq.gz
    ├── 9840a63908882835d9d9f6f9e6ea406677f64a68.nq.gz
    ├── 9939c5ca9438f1c07423f5437eb5f40fee6b413f.nq.gz
    ├── 9b0ab38cb6967625751b73fa120c1e98028b53e3.nq.gz
    ├── 9b6012bed282130aedf785805f29026c7880e67b.nq.gz
    ├── 9bf21861ca5c55dd779dfa818e1a746af283a750.nq.gz
    ├── 9c6473d365e0f880926fbef0d88173318dfa887d.nq.gz
    ├── 9d46999e62e0184ef8455fe6d7f40e141c991b00.nq.gz
    ├── 9d7f8085f89509f612127c87f65b66deaef54f33.nq.gz
    ├── 9e69af0e0cafc8e673d8de27e9eb72cf793eeaed.nq.gz
    ├── a1d509b9ef6b014e50a33ea52694d79a8cf8e91d.nq.gz
    ├── a2a56699c53fac84fbf5e7159ea5fe8fedb403b2.nq.gz
    ├── a34e2efe8ac9f57a0536d9dc223d939b757c1ba7.nq.gz
    ├── a5741af8602886b900da32b0477dcb54ee700a56.nq.gz
    ├── a619ae89d466f6ba0aedf656fc724cad4d9a53a7.nq.gz
    ├── a70bafc1afb6fbd8e55323e6064edca0b94f1e93.nq.gz
    ├── a99916e7a43fa07a039b00b67f2f5a1609a981ec.nq.gz
    ├── aa2ccec8cd63bec9bf0116d3b95ab329877a2d7f.nq.gz
    ├── aa81540f62697a70ff4bece5c06fcc0d194d821b.nq.gz
    ├── aaadf591820dde6e91a442ad36a4caa0ef940920.nq.gz
    ├── abd91b8dae55f69168ef3a0c8aa1e732b5f6ddad.nq.gz
    ├── ac31cfd171aa26099582e69b2718bc87c9f589b5.nq.gz
    ├── ac3de761bb676645fcd015cfcef998c6016dc412.nq.gz
    ├── ac4b58d5911398f21f4fdd5ecb1544b192c406e0.nq.gz
    ├── ac707d8393c9b6c835b1370d8dc0adbbbe1e6754.nq.gz
    ├── ad19cbc83a1bd735bf6eb7f3c915d5a7e78a0cfa.nq.gz
    ├── ad90575cea36ea620eb54924a9c9e9734da6a441.nq.gz
    ├── b08e0d39d0e80602668f372fd6b3e54713a0ede5.nq.gz
    ├── b0c0a1949136105725fffbe3e01d2fddb4576a67.nq.gz
    ├── b16657ad7d13d978a36e362ec9091a9b49078989.nq.gz
    ├── b2ee3a0e5f21848ac50b4d51784253bf2e039d71.nq.gz
    ├── b30761e6894c3cfa59c91bbf29f9d2b65a7ab143.nq.gz
    ├── b484c043ae4edf09a53f1cf6ad3385a27a634fb0.nq.gz
    ├── b7cd32f1ccd029a2f31cb58370f50ace958362cf.nq.gz
    ├── b7fc57ec77689477820197de1ea7daa9b1c786a7.nq.gz
    ├── b80577232098a9df18a73a1ee843d81c69c72124.nq.gz
    ├── b834f4ca9066284e381618a3518a218e6fe97e01.nq.gz
    ├── b8a876cde1ffafdebd952700ce4b3a2b56d4308e.nq.gz
    ├── b952ab30b9920a5980718781a13dd7bcf17cc86e.nq.gz
    ├── ba31e398ee1b9f69a1e0f16bc100ce5103e9dd0f.nq.gz
    ├── bcc71db0f763ef94ad4e8b38f0fbc5f0d788a636.nq.gz
    └── bd379655af76cb3df13d7ec7ae95a2980af6c6c5.nq.gz

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

[jazzband/django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
