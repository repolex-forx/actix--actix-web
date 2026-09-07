# Repolex Knowledge Graph of actix/actix-web

RDF knowledge graph data for [actix/actix-web](https://github.com/actix/actix-web), parsed by [repolex](https://repolex.ai).

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
lexq download actix/actix-web
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5723cf486522d47aad26390cf5b02e95654ae225
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5723cf486522d47aad26390cf5b02e95654ae225.nq.gz
│   └── repolex
│       └── 5723cf486522d47aad26390cf5b02e95654ae225
│           └── chunk-001.nq.gz
└── blob
    ├── 0015743bd4f9fead241ff8ae16ce1c268bd506f7.nq.gz
    ├── 001810a8cd5601f81e48d0c682f9483a0a4f899b.nq.gz
    ├── 0031f0f982e8bad6dec45f4c9b4ffa0d247a0bb3.nq.gz
    ├── 0150d56f2995ef3bc53a67597a3aca63fb08f38e.nq.gz
    ├── 0151ff3a5982e030ddf07bcff887f6965bc6fa26.nq.gz
    ├── 0163f6cbf609d7ded61d77b27e31572c0078f7e5.nq.gz
    ├── 01bca6c5bceda560c19d7b6626b016dfe5e39d71.nq.gz
    ├── 02a4f94e436666e7a7980b6af54b5d27b3b7d21c.nq.gz
    ├── 02ff4ef5784f268ab1d31fcb9061c2f9ebd0772e.nq.gz
    ├── 0357b446de477918ff48b422b180ffa8d2a98ada.nq.gz
    ├── 035f34295a25c06badf8b854077a0a493104f30d.nq.gz
    ├── 03908d9ce8122df9c989dfff9acdd452a299aa1b.nq.gz
    ├── 04216f69a2588eceb6285ef0ccbc67703347457d.nq.gz
    ├── 04b4b5ea9b1c480e5b0b8e9fe3aa6540005b075a.nq.gz
    ├── 04e62daeb50c1259e0315fa85046789b900c2bea.nq.gz
    ├── 05dc21ff7094e6803cec7d31ce3456d7cb70d26c.nq.gz
    ├── 067d95a601e243bff1ff482a338de33bf740de4a.nq.gz
    ├── 06a5c92bd1fd7fafd8dd257af92e908e71642da6.nq.gz
    ├── 088df55d2869d547e73d7703757b98da915d0cd1.nq.gz
    ├── 089569c0982f2b26be6f0f74027eb6c7bf7a2066.nq.gz
    ├── 08cd81a0ddf7fee57fb7026a7cb57857711a8c1b.nq.gz
    ├── 08ef19b68e84e0838980fab59bd6c99c71034082.nq.gz
    ├── 0a71f857acc10556fff15f5a9e33a78c46d8e736.nq.gz
    ├── 0ab33596655907ea5142b0e6cbd264ef4f9cbac2.nq.gz
    ├── 0b16466b4c16d2128140c76de782adb4672517ba.nq.gz
    ├── 0b6c9956eb304231ae8de9b2c749d1bdc9c669c3.nq.gz
    ├── 0b901b258adf51c991eec043316051974b5ad0ad.nq.gz
    ├── 0bae62336160f0e5a5f09e9642fbf6ae2abd22ce.nq.gz
    ├── 0bbb8a6573a6bb113d669ab2e55cf2653eca908b.nq.gz
    ├── 0d23bb41d5b3c010ea3281ac9c915f8cde746085.nq.gz
    ├── 0d45c940344480064bbda37b49e77e880b4bd044.nq.gz
    ├── 0d53ec01381902b595dac287a3f9be43617a94ce.nq.gz
    ├── 0dcdc177e67b561f47edc977a21d241942fd747d.nq.gz
    ├── 0ea70a31991e3de3c4b2a8da755db8975ba10614.nq.gz
    ├── 0eafcff0a1f08a09b6a8e884e955b386705097e4.nq.gz
    ├── 0f0958e5cc5d2b0f6f67da4c60a858b7bc984505.nq.gz
    ├── 0f2be6f03dbae34f8900e8fe4e4e293a0045d3c2.nq.gz
    ├── 0f7800d166f712355d60ff9b7a2d961b10913f39.nq.gz
    ├── 0ff58341f960c10a0b466676f539041720f66543.nq.gz
    ├── 1099731f36c8571c815787d6765d5b55de5de348.nq.gz
    ├── 115a8cf9b5af068183e2bd1427e0d4c187ec1be0.nq.gz
    ├── 11fd2750e9a4bfa920fc836bfea044612c1a8f8e.nq.gz
    ├── 1247c0a55fa675b2b71af434a09fcfa64f8f48e3.nq.gz
    ├── 1258a6f2f78dbe4d745c43fba0a201bf4cf10c42.nq.gz
    ├── 131206647244070931547b4f262bf3a6e20e9224.nq.gz
    ├── 13bea6d7a26e41c8c2bc848dc4d7ec0e764eed2b.nq.gz
    ├── 13fc7e6c512629c618eaaac2afcb41642a085650.nq.gz
    ├── 1427ee16a5ebb3e32b6c7ffb9e457b1519fb03bf.nq.gz
    ├── 1443f9a75b6a20ff43e904932889c68a08df2269.nq.gz
    ├── 14e9f827c44cb5798ed8e342db2c37cbe23c63e4.nq.gz
    ├── 14ed9e958c5dd7d7a3462a75f425a2252827e478.nq.gz
    ├── 15e11c2b9b35e0453ed8130f48db219424dcd668.nq.gz
    ├── 163f67b46ea41381baacf639be22bd7a9a415739.nq.gz
    ├── 16b750c17289cd8b1bdb5eaf0877245e2d354075.nq.gz
    ├── 16bdc619c93e0c5bbda42ebd2ff6c5a2a6140895.nq.gz
    ├── 17998a1a308c6301df7c7769465b33e187d4f54f.nq.gz
    ├── 1853843c326b649b5e151faebd73dcbb1d1012f3.nq.gz
    ├── 1a12f333661a586f8bd8e34ae35256f845a61c9b.nq.gz
    ├── 1a380fb7ef412fdfc3b4003d6d6d3c34a2d02b70.nq.gz
    ├── 1b4a824d992acad01bf9344f505d83383c187918.nq.gz
    ├── 1ba4ce67e5ef105818f7a9eed1fc497118487f51.nq.gz
    ├── 1bb5545aee950656e43ef0269ae0bd3fe65a13f5.nq.gz
    ├── 1c22da38b3835789347d72121f3fd8b09e95c1df.nq.gz
    ├── 1c6e343e3d7d9df135d4868cd125d18ea2fb4521.nq.gz
    ├── 1e77e1be83bf591958bf096254ea2b7fa9ce6aea.nq.gz
    ├── 1ef616dcf7413962455928c3040c9f6a4801e4d9.nq.gz
    ├── 1f3c63cbb055ac87e8ec9108f2980478961aa5e3.nq.gz
    ├── 1f66bbb43bedbb0e071b0d8eb6aacb1bfeb34a93.nq.gz
    ├── 1f99d20956bc296a5faab028eda9ddfc6b51c6e1.nq.gz
    ├── 200858a936f93f865d0b4b19be94e31b2e949551.nq.gz
    ├── 20444904c9f8ad5f5c53d089772045705b50031e.nq.gz
    ├── 2143a066b11715b4f1a3a5b09e973defad53d128.nq.gz
    ├── 2147e418895119ab132ef3a44c8b16a4a6ce1b77.nq.gz
    ├── 21872d0ca760b24c75c256a9caa76838ad7ebc0b.nq.gz
    ├── 218b91bff3acad35a89d8cab7f66b69389ee6f6b.nq.gz
    ├── 22618c9b33ff1c9c074a7447819de75b2996a4cf.nq.gz
    ├── 23e3364595d2d74f05d7e962661992b411ca51cb.nq.gz
    ├── 249b5611474282a138438e0159f7512101b158ea.nq.gz
    ├── 253900633d093334bb056c1c92b236afbfd6c630.nq.gz
    ├── 2604f9ba2ba085e0cb639dc364220bb32eaf3766.nq.gz
    ├── 2669a047e8c26acc0e2b3a7f0ebcd7f0eb266ac7.nq.gz
    ├── 26d0f3daac94fbbd204bf8ee5308b56619e2cd38.nq.gz
    ├── 271f0a7ae4763a8c4f75be4326888fb475a06a52.nq.gz
    ├── 27815eaf2481a842f6f1b84ce07feb12cbd05fa8.nq.gz
    ├── 2800f40baf9af66dc9ba465fc7397bbe3ebcd4bf.nq.gz
    ├── 284a286c918ee89631015abc9dbd882fae5da66c.nq.gz
    ├── 2866e1a2c87017fa32976b3d94603184830f4130.nq.gz
    ├── 2946cfcf6ebe2034e90fda612732558f7d9933e6.nq.gz
    ├── 298bd5335f1e2de62a02ab46e83b94f3e2e1726a.nq.gz
    ├── 29b15ee2de1877a68d1fdebd52ee7c5a054a37c7.nq.gz
    ├── 2a0791a1c8011603d853efc33cedb5bd57a1b542.nq.gz
    ├── 2d940984d1470d4490ae9ac0f3641aca955921fd.nq.gz
    ├── 2e0da2e4fe2a3fb3b80d917eb57999ee6d082077.nq.gz
    ├── 2e1480297ef0f90b91628bbd62c815b30ae6d972.nq.gz
    ├── 2e712d1b14047c9d4552755fa7fb96c463520018.nq.gz
    ├── 2ee13556106bded7207152570b42d0cd76b6372b.nq.gz
    ├── 2f097547dae7afca072c04c02870b1b3cf73f3ce.nq.gz
    ├── 300af2ed390a76a0e413ead728bb262306e0529b.nq.gz
    ├── 31809aef765c66569d5f029eb76ac9b72370f629.nq.gz
    ├── 318d6a4d15809a536f1b8928047bcd68df43e9fc.nq.gz
    ├── 31999228e7f58ea728d760aaaac633061673c809.nq.gz
    ├── 321114b3c5c0f8f628f467c8c5c94640b9c53077.nq.gz
    ├── 329f57f3c4e2e76a9728a353c55d5d71268abacb.nq.gz
    ├── 32a55143a8f3fc019b8118eb54fd4b3d496ae65a.nq.gz
    ├── 34c79efeae3e2a5ab83c0b69437ef61114ba0a7b.nq.gz
    ├── 34e1f95629c6c6ae3dca82b8c1577a00ad53afaa.nq.gz
    ├── 355f13fc813e5cb1f874e0c36fd3963726d5bdc8.nq.gz
    ├── 360b3db0ea1c667aad570f606111df1e56ca9260.nq.gz
    ├── 39bcb9d1a6e0e5a25e84e18361b1caa159b6c4c1.nq.gz
    ├── 3a0caf2ef31f0ab617bd6d5d7f2fa8e8eedd9ab8.nq.gz
    ├── 3a1293bb8d40daa3f1f0b561ce17b7633b316418.nq.gz
    ├── 3a23b91b99f0fec5f8cecc04c2de91eda790eab9.nq.gz
    ├── 3d8d8db0849c9a1255ebfd80aeab0ffb2f187d02.nq.gz
    ├── 3db5e7f9e2cdffeb19ceececc64b7ae09a048677.nq.gz
    ├── 3f8a2c9e35c9f8859e3acc744a7b7c00eeb384bb.nq.gz
    ├── 3fbf022644d7893f40b9262fe2eabec30662ce50.nq.gz
    ├── 41e6104b9c5950c23a01a82dcc732b2ecd1c5a9f.nq.gz
    ├── 4297b00d12119311b562805893f4ea53a128132f.nq.gz
    ├── 43c83891a553b420b457061e940d5619132deb39.nq.gz
    ├── 441b05baea942b44c77621657752766923857ef7.nq.gz
    ├── 4491f42dd4a755aec918d2b8f7ce3280311c47ef.nq.gz
    ├── 4540d8a6b6192e22351fca2bda10e1c29faa4bb9.nq.gz
    ├── 489515e406d98f74b620305d0ea5507142c6fedb.nq.gz
    ├── 48f38df2c39b40b3f674f045106446d4636641da.nq.gz
    ├── 4a27818a5818fa3d010c3790c0b370327537a714.nq.gz
    ├── 4ab426c6c755dad1aeb8cac1df413c865c202d91.nq.gz
    ├── 4b5b3e896fa818d538a86b70a3f8410240597363.nq.gz
    ├── 4c74931e60907a3f228f7955e708955105e45447.nq.gz
    ├── 4c7e6a5a949ae1b6de5ec46dd6abfe211ed28270.nq.gz
    ├── 4cf310be5bc6123125d5aa41dae169ada8cb6932.nq.gz
    ├── 4eecb8dde0e658503a0cc8694bcda0dae7b29f3a.nq.gz
    ├── 4f9044a27b531c2bd456f04b30aaed2193f982cf.nq.gz
    ├── 4fbc2f8d072b8a98941d4f4a0255b495268508f9.nq.gz
    ├── 50792619692e3927f211e32efc80f74939705010.nq.gz
    ├── 50c773f38a20e387a7c541ea963d869279ca31d2.nq.gz
    ├── 51503bc905ee95d0a2716a6e963053caa95ebf38.nq.gz
    ├── 516ee9919363a7451377a0ed6d4ce4eec1f0dfae.nq.gz
    ├── 5170ea4a1f9303497dd5ecf1fb083654dc9f2102.nq.gz
    ├── 51ac4fcfd901ab1210876ecbd8c6722a7c4703fd.nq.gz
    ├── 51b0cf7d95fc769844eccb89b1fe5ac279b8935d.nq.gz
    ├── 525a60b83a5273faa57d77a0843eaa005278feab.nq.gz
    ├── 52d522b0ad0431f5b78ff20bcfc8fc364a103db8.nq.gz
    ├── 530c1e03bad59fcc3d2d93940ba6b04dd86d4f7c.nq.gz
    ├── 5334c46afbaf5e325b9bd4a82fe978e24e1af37e.nq.gz
    ├── 53ee93c83fcae0887518a4aa284beb8fa38f23d1.nq.gz
    ├── 5443a5d763a13ba8e8fb1e1ddaf71d74ad92d7a8.nq.gz
    ├── 55289db86e6cd9ce272e2f126c811d7f349539eb.nq.gz
    ├── 5596c4929c1f3387fded72d1296f49a194888d1b.nq.gz
    ├── 55a01c3012241647cccf481a527ce2d2c9fbe91f.nq.gz
    ├── 560a66b8e6d3d16dd7028bda2521dc5a33e1e14c.nq.gz
    ├── 56d62ac6edc85fdb8bdd2f4f13344a3c7e45641e.nq.gz
    ├── 5844ea2c2fd87dd88af707ee9d2b7f42793bfd6c.nq.gz
    ├── 58464f360a3c9f608907ddc2ac5f2e33625def8c.nq.gz
    ├── 58b06d70f0d7a7dab5dababfeaa080828a7f313a.nq.gz
    ├── 58dbd45ab148704397cdc9741a2f0a56f84472f3.nq.gz
    ├── 58e060821213f69491ae8bb741bd0c07638cc3b3.nq.gz
    ├── 59d72b70892d4c25a51587f7527ea22885ef19f0.nq.gz
    ├── 5a97f75d62d5b5304e681d8ec59f840ccd3ba4ec.nq.gz
    ├── 5aae394f857da5b33e215c03f606d2b38981a669.nq.gz
    ├── 5af757b766d100e9d83d436b3f91030213977df8.nq.gz
    ├── 5b0797ef3999880b644d73d77e5c805c4c6bee65.nq.gz
    ├── 5c11b1dab8b1c46eb99d6c277be08d88e1392edd.nq.gz
    ├── 5ea566fb05453bb13310302984f716589c9d7cb5.nq.gz
    ├── 5ee4467d9d2b63ce417568402ef582bc0cb92ea5.nq.gz
    ├── 5fd0aa790ff39c620744b2f7157999f7938f43da.nq.gz
    ├── 605572d8be54a4994e0fae089f2c1d7a88fe87a9.nq.gz
    ├── 608833319c1f31e1423e963898defb88ee2db8fe.nq.gz
    ├── 60bb116bf4aed29616c26db6eced7bcb538659b3.nq.gz
    ├── 61175bdc9ac36eaec71e0dc5d267bf64ead89011.nq.gz
    ├── 619a2204fde42a91576aba2c85e6e9221a236348.nq.gz
    ├── 61a4d4bca27662ff27c012f648109990c4eff36e.nq.gz
    ├── 61abb5bc2885f65c0ae1092fc4a3853b4ef90ec5.nq.gz
    ├── 61d6c55a3b2b45f9acd8a9a56c742ee02579a3d3.nq.gz
    ├── 61ff1bff54a41f423a385d82641fd4cc23a39613.nq.gz
    ├── 649c1a97a6fc75a14dd6a9352d304783d345286c.nq.gz
    ├── 65573cf7905f2b4d38f27f03e86e9e0fa3eb4c23.nq.gz
    ├── 657ffe9c8e0fc300906b3385acab9d667962b51f.nq.gz
    ├── 65c0dcfd68abcea8efe06669b59bc13df430d900.nq.gz
    ├── 66926818a1f34dfcd7f75d2422ca70c5126403f0.nq.gz
    ├── 66933432e806a28ea50bc39ece0883fd9a28a409.nq.gz
    ├── 6738ad09067074c8b4a608d216d706d105d2fe68.nq.gz
    ├── 6801b5fb0de657e162ca1ea7d5b60e322b7395d5.nq.gz
    ├── 6867c51f196dd391e0ea3feb84561ec5897a92f6.nq.gz
    ├── 69f0aa2a73afc826b402246e430f74627c093ff6.nq.gz
    ├── 6a267a7a6cc9f0e5cf73c94e7d5b6f62ae9dc2bf.nq.gz
    ├── 6a2e8f1a8cd3460f0aded428673fa518213d4b0f.nq.gz
    ├── 6a4392d6bb624bfa47bc2b64e92ad0d46c497b14.nq.gz
    ├── 6a43ac5e63b2b8fada396ba6e0eea51865a2e0bd.nq.gz
    ├── 6a64a5f23256f43fe33488910b8215452e5a6f27.nq.gz
    ├── 6a6f609b0d16847761c283679f5bdeae43c22b9f.nq.gz
    ├── 6af514642e03a36feaa081f7077cdd76d1e317d2.nq.gz
    ├── 6b7cdc0b8fb5a439d3bd19f210e89a37a2354e61.nq.gz
    ├── 6c4cc92296611061d6157e387c49125a48fce9b6.nq.gz
    ├── 6ca429e61d63e37a35a199be101bbe7649044836.nq.gz
    ├── 6cb5957700f1008698d1ceb77431e8bf07fd74ca.nq.gz
    ├── 6cbb680d50aa042af9781c6949b5e0bfd7604c21.nq.gz
    └── 6ddee64cf8dc73bf439bc87493a5459fe464b008.nq.gz

8 directories, 200 files
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

[actix/actix-web](https://github.com/actix/actix-web)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
