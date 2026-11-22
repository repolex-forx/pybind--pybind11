# Repolex Knowledge Graph of pybind/pybind11

RDF knowledge graph data for [pybind/pybind11](https://github.com/pybind/pybind11), parsed by [repolex](https://repolex.ai).

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
rlex download pybind/pybind11
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1b4990838904501de7110d27e96c0a4152029156
│   │   │   └── chunk-001.nq.gz
│   │   └── 6254086d96062249c5153c17eab6b4437dd1589f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1b4990838904501de7110d27e96c0a4152029156.nq.gz
│   └── repolex
│       ├── 1b4990838904501de7110d27e96c0a4152029156
│       │   └── chunk-001.nq.gz
│       └── 6254086d96062249c5153c17eab6b4437dd1589f
│           └── chunk-001.nq.gz
└── blob
    ├── 0020a14a70a06ef7019b09772687ebc24af51dff.nq.gz
    ├── 0073d3634d24ec0b8d48b99c3dfdfa4338c99183.nq.gz
    ├── 01be0b47c6f64b3705a6ff7276d465e38ef2c66d.nq.gz
    ├── 02e8c0f089cad80d5b4e52cc4eff364b1955ff7e.nq.gz
    ├── 030abeceaaa488ab1b621597f40659d0b7ac10e3.nq.gz
    ├── 038cddc7abc77c1d9c504298ab8c0be6fce3b247.nq.gz
    ├── 03cb0238cdadbf6a15415d38906b2f7b3c07a71d.nq.gz
    ├── 04dfb2f21764226347d72cf3d30376c53dbab9d3.nq.gz
    ├── 0509339345501bba7336f2c5426f240677283100.nq.gz
    ├── 051cffc04a8b8c8d2f1f467e5053f4f4f8eee4f9.nq.gz
    ├── 067bb47d2aeb6e9f1c52f5199f1da357fafcd495.nq.gz
    ├── 0680e50504665aebbae440c3e594f5746375af3e.nq.gz
    ├── 0718b569ffbe25ba4326be5399a28252732f801d.nq.gz
    ├── 074d98850b71099bdf7c697cc8636d69e04511c6.nq.gz
    ├── 08ced3d4efc5cbfb05d7f4648ef0600594c9ae9c.nq.gz
    ├── 09138db364a83888b793dafd7bcc680458e6570f.nq.gz
    ├── 09720432cf57798647f93142267e1bf3d81f0b61.nq.gz
    ├── 097b4eba251d83cf2cf86e5f7836cb1a7ddc1c6e.nq.gz
    ├── 0a970065b4a9ba4ab00dcd89a44eec89f834769c.nq.gz
    ├── 0aeeaa9ef5f195e42261b21c86ac8e61aeed29ff.nq.gz
    ├── 0b1f246bb09192d53a2d6fc1917af69c784b3f81.nq.gz
    ├── 0b6f49365d888adb956c007a2807d43b76ec7a94.nq.gz
    ├── 0b9d08f8475471293421b3f7d6470df9884f5482.nq.gz
    ├── 0ca2d25414f009df0fd240dbfecab13f7f0b6efa.nq.gz
    ├── 0d1672cfb61e51c5f3559456d41e74b21ae7a532.nq.gz
    ├── 0e3b18720bab2b63b316a7b79358d3f24bb5922e.nq.gz
    ├── 0eb0398df0e1cf028f01e31f564b174801334b8f.nq.gz
    ├── 0f92e2b05d42be2c3c76955de578b93863578c7d.nq.gz
    ├── 10b092024c99bf0a8dd357708df7000014e6fe57.nq.gz
    ├── 10b283deed3ebea3cd507018cb9f0ed128350947.nq.gz
    ├── 10c0c9446cc0734d04e1ab59ddf7beda8250769b.nq.gz
    ├── 10f6843202ff9ec426456cfdb0d2d1d2d10501ca.nq.gz
    ├── 10fa825a81d3f4ec16eef142e900ef59f44cf1b6.nq.gz
    ├── 112a363b4b0ced84173b662418938432ce35de02.nq.gz
    ├── 11aab9fd9c2a2ffd8a65dd10c101b005a6b2296f.nq.gz
    ├── 121d1cc40c24bd3e2554aafa3131f436a11def2b.nq.gz
    ├── 12216283ab948a0e9ff11fd35b73761dcb9c9c26.nq.gz
    ├── 12acde7b3afd108d5b3a6a42fd3c96d9ba96deb5.nq.gz
    ├── 131bd87710eedf8118824429f8fa4fb14ddcd36c.nq.gz
    ├── 13d0dd19e1bb54e8835dae9c239b272c8d509280.nq.gz
    ├── 14259622428c629a0fae9253700a9c95ba36ca20.nq.gz
    ├── 142c23c77220610de707cbe9905542774e75ba9d.nq.gz
    ├── 15101071752b81317470219e052778a2c01ce7db.nq.gz
    ├── 1539b171a230b20c181fc6f4c5756cf09583ae99.nq.gz
    ├── 15516b21b0922dd8b6eaa0d0aa08205f6640d43e.nq.gz
    ├── 16a88ae171846844ddac28839e2150f11d287839.nq.gz
    ├── 16db302c17a0d314a4773ab5443824e23e6f0a3d.nq.gz
    ├── 175268d11316bb9263dcd7b48151313761be4516.nq.gz
    ├── 1817372fb9faaebdbf00fe9ad41864323dae7458.nq.gz
    ├── 1902ba21def014507f1cfb4f215aa1b395b3788e.nq.gz
    ├── 191284b1a8cc0b9b6874e93a6ad84f57fff22964.nq.gz
    ├── 196e99965147b211afcdc4afd0116e80efb59e56.nq.gz
    ├── 1976abf2611678f5f78c91178040b2046e7414da.nq.gz
    ├── 19c4bbbb56bdf862f26ae3f4c26761b29d7726f9.nq.gz
    ├── 1b06ea8728724a047b187bb98352bf294463fa78.nq.gz
    ├── 1b2122522d5b4043c9df57f2beb943682eb4b208.nq.gz
    ├── 1c3094f417317aa346b4e3a1505e8c92ff792f5b.nq.gz
    ├── 1c3117041bb5351d17f7bacec668f9a528e7de5c.nq.gz
    ├── 1ceb11ba83f3667dd10005cce13aabf132bb9607.nq.gz
    ├── 1d66e119d610fcf01ac4c8d8b2c31d7f9533dee7.nq.gz
    ├── 1e17bc389cacc3c86af1419594d1bbdeac4ce866.nq.gz
    ├── 1e5d2bb876d17f24b88b19ddb525d4146869944b.nq.gz
    ├── 1e94a569becbcfd89a678c4e6fe7df1d6d2ffa8b.nq.gz
    ├── 2030cd6715820616e22af9888a65fe6c32fb8bae.nq.gz
    ├── 21c3cd9abc2577e3f416c78000045299a0a9e7af.nq.gz
    ├── 22814aba5a06790ab1e357459292abae7f655ad3.nq.gz
    ├── 22ae13fd77f6cec93fc344951a741a538b0f6ab0.nq.gz
    ├── 22ae8a1c9440a0dd4a9093cda8ac245c9f49d91b.nq.gz
    ├── 22b728e28c6590e21614d4fedd29e021ec0ceb69.nq.gz
    ├── 22c0c76f5d3248836cc46b9799ee83027784bb39.nq.gz
    ├── 2334521658fc0353417df5a6ce590d7ae18512b2.nq.gz
    ├── 23c191cec2d6b2f6cc9a763a291f5ff8dcf4894f.nq.gz
    ├── 23d46eb264bf321e63c45226d5c9dd4a84e4ca9a.nq.gz
    ├── 24e13592208f1de97da493c7eaa14fdd6d0e5985.nq.gz
    ├── 24f56d158442c2e2f4667806e91fd94b476cc96e.nq.gz
    ├── 263b2990e3e78ccea7fec901f1dd780cd4741d0d.nq.gz
    ├── 268aebc0cee1d1e08e0ee41746fd4ca63cfdbbf5.nq.gz
    ├── 26d618f93adf257efbb3972fe7af3460b8da1094.nq.gz
    ├── 26e9cb75153a95c84bb4a03c93c150052c35f541.nq.gz
    ├── 271716b4b300a076be22cf005d004f615f0d0470.nq.gz
    ├── 273b9c9308d9de40d13abfe16256ace273c71761.nq.gz
    ├── 27e8591670b12c23609b7b5287f399cec324615f.nq.gz
    ├── 27f9a804415e88ada9c59a338a125df37069dd42.nq.gz
    ├── 29b0234856de5ccf84b5f867849e53f9d830b3db.nq.gz
    ├── 2a7fa0fda0741ab72b551c8b28fae5a305740cd1.nq.gz
    ├── 2a9fc4490a1a368f37fd93e525af67dd4a9cde97.nq.gz
    ├── 2ac92875a2212bff597c12e4e47f831abffbd3f4.nq.gz
    ├── 2ad01e6827a46c02719eea21a98b2151480a7195.nq.gz
    ├── 2b24d7cb9971ff1456150fd9cb7890a549266611.nq.gz
    ├── 2b89d203f3c7a3e9455fb9553ded1f9c51e61964.nq.gz
    ├── 2c069adffbd141aa90b9adbeb2ff4e9b21a3b1cf.nq.gz
    ├── 2d264120478b33fcbba89fcaaf7fd14ac00c9eb5.nq.gz
    ├── 2d633a4d0c129d6bdd94b4134c9516fdc92bb192.nq.gz
    ├── 2debc5ff17e3b4c5dd98de5bcbc11f77bedfd857.nq.gz
    ├── 2e5a67ba8fb427625c8a1f15f70f3e26e53a331e.nq.gz
    ├── 2e5f7a153feadbf14d2d82536c6cb6b844b5a9ee.nq.gz
    ├── 2e972d0b88f448aaf783493b697b5fb434754ffd.nq.gz
    ├── 2eaa3d3d16174192659feddd3cd04f476cba7e0c.nq.gz
    ├── 2f76043c3012cda8f45af07513871454e7c299a6.nq.gz
    ├── 30bc4f1e14da9f876947c6ef53e8fde766fd1ee0.nq.gz
    ├── 326b768c40050dfa27b51ccb963a2fba784c270e.nq.gz
    ├── 327e41eb33229db19a9bae8cebd742ff8c256682.nq.gz
    ├── 33133eb8896dc5a8d6e3c9352b2f486a102440d0.nq.gz
    ├── 3358b887f75da7d01691407e6c9248dc18442049.nq.gz
    ├── 33a484945a4377d4552056cc80d91f26a2b9869f.nq.gz
    ├── 33a78a6b1d9054ef0174926e54395a692ca86faf.nq.gz
    ├── 33a9d4503b03f6bd29b3a0f2fb3d4fffe0d41840.nq.gz
    ├── 34aa52068204efbbe7c0b1232cde5318acdf75e7.nq.gz
    ├── 34c98633cd2f2eb6c49f2d0687661331eea5ba98.nq.gz
    ├── 351b7bf22e300ff90a7919d0dbb66a46fcd29335.nq.gz
    ├── 352b1b6ca5c8519e7b2608ba3bb77f81a5e1a3db.nq.gz
    ├── 35b7f02334b258b0a59325737fbff7c2cde21e1c.nq.gz
    ├── 360c2cd7bc252c5eb1385f50c6bea0f2dc666763.nq.gz
    ├── 3617fa3e8518f783d349e416c0c15a0bbd8d1875.nq.gz
    ├── 37a6a6a42e56f5687a8687df2d79ea4142b59af7.nq.gz
    ├── 39112668a433b3185db24e73e473906c9c0b222c.nq.gz
    ├── 391cf1071c1a7663a36c8b7152cf97e55a7119a2.nq.gz
    ├── 39bf86785fc58001ebfce1550e93b61617555cad.nq.gz
    ├── 3a3f29341471ddf4b7c00f41dd22c033011e874a.nq.gz
    ├── 3a9a1f156401aeee03a3d1d52e36d5e43a51195b.nq.gz
    ├── 3b3641e8d6b94bc39d725bc993cfa3e8ecc847b4.nq.gz
    ├── 3bce98835372f7a199b320cd407e9befd7053243.nq.gz
    ├── 3c7b31e093958067f3a3c5980355355e8871dab9.nq.gz
    ├── 3ce9ea0286e9dbd5fc795e60ae77a3c9afa356b8.nq.gz
    ├── 3d74611f2db85d7981287ad4314e2a868a1280d5.nq.gz
    ├── 3f03daf38a0d906a83c49ce1e1bf72b83bb0376a.nq.gz
    ├── 3f342a0e9cec7ce542f11a483467651bb3b6f8d4.nq.gz
    ├── 402f0b357d25eb6b4e310a8810bba3420f4812c8.nq.gz
    ├── 4056f74fe782be5de1bf63df639b3b5416889b91.nq.gz
    ├── 40803fbf8ae4328577e08a842a0800578148f7f7.nq.gz
    ├── 4103c0f5ff1e574c59628ac5d0680c655cc3eaf9.nq.gz
    ├── 4108925520f8b3726b52d6915a1712dc7fa7f562.nq.gz
    ├── 41c80e98d4c7fb8b7a0f33f8ba388e0ecc214656.nq.gz
    ├── 41e21dc129be4c83f584f3102e7a207a4099534a.nq.gz
    ├── 421eaa2dd896af80be1834281fe1a5fd668e10c9.nq.gz
    ├── 424d36dea28d1ff43f5944efd04ef1519c0ac5b5.nq.gz
    ├── 426220013e61b91c7235cfa54a07bbb46aa7829d.nq.gz
    ├── 42b0e96be74e22afbbf81e57c4416f9e443c86d2.nq.gz
    ├── 42bf3ade9d845e473af956b413e98e2274717b8c.nq.gz
    ├── 43e2187b9e7c9554c5ecb520fb978857c513572b.nq.gz
    ├── 44261e881e13a9520088418fe32d099596717ad1.nq.gz
    ├── 45917255c5b16161ee21a28e5eaa3ec32ba84b75.nq.gz
    ├── 46a1c457c6c996d1596980dd90bd2d34369997ba.nq.gz
    ├── 46f0a1f11df06ff78d84dc393353bbbede68a605.nq.gz
    ├── 470d34aad28a588c305df17b32d7703b23bdb18f.nq.gz
    ├── 47430d3a291b916df13fb46433e76c403855dbf6.nq.gz
    ├── 479530d853041ce97283fc0e08178650d18689fa.nq.gz
    ├── 481e04c0c86852f0d5fdf43535faa56b8dbdad67.nq.gz
    ├── 490e6d59f271b61b832ae84ba0345bbb74f956d9.nq.gz
    ├── 49c199e14f83f92e6653cc980b5ef2b4b4a4745f.nq.gz
    ├── 4a4beecce1e289f3acc9d41e9138bd1ecfdb2089.nq.gz
    ├── 4a700bd66ad690af49bbceca8282442af793b9dd.nq.gz
    ├── 4a7b77c69ad746d547397e665a926a1f519f6830.nq.gz
    ├── 4b018551bfebcbfad53b2cf833d3b9f6d992029a.nq.gz
    ├── 4b027dbfea0440a26545c2c90942fd6a734f69d3.nq.gz
    ├── 4b7422eee25ad458c1b575e200eca56a3cd79a88.nq.gz
    ├── 4bd7d37a4f70118b1cd43989dcd105a2e899d0f6.nq.gz
    ├── 4e2c66902e5946dfd0eb8fc49d4d4190a620eee6.nq.gz
    ├── 4e52c90c1541c73be72515b6606fd4a4a6d3840d.nq.gz
    ├── 4ec0af7245b43067dabd97365c188af99fa63955.nq.gz
    ├── 4ee4f069056ab32747df223b26016d8d76a69f0a.nq.gz
    ├── 4f1e78f33c6242d3159801ec988d4a4297d41d20.nq.gz
    ├── 4f5ae34fc8243c6066eccc8d1b099f029c0056c3.nq.gz
    ├── 503c69c7d3d574be824a530ef544257b1dd692a1.nq.gz
    ├── 50c505a655c5834c766db60b233eed05c1ae3e54.nq.gz
    ├── 5118b25da8b13c09801783e7321b0f2a151a9a4f.nq.gz
    ├── 511b47c2d5434ced54ed49ac35d33df80afc684a.nq.gz
    ├── 514a81272e6c8a51fcb92299f8d1d834cf6925bf.nq.gz
    ├── 518f2df2b6dde1628866372eb35d4ca181dce70e.nq.gz
    ├── 5235729e40e04d34c8603b36a5211e4108137630.nq.gz
    ├── 52d2962107f7479188173e2025ccb6f20705fb0f.nq.gz
    ├── 5374cbceb215f0f37cc56d4067c1c138f3ae6038.nq.gz
    ├── 547545263e7dd378bf1e459d600250e47eda990e.nq.gz
    ├── 564dd4a7a5dd7e2dd74e023338e8ee6c2ee3171b.nq.gz
    ├── 5703e3d51c0312db8b73f66bd35a161eaa260253.nq.gz
    ├── 573b7cf4ac3c31307f7ecfba95172a42d1833675.nq.gz
    ├── 57d12fee44e726cd42a149481c2c9c3e88896d79.nq.gz
    ├── 580371f02deaa6658b08c61f0de5f608d679e06f.nq.gz
    ├── 58c8f72bb4ea6a189330c0566bbaea4bf4f51e72.nq.gz
    ├── 5916ae901065c47f12b04ad51d3b1a58f5366041.nq.gz
    ├── 59449ac9b95db1e1234e66ebe635d359c5add3e7.nq.gz
    ├── 59845b441b3c9e0940052ff4db50c491e979f605.nq.gz
    ├── 5a5877e4e6e482e9510c0cf42b4c2c577c703935.nq.gz
    ├── 5ab3142e473ff84e010b5def1c87f6e32b0ca34a.nq.gz
    ├── 5ac4553a530c20f8fa80af31a9f7394d01d411c9.nq.gz
    ├── 5aca66c5ee79cde505d9e558a590cdd1278df8c3.nq.gz
    ├── 5bf950e6fdc81676d9a9774926a623b4f6a2e2a8.nq.gz
    ├── 5d7c31cdaf5ab8e2437c022e77974a3a7f53689b.nq.gz
    ├── 5dacd7aeb69391772c7abaeaf09aae533fac74fe.nq.gz
    ├── 5ed6530ca112cbe643d5dd6d6fde385c4edea6b5.nq.gz
    ├── 5ee5846b5fe085c004cdfb1e23abf0c7b0939766.nq.gz
    ├── 5f216bffac17b7defce49a85ec8611cb267a000d.nq.gz
    ├── 6084d517df066c38c771ab34879caf19866d6eab.nq.gz
    ├── 60d0ef215eab50400db74f3ee7ab64a19d39538d.nq.gz
    └── 6147c6be249f93c2e992c118e96dd7c9eb991d91.nq.gz

10 directories, 200 files
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

[pybind/pybind11](https://github.com/pybind/pybind11)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
