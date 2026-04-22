# Repolex Knowledge Graph of socketry/async

RDF knowledge graph data for [socketry/async](https://github.com/socketry/async), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download socketry/async
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 886d62cafe3d49c8b96111a3bce666ab3c5f17bc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 886d62cafe3d49c8b96111a3bce666ab3c5f17bc.nq.gz
│   └── repolex
│       └── 886d62cafe3d49c8b96111a3bce666ab3c5f17bc
│           └── chunk-001.nq.gz
├── blob
│   ├── 0261013754127e3a7c43b0b49ff1e2e92caf0a04.nq.gz
│   ├── 0499ac89049e5b14aea1b46c8fb54000611226af.nq.gz
│   ├── 04eebd35e550cf9add61966bcad9bf3162609796.nq.gz
│   ├── 06d71c1856867321fe7eafa03782e3dd851c341e.nq.gz
│   ├── 08cd5c98c14c0c511ca071bc424c4583eef8273f.nq.gz
│   ├── 0eeddecf030c206baa9ed9f315f931a446d61ae9.nq.gz
│   ├── 0ef6ce8dfa57e647fb7b1c7495cee280c9dd9709.nq.gz
│   ├── 0f59f1e2486867a8cee1aac45194b8f34155b717.nq.gz
│   ├── 0f5ddb377de3dc3740c416d82f61aacf3c756c35.nq.gz
│   ├── 13137f40eec8fe32117cffb8b5c1da5a251200f6.nq.gz
│   ├── 13cc87be60ee905437361ba8988d502b2f2c7206.nq.gz
│   ├── 164b64ac17a49e9ec92432921ed23a11aa6f4623.nq.gz
│   ├── 1799c52d9fdb6d256181f900dde51cc2372c722b.nq.gz
│   ├── 18ab1193b4d6e52ff051bf438014a8adc14efa48.nq.gz
│   ├── 1986d52fc73afc7696de3a7d8923608fb430dfa0.nq.gz
│   ├── 19e7737faeb15ce1fc7fbe53511793a39b77ff14.nq.gz
│   ├── 1b518ed2a43aaac4ca7362622dee3871b3326326.nq.gz
│   ├── 1d2df40678dddc06739bdfc9e27bce9b69e634a6.nq.gz
│   ├── 1d3ff016ebfc9c2d69d8f80db9f0c3bc7904b721.nq.gz
│   ├── 1de68b2132c5dd8c46e8ca43d528a88b55423f8c.nq.gz
│   ├── 235f86c6e1bd243303d45bcd0c02c9bf6b0b7f59.nq.gz
│   ├── 2443360afd5f26dc0ed015ffb288225949ef1e01.nq.gz
│   ├── 2524693dd04b8294b28a3dcd2750d077786408b5.nq.gz
│   ├── 26c073dc05e25f6bd53698b1864fdfe804d5ff88.nq.gz
│   ├── 2942ac9775fefe99db658710b76a231de09ae3b5.nq.gz
│   ├── 301595f67f8e982286a99df1480c2a1b851d7080.nq.gz
│   ├── 3118db3046aa96bd70261fc341ec78af1359a3ef.nq.gz
│   ├── 3392863b8ab00e0f67c73bfa1c1d159d1ffbc225.nq.gz
│   ├── 33ca46aef9bc8c240f127b514790b887674ce238.nq.gz
│   ├── 35dfa7d1ff2394294a3b9b932eebefd87517945a.nq.gz
│   ├── 381032546afb63e6e7c126d5c183f848871d63b4.nq.gz
│   ├── 3913f4219fe73c5e06b9c29f64b516540110b1fc.nq.gz
│   ├── 3a7389dd9f531b3139f727f544cc08daf939af35.nq.gz
│   ├── 3be8efaa25ff88f9fa10b53cbb04aca38d8be884.nq.gz
│   ├── 3bf3db5ff85b54a70e441f537fb7818e194fc1d4.nq.gz
│   ├── 3e76338e179a02b41ea72794771d3caa35c002be.nq.gz
│   ├── 3ed26ba5966b9df4e24a859916cca31f023dd873.nq.gz
│   ├── 3fa12a8c6d45d0219f9f3aed4f40b244e8e55f96.nq.gz
│   ├── 40553bfb738e001d9c8b1831de1d2cf626566704.nq.gz
│   ├── 412aeeefb22ba1f722519eea8ee2641a9ac3a095.nq.gz
│   ├── 4144100988282b5cff96b78924a65959e24b9d64.nq.gz
│   ├── 42885389ebab09cf2dd6ad078688d5e42765860a.nq.gz
│   ├── 43ae7029c1d0dd6248d964efff23b70280653c8b.nq.gz
│   ├── 469b6ee0a4b12f70411530b4522beb572fbe8952.nq.gz
│   ├── 46c41c965272d24fd6516264e75a9d3d34e3411c.nq.gz
│   ├── 4818ff06035e03f32e490521d7837a7b30fac400.nq.gz
│   ├── 482744c7c3b9e5a047106d0036442e2e8af7e8a5.nq.gz
│   ├── 48f7ff9269004b0d1e9b5ef1feae4d7398dcb0d8.nq.gz
│   ├── 4a27fcdaf350af7434d785b4601f71a233888273.nq.gz
│   ├── 4bca387e031352fa2ff38d0535aeae6694f3f0e5.nq.gz
│   ├── 4d8227a7abacb1935eb34ff72e74bb1e48e528f4.nq.gz
│   ├── 508bacff997daad1e1138cf4be6ee7e2417f544c.nq.gz
│   ├── 527cc0cb2d4d1c823a837e372218273257d9b0c4.nq.gz
│   ├── 53ebbcf4fb000772a0fb465c8cd30558cad77757.nq.gz
│   ├── 54c93910f6a49ab10a00c937d0f21e7184749dcb.nq.gz
│   ├── 55e3983e5fe4c7f198c6f1b40c6b5eeb1e5fc0eb.nq.gz
│   ├── 57072a9d914077eb2561b8b291eab3ad06c9a25b.nq.gz
│   ├── 57c8779f9fe84151214e2d4662b550e25a70009f.nq.gz
│   ├── 586c0b2c25cfdfb5abf5f933b303e9ca05216103.nq.gz
│   ├── 5bbbf21ced8ed9bb94f3c5477a4aa3eb9067dc5d.nq.gz
│   ├── 5bc55a1fdc9e01ab017a183c6d0e5c919668ca72.nq.gz
│   ├── 5c4df367c7cefb768979c570b8a50425da7a3dfe.nq.gz
│   ├── 5ceae32a31dcdf7f704f1398559e5d7d67207cc4.nq.gz
│   ├── 5d0bf36ab0c325101b7d6cbd33871e1833292e78.nq.gz
│   ├── 5e7b15cf24e9025905314c8a3d021a09050a47ff.nq.gz
│   ├── 60ecd353efee6a4f3bcd50616191ebfaceac7ab5.nq.gz
│   ├── 61863e145af3f5e9c6e78fa086fbd8ec3c2f809d.nq.gz
│   ├── 627af83629b8faf7089298b996974fd5c0350e9e.nq.gz
│   ├── 681df1608000d0db8fd8280b978e9a51ca1bd34e.nq.gz
│   ├── 68cc8bd14681d07b8effe5a8f779c9ae045cf827.nq.gz
│   ├── 695ec6242b85b015c9b1ed84847a707b7f5fb52c.nq.gz
│   ├── 6a6e31966a5a1ef62e7f5c8ed95f8847f8b5208c.nq.gz
│   ├── 6ab9aca40b6f3c133fa8ea2f6abde2b5138f94a5.nq.gz
│   ├── 6b8a7294dc00d055f481d2d2f1b48b0e8d7304f5.nq.gz
│   ├── 6d2b23fa4784335f18704c6064be1bf33b8d3f42.nq.gz
│   ├── 6daf9733c4e7868c7e04f8cc618ada5b81403c84.nq.gz
│   ├── 707ed2a8f0232f3d3dbb9190ba0b1081ac9e3184.nq.gz
│   ├── 71bb30cf0f69797b1d59a720847016ab411e9141.nq.gz
│   ├── 72a19cf5e9c9d29c8805bd5f8a0dcd35d93fa2d0.nq.gz
│   ├── 73996897365e0ccadd86eb18b3857f770486ca49.nq.gz
│   ├── 757174361665ce0daa4d160afd56d6120527b15a.nq.gz
│   ├── 7661c4e95256bf14856a744b0432b1cb11952ca0.nq.gz
│   ├── 7781f95827a15f3cae713133043258768cdc044d.nq.gz
│   ├── 77a7c1bcb4fc328d79f7993ab08b1c3217c10de5.nq.gz
│   ├── 79f3bf12bb9db13c45c23a8b52bcd8dabd7c2e89.nq.gz
│   ├── 7a55acaabd5f45f69fcb8f6f4f9834e94d22c9a8.nq.gz
│   ├── 7a5bb2e498650d2c6f49349996b8382cc8f463fb.nq.gz
│   ├── 7d896fc2f4efb8b52fbfd3412deee877d4bdcc35.nq.gz
│   ├── 80289605de9ddda30e70b41c4183efc07e1372e4.nq.gz
│   ├── 80ceb5e03d2e6ddc60a16923bd6e1b9125068034.nq.gz
│   ├── 80d39faed1c5d1cf18e7710b9676afff72f9ed47.nq.gz
│   ├── 8191319a0f72d516f005337118d807050b40606d.nq.gz
│   ├── 82adc960b5439faf5b4d58f4a817e6114a7a2ba6.nq.gz
│   ├── 841c79e4beada4cfd7751ad4ab941d7b6fba282d.nq.gz
│   ├── 846bb975baaa6e6072ee2fec6125843c472baf3b.nq.gz
│   ├── 860c697c19df4313097e9699659d84cbf8492f04.nq.gz
│   ├── 88519126c92da1580cf3da619060130c300b7e3b.nq.gz
│   ├── 88541e587815c67acad0ee3e28a09810c066f09d.nq.gz
│   ├── 9203e0e299dc39c29595c97be74fcaeb8aa05657.nq.gz
│   ├── 930a70dfc91782359e19d2f5b2772b96d5a57086.nq.gz
│   ├── 936fcfb09c0be4512fb538a2edfe3bac39b4bf69.nq.gz
│   ├── 93a5817044374b1ac30d16ad702aed7f7f4cea55.nq.gz
│   ├── 93d13ff9cdfa38eaf4295892a64e70af832ec9ee.nq.gz
│   ├── 9602998fa676e6c1bf477c5aa9123a01eb85bc08.nq.gz
│   ├── 966bc13863b0e08018e1c19c6fa9385d97905ce0.nq.gz
│   ├── 9893e26cec4a29d4ecda50c665a115f15b5bb70e.nq.gz
│   ├── 9c2e16995483de1c03d615a4d35e8330e17abc5f.nq.gz
│   ├── 9c319b7c2d8d0e82fe8f9b7f7fae3a83d6cb9182.nq.gz
│   ├── 9e59d8a80953597de0f2b483b7114f5e12fe6873.nq.gz
│   ├── 9ec63e2fcc78a03a3c274264856aa0d15d270672.nq.gz
│   ├── a09c06c94904c727fbd88b574e5abf570beaa23f.nq.gz
│   ├── a27528ac3aa88077b5ca605b1b42ace5f4541d17.nq.gz
│   ├── a4252d48a416b79449dce9606fe035f18c60a5a6.nq.gz
│   ├── a6e7d262430919a9468c27ef7f42e55a3eeba67d.nq.gz
│   ├── a72314d619ba549ad77724ca563ce3da20edf586.nq.gz
│   ├── a9cb7f066c88525b392bdd6ac051bddb217d30bc.nq.gz
│   ├── ac5ca66ae153891e4fe96a2c4d7e48f39e705ba5.nq.gz
│   ├── acea3d6eddfa8a81cc2cd84be291ddc7b5195da1.nq.gz
│   ├── ae634a78aa01920d7d8cea96d6426110d479fd59.nq.gz
│   ├── b0d38a33aaa5a04d80670726b06a75f69b794d20.nq.gz
│   ├── b12af8d143bfcf302f9711c7865af2f838bde235.nq.gz
│   ├── b63d633674ce91df17af0056370c69af5682811a.nq.gz
│   ├── b895189c9ccd3257dba4f06be6bde8c506935c57.nq.gz
│   ├── b8cdfd9ae2edacdea0b5dabe5ce3f5085efa036b.nq.gz
│   ├── b9bf9a5a521ff08aa39ff6eab2c83cd0a11971ae.nq.gz
│   ├── ba4de7073361d4c13278ff402da3e9c81ec1aff0.nq.gz
│   ├── bba9420861f72210004c454446240d3faf7f6e1c.nq.gz
│   ├── bef02252513f7fe62af961a60d49ecebc2d80726.nq.gz
│   ├── bfb7b9779f82f5319a25ad72e1b92634e960b328.nq.gz
│   ├── c0c4d86e65aaab19739c406479b4e49ca482e97e.nq.gz
│   ├── c14bbce4335514d8f1bb55d6ed8fdbbf4e7d2aeb.nq.gz
│   ├── c33821c815bccc7dc8b570b4ae847a396ef51288.nq.gz
│   ├── c35db36b6c328df1924facf50f7a216747bc3331.nq.gz
│   ├── c4131501eb1a254698121db6d11c9d58aa0ed7b8.nq.gz
│   ├── c501bbf8ed99896b5ef6aa33a20662e38b168e74.nq.gz
│   ├── c595997421366e24ef4f409c3240a9323cb78609.nq.gz
│   ├── c8d423fbebcc53639f54e53f02d3b990666c43c3.nq.gz
│   ├── cf307ab8f48df42efdffbdc25b7a843b08a8528e.nq.gz
│   ├── d06b3bdbf8198d06a1f919c65a164fd9a98d93f2.nq.gz
│   ├── d14b0267596fd5e7a2801c0248059a1ebcb17150.nq.gz
│   ├── d2bcf4649c7830e9a06fab6001d347b38086bde0.nq.gz
│   ├── d33288b9436fd93b8b98b3e07fdc02fc6ae78eb1.nq.gz
│   ├── d88abf3068b21dbf7e421368c098c94574ec32b9.nq.gz
│   ├── d8a8760fea2af6791a6dcf68744abe6aadf0f02c.nq.gz
│   ├── d8dfb16b36a4cc87501425343fb54531edb8bdfb.nq.gz
│   ├── d98e595fc6f3b8b88f2d1b49c1ddec4bbefbb896.nq.gz
│   ├── da60e9ef530b587f7f34b6720192b332b3cafaad.nq.gz
│   ├── db80b6174f3ea565a96ce75237c174185df44e48.nq.gz
│   ├── db8ba11d84839f877c1ba73c68eb47ef45d600c5.nq.gz
│   ├── dec6beb09b11cba707fa0a217a2a9dd1a9d60f39.nq.gz
│   ├── dfe2e19e74c66f3ad8a23764aeeea14d73596964.nq.gz
│   ├── e1a85a7783ac082872f5fc0c6087a2d0196390df.nq.gz
│   ├── e3f3a22a6510899088716237c1e462b973d691b0.nq.gz
│   ├── e4bc8a078a5c4cad03e722bfaef4c0ea624cd304.nq.gz
│   ├── e71f9453989186b90b59324fb9c159bec289a678.nq.gz
│   ├── e91d97cb7875d1195593584d3fceabd662207e97.nq.gz
│   ├── eb763e0cc58698c8a93ea8ce20bbeac5d8a36893.nq.gz
│   ├── ebec0662493a1a00a5e5ddb94b012d917b94f4fa.nq.gz
│   ├── ecaeb1a4611f3eeed4c4ce03806d22e30a46dd5b.nq.gz
│   ├── ece5fef8e4f10b2d4c487d6813ca4a3fe8ae11f0.nq.gz
│   ├── ee82a6f2bf140d07d3ffddf77add5e0dd209878f.nq.gz
│   ├── ef1d44f73ee3da514b779ea0ab6d61ddb6f45fe5.nq.gz
│   ├── efe4a5030a6af241bf7dc05bcfeca1b2293f76e9.nq.gz
│   ├── f1f66522e82a882e2b0c275d17c1e061f6421233.nq.gz
│   ├── f22d7c77552fd7601cce8747ac154fd2fd6eb6fc.nq.gz
│   ├── f6d11c368636303a680aa6cc9bf863b660ca92db.nq.gz
│   ├── f9eec78ce6901fe54f050d8f222cffcb58c774d9.nq.gz
│   └── fc1725b8e518804feeb32c13765109091bc38d0a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 886d62cafe3d49c8b96111a3bce666ab3c5f17bc.nq.gz
├── filetree
│   └── 886d62cafe3d49c8b96111a3bce666ab3c5f17bc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 178 files
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

## Source repository

[socketry/async](https://github.com/socketry/async)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
