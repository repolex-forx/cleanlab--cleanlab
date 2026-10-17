# Repolex Knowledge Graph of cleanlab/cleanlab

RDF knowledge graph data for [cleanlab/cleanlab](https://github.com/cleanlab/cleanlab), parsed by [repolex](https://repolex.ai).

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
rlex download cleanlab/cleanlab
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 750625747de1b26d8530954f51f0530bd0b51d3c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 750625747de1b26d8530954f51f0530bd0b51d3c
│           └── chunk-001.nq.gz
└── blob
    ├── 002d83a4e640dc18db152e93c20c72595131e7eb.nq.gz
    ├── 00592291f10c7048f5051d66d8f61f9b218bf79c.nq.gz
    ├── 043fd6ef8269c95e3fa71ba93dc7d486636d07ff.nq.gz
    ├── 056b4d38e3261a9f589796de91d8657b92847e65.nq.gz
    ├── 056bfbc0a2263d27666a29b356bdc856be3094a4.nq.gz
    ├── 057e0201b84f90a913b75d2aa6c9f2f678ffad79.nq.gz
    ├── 05a4fa09ff131e8cadc20b0e6687d915ac7f4776.nq.gz
    ├── 061f32f91b96f05f8fa2b52b2edcdcc19aa33d50.nq.gz
    ├── 06ea1149d6b765eaa10f9c8e7803804e9ef49dbd.nq.gz
    ├── 07f901b67b9ca0c85b5417b86d7e19adca8330cd.nq.gz
    ├── 086232110c7a37976150a0403c183fa93a435d5f.nq.gz
    ├── 0910bb056939ec2b0036e3596056f07d444b96fa.nq.gz
    ├── 09d6928fb95bdd1ee9a75fb53b294551b39e6749.nq.gz
    ├── 0ad6a348952ddd2e9f83d26fe3ee103da7371aee.nq.gz
    ├── 0b306746f47cd3c5e59aaf11690514fd1cebbb7c.nq.gz
    ├── 0b65f1ea4b4bae15a75dc1812f1b3b1060cbc3b7.nq.gz
    ├── 0c131476eb8f15328142cafdce82ef3645de2716.nq.gz
    ├── 0db24321d49c7d9db092f262bf1e9be292f36212.nq.gz
    ├── 0db549393959b00c7f5a4c731d9e17d12626f15f.nq.gz
    ├── 0e9821010b1fd911cfa71b319883ee69db5b9e2c.nq.gz
    ├── 1262958fed8f8bd18cf5976f91e0f33f71d42575.nq.gz
    ├── 126b86289d7946fa7413e9d555c2d134d1f936eb.nq.gz
    ├── 1273029f6a647162e18d07099e6b920855f433e9.nq.gz
    ├── 13c08d35d356669578b713ea39f0f73108b57e7c.nq.gz
    ├── 1433f8d030430ae3f45122e2bb48a401b95a49c1.nq.gz
    ├── 1486a76e16614692e3cc071ed1dff081c920b6ef.nq.gz
    ├── 15392d4a5e838ec3176f74f26b2abd71270ebc0c.nq.gz
    ├── 15d8adc477c8e35e7399ea02cf55648da0df6da7.nq.gz
    ├── 15dd6686caf874e9c894b4d76faebe4062360a4f.nq.gz
    ├── 162c5767449a6a22d7fa45f61aa56d8b48974780.nq.gz
    ├── 1726041566c5d966ed4028b04601256865f7069d.nq.gz
    ├── 174216c21d3aef4688401e02ba37a5a9200d611d.nq.gz
    ├── 19226ef6c52cf513484961111d86b797f22cc69c.nq.gz
    ├── 19bf1451f5720a279afab3853f129e1649a6176f.nq.gz
    ├── 1e8ef2d3d4e759bd0965b973020943a2b2b4bf6a.nq.gz
    ├── 1f2acce9cb222facc8f0073e577b15c960172873.nq.gz
    ├── 1f6348251899241a00575484cbbe9dc48e08a166.nq.gz
    ├── 1f8a6423b0be327ae58315354bd0d6fcc73e5f13.nq.gz
    ├── 214c7e316317a464fcf6ff2b3b9af7e87a5cfab7.nq.gz
    ├── 2369de8d56418778fe334bf32976e9f5ce37113e.nq.gz
    ├── 23c28d0389e9e99c30cd47a49d070d9d59d0b421.nq.gz
    ├── 24320ac2b945a0c45681a049741619a634fe9056.nq.gz
    ├── 24cabca11574d21c5711ca2527f01db0096119af.nq.gz
    ├── 2575a8554542366e0517f5008f4aa08a112e28b9.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26c516758ba3603a42c62be8e0ef79517372b4eb.nq.gz
    ├── 27439ece9623c0dd0b722165f779650b09207385.nq.gz
    ├── 2991848414ea5d30bceb2212d121e5954e6e8f86.nq.gz
    ├── 2a5eb7a79147c122b448b6c874f8254ffb2661ad.nq.gz
    ├── 2a90a6224eab80c14c27a6eb4623332cf1463125.nq.gz
    ├── 2ae34be2a48017bcde0c7b4c1cf06599d3ecba2c.nq.gz
    ├── 2b73d27dd800f0f0e9744358a1eb63d9531dc9c2.nq.gz
    ├── 2e7b99b7fc9a5019289bb03a961b0fbf9bc03dbe.nq.gz
    ├── 2f9c8a44dc60273e29074bba7f3ebbe82982643d.nq.gz
    ├── 2fa6a6643f423bfc9616147e35cec5bb3ff6c656.nq.gz
    ├── 2ffa0164a2c66a6c2699fb370e1985a91371287f.nq.gz
    ├── 3059965aa108446595641ec2da8a915b7261a1ed.nq.gz
    ├── 30901ff49f0a86f3321b7d2e8c52e636fb3fde33.nq.gz
    ├── 310bff5aecebf7db6f4ba04b398c5dc2b1eb1cd2.nq.gz
    ├── 313a1c9f373d6ab71fc05d5c8f477780d50ca125.nq.gz
    ├── 31e363c659d358fe071dad73ccbf1188a7970f93.nq.gz
    ├── 321be90ecb7efcf9d7502ddbf654b36956060183.nq.gz
    ├── 33f743584b3b0bc77b645ceb4902dfc5903f82f8.nq.gz
    ├── 35c02123359011eba5ae48f90155fff273b25a86.nq.gz
    ├── 365c0171b129e0af186cfd766e88c9bfb464c7be.nq.gz
    ├── 36eec92edacd53a941bf5498357b2028ff18cd13.nq.gz
    ├── 37e7b2b95fc0604b06ed691d0887b8287ea983b0.nq.gz
    ├── 37ea6d991549425f1f2496b836e8e7825498c597.nq.gz
    ├── 3808e8b3b6c1cfb79b8f220dcabe77bb0fb32b48.nq.gz
    ├── 3815719456d52ba1fb61cceb297c0fb8af2ad089.nq.gz
    ├── 38221250349e221f2e75cf9dcae50ce007935a9d.nq.gz
    ├── 390ba163263e9233f127a0e8c72e1cc07596d3fb.nq.gz
    ├── 3afcadf8bf671f7b49967d513fa4d3a9be8fbf3f.nq.gz
    ├── 3b24007b89d9f288b4af7df4dfdccb172daf92de.nq.gz
    ├── 3b3956ca3ad1296f5df937b80baeb7a2126dfe85.nq.gz
    ├── 3bbb149a1fef9235619fba58f26fc1042fc81b71.nq.gz
    ├── 3cd1be95fc8c8e7f7278c8ca127ee8618e7e1338.nq.gz
    ├── 3d26d643ccb35196d28889f106ceb7fa79a6dadf.nq.gz
    ├── 3de928cb26cd37b25e3ee2cd7a03b95ddc9a3cec.nq.gz
    ├── 3f37fdc9c72b32e7ff1552ae08b63d4a6d302dab.nq.gz
    ├── 3f5709723e2fb1aac55e662c8a758ae02f869b11.nq.gz
    ├── 40090b16d70c7a677f6cc7815cf0915d38391ff3.nq.gz
    ├── 406a7756cb33072c6c02628b0cb23fc0787e7f58.nq.gz
    ├── 42ded02f54c74b9260b459fc0b8508003db58b50.nq.gz
    ├── 43032d8c4e5ce1f014b6656e43a21d4676c982f7.nq.gz
    ├── 43b41f89e3b5cb03758a26d8a849f366a6365671.nq.gz
    ├── 443cb185ae2540e217dda90db4ef6bfb395bb2f1.nq.gz
    ├── 450dcd0190aa4831796c0e5771581400a56f6753.nq.gz
    ├── 45b935e4843a5b07d7f69f7830b7fb1a5ab79a91.nq.gz
    ├── 474a4aadeeb02153488a2100ff94a1b314e12f96.nq.gz
    ├── 4768841c2c41bac09d996429886a4b2363e8d6ed.nq.gz
    ├── 4873d2bfc305494f16008a2ec8197d979e8cb5e4.nq.gz
    ├── 48aabe1a0406804e2dbfea3a9d90b0d019194ad2.nq.gz
    ├── 499c5263fb6f4532afff75b9b776f6c3ac013322.nq.gz
    ├── 4c7b2c35bec0719b658bc9eba682b051d0726c2b.nq.gz
    ├── 4cff4863a0f9c2a3e1c9d1d0cc7e2fd46a6ed5f9.nq.gz
    ├── 4f800752e97c72fbb7e5b8cec6255e7e110dd953.nq.gz
    ├── 50f55a219393b50e40386601dd116ca94900d8b6.nq.gz
    ├── 51102ec046662418dcc636d4b692e397d743ae59.nq.gz
    ├── 5209fc8b3026a613fa297ce02790a7eeaa88da4f.nq.gz
    ├── 5384d8b2597747f5db6c400e5dd4486f41451dfd.nq.gz
    ├── 550451b1eca1a686196f975dd55b6e6dac893ee3.nq.gz
    ├── 5519d4e99ebfdb936ec1e9efe61ad9bc3ffccc0e.nq.gz
    ├── 552f7b802b7a097833225a62326db7b0e84f6dc4.nq.gz
    ├── 553a6b8d3a0b68e17a1de810a1a332a3808a2c94.nq.gz
    ├── 573254e56bc8aad648d984eab15528c86912a98d.nq.gz
    ├── 577e097c7cc7b5ff929377563d858f1b84ef5156.nq.gz
    ├── 580bc8d07210f30d1c81b47c10aae7af36f98ca2.nq.gz
    ├── 58816872ee52598c6ee0a55bbd367405a94e965f.nq.gz
    ├── 59364125a16e7a133c5b729b6dbe491312fecbde.nq.gz
    ├── 5b88c9469490e5c29df4bc2cf6e039a39dec308d.nq.gz
    ├── 5b8ee6144fa4722a43302a5c0bdc8edb18cd66a5.nq.gz
    ├── 5ba606b0143a26577a8ed303135a0786a1f81a30.nq.gz
    ├── 5c8a3b97a3eb5cfa4d9b9f95ec453870b5297faf.nq.gz
    ├── 5d115d06b66a0b445d7e693955e65432b5be6426.nq.gz
    ├── 5d80b4f7444800febebd49610579110b6b235040.nq.gz
    ├── 5d97e7e011177a7a9a6de20af3cc0453f2811dc0.nq.gz
    ├── 5d9e5701d45bb63ff7248119fca3155d55bd80f3.nq.gz
    ├── 5e38d82e7fdcec61ff68d65786b03877738ffac6.nq.gz
    ├── 5e59f88b58f511fb3e7339b456c543163aa57066.nq.gz
    ├── 5e9f9559231ad7444492cf812b001cb54fcc553e.nq.gz
    ├── 5f1fde5402b466a327950f4b2970e2c47943cd00.nq.gz
    ├── 5f4d901c0d9a758b598aea0c42f316d693d056d1.nq.gz
    ├── 6133d4c0ce6a5bfc4bfd8b37266ac2b7e0886c63.nq.gz
    ├── 615faff5c0b089ef65d2e21f0c1828795815818d.nq.gz
    ├── 63dc2ebc1a22fe32ce0dd9f27d77e4e68f8a5125.nq.gz
    ├── 63f4c9cd73f13f7647e172416020b220a753a9b1.nq.gz
    ├── 640716bf7d5879fe30308b2928563dcc5f711efa.nq.gz
    ├── 674e73a8d5ff7621ab40f6da23cc8dbe2229541c.nq.gz
    ├── 67e977e1424c28237b6aa146b38b52a7a2d2c747.nq.gz
    ├── 68e80edf85335c9a66690c78cec154cfb8d349b2.nq.gz
    ├── 6994eeff7878ae5b26acba820d809bf85461704d.nq.gz
    ├── 69ea1dfcde0fe057b29935457828ba37c81cb3f0.nq.gz
    ├── 6a7af57563dcbce6a33e2942e10417409c848ed6.nq.gz
    ├── 6b0bfeae4808e0f68f6dd7ddb59dc77ed01bda40.nq.gz
    ├── 6cc446e6fc5577af5fc2252a866028bc9fc218e5.nq.gz
    ├── 6d651439df4066a3112e07107cb11b449d4e9df7.nq.gz
    ├── 6dc86aba359ab43e899f70457c866c3e3abf6f26.nq.gz
    ├── 717cf5bc863cc34cc59d5fda073004d2f4e2934d.nq.gz
    ├── 7248b11f73c14b48e271183da1b4c725122c3361.nq.gz
    ├── 74eee8258da241851a9a27910af64a3f47d26eff.nq.gz
    ├── 75752ab9cecf6f4155db7faffe6973681adc7c1d.nq.gz
    ├── 768348e9145a5351c124e571d37771cfed63e21e.nq.gz
    ├── 782749c7513e9a01d2e648a48bb8aa1125a551f2.nq.gz
    ├── 7968d6aed6e43f28265bf793d33697d2dddaf14e.nq.gz
    ├── 798062f5b6ce565005171069e649b2fb3140e058.nq.gz
    ├── 7a2e1607d1befc425b45d0d8dcc705b907aa992e.nq.gz
    ├── 7a30058aa8471f437c659ea99d1ace7ca0364752.nq.gz
    ├── 7d6dccf43dcd7aa99832fa44e05cc17c14cc8aee.nq.gz
    ├── 7dd0de8c949c2d81e2c2eaea3c6c6ab32b605eb2.nq.gz
    ├── 7e48283b3e9c4d2f46915ff9d84d6ed8c65b828b.nq.gz
    ├── 7eb52ddfdf7fdf2eef7c7d0cec5b41919facde7a.nq.gz
    ├── 7f0766e089335d0f4b5c48d9c955575070b0745b.nq.gz
    ├── 7f368374e287ebc0edff01bea8a5da1e44f8b2c5.nq.gz
    ├── 7f9f2f5508a509861a345278ef98e1d6a1325ec0.nq.gz
    ├── 7fe443917c121edf9f4365b94445f7a03f4858bd.nq.gz
    ├── 809f7b25aa1002a1149889242176c021b81f84ec.nq.gz
    ├── 81f60befd32d09dab4b02703a75ac3473c7f1d18.nq.gz
    ├── 8346f23c156bac5fe98d4b14b48cf5c26f9d0355.nq.gz
    ├── 8609b9d4391643eb87177d623f0ef6a5447ff0eb.nq.gz
    ├── 8610c7089e3015417da13775425d55ddc2153b1b.nq.gz
    ├── 867c64936d8b30117073800fc5c36c179c330885.nq.gz
    ├── 8892bd5837ae901fe5da59c174dadc03e32aeea5.nq.gz
    ├── 88b17aebe12fc7e6e7d31b1a22be391a4301a5e0.nq.gz
    ├── 8a05136b1fb41247a522f834887b0ded5052dbae.nq.gz
    ├── 8a38a27f950e6c11d1db050affb5e56172fef44c.nq.gz
    ├── 8a5eb8f5f50ebc77b937ada3e0d184c4dcd1f4e1.nq.gz
    ├── 8a7f1ae39a079ca494dc71c2db1664dc3f3f2fbb.nq.gz
    ├── 8aebf48ee70033c28e9db5d9664544ba1c22b56d.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8c106dee246734ed450e19a4f6de23aec28b0bb5.nq.gz
    ├── 8cb06d0a8990410aa630f68c74e7d071da9544ba.nq.gz
    ├── 8de4222d1d5bb6825d3b174d16c3fc31c6ef87b6.nq.gz
    ├── 8ea2b2659e747663ef763cc788100261bc21eb21.nq.gz
    ├── 8ec8451d090c83f18ed52c7b3abdd12ffee9550d.nq.gz
    ├── 925e2a743f89d489d9be404122bdabbdc3b1b6f5.nq.gz
    ├── 925ee25da6daf081eea03a7611907d244e25af64.nq.gz
    ├── 92ea3494f2876b2824e6dc6679970f90b14448db.nq.gz
    ├── 94c20f163d016fe12ff6350d3aea1889fb28bf19.nq.gz
    ├── 962a87a19778b5e557167992fdf35e0b6fbe3c23.nq.gz
    ├── 96c419440e650a37fc4af482859455521f512bf9.nq.gz
    ├── 9928af71eb7c67c379934383d12b2460b80e023b.nq.gz
    ├── 995f40fa7f4a4ce63082e3e59a5dd99f08bcc2fd.nq.gz
    ├── 9b01e3764ff9752a93e538f0cd4bfb320092c958.nq.gz
    ├── 9b7458d453a54c1f24b8aa1503d13d03bd135642.nq.gz
    ├── 9c2753597f05ee622e009c872165b4a5e526f9a7.nq.gz
    ├── 9c2821d9646099c02d648663ba2bf218d1b689ae.nq.gz
    ├── 9e9aa27f103de1db65c369e73fbbdc958bbd53fe.nq.gz
    ├── 9f6140d2fc7cb6d6ab8062038fffdbe5d8358ee2.nq.gz
    ├── a139f581e44efab743e3cee22c954ccdd1b13397.nq.gz
    ├── a1f3d81af64c448c1e83ce9a3553bbd502eaf3ca.nq.gz
    ├── a266bd8272d36fbeb8b144ce4dcf8d591daa7dc9.nq.gz
    ├── a3ee910f5d2c406fae633d3acc0e37de3f623e8c.nq.gz
    ├── a43b33f2172865ac2683d90b3cc38f17b71870a8.nq.gz
    ├── a4945bd46866bc1af603348b3b7311953ed09638.nq.gz
    ├── a73dcd25a18de9c93f2ba1269ea912869604642e.nq.gz
    ├── a8396e997fc898eae797f3a3da728673a618cef2.nq.gz
    └── aa3330842788086e2a6b697a384812089e9673ed.nq.gz

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

[cleanlab/cleanlab](https://github.com/cleanlab/cleanlab)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
