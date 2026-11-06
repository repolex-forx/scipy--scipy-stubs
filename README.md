# Repolex Knowledge Graph of scipy/scipy-stubs

RDF knowledge graph data for [scipy/scipy-stubs](https://github.com/scipy/scipy-stubs), parsed by [repolex](https://repolex.ai).

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
rlex download scipy/scipy-stubs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1cd8e53887c29d864e605eb68a60fb278f3b8974
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1cd8e53887c29d864e605eb68a60fb278f3b8974
│           └── chunk-001.nq.gz
└── blob
    ├── 017a80a8cb001d8244a4f2768f5c705777c7c7d4.nq.gz
    ├── 01803e88ab41688434d8abbfa8a218af47d488ef.nq.gz
    ├── 01ef291c412eeb44573a47468e8f8d83d559baf6.nq.gz
    ├── 01f249e7811b91be7393f8505638b3ac9ced2c25.nq.gz
    ├── 01fc8fb796fc0d484e60679f8b3e6a89f5639506.nq.gz
    ├── 02d5abf33578470b9d098984491f02cff724de18.nq.gz
    ├── 0413b4244f7b0cdc03b48a4c984a9d3f37a6d838.nq.gz
    ├── 050ef13f61c22b97e2e1fd829fe8f6a090e978be.nq.gz
    ├── 0534800ec6d27342f65dbe780cb5917e332ed74b.nq.gz
    ├── 0621d770889794f29efec1b094c9352e7ade7a82.nq.gz
    ├── 07680a52ca63fabcde7650f79f2bd6effb602139.nq.gz
    ├── 078fef4b5fb5ab132a55beeab4513a26fdf4829d.nq.gz
    ├── 07c3436cc969afd92732371732492b45b4f99baa.nq.gz
    ├── 0816102116ce2fd11a03250235246297a9dc4d72.nq.gz
    ├── 0832e4559e8e36d9304d8ef6e040e3d57ed18da3.nq.gz
    ├── 08664af3bba05a6e261d536e37457c19fadd2beb.nq.gz
    ├── 0952c71b56c090921dfaf57a5e06fef17375436d.nq.gz
    ├── 095e30429fa399a455a7f0449a4feb45c141c2fb.nq.gz
    ├── 096eaf24036842ac7841bde89839d2fa7d40bc08.nq.gz
    ├── 0992a3e6452998cf01a099c456a995f5c2546ef8.nq.gz
    ├── 0a3c3c6f2000697973e0775854761de374b89c82.nq.gz
    ├── 0abcb64ef2b1e16d3aa3cca0b7655adc980c45b1.nq.gz
    ├── 0ac09ee9267e63dce5891694aca109d0fc2d3e37.nq.gz
    ├── 0bce39e1c25c2322ca15fe6658c253ec56b79e67.nq.gz
    ├── 0c3ef5a8b44b8659398783378dbeba72cd98b3dc.nq.gz
    ├── 0c557c73c1cd47e60c571a95c0629de23e72feb5.nq.gz
    ├── 0d59144ef755c124dbedf0e29717c1be80431c96.nq.gz
    ├── 0de12ae5bef6ceefefba1ac9dc58ae16557eebb2.nq.gz
    ├── 0e0a0d0b7609d6d0dfe16ebb9228c7ffecde4e54.nq.gz
    ├── 0e0f34f4f78b48365d2123dc1f644be18c993600.nq.gz
    ├── 0e2ea4773ba0b4ba354734e468b2e9634cf6d397.nq.gz
    ├── 0f34beeee74323b9032bac74cc460803427f87a4.nq.gz
    ├── 0f4c1a8ff7a9c0beb12de8b0a27a69943743dbc9.nq.gz
    ├── 0f9a91acdc0b93987a07bbedef1da9e7a6dbb006.nq.gz
    ├── 0ffc03eb2e3fd4490209ec074e33b8049f37e1fa.nq.gz
    ├── 101bffd73ce68af69d352eca497c97dd2f754426.nq.gz
    ├── 10b6f1da10bf23aaac57925d2b77aa013177bbe6.nq.gz
    ├── 112b7080315d58e45152b02db7728465a54fa0d8.nq.gz
    ├── 115fcb6a70217b99711e66eb31fbd66090884dc4.nq.gz
    ├── 11bb178a7de6f813a338e83623d812e8795f8672.nq.gz
    ├── 11eb21482027c1675df739016f37815664e40a36.nq.gz
    ├── 1327689595675ee014af3ab45977e3eb5e03d475.nq.gz
    ├── 13d2c3a302c6ef03cf92c25a9e64e6434a07f162.nq.gz
    ├── 16ee00dff1801a9efc7a0a69dcc6eb1784b7802b.nq.gz
    ├── 170910ee77424a09bae2d2753a76fcc8b489ba8f.nq.gz
    ├── 17fd90b6294b81f8aaf88df012cfc08e1992cbab.nq.gz
    ├── 188098f5f6142ad23e2eced392289e93b023f559.nq.gz
    ├── 18b6f8e6b5b79d3a89a5972d99be91d2ec21e24b.nq.gz
    ├── 196bdf618ebc5bb8a27ad768b22e33453487d7bb.nq.gz
    ├── 196ce7014e4b00a247ae7cfad169db1fc854d979.nq.gz
    ├── 1a67e60578e0a24e0b954c23f805e5cd1b1b348b.nq.gz
    ├── 1b23f454439703ca4148d0648d2793541c010ff7.nq.gz
    ├── 1b41cc441b96494dce320a51af66de7d96d388dc.nq.gz
    ├── 1b8bb353c1e13178747b7968584d9c2cd5c57ad2.nq.gz
    ├── 1c552fd75fbc730c719fa9309d33165fc651dd8f.nq.gz
    ├── 1c72d3429728b2ea3ad6fd09e9fff36d9694952a.nq.gz
    ├── 1cd2f716eeac02ba78945a0e9c7788f13a763c5e.nq.gz
    ├── 1d6f71e64fb36d46b2bfcc739571b20a03457571.nq.gz
    ├── 1dede67f0d0ba9ad40338b13817dd6edc6f077cd.nq.gz
    ├── 1e66bbb923c32bba5a75c8446833efee45c492aa.nq.gz
    ├── 1e71222910436fd0af18ef6832880c302e99b009.nq.gz
    ├── 1ec752b65bd1e3a30f503a6b396857e6b2039088.nq.gz
    ├── 1f80b2dd4d543dda7be3a5eb2d83476ea9cee910.nq.gz
    ├── 1f8a8e873f7f9b3ed0367baf35c52402eb6a058f.nq.gz
    ├── 1f99bee55029826bd4aeee09842e75e2925826bc.nq.gz
    ├── 1fcb062e3a0be6078a3f57fa5fd6123477b0c9be.nq.gz
    ├── 1ff5a68729177bc24da647555925cf2b87f03471.nq.gz
    ├── 209e551276b191880f417c5745916634e51725dc.nq.gz
    ├── 217f5a45dc447eea97914d8e48a3ad1fd69d8d63.nq.gz
    ├── 21e8a99b70cfb0adc1638261d6d97dca2e67cd50.nq.gz
    ├── 22a250693654f6e8585f3afd841b9e6edb33790d.nq.gz
    ├── 22e3bd29a192d8afa7cdb0de3d37dc20795c191b.nq.gz
    ├── 2440a5ce9cd8ab918f6a82386f627be8d6f10403.nq.gz
    ├── 25d4535f3719ad1c8c86289bb2ba48886cd9e253.nq.gz
    ├── 26299362a7d2bee982f52248eb9ecd07d06eb3c1.nq.gz
    ├── 26e2d54093a066ba766ce79bb880a8816999a5ef.nq.gz
    ├── 275aaf93f5a118020c5211c3840d806443fe2fab.nq.gz
    ├── 27d624a7d4d1e56a32bcf6477a7627296826d9ed.nq.gz
    ├── 2878f07586f6579ac36f17d13829c5f5bac8346c.nq.gz
    ├── 28ff669e7e061107cff833771adc80d1487711ff.nq.gz
    ├── 29288193d36688173cf16d09743c688c30ab8a17.nq.gz
    ├── 2933229d01c587d903578ae1fe644a7af3b965af.nq.gz
    ├── 2a3c0fa4a1511dc07fcbbcb591c3c45d369bf211.nq.gz
    ├── 2aa707df1f843aef806482ff61b3247ec3d811e8.nq.gz
    ├── 2ab917d5089b3a2aeb2f7539653d380f075a34c2.nq.gz
    ├── 2aed676c52e7c1fbc79437a97c3074ecb5e01245.nq.gz
    ├── 2b9d8c2bd46c347f850ec70be11976bf0524f9e0.nq.gz
    ├── 2c8049ee9915e21d0f0bcdbd9dd09402f3809bf0.nq.gz
    ├── 2cf5c763a66db10c74a87b9ec7f32f44bcc9fcee.nq.gz
    ├── 2d03c870bfe539a5aaa8dbb09af3f5791341120a.nq.gz
    ├── 2e2d1c326640c19e197e7176cab6c493e6ab22fe.nq.gz
    ├── 2ec218a9a4f3be7acb14d5ac68b20acf27a057d7.nq.gz
    ├── 2ec825482baf3d54ede761c58f7d97782a4ad3de.nq.gz
    ├── 2f10bda2a17037d8d40767f803c0f2e50bdfdf31.nq.gz
    ├── 2fab303e01b9a411298ab7521702ef0cc01c7268.nq.gz
    ├── 2fe2362cbb208d4eb12885b3ae54dccb78b8349a.nq.gz
    ├── 3185eab3bc3bab84ea5734d25910fd3f5ed48406.nq.gz
    ├── 32be6a3d1db1d4b3a00eaf749c2dde07075fd5d2.nq.gz
    ├── 3324b3b2772b4f788b1d48e9a03892d762547039.nq.gz
    ├── 335af91ceede4102a5596617b823c4a31a5d2f8c.nq.gz
    ├── 335bec99de758961ebf8cbb96b1a36917c91bd44.nq.gz
    ├── 33ff0d6fd326641d128d7ca48ef07ec8aef6eb10.nq.gz
    ├── 34828c17df2cb3565d2a53cc6c7f776e8f47e6f8.nq.gz
    ├── 34c9d89263d434d423f37e449c6c2908148cb92e.nq.gz
    ├── 35eaafe44c9b23be59340ddbf058ec0d63fcb635.nq.gz
    ├── 36e76e6fe10cc393490ae87741bf7b5639fb15e8.nq.gz
    ├── 36f750e104016e09166d48e82253ee887132cd7b.nq.gz
    ├── 377fe917412f91cd95f33499ec5ea6b84e351747.nq.gz
    ├── 3780d278cc773c160c303f141fd4f860ae77eee0.nq.gz
    ├── 381ca4a0f32e8ad6173b1798b4066a938f9473f4.nq.gz
    ├── 38c34439a0f1fd91ebae53cf51787c3974d999f7.nq.gz
    ├── 3aa0ec7abdba1fdcfcf8f320aebfd951fd80c05b.nq.gz
    ├── 3aa65f584673092d0be0de804e2fc38369a252ce.nq.gz
    ├── 3aeddf23af2a6b90ee16bc11dd618a8ccc7c2ba8.nq.gz
    ├── 3b6dde96522f8c0db4a23e3ff4debdb750cbe839.nq.gz
    ├── 3b77cb453b248f3e442ff37f967f3af2c1971b34.nq.gz
    ├── 3c0afc0e0a293be430972d44905d71ba9a0ec880.nq.gz
    ├── 3d81249003d647d6727191fb0f9724c108f67af3.nq.gz
    ├── 3dafbc237f0e9d8b4195bcc195b8eacf428f46e3.nq.gz
    ├── 3e0ed44ab8191b226ee55b7aaae283a76ddc9657.nq.gz
    ├── 3e8971edf234fa9820c601fc092afad1cbb5d7c0.nq.gz
    ├── 3f9226c80c8c27d78d4a7981881fc8bf7fd0f105.nq.gz
    ├── 3fadf6e162c240c56a2e2cd9eca9371acc9aeef8.nq.gz
    ├── 40235f75899bb51e12333644e668ffde6e844b58.nq.gz
    ├── 4052af80db3c9754d47224ed5936be5050f35a91.nq.gz
    ├── 41581b5a497a449ddf8e1b93535663b301c38bb2.nq.gz
    ├── 4256e1021f5310fe8441c095efbe02dbd1614caf.nq.gz
    ├── 42ef6e6561f2d58a150ff09968c53d2905dfdc8d.nq.gz
    ├── 42f9cce10a7e4179f3bf04196fe7fe03239c67b7.nq.gz
    ├── 435ee60ec5c146927d435d196f6a1653df1562a4.nq.gz
    ├── 43c1af350d34a858a58c06fe3536e7c6efea2648.nq.gz
    ├── 448e1f640cf6525bef971f950f15d4b9b3332fa5.nq.gz
    ├── 45a061e56467c67909c98c68073fd775ad6a6908.nq.gz
    ├── 460bf4e755be264e53f46848db45906a2d356652.nq.gz
    ├── 4638fdbc50ef67cce2110235ee57b4ccf4ccc319.nq.gz
    ├── 46524cc6f7f8ab522ff30f846808550e8ef5c8bf.nq.gz
    ├── 466a48e3f17642027904b7b6fb112ccc0cb2b7b2.nq.gz
    ├── 466a62754d192603b2c9401d823718547eb2e727.nq.gz
    ├── 479871e5ef676916415010b20be4b0da4e85e14d.nq.gz
    ├── 482669920e0723fabf75f892a3bf3d7ed1055d50.nq.gz
    ├── 483be1d9c0797f96ddbe3cff0747f4223a066cb1.nq.gz
    ├── 48539ef1cbddee75bbf50826b1292f6d19ef08c8.nq.gz
    ├── 48b5304876f3cdc8d1e2ba60557d74fd4b88b9a7.nq.gz
    ├── 49c133ad4c12cefe2d6779adb86635b98796307b.nq.gz
    ├── 4a57a2e7bd46620de512a57d976cb696dd6c1174.nq.gz
    ├── 4aa7bcfe13035aaeff797b8c02396ea32d46850b.nq.gz
    ├── 4ab349e3df858bbe9148747dea9fb867777a833b.nq.gz
    ├── 4ad8f7e640cc0a56c4858608a9424d6b8edf6198.nq.gz
    ├── 4cdb960006e826a48c03e6a4540c106d95b6a8be.nq.gz
    ├── 4e3339bde65590d0700cf1cdb942d9e8f8c804ba.nq.gz
    ├── 4f9e2e56e8354593e7d8ca2b6f936b516bd5ee02.nq.gz
    ├── 510736d3313f4094f98cfb11958bc6f9ece937cc.nq.gz
    ├── 51e940763091de52516a7a467a256abc1e4a71bf.nq.gz
    ├── 5232c9f3eece6d32be0e756ecd55d7440ba570cf.nq.gz
    ├── 5401d5accc98598f55406ca44ed240ff4c9787c5.nq.gz
    ├── 55521cd574513cdd6125f6c2c3f52b0f013bdfe5.nq.gz
    ├── 55d350174767c87c17823ba4d542ae218446229b.nq.gz
    ├── 568f24999c03ea026ffbd1beea53d4e09c08228a.nq.gz
    ├── 56d70f86a4c0cb1af93b121b40b362dec3acc85f.nq.gz
    ├── 588c24c2f6183c1f44e39398113567f7cd58cbe1.nq.gz
    ├── 58c5764a132327ec8b358c9ccf087c8db678a11a.nq.gz
    ├── 59e3baf5f6408a9fb59fdeece3786a7b4ca847b8.nq.gz
    ├── 5aeeda937622fa5bd0f10196f5d17b0c905d5b95.nq.gz
    ├── 5c7a4b5faf29439c4656d6393d1bc9e133c3a384.nq.gz
    ├── 5ca058dc0a6f5c371f4609c930d11958b6c90b0a.nq.gz
    ├── 5cf06a1fbf3bfe71cbb61badbbe056a5f9d859c0.nq.gz
    ├── 5cf12c56e7b6e4f2fcc2740b471365b976aec583.nq.gz
    ├── 5d9bf8beb530223cfb548e2414241e112decfd0a.nq.gz
    ├── 5d9fdb7698a8be03437709fcfa12a935397982dd.nq.gz
    ├── 5e1f32b33c5de95f304b8ebf050684d086202289.nq.gz
    ├── 5e97f43a0211e9fb6c933d7070aeeee6bf35a88a.nq.gz
    ├── 5ecf5008dea9aa6319eaa71842efdaa62b34ce1d.nq.gz
    ├── 5f1a4a356d777d50d7c7901c29316c732b948211.nq.gz
    ├── 5f2f64c63318eb24ef0e11328196bb2b51d6d02a.nq.gz
    ├── 5fa562364cd4d6fe60841d261fa7059a9ae63045.nq.gz
    ├── 5fd9a1c855d934e7ffab141e2e38e88ccd8eea3d.nq.gz
    ├── 6003399c6c8ba091f0dc67b7eb5ef39e920b1152.nq.gz
    ├── 60230a6dad7ad39a4476fe573ca4492b70282e2d.nq.gz
    ├── 602f1ad33f0c97abf3a5ebc826c8becf936d7968.nq.gz
    ├── 60952496c03a92062277bc0196dfb32331229e8a.nq.gz
    ├── 6124c572088cf7149ad62ceca5474fdd0fabeae3.nq.gz
    ├── 61a09b9f0b8e248b8ce523d9edaf021f2e48aa1d.nq.gz
    ├── 620a42f00e16bea22f45924c78350c2715a2e994.nq.gz
    ├── 6220cbae24649658589df4036b77e92fdc268c2f.nq.gz
    ├── 63567b747f5643ef1845230217baff3c57e4605f.nq.gz
    ├── 63b23fb303d27890b74841ef3b896103ae3ff461.nq.gz
    ├── 64708a5a74f65b8d86343b60001ac988f486ce6f.nq.gz
    ├── 65481f9f0da69b7c3c41ea387f93681ff7a2b879.nq.gz
    ├── 65a1dc0b45c4456db689f8863a90ff9e3221f075.nq.gz
    ├── 670f7d407a39d28d4e02bad55ef9b78a5d8f0253.nq.gz
    ├── 6aab56c9c8031040480334bdc1176752bfa9648a.nq.gz
    ├── 6abeeb52c45dfbebc70a534af9ed30660d4a8a23.nq.gz
    ├── 6ad87ab455b1186335e90c50411bcb693c77c1a5.nq.gz
    ├── 6b9a8cbeb143eb33984788bd0449bd17669a2001.nq.gz
    ├── 6b9f5852e6294a9312ac5a143bdcdad9a30b25aa.nq.gz
    ├── 6be2e2007ae0f7de4e3001efae7e9ddd7a028649.nq.gz
    ├── 6c981935f4adb4491f2e20dd1ff22e60799ceb1f.nq.gz
    └── 6c99ec6e9f6ae323dcfb7c6a5dab4b96f7ad30fa.nq.gz

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

[scipy/scipy-stubs](https://github.com/scipy/scipy-stubs)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
