# Repolex Knowledge Graph of haotian-liu/LLaVA

RDF knowledge graph data for [haotian-liu/LLaVA](https://github.com/haotian-liu/LLaVA), parsed by [repolex](https://repolex.ai).

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
rlex download haotian-liu/LLaVA
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c121f0432da27facab705978f83c4ada465e46fd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c121f0432da27facab705978f83c4ada465e46fd
│           └── chunk-001.nq.gz
├── blob
│   ├── 0008e5e7cf52e99d85388ef7f0f77d76940c8cef.nq.gz
│   ├── 00c56867dd1fd88094df9556f3d1c57e71a7ada8.nq.gz
│   ├── 02a8c6d8dda4f5ac338983251adcdc1d3a99a3f3.nq.gz
│   ├── 02e5237ece031af23fcd76b5b4e0d9b0bc5f55cc.nq.gz
│   ├── 035e14937b3b57125ac54463770dfda25fbff6bf.nq.gz
│   ├── 04f47a91a74af9ba5686107fb6a4441117494a56.nq.gz
│   ├── 05f67b33a73e17c683dbf9c09f84bacd10f285f5.nq.gz
│   ├── 06160f2422b5368f30fb967f7cae635208a1dc69.nq.gz
│   ├── 063f3f13e119fdb7f6af358f50315e022f15f578.nq.gz
│   ├── 069d0d1c10da42f5d278598e8534f166d1f9f5ff.nq.gz
│   ├── 0bb1a99f24c94b7d2f5c8f8b6c5c8a071d16006e.nq.gz
│   ├── 0def682ea3c497e36aa85f1c53eb2cfab6e2fb87.nq.gz
│   ├── 0f796a3880341739677a5fe3bfbcc90515a0f324.nq.gz
│   ├── 12311c3ccc3511446298c8e829216266e702ec16.nq.gz
│   ├── 1300cd49992d8c342396cebfebc592909d6391e4.nq.gz
│   ├── 1561785e4e3c6ff5ecd9e75f27051a6a13817cd7.nq.gz
│   ├── 16cf35ce1b77834d9d8888d53e6cd0f7c2c4ccc6.nq.gz
│   ├── 1e324210e229eeba23b75791bba82df7c6e639eb.nq.gz
│   ├── 2065dfb20a6e40128749d507ecc27d01349e2ad9.nq.gz
│   ├── 214754bf2f206c2d95ff744429d49420e2745d19.nq.gz
│   ├── 23a59bf4ee0f365de9fbf3838836b170058126d6.nq.gz
│   ├── 24b0fffcc11a2045dfc7f5ac6cae4f057aaba6d6.nq.gz
│   ├── 25367e95edb6a30db6627c7993b99d8c7e526a07.nq.gz
│   ├── 2563f89c6cedf5e73508afec8f9979105df9b745.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26c7f4e0819bf0bafbace898f5f5a4f052490aa4.nq.gz
│   ├── 26fe3002413a23b5029e540c8b338ebb14307bf6.nq.gz
│   ├── 2754fa66d04134530bb47e6ed2df2440cfe6411e.nq.gz
│   ├── 27555554a960866d6571767db2437cfb4fd95ba4.nq.gz
│   ├── 27baec12f9ef48d4e3df41e15b1d2644aab4174b.nq.gz
│   ├── 281afe2f7f3581fba766a9ca1da2c1bce60c5178.nq.gz
│   ├── 29ea06170f23a845627c7e3dd52d3a5bdb379767.nq.gz
│   ├── 29f63a26d5a4485a64bf235391d0f7593a96f3b6.nq.gz
│   ├── 2c2c40295e0351f25709ba25554c9329f15bf0d2.nq.gz
│   ├── 2c81415cd0f4ebbbe66385450236c427f5e8fb02.nq.gz
│   ├── 2d870e6c0b8e97dc08d4e1b6a2d4ca0af9185ee1.nq.gz
│   ├── 2e254da152ac644ff54fb5fa57e625d9e6ba31d1.nq.gz
│   ├── 2f424d7b13c327e051d8c3312a0b620878fd7e4e.nq.gz
│   ├── 3139b31b27e6e67b31b27cf0ac7bda317f46d6b8.nq.gz
│   ├── 31cd4f48e6055cd6d00a162af30b1c8139e26b57.nq.gz
│   ├── 31db2eff8d1c4b3ae645583dfc5e156e818b6f1c.nq.gz
│   ├── 355ab81ffa1a73e874f3a8fb85d2742896068d08.nq.gz
│   ├── 358155c384a2d18e6927d62562ac3f12eef36a87.nq.gz
│   ├── 374be090510b302de9882d880c755787a8eafe11.nq.gz
│   ├── 3a0099656bc17e996c3700ce36926796693ba045.nq.gz
│   ├── 3b39cc7beb12301379af7daebbb5553fa92093ea.nq.gz
│   ├── 3bee468d34515fdcbef1a8b8803c9fc4f7dc0b34.nq.gz
│   ├── 3ed50288c31c118cab22312ad02a559d45725490.nq.gz
│   ├── 4006cf917e26c365080b0844c56fab78c48457c0.nq.gz
│   ├── 4018fb008ffa2ad0a8ff8c28ce6729d77076c3bf.nq.gz
│   ├── 435448394dfcef578ac478f499160fba4ceacd6c.nq.gz
│   ├── 45be31e896e9c087093bd9bcb6d355ec6dfd11ab.nq.gz
│   ├── 468f4bb120448a036bd5b5c7955464fe2e13892a.nq.gz
│   ├── 46b8e029bbb02ccaf8cae1a7025867553fbd6c6c.nq.gz
│   ├── 477c668b62a30da69a6efc630c736fe319970bae.nq.gz
│   ├── 497a702ab5efb88b8f67333eae81645eecea78cd.nq.gz
│   ├── 4ae55d59c2c8bab80299272314a41bbeb959d8ed.nq.gz
│   ├── 4b71e3d5618a262e4746f58e5d10947b73370dca.nq.gz
│   ├── 4bc49735c0c8f6eebb498b7ff8cb93262e1cd5cc.nq.gz
│   ├── 4cf3a49c16e1113f4d941b409bb9c7bea6c90fe0.nq.gz
│   ├── 4d1f016db1028101d45ba7d68cb3f0bcb558c2bb.nq.gz
│   ├── 4d46c8b876df618faac548e9b369109d541f4f23.nq.gz
│   ├── 525bd43b850e9f6a923158abd23bca6f8d15650e.nq.gz
│   ├── 5462cde720b76950382f4f83eb14d08ac438edaa.nq.gz
│   ├── 55b739fd437a1897c1c1ec001f47aac2fbfdf68b.nq.gz
│   ├── 565e54d1d4d35791d5ed22ad4e60c43fbdd877ed.nq.gz
│   ├── 567428adb29c03dd83c1f08be6b4e972af453630.nq.gz
│   ├── 56881c770ec5aca56bc2bf6c38cb6101ae58fa24.nq.gz
│   ├── 568a381ae2b302f4163eecb87f6cda75734f1ac2.nq.gz
│   ├── 59a0d4aa4d8f391c5b5e62452c4e9ef38934b4a9.nq.gz
│   ├── 5b32cb501799175e3829f92b014795ad1cbee79d.nq.gz
│   ├── 5c3c2c31fc35377a926739e8e4bfd4c23fb39e7f.nq.gz
│   ├── 5ecb30d5654b6a3f7162bcc25d3b09a855cd7789.nq.gz
│   ├── 60baadaaef58ba96987f515b62caebf60a75dd2c.nq.gz
│   ├── 61b6de158b5eaf7480654ce2cea7aaeb0061d53b.nq.gz
│   ├── 638b078837f175039b2db49a63821288d9681daa.nq.gz
│   ├── 643fee99cd6252e2f53353b9744f3ad392e5db4f.nq.gz
│   ├── 666dd9691bde7d54ddf2871e311d6f621e29f099.nq.gz
│   ├── 67f6ca20e17d808e3e77b806ad8a988b120f40a9.nq.gz
│   ├── 6917317af62da757ca759a92b326ddfa65b203cc.nq.gz
│   ├── 696efe53340f4abe5ad3ba8b9578df056e6c897d.nq.gz
│   ├── 698546e995d365d1ccc2c25a87e6c5cd681e6eb6.nq.gz
│   ├── 6b090faed0e630b03b2294545050f1f4f5032cad.nq.gz
│   ├── 6eb89c0c1408299f1423064814d78c293acf9da2.nq.gz
│   ├── 6f44ebaba1aa493b8bab3baa4e827b76752b1869.nq.gz
│   ├── 6ff6a3dc8c18c7358083135d1eb5bbb9c20fa50f.nq.gz
│   ├── 70284585018497b091ba797a05d57c07e8bce3b6.nq.gz
│   ├── 7217e5dc1bb683453204a20890f01f5806ce12cf.nq.gz
│   ├── 732a72e2fdc6d79ba22ff18fbc67d3adceb6187f.nq.gz
│   ├── 7836d19f573d30e4224f2f89a53104acf03efb91.nq.gz
│   ├── 7b6d6fc69b336c0a5d103be9fb13a0e0897c76a3.nq.gz
│   ├── 7bfc17088cda577b6f25ec09b20ee8cb2664fec8.nq.gz
│   ├── 7c4a4fc28f8ef61c6d5a4eca8f03a5c268998fcf.nq.gz
│   ├── 8147382a3152de03c24b4cd91f9870ced1a95d54.nq.gz
│   ├── 83f263dd570e447b3b009542d26688ce936436af.nq.gz
│   ├── 872943cecae8ce469031425ab82df74abcc62649.nq.gz
│   ├── 8881c41c67002a3798435b051c9a609dd1c0d506.nq.gz
│   ├── 8a2c7f35b9fe3961f0d974ee4799fa517922df83.nq.gz
│   ├── 8af4559c65fc2728b11fd2097a109981ee1ef686.nq.gz
│   ├── 8c82dbc256bd610c5ef2564ed2449b6a91857968.nq.gz
│   ├── 8dac93823203ead2af275b908f3b3c5e4ccbe631.nq.gz
│   ├── 8e2d1ab08ccee392f174a64b4d885bb96e148202.nq.gz
│   ├── 8fb59f2eb46c7e0db50d2994b2e9102d46def656.nq.gz
│   ├── 90f00707cf9c9ae499184f0135f7cc9d84327a21.nq.gz
│   ├── 90fc681a20ee72131862772107f6be572f010c99.nq.gz
│   ├── 9144329893c51f402ff2e2f65d9fb7baf177bd52.nq.gz
│   ├── 915947ff663fae5f7cfdc1967acd39fe176c7518.nq.gz
│   ├── 92602258ccd953a1d7137056aaf15c8de8166e21.nq.gz
│   ├── 9316eaa309ea8c12d9612a01d85958550357b9a7.nq.gz
│   ├── 938706438b1d332505fdd0e9670df72c31eee1b2.nq.gz
│   ├── 93fe449d943b36780341ce00638c94eba2e1f37b.nq.gz
│   ├── 97f5cfb7fb7691ef3921e3e6afc6d82ec54d4c6c.nq.gz
│   ├── 9b0f8ca657a429d92c233aaa404d9637d7500cc5.nq.gz
│   ├── 9ff31ed469bb95e40116e66ad249c38770ba3735.nq.gz
│   ├── a0130f304cd0b39f02f3b155897ff8d92b13126a.nq.gz
│   ├── a13877451bae7a6e774258a2f1753bbecb32b890.nq.gz
│   ├── a3297b7c295abddedfaac7f6fbe882d7b672487d.nq.gz
│   ├── a394efd653554ce687ab8f0c908238bef4f27dee.nq.gz
│   ├── a46845a6d35cbe2a6d79360fa962220f8d340de0.nq.gz
│   ├── a55dc3136718f89096452e9a3018de23b5c385d9.nq.gz
│   ├── adbf46ef7a6e86181b5927002597ef786add5bde.nq.gz
│   ├── ae903e63087516bc8ae77142532196be6a85589c.nq.gz
│   ├── b115b8f2327ea9d972f9e41bcbb03c68be6b3508.nq.gz
│   ├── b293aecb87839015f8ab37943afe71c2f8904871.nq.gz
│   ├── b32449207ce184a0d13eac79fbd83235acd451db.nq.gz
│   ├── b327fcc29eb44d7fe68be35da25bafa0e1d6feba.nq.gz
│   ├── b354be1874dad47a6bdef1f43cf84e2be4197856.nq.gz
│   ├── b4532882149acfa85d74840784052ddfc7061ed4.nq.gz
│   ├── b850e137eb1b020c36c9e2f370934e50b188afe1.nq.gz
│   ├── babab6e12b4bb8cfa74a7edfa5e56cd1b3e2bf6c.nq.gz
│   ├── bb4094e5ab241057019bf767e2fd7b7e9dfc7e7a.nq.gz
│   ├── bb4da40c65b96274fed8b1df2c3454db7d6b5f8f.nq.gz
│   ├── bd7a4c8085ddb7b237b17b054e5eaa0569018178.nq.gz
│   ├── bed25f57d0aaa8c37f63703f6f641999b02b1b3e.nq.gz
│   ├── c07efc122950da37455608b609dcf1f2b4103d56.nq.gz
│   ├── c14f770b481a548c978daca4b42fc0f74aeebe13.nq.gz
│   ├── c2ed4c030cb7a3fff79f47a8e681f4df7c989100.nq.gz
│   ├── c2ff17c915481fb556aba6ec816a9e08f519c515.nq.gz
│   ├── c46597a2cdf85da52b4b109ddf2a103bea72364b.nq.gz
│   ├── c6dc05c3d144d028eaf696b9518354f482d34a0f.nq.gz
│   ├── c759e4098aa06f89d04199182702176aa4c64b12.nq.gz
│   ├── c8c10e30e2d7f9bde33105715b04f5251d5c1950.nq.gz
│   ├── c946b8f79deba324a88ab0d61a322942b19fa764.nq.gz
│   ├── c95ebefe07b7d8d9fd0936a014679d07102cc270.nq.gz
│   ├── ccf206bbd7a5d6376eef82d61b3ef8bbe0f71c6c.nq.gz
│   ├── ce27c93aa1ea8a667a4bdd894be6db1d352ad7f5.nq.gz
│   ├── ce2853a41a1d232ff823bdd3afeb4823132b6672.nq.gz
│   ├── d0b3a5c63bc7c8bb022ea2be41275cb921e8755d.nq.gz
│   ├── d2eaef8ea3754d8ec0695e328907a8d62553de46.nq.gz
│   ├── d435b7d835bdfb2934e32a93f1e8eaab39420ad9.nq.gz
│   ├── d4a24572427098354f723fad5e737ff6dfe223fb.nq.gz
│   ├── d4bf1b4c47ccdb1401b18f8397868ec016d1c43a.nq.gz
│   ├── d5233419535a2821277d98ce151c0900a27bec7c.nq.gz
│   ├── d6e407a400a67020d801e6c27a3c32a2ee38f30c.nq.gz
│   ├── d71650eac767d178f9be2cc24508ac71907713bd.nq.gz
│   ├── d99a490bee397f969e93faa0c083b69674435ee8.nq.gz
│   ├── dbd91789f0cde61dd13a7f9a5f7a69488ad07279.nq.gz
│   ├── de97345cf424fe72cc90de30f42d127ff20b99ef.nq.gz
│   ├── e0a54c2c2bc10f76458c42a43de0970a9251759f.nq.gz
│   ├── e30e958da061a4f0a0bfe34b12d2fcaeba7ff2f4.nq.gz
│   ├── e3d50829fb0fdc705f8792b42535461fd7140c5b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7883dc886b96d078883e01aefd16792133e204a.nq.gz
│   ├── e96127cc9978c014b76e8c8ed138b7d6b52d9df7.nq.gz
│   ├── e98058ee30350a2be1da90c47bf2f335ec21457b.nq.gz
│   ├── e99a60879920b389799fb3a0baf1fd864ee0bccc.nq.gz
│   ├── ecba9c1ce714d481638e269ee4857fbe6a8de2fd.nq.gz
│   ├── ed236e4e3cee3105edd8d2c0bcee8e1ce22d4614.nq.gz
│   ├── f11303f299aeb675e23b0cb37ff4c881aec6f99e.nq.gz
│   ├── f8351e41ccd4a64dca237bd8f8be0702b23989dc.nq.gz
│   ├── fa836ca4b4d836a539f7e6d0aa2a012e6996edf5.nq.gz
│   ├── fc02e09d7792eb6a13ec32447b5e7f59ce141c8e.nq.gz
│   └── fc29a0b6b7d828b1b243efedb17b89ea02e2c602.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c121f0432da27facab705978f83c4ada465e46fd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 181 files
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

[haotian-liu/LLaVA](https://github.com/haotian-liu/LLaVA)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
