# Repolex Knowledge Graph of dsherret/ts-simple-ast

RDF knowledge graph data for [dsherret/ts-simple-ast](https://github.com/dsherret/ts-simple-ast), parsed by [repolex](https://repolex.ai).

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
rlex download dsherret/ts-simple-ast
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f288183ddb496adc6f4c5b6929830b5b73437185
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f288183ddb496adc6f4c5b6929830b5b73437185
│           └── chunk-001.nq.gz
└── blob
    ├── 00e559b0bffd62873b24fc164dea5caf5ee8ffaa.nq.gz
    ├── 012cdd5a9775f384d111aa26eca874fc1d4fbc7b.nq.gz
    ├── 0198e5dee86aca7bca6dd184aa9a2bda9bd5a2fb.nq.gz
    ├── 028b3c939a113349a1d28fad2c8532d79b7d7087.nq.gz
    ├── 02c23dc35183dc111848ab905c322042a26d0158.nq.gz
    ├── 0316cf1a852be483f8cef62a5f27bf69a76218ff.nq.gz
    ├── 03377d4e38aa8c3c8d8d004ba045e9ad11a372a2.nq.gz
    ├── 03bee8540a503f470a217ab0ccaabc626d9e478e.nq.gz
    ├── 03d3aaaea3f5cc152099d4d952d6582842432142.nq.gz
    ├── 048551c795554246ace340639dbe9ec92d79bede.nq.gz
    ├── 050e1f802d69feb3bce028dfa9b541c277df5b97.nq.gz
    ├── 05a399c786c8d8d1041fc319187635d490a07d31.nq.gz
    ├── 05fe5b85bf21b3db804b84b31438225b75696b6a.nq.gz
    ├── 06cfc67501f75e2d4ebe226c1c0903c14d1b3207.nq.gz
    ├── 075040e576202c9a907dcce97fa32aac7335f3e8.nq.gz
    ├── 07776672c213e243b748393da4bd50d2614f18be.nq.gz
    ├── 087c45a9dc6118978ad1258172ccc81a3564934a.nq.gz
    ├── 08db0ef86fb5823ddc62ae7399f02c21aafbb880.nq.gz
    ├── 08f55d53fd17da9e9920d4130cc618a0b2f40cf8.nq.gz
    ├── 096d0cbc2436dc1ed7603fa164510b8e85bcf508.nq.gz
    ├── 09a97ea0d808993fc4fc9cd0d2482621e94fec5e.nq.gz
    ├── 0a72623f1164c94a852e5502501344f0cc2290af.nq.gz
    ├── 0a85991aab4b8d07d4a5c8ef0535bd55f96795d1.nq.gz
    ├── 0adddf618f389281b49d4c2712b76446db1a0061.nq.gz
    ├── 0ae7c9017e716c38aafe8ecf19021095cccd9a1b.nq.gz
    ├── 0af8167df864317505e50aae692dcbe1dfb1cb4d.nq.gz
    ├── 0b1a5e0fb0e5e31f8e613de0cb007031daae9849.nq.gz
    ├── 0dbed47d9c70226047bf2091dba45ccf52bb0725.nq.gz
    ├── 0ddadbf575217904f497f077c0bcc11ad39cd948.nq.gz
    ├── 0e877b9b97981c50fc98122e6eeffe6792824379.nq.gz
    ├── 0ec94a58cdb457d3e8333a0a46dc739d915cb042.nq.gz
    ├── 0f391f043a2592c2c5554a2804e8078ba89c0bbc.nq.gz
    ├── 101be2591d1012828a17bdc57fa7231f64819d10.nq.gz
    ├── 1023d8aa0f4d21b9ba52ce2456735b7ee6151410.nq.gz
    ├── 10cf7b1b89d405d5bd15964c19c1fe39597d18a4.nq.gz
    ├── 10ef60c5623631b52bca099250e5d65c013da9ad.nq.gz
    ├── 1145586185153486e6c579a3a58c80b43c693236.nq.gz
    ├── 12b7b5bf0f15b3e33fc9f343397dfd5e17e8792b.nq.gz
    ├── 12c872eebeed550544f95204d133e2ece8e7cab1.nq.gz
    ├── 12c8de5cc67b1f7cb8adb449876b369f153d43fc.nq.gz
    ├── 1307a2fcac4d6e8a05a8210b054960a2a9b5f768.nq.gz
    ├── 13b1aa7f4102ed9e206481b07382bfbb3f28cefc.nq.gz
    ├── 13f0291b3bae0ad2f680866e6b927f5ca695b2fa.nq.gz
    ├── 13f213f9aef619aac6fa74aa1bb298381a595550.nq.gz
    ├── 13f750fb14bc0c08961d411c36c7bb4c22127152.nq.gz
    ├── 14176e4325cbdf44081731a61a75782834a2191b.nq.gz
    ├── 144ff248d1d0d84a657c4d40a05c4678d9bda450.nq.gz
    ├── 15ad183d9818bcfcfc87600e8c6f8ab651e085a3.nq.gz
    ├── 16e7153fe0112d52945968504e904f5dca48ca1b.nq.gz
    ├── 1740515f192d9a9dbaf281a18d3073db228f6260.nq.gz
    ├── 1a3dfb31a3b77d2689db4d192b89650857dd2a6b.nq.gz
    ├── 1a6289970e9af7e5f2865970413289f9a5cb9684.nq.gz
    ├── 1d6183e7afaea854a6673f627d437d5d81d206fc.nq.gz
    ├── 1d77e20889aca2314f9af781c3553ef3cb23bc2f.nq.gz
    ├── 1e6b9b002099f99a964f22ca35cbcc75c23f943c.nq.gz
    ├── 1e8c740ed6abe8bf9b373f3b2f18a22f2fb9fa32.nq.gz
    ├── 1f10725cfbee30c7d59957edb27a3e84eec0fe02.nq.gz
    ├── 1f54c7928653e3ebf5f1118ee1f7f82f71a35b07.nq.gz
    ├── 1f915816f41198578c683be0b1d5f3796cb48de7.nq.gz
    ├── 1fdcfa9f6187527a5de18af58c007ad25d83cc50.nq.gz
    ├── 20070914c952557c76912b287dbe32c6342e29ee.nq.gz
    ├── 20d8df19ce109497869ee154436c1232f800cc5e.nq.gz
    ├── 21dde268db0b8b25e4d89bb34950cbdddde41d7b.nq.gz
    ├── 21f02d9dd4faf66bc9910d2700e12819df4a5019.nq.gz
    ├── 24c13bfdd86e54ebdbbf8f882528caf38ac45db5.nq.gz
    ├── 24ce9b78e8f229044b7074d108ec7b808b6fb914.nq.gz
    ├── 258e3b8de126939f378c7f9a2eec177b92319028.nq.gz
    ├── 260851b01cc78d08128178d6a40bddd2efe3c0b4.nq.gz
    ├── 267d39decaf5bd816b9c21eced57ba1d1b0a6f25.nq.gz
    ├── 26ae4070fc0daf561b6e3e58ec1b4f6d0a841c9b.nq.gz
    ├── 26cc83854425e38c42fef8f9b94952ae6b2da4cf.nq.gz
    ├── 2774f9d388e43c917225c0bb798ea394912e45c3.nq.gz
    ├── 27910489526b73f5ef674647ee237adc667998cc.nq.gz
    ├── 287a8d36603bc3ce041ca5caa0c6a7417ea6dee7.nq.gz
    ├── 2883e3031f25c83b4d2c9b36dd22788f642e8860.nq.gz
    ├── 295860111524ab2ad252ad87cce16fde34cbbba5.nq.gz
    ├── 295c793d5266e7806a9dcf68f85610b265dd6ecd.nq.gz
    ├── 295d46be9751c1aa141839d00c46ecb0b27b404f.nq.gz
    ├── 29992905797a6a8dc6e8171b25e938f00ee6318a.nq.gz
    ├── 2a0183bf4fe9d5a0bf3a7decade2764f8cde504c.nq.gz
    ├── 2a0bc640e405f5e147a2bce28f644e7e076864b8.nq.gz
    ├── 2a20640fb89b79555b0bc328b5b70087eb2d2d50.nq.gz
    ├── 2a9925c63699a2e36483a3a6b9aa2a772f4478d3.nq.gz
    ├── 2accfbd6ef0815ae09e00d205761c1f5564ba4a2.nq.gz
    ├── 2af432610711d405403aa21ac14a3e89ccc74669.nq.gz
    ├── 2afc5cda24e4677c8e42a828d2cd73eb1e804d06.nq.gz
    ├── 2b03fedf2423665d671ab9555e9bbc05f8c87524.nq.gz
    ├── 2b59bcfa52c89c1077c216ede104429cdef774d9.nq.gz
    ├── 2bbc6379c1980e7d3acec73abe9aa88cd0d45aef.nq.gz
    ├── 2bd916e3d5442d18dbd023fc2317daa8b2dfa7df.nq.gz
    ├── 2c3f9a226581142cac41079de9dc00c0bfdd4755.nq.gz
    ├── 2cd3370608b9a5f80a5ada1f77c2083221a7d6b3.nq.gz
    ├── 2cd5e362d1eef11623a4ce84bf9507e0ccc807eb.nq.gz
    ├── 2d051ee8f1f03bd4670c9ad7ad5dc50882fc2ea2.nq.gz
    ├── 2d24a4cb7ce3865f8fce4ccc518af99834f581d3.nq.gz
    ├── 2e58d2c919be8d9e55370ad5ffacbd524c459a12.nq.gz
    ├── 2e5b4f1d2b168e068c57fcb54f26cdfececd7000.nq.gz
    ├── 2fbe0be598b4d7bcd6b75455318d380fc94d12a9.nq.gz
    ├── 2fde5bb5f37de7e4c24042ade766b0626d7bf2b1.nq.gz
    ├── 308b3e4a90c4fbd516dbbaf9e915647f8dfac299.nq.gz
    ├── 317cdee7862bd1345c53113b275adc17bc54e15e.nq.gz
    ├── 327f6e52c5535d38d5d73171e571d92c200f7a7f.nq.gz
    ├── 330d0d3f1d0562a060030d21656db7a36d342a3e.nq.gz
    ├── 336ee92e059b9673f18d331b90ba8d82e54e43ba.nq.gz
    ├── 33c3a907e08dbdd0c37267bb2975cc1c4e2f4830.nq.gz
    ├── 3459ddd4852a96c33651e692eb86e6299819bfd7.nq.gz
    ├── 352c6fc0c1221621561632aeae2c8e6525fdd79b.nq.gz
    ├── 3534518ceaf031ad2ace86488607b42d7c766bd0.nq.gz
    ├── 355e45d0cbfe195aa26e9c2a9a21bebefcc7a398.nq.gz
    ├── 3561c883f27153e13fee6a8743be98f7794ef0e7.nq.gz
    ├── 35bfd40a98791fe65ecb1806e8e1390554d6b012.nq.gz
    ├── 35e5299d3587f3be0648324966fc08aa9dcc83b5.nq.gz
    ├── 36b1701cb9a7f2a75d20d1d07bcee985ac6cb48d.nq.gz
    ├── 371567e3fa44aa01aa5274ac9d7ad3d4deaa6039.nq.gz
    ├── 37cab60072f0b5c9a26e2a2c8db1b0f0af92defa.nq.gz
    ├── 389dc217f53b4f936ff1e90e3b0e7e21268b94f2.nq.gz
    ├── 389f65debf8b165edd715bdc93129d4b5fda6e89.nq.gz
    ├── 38ef63baca1c537cfef17ad5cef526a59efd2b78.nq.gz
    ├── 38f21b695b61bf8365c5e90cdc599d21e8b7ab48.nq.gz
    ├── 395bc0a40ff044a37ca15de45e1ac5e215563a94.nq.gz
    ├── 3a4de5647ffb40da0ae3eb34e71e46daa3f49a0c.nq.gz
    ├── 3a6f851a2572fe7483e3530d2538f3975ef2b878.nq.gz
    ├── 3b273318a5a47903faad204ec747bb80e8db7174.nq.gz
    ├── 3b3a93ace84ad718c573706efe5bc40c88612d1d.nq.gz
    ├── 3c3c492bf6a0f2fcdaaa8caf96784bd5531baad5.nq.gz
    ├── 3cbf1b89ab37b88818e1f8cd592b6c2763d80557.nq.gz
    ├── 3d55533daf40d3be87f91b54482020cea550e70d.nq.gz
    ├── 3d8ca194fea0ee7773127da907766839a0bdb4f4.nq.gz
    ├── 3fa5fb316c37fb5c2e03c387ef85024e4f0f8c6d.nq.gz
    ├── 3fd03248e6a36d494db4b693d91f3fc4485fe9ba.nq.gz
    ├── 3ff4388197ec8e5e7e1d44ea31d729b66ffb9a5f.nq.gz
    ├── 400058f6f881fd07070ba99d59033b9895e9e5c0.nq.gz
    ├── 40d0e80fd3f0760523cdf2ae2bc9fdff422b3bd9.nq.gz
    ├── 414843e24b746c6e8eead1f4a606893feea57567.nq.gz
    ├── 42b3b2f3a8f8ae1d104d0c79561a8ca833c4cc27.nq.gz
    ├── 43ebf39cd5e278974069c9ab51d40a896ecf063d.nq.gz
    ├── 4437c61499f11c5c5ef38f308cd770a7fcbb6d5d.nq.gz
    ├── 444fe266b85f3dbb6a4ce2f58ab2d7784e1dc4c5.nq.gz
    ├── 44bd33ccff5a3f369be7f182e9cdc70f843a7825.nq.gz
    ├── 4539c87f66e322d6ff73d05660e65bfd33aa0166.nq.gz
    ├── 45615458677c85ee05e17400b8f6185a9cc4b5b6.nq.gz
    ├── 4661ddf6bac2752c52a882352724792dfb3509c2.nq.gz
    ├── 469ce37a7ab22fde76849999d5ac12f57d7a1d77.nq.gz
    ├── 47f4a69eee24bb379d46d09ec035615dc6f9e5eb.nq.gz
    ├── 491e561f9814fbc06f6b602f835d9f33e0977aa1.nq.gz
    ├── 49dc8a3ac3a2cd6235d7769a8037b233a44ff146.nq.gz
    ├── 4a20d43d6fe9c1a3c274299683a6803d89dee59c.nq.gz
    ├── 4a9c034b6c36707b2fbd3c8b0168742131be6802.nq.gz
    ├── 4aad646c226828d7c5e884499c126516e0634db4.nq.gz
    ├── 4b85a9d890cb2be4f93ae29ca2b37d1dbf37f712.nq.gz
    ├── 4cdcd1b2e3317ba7badd0327b05b7c2c2b7e2a9c.nq.gz
    ├── 4ce0bf6320a5bbe57403805b310b5bf92beb7285.nq.gz
    ├── 4d42a851c75c2969d877d1578779234c083f51d3.nq.gz
    ├── 4db71ed7f08a272f9bf67f770517c1c42f8d2ac7.nq.gz
    ├── 4ddc776035f22f75b337739a5b8b4cba3d0a25e4.nq.gz
    ├── 4e5e2f30c3973998da1a943991c62eaa06a19202.nq.gz
    ├── 500416e9cc2db238b49c204c97d8a7a6b28fd5d3.nq.gz
    ├── 504be42693ad81a19bfb2af1d458e6706c5f2f02.nq.gz
    ├── 5110867b8705991b1185b4530bf814cffd38e9fa.nq.gz
    ├── 512e4c7bf277f4a2d40179c728f7bdaf7ca37433.nq.gz
    ├── 51a3f3c662bd7b08b1d2b5c8ab658c6fdcb8e90f.nq.gz
    ├── 52c72e66e8ad5c360e668a6d96e7dd01fe6b8231.nq.gz
    ├── 53a77b022ee8e9ef67a49fd4989ddfea61dd1acb.nq.gz
    ├── 54bb8426f6656d93a17e983b34eaa09ed253ba97.nq.gz
    ├── 5504b94ed7239d9f8768416995f5a99de906ef76.nq.gz
    ├── 56d51a76dbce060f96a810ebcae3e3cbc74ce6bb.nq.gz
    ├── 58447f67de835fbaff0a0f1b201c24b2274f7ff0.nq.gz
    ├── 5923601da019fcaf8c2f09f0a1f773dd3f249d1f.nq.gz
    ├── 59cfe09676f37730e2a9f883f254bc374808c1f3.nq.gz
    ├── 5b257bbe8637c5b041dcc6df293fac0f286f5360.nq.gz
    ├── 5bb8eb623d05bb2968dc9152fbc1762ed075f0aa.nq.gz
    ├── 5bd39ca9bd903bd8cbe43773df336b1edecba456.nq.gz
    ├── 5c65d301712e9bb4a12505ea31d257c1c23cdae0.nq.gz
    ├── 5c7906fd0e6194acd3e366745b476b9186aade69.nq.gz
    ├── 5d52e9601f467a0b6851dd7f75e11e94fdd147c9.nq.gz
    ├── 5ead62c68c14d769de489d21a433d40193be1959.nq.gz
    ├── 5ec2bc9c72bb13a8d8c5537fd968e018434eb77c.nq.gz
    ├── 5f176f5750c284220d6592cd5de2d4c4017d9944.nq.gz
    ├── 5f64b0f75f2bee7ec42051bd5800bb40820ee51c.nq.gz
    ├── 5f98abd6a291bd60a86342ef201c74208cb6c39a.nq.gz
    ├── 5fa98c7158dc2963c557352cbf5e123d73c974dd.nq.gz
    ├── 60364a5b681921a2ac9cd79ca407d78a58bd8de6.nq.gz
    ├── 6047135968eac96005dbce118b2bf1164f7fc8e7.nq.gz
    ├── 6124e382e46f183f22c7fca0024c6ba1253d7e25.nq.gz
    ├── 61f4cb581568784aacfb82c16531b9785da1d125.nq.gz
    ├── 631d63445e58c62759619dcf6017ad4b09be46ff.nq.gz
    ├── 63dd0f02d4c5965623fdc3e9ac20c9ab3a5b7b2f.nq.gz
    ├── 644106c9b324e7091b57a4e061d5a763aa95d3b4.nq.gz
    ├── 646be0fc8777082feb670f9e2a52cd6e156495df.nq.gz
    ├── 64746499f3a88f5e0353d4d263e21d232c27f712.nq.gz
    ├── 655e4282d320bafe57f709bb926011c24b60472c.nq.gz
    ├── 657f424a898d15d1404d75384eff6bbd5397ad97.nq.gz
    ├── 663f6b02841e622d5c2e768c1a51dd3f36e0b763.nq.gz
    ├── 67025ad7547897a964633045626bb3d59eb35ada.nq.gz
    ├── 6819c10a17a4043b9cae70165279c5cd0d8cfcdc.nq.gz
    ├── 68d79d8efd0b435ffdef7d9434c798df1b6f1151.nq.gz
    ├── 6923b948e93cb605d6f640b9cdd152e9a6426ae4.nq.gz
    └── 697b69fff0c9e497e9d65bf5813c4641e641fc77.nq.gz

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

[dsherret/ts-simple-ast](https://github.com/dsherret/ts-simple-ast)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
