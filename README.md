# Repolex Knowledge Graph of scverse/spatialdata-plot

RDF knowledge graph data for [scverse/spatialdata-plot](https://github.com/scverse/spatialdata-plot), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/spatialdata-plot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6c8b76d3fa866c9378f4b4b8fe1ae17b3b3d7b8c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6c8b76d3fa866c9378f4b4b8fe1ae17b3b3d7b8c
│           └── chunk-001.nq.gz
└── blob
    ├── 001ddbabbaa7446c9fabb77ba99bf8467c9f151e.nq.gz
    ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
    ├── 029718736de3352b660753db31e1f0432c9ce273.nq.gz
    ├── 031566db55c97d04fdb2d764cffc1de7bc0fc49c.nq.gz
    ├── 0317972879b29f14c7c7a070c15db090c2eaf01b.nq.gz
    ├── 03878810e82ae3fe2f3e56c4090dc209e9a2e585.nq.gz
    ├── 03ee33f74540445dec23dd48e7778d9d45949969.nq.gz
    ├── 042b98f85e6bc8bd4200d9798c713a3abfd44411.nq.gz
    ├── 0473d58c57f2156f7d47bed95a7cee491f36963d.nq.gz
    ├── 0477e1336b12ad0c4bd1e3f7c04641f74ff49c82.nq.gz
    ├── 04b445ab9401c5e7b244d39c5a84a151d10648a0.nq.gz
    ├── 04c00f56ebeb4464c3a0a1d55eac297f160db33d.nq.gz
    ├── 04c889b3a82715e546477868549f2f0bd1082b2d.nq.gz
    ├── 0511ea807c239534cf8714c9018fd7342fa6fb49.nq.gz
    ├── 05a14c35ba7deb1a2f4ea6441bc77b09abf4da04.nq.gz
    ├── 061da1b77df0a1f9e45d202ae2c7b9632ce21343.nq.gz
    ├── 070f8e1d9bbdf06d21ff525de4aaabe0dcb6db94.nq.gz
    ├── 07e959caa86aa6e47d7c433c17221c5d1e6c179c.nq.gz
    ├── 0807af6da8cb91fe513cd6c8093cb7450e6349af.nq.gz
    ├── 0848f5ca1c1e7e4f6d020d8111b04117fc7116fd.nq.gz
    ├── 094ed9651320972c7461392edba3582693f287bc.nq.gz
    ├── 09a6bbb788efc70c88fdb9e678318c288e334f15.nq.gz
    ├── 0cb5657cc8812e2f607bc5e8ee4ee82c39b8971a.nq.gz
    ├── 0cf51c43e0839fa194ec17f0b79ba079c0994f3f.nq.gz
    ├── 0d251b9d035d5eee09e9267da42b3432c440a698.nq.gz
    ├── 0e9903b5df91e9a848bcc72f3a2b6a3937833204.nq.gz
    ├── 0f59149c14e34f6af18f3d9b230e4456b268300f.nq.gz
    ├── 0f9840c24b7fed47929f7ae846bf082984487bf0.nq.gz
    ├── 10317dc9566d0af05e0cca3c912e56a459672a8c.nq.gz
    ├── 104fd852ce906cf62355d835c1b4ed0e24c271d2.nq.gz
    ├── 138224b7982d552fbdc84db0b547e975f5ece47d.nq.gz
    ├── 14ef6be63311c804f24ff26b0083010fc6216804.nq.gz
    ├── 158f52766291f708c1be90cded088440d6715273.nq.gz
    ├── 17291ba903deb7595737cbc944c31ffdc102954b.nq.gz
    ├── 17c5ed29689db0b0e8e573ea2d7edf1e8838ca4f.nq.gz
    ├── 17d48092abf259380938461256420e8fcde15c48.nq.gz
    ├── 18cd7956828740b77b5b30bff48951bd246153c4.nq.gz
    ├── 19b508de05eb75c42fa8d26e656677c864c11e55.nq.gz
    ├── 1a591f7e73ce630a1a318a434ebde884aaf7c173.nq.gz
    ├── 1bf9680e2ba162b00367836d260d719b6c379394.nq.gz
    ├── 1c018591ad7a520f4073d5d965368b9f38c268f4.nq.gz
    ├── 1d8eb6c2575eac764717ad28b2db4cdb66fed0c4.nq.gz
    ├── 1e80d945c0bfb49ca93d93c39bb1a2146147e69e.nq.gz
    ├── 1eae50e4e1ba8a097a3a4e15d2b314defd58ba81.nq.gz
    ├── 1eeb7bcf3bb984b74e462d993ba4c8137b9ddfd7.nq.gz
    ├── 1efad1d39069d3e694e03102d65ed19587017efc.nq.gz
    ├── 1eff92282b4fcc67f61a0d618bfb749d7d226dc4.nq.gz
    ├── 206b63fa6b498d410d64e2ea4dad7aaaf4af3216.nq.gz
    ├── 2080f01ab398c801aae05dc0ed56682756f64428.nq.gz
    ├── 2099e7d85d649538e84c431ae88b8f7272fcf990.nq.gz
    ├── 221a4d0f3ee121333d61bc489bf473d99b01b4d4.nq.gz
    ├── 225bb452681fee1d588baff8e16c83ea3070da98.nq.gz
    ├── 2398f62740d6c35dea56446e2c9b7d6341624b07.nq.gz
    ├── 2618c49a8a7857268bd5f033ce8d30a0d0a81cc7.nq.gz
    ├── 26f0cce0d83f2d8566a9e0c899a0e884c83dd5af.nq.gz
    ├── 2779196f3e0acf0739ba830cc4522e35c672264f.nq.gz
    ├── 27a4341b29672f7f181d433336c6d496cdcaef7a.nq.gz
    ├── 283d26f46946220ab54129b73205278c474bb763.nq.gz
    ├── 295a681876ca950f03438d7396c51f05bfcad209.nq.gz
    ├── 2a2866740499180478ec29e5e9d619ca1a6b89ea.nq.gz
    ├── 2b6b25c1efac8ef44f622f894a3167cae45f4076.nq.gz
    ├── 2c068555ec39195ad366c1f92c9fcd592dfbc29d.nq.gz
    ├── 2dbbd7847a1c54b10c7f7ba0d0281ea9ae488d10.nq.gz
    ├── 2dc005286ef2099eae771bf6192b6403029d9cce.nq.gz
    ├── 2e224d5b7fdb7b20acd35c1e686a57a0e1b21e47.nq.gz
    ├── 2e9ab8cb6bdf278d9e1657c87025e7a729fc31e8.nq.gz
    ├── 2fd8e38361946c16f24afbe5561e07ebcc262631.nq.gz
    ├── 2fe75b07033c2931737f15959d4fa685be2abce2.nq.gz
    ├── 300915a3a11df32baa60a69c04fc8da08769b71a.nq.gz
    ├── 320096009382d023b4ea4285b4bf4afdaac734b2.nq.gz
    ├── 32b8dfa5ba79ad7b3bf218a7d97132754e0bdb72.nq.gz
    ├── 3332f0fe90511f867d690dda5994e146a92cdf35.nq.gz
    ├── 3333600dc0d3c0912b86c839a68c45adf3f99698.nq.gz
    ├── 35d74d93defb5fb37bd29e06a90fd4487c1505bd.nq.gz
    ├── 368303a40480c10fc40af0fe440902440f057bfb.nq.gz
    ├── 36b255f30dd8df46ed6219720c71d38de98b9dbe.nq.gz
    ├── 386f61ef16ead44a20bf1d903ad02deb2fa5c5d0.nq.gz
    ├── 3a23b42d750f31133f7da34306a13cfba0f25dea.nq.gz
    ├── 3a464fbf014aca108ccea51775d939796256d717.nq.gz
    ├── 3b40f031c36aa0243bab2ace70e71c2421a38b95.nq.gz
    ├── 3be6d2bc055221d799a29cdec342f86a26e2960a.nq.gz
    ├── 3c041895c49045bd84f43ed7156dd36e8e3c75e7.nq.gz
    ├── 3cfbb24f1b9bc86b4ddebca7236d1cae637c471a.nq.gz
    ├── 3d3e9f5fb321d92418ba675a34882f77b9219d30.nq.gz
    ├── 3d4ba4e65e722649278acf6b50e8b466f7ac4bea.nq.gz
    ├── 3d59f288cdb3573e9e4832d687260bfbd3fe2dbb.nq.gz
    ├── 3d824efa3fc57e37f5cdfb5f216af5b7e33beae0.nq.gz
    ├── 3d844b33006be81e502c57b8ba4245ac62469cfd.nq.gz
    ├── 3ea46550f1ae4ca9cd722e8c635dfe151065c474.nq.gz
    ├── 3f3c6565116ef3695e8e6fab49210659ebe73b68.nq.gz
    ├── 3f887d9bea845f08de350fd75091e7726020fa5d.nq.gz
    ├── 3fa74aab52cb410317665ff4f943a073c92a989c.nq.gz
    ├── 3fc4934aca0ce0d1e1c1c263d7a1224032d7b892.nq.gz
    ├── 3fe95f2f855c7749c9a92ec98c6e147101a84026.nq.gz
    ├── 4070fe995018e1197f073504cd3679ed32defe7b.nq.gz
    ├── 41a9cc62cce30f8d71524e69debd5b91042e5871.nq.gz
    ├── 4260a82b474de95a2dd858d1b591e4c265828c36.nq.gz
    ├── 4269aa11da1e1f54e0b89b28034bac951f6ff41e.nq.gz
    ├── 42810c8b6ab5d4a90a5a0052c3bbf5c043186e52.nq.gz
    ├── 429fdc4f61c783ef9eb08e653c3a5965f5f5b87e.nq.gz
    ├── 42db1cb9e8da77b10a7f145c3e88dcd8f916e9bb.nq.gz
    ├── 456c4aac75f9dd05669e609c42358e7777160f50.nq.gz
    ├── 458ffff65f8b9977496ef94a0bf7f32a38f533aa.nq.gz
    ├── 461569ab9230998c760589591c0225eedff59c41.nq.gz
    ├── 467d81a244b4e527f660bdf464837762d77cffda.nq.gz
    ├── 46d9dc44661817abc439ad88a09b0e75cb67af5a.nq.gz
    ├── 4768b0e0b5c69ff68990ace65ab4bf826e2c19cc.nq.gz
    ├── 486d01ef7ad01ae1a718edec81c0715c2e7991b3.nq.gz
    ├── 48bbce0fcf5dd947f6ada15559083ee629a0613e.nq.gz
    ├── 499b94135669dbd76a2502417c38fd4b5b71f34e.nq.gz
    ├── 499fb50fe43ccf82d8ef3b3e9a1548f34c058b7a.nq.gz
    ├── 4a88673205baa2752252747168dbc8e477dfe33c.nq.gz
    ├── 4aafabc55dd51a39e4e05162f58d1ba483863e07.nq.gz
    ├── 4b00fc9ada617165652a051b4e9628a932754326.nq.gz
    ├── 4bb4398e11ec8aba85e862cb45a8287dff05143d.nq.gz
    ├── 4d6d3861e852ff0497a550c19a99483b3b80a0ce.nq.gz
    ├── 4d70491aa98d84480937561a724b065c177ca3f5.nq.gz
    ├── 4d7865d1e1dcb670ebce235639790f83ac41f701.nq.gz
    ├── 4f9b71be3cf84356446e2460f0b54fd0ccddfe18.nq.gz
    ├── 4fad8345ae83bac026b512c02dfb03728a65460c.nq.gz
    ├── 4fb03579c520677e6264612bded72685726e2389.nq.gz
    ├── 537aa53ed8c56f70eccbbcb6b7aa19eb4a727bf3.nq.gz
    ├── 53b93c4745b72ce294afac38ec45641f2ed4e3b7.nq.gz
    ├── 55085556a9636381f9a22a2163787c7be879d26a.nq.gz
    ├── 550a479c21f91994742b595403512a65a752c8dd.nq.gz
    ├── 55329ea95ebac0247a1871f83d123d74caaa967c.nq.gz
    ├── 55ee5e497f55267f88ded6e1b612cd23778e2a67.nq.gz
    ├── 5673358e889fe0467d9d178e6160f9e6897fb3e3.nq.gz
    ├── 5683233e5e86b478e62495b93ce16d32d635f36f.nq.gz
    ├── 56df1942e031bd9d9f7e6650f8ea8ad85bdc4ecc.nq.gz
    ├── 57aae80a27d91800062f529a77e1cc335a532b28.nq.gz
    ├── 57f0d6ef90579ed184ab1ea06a71957ee976792c.nq.gz
    ├── 5817a42d8ec54386a3415cb77ea600b886f7403a.nq.gz
    ├── 5830a3946bc8106451d42926d6cbc0d35a211930.nq.gz
    ├── 599e7b570ea6a8be27e31a8c8319497c4c832584.nq.gz
    ├── 59c50cbb2a274dd53b14fc4c39b7e47dd35d62b6.nq.gz
    ├── 5a4fa893d3ed5df34282e8caa3dd968c467d3d34.nq.gz
    ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
    ├── 5ca5d8d122a5e94832906ee87ec6300325d33fbf.nq.gz
    ├── 5cb53dbc9ceeb55bbd50a58e32c030dc62dbe5fa.nq.gz
    ├── 5cdf34c18b4b07865853a801431d53fff7a5cbd4.nq.gz
    ├── 5e4a75bd71851720db85604eadbae287fc1e5ea8.nq.gz
    ├── 5e6cb1afa5755a394be73a8bd97bfd171c578502.nq.gz
    ├── 5ec89f6d9b550dc4eca3ae101c8fbe2c43546a16.nq.gz
    ├── 5f2fdbaa72b163e799c37ac37b73eac3c2cfc598.nq.gz
    ├── 5f3aec85b17bac6570b593122e7c57114d53d5e0.nq.gz
    ├── 5f45a9a3a3fcd1c6a3952cbce4c5dcb5e0170960.nq.gz
    ├── 5fcf5c1591671e8ddfddd2e73fc42c8706f92e35.nq.gz
    ├── 600fa8422c01fd9ced2e707ebb408196f89069c2.nq.gz
    ├── 60e23dfbe4a83222a5438ec44fd1294f6fa71560.nq.gz
    ├── 6128bea9c9b25571656c072499b02dd16f1e5a19.nq.gz
    ├── 621039af96c8c129eb3fab8f2f166d60d6d2271c.nq.gz
    ├── 62658aa499e00f070da40491d8f173f130e3d6c3.nq.gz
    ├── 62c74bba7afac4500698f983f71bacb9750d4c08.nq.gz
    ├── 62e646daa83772a368f740045a8e133e68d53c12.nq.gz
    ├── 6372ff0ab06e8a39ff336eff52617780a6ae82e4.nq.gz
    ├── 644827af9e96cb09f0711e121bcbedcf7f01ae7a.nq.gz
    ├── 64d0599f215682264f3d77c8ceb35e80d4e950fe.nq.gz
    ├── 64f98e8ba0d8735e8597877ccfda9843fe38dc5e.nq.gz
    ├── 65168452341f0431a27997f5a87c13287ab81eba.nq.gz
    ├── 65267bd7ef4f989fa7c7ac1e8acd1eeeb745c7e3.nq.gz
    ├── 655f20198c238b11f26b03419cde4cbafb5bb3c2.nq.gz
    ├── 65dca162581e171e4ba638ee8765649b99521019.nq.gz
    ├── 662ea063846d3b0618afaceb736809151728b45e.nq.gz
    ├── 663dbbe294f895f852d3dcd9783cc6082f5dd4fc.nq.gz
    ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
    ├── 667760db6cd92360d51c8a91c0465a300d747db2.nq.gz
    ├── 66c87d0e70a3320ec825519bbc174a7207fdd6b6.nq.gz
    ├── 6775ff363be259aca1acab83ada3265c4933a902.nq.gz
    ├── 677908e7a9d2ac6c088422b4e6e9d76bceb6afb0.nq.gz
    ├── 679047633065f9c3c2253a5abda5fb784dd7bb1d.nq.gz
    ├── 67d5143e9e355f8b29d27308ecebd7148d58f65d.nq.gz
    ├── 6800647ec31608144d47e761921091b387dad697.nq.gz
    ├── 6804121a2404464fb97198c62cd745d5d66f79de.nq.gz
    ├── 6924ca0e6bd1b157723e213271b245f33b79af8b.nq.gz
    ├── 6a20052c05b89b27b42a88736bd2e47696e0dec0.nq.gz
    ├── 6a9be146ee400e77c248d5b563e290b4900b029f.nq.gz
    ├── 6ad7c002663d62add461ef392d7824a2136d257b.nq.gz
    ├── 6b015cfaa1a3e9a3ba572ebca439caecfc838641.nq.gz
    ├── 6c3cf44c810b923a0683168c3f9ac8e581bda524.nq.gz
    ├── 6c935ee36492f8e50d44b00cd74a743a34a97ca0.nq.gz
    ├── 6d0806c56d38e309f56765f6483a4211ee1a60bc.nq.gz
    ├── 6d50bd38e160331465490965d6b323ee9f33190d.nq.gz
    ├── 6d739f6844d04beed8c619639ce6eb83d4f2330f.nq.gz
    ├── 6dce017ae060469904d19dbbb0e36c5af1740c2c.nq.gz
    ├── 6e05a6488660527a7e264ea0adcb7e8c452d7344.nq.gz
    ├── 6e222e8bd09ccc45bd43d464cd3ef9de0527ee97.nq.gz
    ├── 6ebbae8105e9b23c57c59a0f30f71dc9b033310d.nq.gz
    ├── 6efeaa669ba0b199fdf12ba7b0913f6538ea1d34.nq.gz
    ├── 6fef5035d70341b785cd11d6beb00e98cae7fa82.nq.gz
    ├── 70788eb7498c5311f4fec883a9334d2edd6e9ac6.nq.gz
    ├── 7298efbe294d155162805a256cd959c64515fdcd.nq.gz
    ├── 72b83510362ce0d525fd3d3b08e4ac8b94581179.nq.gz
    ├── 73d7a1abca74e6e39eef21b151a2248d11556d30.nq.gz
    ├── 73e1c6bba5488f6b6fdd66778262337621f895f6.nq.gz
    ├── 746daab20606711d2bda2f543c986b94e70e4f9a.nq.gz
    ├── 75e70f97ef74046a8bc08ea4dc65bcca00d344f5.nq.gz
    └── 76cdadab1519afcf339e1ba6b63a32ead760b2bf.nq.gz

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

[scverse/spatialdata-plot](https://github.com/scverse/spatialdata-plot)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
