# Repolex Knowledge Graph of twisted/quotient

RDF knowledge graph data for [twisted/quotient](https://github.com/twisted/quotient), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/quotient
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 95f2515219da99a77905852bc01deeb27e93466e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 95f2515219da99a77905852bc01deeb27e93466e
│           └── chunk-001.nq.gz
└── blob
    ├── 00c2d792df1583e441db1ab0e7777d56991b96ed.nq.gz
    ├── 01cfa9b00576581065649188733459a7b07a129d.nq.gz
    ├── 04c426d2d26ed8fe9b265dc5547fe5f0b619c9f7.nq.gz
    ├── 05689cb0cf99fcb4f3781ddce18bbde615aed54c.nq.gz
    ├── 057d7a90805988108b389e80ee697a1061534a3b.nq.gz
    ├── 05e7b3dae2e5f6019f2be72e8f48d18d73ceff51.nq.gz
    ├── 060ed549097474f98a25c23d613e9cd9d72194c3.nq.gz
    ├── 0714f6cf4d63d19339487e6a6feccbd0380b5e7f.nq.gz
    ├── 0730c3c49c18d229ec91980028cd548b779e2633.nq.gz
    ├── 076110a98c13fd7db4d9bedb12f3f5882756e0bd.nq.gz
    ├── 07dcec55238bf82674bbcf222731f8e22f141186.nq.gz
    ├── 08c086125d0aad260427642bf2734089058f9b89.nq.gz
    ├── 08e779c5e40f9ff04e1e6533e2a5f3bd7cc975af.nq.gz
    ├── 0953be641a57c670140f19e478d590d2b0e1e353.nq.gz
    ├── 09a3f2dc59de7cabf5c463130674ac77c24501f6.nq.gz
    ├── 09e75842a5cfb3f6fef58f3c85cd51b7ed837a80.nq.gz
    ├── 0a96bf3beaa82da3d30743ec410726ae1f2232fc.nq.gz
    ├── 0ac03f86266508b007e2d5a131551bbeeae8a46d.nq.gz
    ├── 0b6d9e9bab37705b15a2f80d0b730ce1e6ed44a6.nq.gz
    ├── 0d6dad207179081bca8124ef302a3dff2a7caeb9.nq.gz
    ├── 0eaa4b3a1bca7dc2dc410c72942b9b3632ac908d.nq.gz
    ├── 0f8a0b30064ca9edcb668b2973121891c0414929.nq.gz
    ├── 1186662066b39e43a43d092da183ee1052f63d95.nq.gz
    ├── 124a674a34a3a3049d5c4bed0f23491daa50ec5a.nq.gz
    ├── 1262c296dffbd43a7c3b1815699b0e53fe705181.nq.gz
    ├── 14249760338541fe6fa1436a8babaec8bdc9ebed.nq.gz
    ├── 15f4d7995a5df8e9b41f948cf403ccf84d430860.nq.gz
    ├── 16bb7bb11fed395ee61ae0a89fe5ca68cabfc746.nq.gz
    ├── 16d828394dae590c4aa5964ef370c5d88fb3e81f.nq.gz
    ├── 16de4d0076f52cd13b28d0bd3bd151f5a690c57d.nq.gz
    ├── 1795ac1560f487520807eca237067cd9207a8fbc.nq.gz
    ├── 18c998bd826efb48832d06e8edb38bdd27323ab9.nq.gz
    ├── 1949f0bbde1f6b68f5abcea7579f8ee865bac57e.nq.gz
    ├── 1b2fc28a4d25e3ccddc3cedb215231d4934a9f89.nq.gz
    ├── 1b4c496656eb25f1c9e4922ee55ac6399717aca7.nq.gz
    ├── 1ba1dbbed69739a82ba24e35dfe6e50d057d0d74.nq.gz
    ├── 1bf1d6e696898b02742cc81bdfcc7ed03158bbf7.nq.gz
    ├── 1c7000d4474d8b1bc029f68354bb8825382722c9.nq.gz
    ├── 1e58efdfa966bfc91d35188706a2f4c0f180a8a9.nq.gz
    ├── 2031b07798389487dda4456e56f47399403f701e.nq.gz
    ├── 21dc0ccb8ad881165103e29b602833134591e060.nq.gz
    ├── 223b0cdd95bfacd2e88d23da11a153565f1d3cbd.nq.gz
    ├── 228a780f10ea4c89309a5a2a7215416ddf0baea4.nq.gz
    ├── 22f7bc666a4931fc1078af8e2bd91fd6b72dc37b.nq.gz
    ├── 2318d090a68bee0b88b56c556d74ab2ae94beb60.nq.gz
    ├── 2369adb1a11c6fd1e527c0bc347a6537a0e3f0af.nq.gz
    ├── 256ab73e8a3889177ab64af1bf3fdd8cf3ddd3e9.nq.gz
    ├── 269cc24b42a0265cfe1d10849b41c987e7f0f193.nq.gz
    ├── 2709dbd97db51f04b8f0a5eff506773cf526bde4.nq.gz
    ├── 2750189681d0431121755a571e7c4afc71cbbfa8.nq.gz
    ├── 282d6aa8d1cdfb399e2c537e78045831cff99525.nq.gz
    ├── 285c154979613b7ece18d5d63664c1760f166fc3.nq.gz
    ├── 28906468d062c70ce6d14c6e7a1cd5996ed05681.nq.gz
    ├── 28adc8c361fa48b4dfca76c8997c8c2d97f595c2.nq.gz
    ├── 294c090a6e115770e736e12b95be9180adbd38b1.nq.gz
    ├── 2a58f8ea438f685f674f7032f1f7811cff8a9084.nq.gz
    ├── 2ab2a3103d7b5c2c160a2e0a29d461ffe3552f98.nq.gz
    ├── 2b27f3a795d9b45d631abfaff613eb18d5b217bb.nq.gz
    ├── 2c3befea36245acc8cb669e9e8cd9440bf128f44.nq.gz
    ├── 2d66384be6c254194fb28b2578f75eb0cd94830d.nq.gz
    ├── 2f0c58c1433b548595bd02921e3163204b7ad0e5.nq.gz
    ├── 2f5bb03c1c114b3f76a4f81eb29c8fd4f5f599f7.nq.gz
    ├── 2f5d899fa7f648fcf39003225313e5b85e2c4567.nq.gz
    ├── 2f601b1a0fc6e02a6be4c85aa691907a81216392.nq.gz
    ├── 3106865dd679254408bd6637a61e57082e1b9cf4.nq.gz
    ├── 31b88c96c210172a8986e1e7a534f35fe8d52226.nq.gz
    ├── 323357501269f3cefcaaf8503b51bf05d2d1a565.nq.gz
    ├── 32d5d2ad3c9d5fbbbdb7dca1a65aec99f3f3ea13.nq.gz
    ├── 336e519442825193c7d189d306b9c1e89e7e6815.nq.gz
    ├── 34247ae87d106d05e7c0e631eba50e0b98448770.nq.gz
    ├── 352200339ceaea9b902c6161b94bccbb7f22745c.nq.gz
    ├── 352645112dd3187da15e7e44fecead9c85143e1c.nq.gz
    ├── 35641d3f6e8756d5fa0fd1e36c1fa6a132692a46.nq.gz
    ├── 3702e499c7e378898d4a1e9c036f620f452f331c.nq.gz
    ├── 37e84628a9eb796f654c6806eba4c561f91b70bd.nq.gz
    ├── 380e42c4e3cac30dd0dab8c8e2d0a793d6e7e2d0.nq.gz
    ├── 3920850b98903e7e2faa3304c6864b145ad3b294.nq.gz
    ├── 3b028059350ef4cd78d136ad8d2cd26554b54cd0.nq.gz
    ├── 3bff3c44f08d9c4dcefd9f5c06b7239cc74678f8.nq.gz
    ├── 3cb89198049f166dcf505e1d3842366d7ee90ccd.nq.gz
    ├── 3d5a91d8ceda7550f769c30d415679cc65842be4.nq.gz
    ├── 3e7ba6f425b2d83a524568705824c939ba230aac.nq.gz
    ├── 3ea7201d8f46fda3cd77ef283d75656c059a432a.nq.gz
    ├── 3fb2e29ce2a1d35b6b7bd37c927809e75e1ac092.nq.gz
    ├── 400262e353d54f27a5d27b297c88603023c16a4f.nq.gz
    ├── 4073b6c1a47ab5bb25ab2235b8de3582794e411d.nq.gz
    ├── 413af16ab278358cbc01a615d425c11e6271cacf.nq.gz
    ├── 42377fcc39574af66b8ccdd8635985778bf63875.nq.gz
    ├── 424a6ed131afec4990c53dcfa0ec2c9edceaa431.nq.gz
    ├── 434d57ca6cbb8ff08c6aa70a0ec65a1b36b18268.nq.gz
    ├── 43d170b792b87f0b6b29394b56225aec45266ee2.nq.gz
    ├── 4426159019ada1a9ca2ad9ed6ca5a661cd3abc0d.nq.gz
    ├── 45bdb77cb2899595fe2afffec371b79719fd18b1.nq.gz
    ├── 45d5655fb489eb065e278771c5516fb0d4e13884.nq.gz
    ├── 46f4c907c6e5379e6ae0d2a15eea5d23713116fd.nq.gz
    ├── 47f516dd7e5597badcbe1883847f228cc210946a.nq.gz
    ├── 488c93ba8fac28f17a0a0a70c43471c060b1cd1c.nq.gz
    ├── 48a898e7b151f850fd6553246114dcdaad6a0c21.nq.gz
    ├── 499da2dc7c1adcda6b0e71980094db54b4950149.nq.gz
    ├── 4a3b507c1abf48a91da8c4e44023efdceea00d15.nq.gz
    ├── 4adce89b1de83297f03eea1a760bd3994deda41e.nq.gz
    ├── 4e7c4a7efdcdfba501e65537018f3c1cf84bbcc7.nq.gz
    ├── 4e89bf0ec7c6005c1c1ab9a1fb256758992459a1.nq.gz
    ├── 4f08ccfa807f5e7af7bad8b8ea0a8c4152e4115a.nq.gz
    ├── 4ffdfeb5919976fb5ebea750e466fff82a3b7529.nq.gz
    ├── 5036c5bb5d590444572eff304e8f1077700a7f25.nq.gz
    ├── 51793a1539ec1d0646f90fc51457533054842748.nq.gz
    ├── 51eea64aa73e9fea7b56aaef1728acf5eaf37a1e.nq.gz
    ├── 52208575e57603e628a046a9015be21017424ebf.nq.gz
    ├── 522c074d01538f127c2d8dd3780c7c7936520d7e.nq.gz
    ├── 52671ec6dde342f0cb66f8bcc6d0b397fa6d6d65.nq.gz
    ├── 52773f4a29b2522fde809178abebff26bceacb7d.nq.gz
    ├── 5317cf6411ee3623d1f1230b9a52e38dfb5cb64c.nq.gz
    ├── 53eee0968d27dd125100c1382028410d4fa5c8c2.nq.gz
    ├── 548009419b99281cbb7c097f3bee689a237e4236.nq.gz
    ├── 5523c4114225d03d5c1056db85dcc3bdcc78a66f.nq.gz
    ├── 5572abe3d2aee0ff185c4a70fa7db235adb12bad.nq.gz
    ├── 598f98cea66a4627071d3385d338c562b20eea22.nq.gz
    ├── 59c67c2f8f1e7a60ee537b96818317cdd1df97e5.nq.gz
    ├── 5a436133df64c41ad2d45d41c12d9aae484dd04d.nq.gz
    ├── 5aab685a1db148698985cc67d41fa9b00ed3ad55.nq.gz
    ├── 5b055330ac251b7c736976e02311b73cdd7aa922.nq.gz
    ├── 5ccfde8d0aeb41f1fdeafa286234b03f0593be19.nq.gz
    ├── 5db38d5190d62f7b5356e0bd41e705f475c8ef38.nq.gz
    ├── 5eb82a7c2f255c711f8877d78e594c072505e05d.nq.gz
    ├── 5ed4cb6bb8295e2aa7904653bff0f16cf3c7ec27.nq.gz
    ├── 5f5d657e100ab257b2ff64a0d1e942c1ca1fb547.nq.gz
    ├── 5fab24de0897cf28df278e8c82554c891428d080.nq.gz
    ├── 60686f7d5f1dfe0a96a2930404766deba648bc22.nq.gz
    ├── 60f1d0674950e4d076a0f4a7cb4ba4af959da794.nq.gz
    ├── 61b842949cdca04d8246d878c9ca3a5fb1ad005b.nq.gz
    ├── 6203b339a2c5678c1aeb95b1d21ccfd629332255.nq.gz
    ├── 6363d1736fac93a1c0e915742f456b690fccc1b8.nq.gz
    ├── 637839dfbc0601018f78222927d2c9aad1f3cf58.nq.gz
    ├── 641588a2e5293f6be9d5afe201b52df86d8c32dc.nq.gz
    ├── 651321ebabe13d4247b0df0dde07fc120065fcd6.nq.gz
    ├── 683e1758d56e9ba6c5d87c0d54eb2d18ac763657.nq.gz
    ├── 68b18844b884c746fa7c230e2d789508203fcece.nq.gz
    ├── 68d88761949852172a56bf77f7508464ea068a0a.nq.gz
    ├── 691f013f92c1fa69b3b969bcb43afae55dddf5e5.nq.gz
    ├── 692a7962a28e3db621575b3081871f3c18082656.nq.gz
    ├── 693fce97ad597f00a3bf0a73d69974207e61836b.nq.gz
    ├── 698b27ac3abc7243a5b16e74f2f685942d25f8a6.nq.gz
    ├── 6a7a1d882fb12548dbc50e18955f31759a979d7a.nq.gz
    ├── 6af594c47a0c20aa610d33aedc5be4687a639bb1.nq.gz
    ├── 6c5cb2997f98fa5fe259f35c8127200e5dbc4e04.nq.gz
    ├── 6cfedb2bf223f17eabd06cb6a3b953c7ccf0ac2b.nq.gz
    ├── 6dc9db59095ce7541ccd4da82f7e7bd1788aaa58.nq.gz
    ├── 6de519d05cea2ef53806befbc2ef49880eca4d07.nq.gz
    ├── 6f027cbd80f49f00855ece74522cdb3a101af369.nq.gz
    ├── 6f64a565a38e78ff2a88341ed73b29066395a809.nq.gz
    ├── 71dabac2c6d7d8a2a6fb831bad7734419e442b99.nq.gz
    ├── 71e7600e270d0dbfccd3b52056cd687e1b189762.nq.gz
    ├── 7370386ea543db6a360b57e048d48c839b67f927.nq.gz
    ├── 73c1806a41f96cde57c4716258de1e2f6f32a696.nq.gz
    ├── 74e6e2b64d0eaa1d1a725a3d22be88e607020e89.nq.gz
    ├── 75639cbe2ca616116d1c28539799b011065d74ac.nq.gz
    ├── 75c0f148ff8252f9df142a62988313f97878ea40.nq.gz
    ├── 75e26df58bf8ba8bea8a840254d9a27713a52c45.nq.gz
    ├── 7694642cc2f54632858420b23cb086000d3da318.nq.gz
    ├── 76dd6835f59736126af3fb245d0c1e4331486483.nq.gz
    ├── 76e188b37510868a359922dbc44b2e6d29064a00.nq.gz
    ├── 7726e0985ec7793d815309af18a1076ddac67da2.nq.gz
    ├── 773013bbe3e05afb8c44830003f8b590a6240415.nq.gz
    ├── 77530d2c9252b6ba788314a65cb51d61f87aeff8.nq.gz
    ├── 786cd2c8cc4169c8a640e194a5d0af0450ffecd2.nq.gz
    ├── 78ec4dd1215ba82fb13470150422dac2ba94af0e.nq.gz
    ├── 792f7e268ce1b07841a63b28d2976cc404f63fa6.nq.gz
    ├── 7a0cc012c7acc84242d94667a718176cf53ca606.nq.gz
    ├── 7acc6378bc9ee208d9034830d457befbe7282cfc.nq.gz
    ├── 7c070ec326fe163b9f7d7dbb4708f9cae25fc8e2.nq.gz
    ├── 7cee2984496bc1d3e1b441d6da7b7079fe24ee43.nq.gz
    ├── 7da5d75f01e9d8486a1e743006d39745bc79d2c0.nq.gz
    ├── 7dcf32145d95a637f7ce1ef2b23201d614889b96.nq.gz
    ├── 7dfb5482a805b19690d9bf465f274bd99a1c8eb7.nq.gz
    ├── 7f528140415af511e72a10b61a09eb62e0e1ca17.nq.gz
    ├── 7fe2287ddb30a85fbaf52bf84756b7018d8347b2.nq.gz
    ├── 80a7b6e72fa2b91abe5c6fe36f4a7ded8a3768b8.nq.gz
    ├── 80d588875a2416bf2afb8a1cc0573b3afbd52f8b.nq.gz
    ├── 8140721daa22a09c466f2cd93bd358c5a644f554.nq.gz
    ├── 828417fcdf9fa3b32a3273a583688b569cab6080.nq.gz
    ├── 842bd38354befa171be1dde0c57158dd11c79716.nq.gz
    ├── 851e291874163eb3f0b3110ea1a8bf52087d4f0d.nq.gz
    ├── 858cece6d31fc691d8ac6b0a097bf4bd2ebcce3e.nq.gz
    ├── 8ad396ee7284c6a9c3f0f4388076447edce52342.nq.gz
    ├── 8ba3c92b3abe2cad41ff4e11264df56b24364e81.nq.gz
    ├── 8cc8365f126012ca319e80ace7e4c53ab8a9e24b.nq.gz
    ├── 8da763bd61b13ae9604da0cc220eb584de5660b6.nq.gz
    ├── 8dddde41b4bfd894d63f36b68aa9f2ecad32552e.nq.gz
    ├── 8eb509cae081ba65f9f11e3da486729bc4dc98e4.nq.gz
    ├── 8f511f38f0c27e622e9b1a65f29652951dfe5423.nq.gz
    ├── 8f63c8ddb386ecd42e384dc0ee7cbf74c4e6cf30.nq.gz
    ├── 8f7ba8a6484f9f5cb65ff16d1a478bf0479dacd6.nq.gz
    ├── 8ffbff8efb1cfa0d283a92666eeead0c114076a5.nq.gz
    ├── 902204c31c8e3e6f4ca971b9b555d1601dd72ec1.nq.gz
    ├── 90bfcf85068d4b998c91dc7f5b96d0da9a11efcf.nq.gz
    ├── 91417e9ed10603a57a8611f7309879c33bf7340e.nq.gz
    └── 91e78cedfe6be51cfcffe18b0fe9f632ac799827.nq.gz

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

[twisted/quotient](https://github.com/twisted/quotient)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
