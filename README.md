# Repolex Knowledge Graph of foundweekends/giter8

RDF knowledge graph data for [foundweekends/giter8](https://github.com/foundweekends/giter8), parsed by [repolex](https://repolex.ai).

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
rlex download foundweekends/giter8
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c2612983949cc5d60c1eae5f439dd448e73d1cc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1c2612983949cc5d60c1eae5f439dd448e73d1cc
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ba622b243e2cb0b966c3a59d1c140e71c7f26a.nq.gz
│   ├── 02ac4c18a523525fe4d6ee2ea7179a649d00e06b.nq.gz
│   ├── 049c650b49a9dfb7d70ae38517043239e417f354.nq.gz
│   ├── 054bd9fe6d69f2d0c976d63c42e121ac0075bf27.nq.gz
│   ├── 05cd145b8481b86424947ef4e500f78ee5961bb5.nq.gz
│   ├── 073c402117d2f9cfb8dbd507899abf03dcdc6848.nq.gz
│   ├── 0ac013abc7370568839eff5825656f01e4cf4d24.nq.gz
│   ├── 0b95dff6b7d63eb249680c3d6437e1084a178a16.nq.gz
│   ├── 0c9c6178a58679552449b0ce40053fbfc3902ea4.nq.gz
│   ├── 0e0b561c1512d345187adc1c477d161793f0a921.nq.gz
│   ├── 107459b2a5e5a3c941ec1cb48e02df6d2748b246.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 12bc0d180a55f0cc744844deeb73011d880e4209.nq.gz
│   ├── 1436ef6fd82854211c4a49682fa66bb5f211c5ca.nq.gz
│   ├── 14c67eb66501d5ac08fd1e06dc80ad86af0025ae.nq.gz
│   ├── 180ad557fc573e3efe3f546b7c39edfbad9bf978.nq.gz
│   ├── 196feee44575b49e03d46fd2fd087d94ff111eec.nq.gz
│   ├── 1979e08661465f0f1f7be13e396b5d4d543bbb81.nq.gz
│   ├── 1b9e362685225fe3fec84bbca7290d2fc32c0a33.nq.gz
│   ├── 208b561d389e91b38bce3e3516a70dded9aad377.nq.gz
│   ├── 216dd51c2d69454735532224e859f84f6f0df074.nq.gz
│   ├── 291650388c28d8190fc31b635806706a0683f004.nq.gz
│   ├── 2affe1b50e89f3a70c27e528d1c00e664ea30102.nq.gz
│   ├── 2b4b196baa0df5671d507ec28cb5496b4d4869a5.nq.gz
│   ├── 2b6a51e7bfb457ded63d8421a64ad0fb671e01cf.nq.gz
│   ├── 2bd010d6d8537cf8b0f384fb225b96aaf0c4f89e.nq.gz
│   ├── 2cc927386511a03cd1cc449a68334872874638b0.nq.gz
│   ├── 2e0957e6f5c2958cc3680527a7b579f5bbf3d2d7.nq.gz
│   ├── 2f5ca5503794748078a579ce8d319f3d7eefcd4a.nq.gz
│   ├── 30144adc0857d3515abc4b59c530f86c3a13a769.nq.gz
│   ├── 30ae8c4edd3ded22af96014d5f9bbae2910cfb30.nq.gz
│   ├── 31a9745e0739ddd68d603cd9f9fd5d573f18651a.nq.gz
│   ├── 334b7e9455cd77c643cb44e1574b2dde02ee28b5.nq.gz
│   ├── 33b745e34f298a8b80c590248eba4b8f2cd98fa6.nq.gz
│   ├── 341ffd9790cdeb52a96b2c3fd2d34645b8f87015.nq.gz
│   ├── 3447823a6b16a437dd5ae8bbe002a466ae0be950.nq.gz
│   ├── 38aef0547576c3df5574961f13509c6f5d69a81e.nq.gz
│   ├── 3a5abdf44b3073c6a7a83706b5a560ced6c8da3d.nq.gz
│   ├── 3c56ffac58b0033ab6e3b47aec837d8d5cf2d748.nq.gz
│   ├── 3c7355ceec348bd81ff8abbf2e2c6f26e96e67b6.nq.gz
│   ├── 4122cda06dff1c8cf789b03eb2e73f2e195ca4db.nq.gz
│   ├── 436b372c4a748531009c9d756d99c2e8211b4ed1.nq.gz
│   ├── 4431605d6a491c44e15b2ade837fe486559e0935.nq.gz
│   ├── 452072266eec35205500924e1fa28a5ab84dcb51.nq.gz
│   ├── 4629bc153c8ca29729d0bc6b6f9aecaf3a467291.nq.gz
│   ├── 48a28866ebdeb427bf1a118592ec5ad8e8b519f6.nq.gz
│   ├── 492a84c266e32f42e0df6b2936c4633ee1042803.nq.gz
│   ├── 49eb3198692480b79cfbcb090aa94919da37f274.nq.gz
│   ├── 4d6dc05c115c2a8a9e6fbd9a835f707a527642a2.nq.gz
│   ├── 512fa2309f62db669f07ee70916073059092a291.nq.gz
│   ├── 5304128c9ae28a6fc5ad37004acda574b604827a.nq.gz
│   ├── 53a6d18e440ac2294f3fd42ced541aa40f448d9b.nq.gz
│   ├── 555cd73dc65a6da8f964ed8cfd590349f567b6a3.nq.gz
│   ├── 563c06a3b3811f61fcd9fbfd865df9426444eaf9.nq.gz
│   ├── 571a3c54adf449ff97ce79d157c514bc9aaf9203.nq.gz
│   ├── 5da1f8030a6451fd2e36d4717513c7e1ce5f47a2.nq.gz
│   ├── 62b7452cda41825b2ac19eb8f58d15d330594c3e.nq.gz
│   ├── 62ea636c177f49af4c0909e08d8a15b00ab10034.nq.gz
│   ├── 643bb0030114282dacf50beb26c109ec0d6bee18.nq.gz
│   ├── 66ea014187d68fdca209a1014138444f4692a70c.nq.gz
│   ├── 67f00b5dc91652bf5e551ed6eb6c0c17186889b5.nq.gz
│   ├── 67f58d9ec58d807fba03d4feb2b8c221811a1f98.nq.gz
│   ├── 6b13aa9531e469bfb6886e8de7c8d8b7d4d12923.nq.gz
│   ├── 6ccc811b9418c9146fee9fc7727ae959dd8c923c.nq.gz
│   ├── 6f2f450ea8b78d5777f06279e670ad7cdb223d97.nq.gz
│   ├── 7009bd0977ae2446b35601f274ef8708b100bc13.nq.gz
│   ├── 70c2af95fb7d63d566c9644b03f22825529c579f.nq.gz
│   ├── 74fba2d3816fe0451d3deddfdb37928ed927f339.nq.gz
│   ├── 76f7bd4999f7a2ef6f072b5faefca8f64767c97d.nq.gz
│   ├── 789853aff45e180755e0bc584b38d1f21797776b.nq.gz
│   ├── 78995cac01d546c87641277c4295b10535c9238a.nq.gz
│   ├── 7950afb45db7257abc500ffd8dcab959f0f26884.nq.gz
│   ├── 7c460429f540a2e1264b02b3c20313b5a35d9437.nq.gz
│   ├── 7d9d09de1567d2081ffc6eb8f5e141a4e69a7893.nq.gz
│   ├── 7fb4087272a04579b7f10d9a87bc331aa60fa37f.nq.gz
│   ├── 7fbe240d21f898070c832b2fe73a20a6b9385b25.nq.gz
│   ├── 81d1eba8f3a71c0b378200962a6ca57e96479b87.nq.gz
│   ├── 838001ea3e1ea2ec65500e67f73e4446777fe67f.nq.gz
│   ├── 8438cccfa52a320272c4ec266124657d87e16419.nq.gz
│   ├── 84de6504c9c18755b6fd607b7047955564af7835.nq.gz
│   ├── 87ae885bc033a6eb443d4f0dfd2f777d25dc4b98.nq.gz
│   ├── 8829d14e2e2139e207051a91a77921aee4f64c49.nq.gz
│   ├── 89a2f07368017c6b96ccb6ad3a16329519c49c06.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8d16871b23b04bfbd30c144424a6b38ef64cc438.nq.gz
│   ├── 8d592e395889503a54c55ea1bd04fc3f16794a3a.nq.gz
│   ├── 8ea8966d38d70f188b44abe0c375d3f93afb9915.nq.gz
│   ├── 90f7068118d44a71f945636e767a5a35c0aa55d7.nq.gz
│   ├── 91b53168f0d0204b23d4670a9b3d30f5d4e5a5cf.nq.gz
│   ├── 91baf82a486aab0e6f437ea0785e800b747714b8.nq.gz
│   ├── 947c002754f1a2e411c2d76f8e0914ff06699282.nq.gz
│   ├── 95a78b275bcbde815f02a723fa11a516176fb769.nq.gz
│   ├── 9a3c4046c35eb36e89a230891606c2a41b5f4a4f.nq.gz
│   ├── 9c041b64d94ce8ac9f8364fa583cc54d38762939.nq.gz
│   ├── 9c354693b8e343566b214d6f76a3ee5b9783d68d.nq.gz
│   ├── 9c3ecf05c0e33ec944baea869e5d9432f7cf9fdc.nq.gz
│   ├── 9e97addafa418ae4e441933fb52a1ead216e8d2b.nq.gz
│   ├── a2077c78e590619a76855e528991af4cf159034e.nq.gz
│   ├── a484b774aea1994826b2407850c3dfd1571e44a8.nq.gz
│   ├── a62941bdd54932cc96b82bc452247858e0211a7b.nq.gz
│   ├── a84cfbadb8a8f2731a3b09bb23f5840787748c2b.nq.gz
│   ├── ab777f32315a8f8f44de075db63fd9d976f091dd.nq.gz
│   ├── ac1841812b2b0b21a20c3a090a4dd12107511107.nq.gz
│   ├── ac5aa6419e06040ee1ef562c6168596dd8981e01.nq.gz
│   ├── ae10c85b7ed795c558b110b613d07cbed656f9f2.nq.gz
│   ├── aef30bd3f6ba004d2ae1d3d1cba82873bc0a07a7.nq.gz
│   ├── b014678271bd0171acc27231f68cd098655a5612.nq.gz
│   ├── b28796f14ba3fc8e588fc3084dd5d7953e79eb7a.nq.gz
│   ├── b499883baa9f1c5b2c3a1359c0b3bdfdff0d77b8.nq.gz
│   ├── b57aad687ef4cf56e828fd1303d1a8ad82cd916e.nq.gz
│   ├── b6497a3ed59af3ac51bb01ce2ab5d1869b544689.nq.gz
│   ├── b6fbe6b998c261ef90eb66cc86f888dcf83b2776.nq.gz
│   ├── bc2617e379e8b760c4a8b9b86d3620bb39e17e4c.nq.gz
│   ├── be50cc8ec6cefd78a73a8ab3a61696655c91171f.nq.gz
│   ├── bef6c605b8aee40cb5493a816d0cd3635fb83312.nq.gz
│   ├── c40d4df5812b86fb2be98c2250cd8ea96e7599ba.nq.gz
│   ├── c5229b4e94f24f34ae762eb0e9b58b10f6856f8c.nq.gz
│   ├── c589cf7576be9e03a8d67a8e26910a6c15f15b80.nq.gz
│   ├── c650309631567a1dcd7a60205ca0689e54fe6e03.nq.gz
│   ├── c760e5a7a771ae33623fb332e24551ac12df442d.nq.gz
│   ├── ca6c06c1fdda14ef05e357a9d29ebbef59d4b7f4.nq.gz
│   ├── cb743e579aa93df4bef819b7fc4a72bdf3809b8a.nq.gz
│   ├── cba9fd95abeb46e44b298a5939807265bf5cc483.nq.gz
│   ├── d1f0c9b868168bc29eccc5c5cc62b5c28d3cd10d.nq.gz
│   ├── d2a423d576e175d6abc32e542b2d631704c9e04c.nq.gz
│   ├── d3d9f653008dbe41710b5eb506f7cba172af68ee.nq.gz
│   ├── d4287112c6afb76c00419432dbc7aa79945f09ee.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d91526f91d524691f42b16fcdc3954fdf38192a7.nq.gz
│   ├── d9e18b0df5e0b2d41eba5e6933a3dfd515f48137.nq.gz
│   ├── db409aa3393972e2c3567092ac8e73f7db5bcb81.nq.gz
│   ├── dcac7759cbf6e9e263e3ea20fae9a4ad1075f901.nq.gz
│   ├── dd45e01c3a2eb4a08e238d316614be17b59bf156.nq.gz
│   ├── dd539b30648ae4e2242a1207ea40d29689bf48e6.nq.gz
│   ├── dfe9e375260775c34de657a13f361defb70b96cc.nq.gz
│   ├── e26cfbd392490c23334b4487a3e11051d2c3f239.nq.gz
│   ├── e42d68b3f3d0bb5cca1ffbff3e4f87b9bd561b02.nq.gz
│   ├── e656ba021c554c7d0cf1c0c528df352bd9172d0e.nq.gz
│   ├── e67b81a64761714d63ade7f2b561d7d2eb8a5f7f.nq.gz
│   ├── e6c4465ffa352067b5dc24e03169ca6e382d5d83.nq.gz
│   ├── e84d94ea56429dc00bf77e4917437678bbc3047e.nq.gz
│   ├── eb862812685222c14c7b0a2af7ee12379adf473b.nq.gz
│   ├── ec28eaa96cde4fe4e2d7e753a907eac3b15f7c21.nq.gz
│   ├── ec52078e0115eb493e2b826f9cf5947c18d8d43a.nq.gz
│   ├── f077f286f51828f25848a5f73d5e5c1645f46e35.nq.gz
│   ├── f320bbaa19b52893f4693713564ee4703e924ba3.nq.gz
│   ├── f5dbebcf81acccc2c6ca6280ed29e1d459c3e6b1.nq.gz
│   ├── f8be2301e6dca8afa2e8f33a72e2684728bcbc11.nq.gz
│   ├── f8c069d0b0b58db1c278980cb8317f9dfb6fc5fa.nq.gz
│   ├── fbdf43305b6ecdbb6df7a62284923e4304e80871.nq.gz
│   └── fd3653569cc8a2e385f6d20402f46156a54b3206.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1c2612983949cc5d60c1eae5f439dd448e73d1cc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 159 files
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

[foundweekends/giter8](https://github.com/foundweekends/giter8)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
