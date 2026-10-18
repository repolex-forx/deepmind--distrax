# Repolex Knowledge Graph of deepmind/distrax

RDF knowledge graph data for [deepmind/distrax](https://github.com/deepmind/distrax), parsed by [repolex](https://repolex.ai).

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
rlex download deepmind/distrax
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d5314206ef8e24800486ab8c491246219a31eac0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d5314206ef8e24800486ab8c491246219a31eac0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ebfe3a5c1b39cfcf5d582e0f3f9ab5a70bbadf.nq.gz
│   ├── 0110436312868c6742fd5e686e961033c54c05ba.nq.gz
│   ├── 012ca333bf22792903197ed4481a40be2d0b25e2.nq.gz
│   ├── 02959b003def948990154835ac313d57672ca55c.nq.gz
│   ├── 0461122dbea04da88eb7385fbbb3fe4c28450007.nq.gz
│   ├── 0572944b51d99ce1273fa1bfbd5d4166ba11e34e.nq.gz
│   ├── 05ef59b219c0bb447ac19fa45ef5b99291cbd424.nq.gz
│   ├── 0c0328ca57d5df40bf7dcee7f8fda9da30693b08.nq.gz
│   ├── 0d0f3acf55374b43b0b132b263c13176aea90dee.nq.gz
│   ├── 12c91e5781395be1e5075664ef34b87fedfd74dd.nq.gz
│   ├── 12de693a5980b55cd08f81e4a0a1b4488adf4874.nq.gz
│   ├── 17a600c6a977449ced93fead1364f1afbfb5db76.nq.gz
│   ├── 18e5bddcbf5bf1408ee38aa1f5689f3be868cba1.nq.gz
│   ├── 1a96338d1a8b2c53ecef99b4b2c8f8f14c998cab.nq.gz
│   ├── 1b3027e42e6e2a39edf460afd7212eb6145993e3.nq.gz
│   ├── 1bbc8bc6a71d3d3456ed3530d5e11f3339fed2b2.nq.gz
│   ├── 1bc16119647c4075d0c7c609f685e3414ca7b305.nq.gz
│   ├── 1bc61a92567d84b337eafa88f91318b81ff100a3.nq.gz
│   ├── 1e5c17047054ece42c1e6450fdc6deeb30658ba4.nq.gz
│   ├── 1ef6a8dc075d616f3efa4049898dedfc741557f5.nq.gz
│   ├── 1f64e1c9e33240995272c9d18d75f9d7c3d01911.nq.gz
│   ├── 218967987423d517d1ac86579aaeba53f578bfb2.nq.gz
│   ├── 21ab7fd3630f33363f6f416e9ca4bb1ca9e93069.nq.gz
│   ├── 24cf7b1a45930c87cf064d2122bacbcfd702ed65.nq.gz
│   ├── 24f5304fc5f575070771625f715c8d90b72f7131.nq.gz
│   ├── 2f8c84ffb840aadef451bdc209c3eacc74b11fcf.nq.gz
│   ├── 30e6fc335659b2da574f05fd2a350b03758319e5.nq.gz
│   ├── 32d6218323881db91bdeffc0f375d111edfc5570.nq.gz
│   ├── 363aecc50718a73b0d8ae15b3b536027f0d1784d.nq.gz
│   ├── 372ea1609421310ece0fd03d0d6af7784efd1395.nq.gz
│   ├── 3792a5570404b53274ba1165f7bbbf4b113fe576.nq.gz
│   ├── 39a149d0712e75b8b3b849ca9c79e2d6b31935ed.nq.gz
│   ├── 3a9745371554e6df6e6811ad36422cc71dc4f0c4.nq.gz
│   ├── 3b81dcb82c36c91aa0a23d007e01694c5e51243a.nq.gz
│   ├── 3d632c1e59a6c61b052e3f426ebc93d7f598c07f.nq.gz
│   ├── 3decda9ed65c9fd58fa3ca6eeb57e982996b42c8.nq.gz
│   ├── 3e4ee451df2b3de31b4a14972e35aca16aa6d8d7.nq.gz
│   ├── 3f88a90ff919487ebb24271d10264b3dff0fc019.nq.gz
│   ├── 41f6b94eeb1c515b1afc2f8c17627d696a8573fb.nq.gz
│   ├── 43837e989bb80a170e582588f226f7d3c5cd7efd.nq.gz
│   ├── 441ae30f9acf4a57f2d98fd29e5bc21541e9ec6f.nq.gz
│   ├── 4682d93bbfe63f96b35eb8c87e4cc107c75c1f2e.nq.gz
│   ├── 46daf9d9084343c4b72b95cafb7dd08c0f90d44a.nq.gz
│   ├── 476dfe2b18a5c855600b70e00e12d0daf75ac249.nq.gz
│   ├── 480c477a83aaf83738731b8df8c91181bff642bb.nq.gz
│   ├── 4b15d3a17a308480d47702d50922726b48599db5.nq.gz
│   ├── 4b5f5a1f7df74ce0dd1a04cbaf3628f6031a4718.nq.gz
│   ├── 4f4ae22e60a35604da824b3a1b90468db0f8524d.nq.gz
│   ├── 50f3bc0ecb1b347957ce80fd7705f1bb49e2e491.nq.gz
│   ├── 52d91c88303b883e5e88c42548e15fbd73a4906c.nq.gz
│   ├── 533faf903d09116843caab3f5a813602041b487e.nq.gz
│   ├── 538ea4e3c73f48088869ec5dd0cd3631973fe83f.nq.gz
│   ├── 53cadc8092a4681a71e2a4ff8bf8549626ef08ab.nq.gz
│   ├── 53ffb11d6189ef6f588a4040506b2db8f3e118d1.nq.gz
│   ├── 54e72a5b2a79baddbcaf148f08beea7dba6bd2e1.nq.gz
│   ├── 593b7e8fe759f7ebd0373d2ae76ae11154050bef.nq.gz
│   ├── 5b682afcd751156e9633de969edb8510b30e58bb.nq.gz
│   ├── 5bb2154f58559252062368edd6e01a0f5dea3af8.nq.gz
│   ├── 5e05fbaef01d9711c5e3f74b12488098a93d3aa0.nq.gz
│   ├── 5e8699b211408341da8d4fa4498485e9c705c934.nq.gz
│   ├── 5f99ea8ca52bf8a2714fe020670cfaf36cd2fd77.nq.gz
│   ├── 63e210fbbaf0d42d2b490c3653e5cde7497e779c.nq.gz
│   ├── 64353b4fa649ef29913505c605aeefce0139dd66.nq.gz
│   ├── 67c0b0ea812f151177328430bed65bb5a9a0d15c.nq.gz
│   ├── 69322b23230f147e484ae75aa3496d0b4ca23b2c.nq.gz
│   ├── 6eeb62c176caa3dccae5f40da06cda4ec5a695e7.nq.gz
│   ├── 70a5d4b7878ad359ba592e67ae2139a9eac37713.nq.gz
│   ├── 70fd03bf5fad77b5eb5910c0b53d4a713f5b0992.nq.gz
│   ├── 73f8535caa5a30971819b905ec414ccd0486d5b5.nq.gz
│   ├── 7627beeac4efce72fe9f8d19f044f200842fc6d4.nq.gz
│   ├── 7e50e6e96d4775697301dfcb6299d896d9361119.nq.gz
│   ├── 8013868fa6e1769477b7d7654ab93593441e9213.nq.gz
│   ├── 8133aa36e50561dc43fd99cb5a531c971c0ba93f.nq.gz
│   ├── 81a77b14ef0cc19d340c7aed021f39288a2ef2bd.nq.gz
│   ├── 837225979811745aa466bb2de139250603f5fdd8.nq.gz
│   ├── 856b072aa4a1277726b9a350455f175ef1d17914.nq.gz
│   ├── 8cc5474eae2cc85dab553ce85a60130a675ca00b.nq.gz
│   ├── 8f1d3821765a57f1fc3c02406538bcd721e1806d.nq.gz
│   ├── 8fc972c3622b1eb82d602c5dd312b9656bb7aca6.nq.gz
│   ├── 91ecb305bd1169899c13885442739a921546e9a5.nq.gz
│   ├── 92f1c66d22c7c775b999d6962eed4edf1eadc54f.nq.gz
│   ├── 93766cd15415fe724186ba05a2dd4eb19256c2a8.nq.gz
│   ├── 93e8eb482fa4c30918d647acea2871c351497bba.nq.gz
│   ├── 9491438b1522e0d7a7b838cf5eeccbba52ccafec.nq.gz
│   ├── 998e0f15c8a3801cfac4aaf2e7b3dc059c4c5dcb.nq.gz
│   ├── 99bc15c3717a24d6aacd6666afff5c1ff846879c.nq.gz
│   ├── 9a86a2af832dd2c3fd4ab3322610e0d456f5d4fb.nq.gz
│   ├── 9b523f175f5de063a9026259d777c5fb6e46928d.nq.gz
│   ├── 9d5ae645dde5f1ee7a5aaf2f95c3356f1e3284ac.nq.gz
│   ├── 9f557911766ca78aac8a246ea2a23411bd14a757.nq.gz
│   ├── 9fce2e5217a5265eaf506ed7e86ce846a32fc0ae.nq.gz
│   ├── a261e983a2985b395b56e682cd3da5b1d258ab2a.nq.gz
│   ├── a3320cb06f8c34e714780b9f435db7b5e160bde8.nq.gz
│   ├── a3f0351e833f235fb7308ea8345b94dac33ee561.nq.gz
│   ├── a50232abd1379e94f7735d2fdff407c4ed173f57.nq.gz
│   ├── a6ec887724a0f1cc2864e9e4a9bd628fd8386136.nq.gz
│   ├── a9697e21b4d90dbfaa75d31614df127069495502.nq.gz
│   ├── abb9f23d6113d6cd2a2b32492b0c97e43fa7471d.nq.gz
│   ├── ad0c4912f8ee7ee8a0b727135910d6df3924ca57.nq.gz
│   ├── ae59e6990ad8edea4dc580a30846f3e3e8d0e3e0.nq.gz
│   ├── ae6eac9bfbb7c5c757353cd6c26dbc168f507932.nq.gz
│   ├── b20193558158e5676d97440af35f94f2e9086eb5.nq.gz
│   ├── b22d4d5e1b77a4b5f9646bc1a44776e36f54f596.nq.gz
│   ├── b249def7578c399f06646116ef158908cfe1d711.nq.gz
│   ├── b3ca14a5e841c42037cd7e59d16b55dbbdcf7535.nq.gz
│   ├── b53ad700553139dbb0704c021fb5bf042ae73ade.nq.gz
│   ├── b8490bb1e5c462885b3381d5838c33ac6e865629.nq.gz
│   ├── b8fe849d450bdc8e237f42ef781e675677779170.nq.gz
│   ├── b953309c21887428b6f40fa8ab5e2479fbfe4195.nq.gz
│   ├── ba6636f39cecd4c736e28efc21f5b239af88ff29.nq.gz
│   ├── bae86334c9ed1f803394920544987b5514f304f8.nq.gz
│   ├── bc0561318e2ca4131ec4eb0ae05b06951dde51a6.nq.gz
│   ├── bc0697c30db0c3c0508b85a2474c2da869b511e5.nq.gz
│   ├── c09414acbfc41cdf41a847bf62dd6bfdaf4e13f1.nq.gz
│   ├── c1ac29aeed9c3ca548717e734d261dc0373c262c.nq.gz
│   ├── c49ddc4a7a0e6bcc96339b650b30ffb27a562af6.nq.gz
│   ├── c5909131c4e98872674552621eb717ac0a0f1f71.nq.gz
│   ├── ccfb685e0b9536e7d4c65dec5a947c110e3a644b.nq.gz
│   ├── d111762b929a23ab15844b3fc5f1e9b49382019a.nq.gz
│   ├── d2b185a78c5891e3ae6937102aef1684263c3c81.nq.gz
│   ├── d4335e0b5d9ddc21201f7735d93d40d382c24654.nq.gz
│   ├── d441910122e2a599c57d8b9169f4d7a697f78c40.nq.gz
│   ├── d50649d57da9e35bd1cee4b41c0e38ecd9eb0ec6.nq.gz
│   ├── d5b1d62cb849053cc4a30577d816c900bcb9a2ad.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d9586a52086aeac0db3b47e39668f4b8c37ef96d.nq.gz
│   ├── db68b6757304b88cde42f5a244e1e47295a66a7e.nq.gz
│   ├── dd45be50c94dc070743b5e3c357e137aa9176b0f.nq.gz
│   ├── ddd76d21428111a4f30a9683d385196830a03e64.nq.gz
│   ├── e23b6545d34351f8a7cbe05ccc478e721c7346fb.nq.gz
│   ├── e4832d24aff7f9ab0bc5f27ced4d4fd03796c543.nq.gz
│   ├── e6359712a6459151d106c7d5105a8c1c718b470e.nq.gz
│   ├── e6f21885332c05751879755364457ef38204cff7.nq.gz
│   ├── e7e0fa65979435a58cecf92f602e35246bd17107.nq.gz
│   ├── e81c94b09d5f02940c31f84d975c9122da3a08ff.nq.gz
│   ├── e9b3f5bdd81afc8a0ba13012bbec34d8b20b7510.nq.gz
│   ├── eb70a3ee4d58186dda43e6421713788fec436f7f.nq.gz
│   ├── ee4aca86098c29ed60ad990a9e70b05bd4f9cddd.nq.gz
│   ├── efc5a07155bb78a99198f8896ff421cbf16b185f.nq.gz
│   ├── f84bc42a96d9205064b0636452d68411356bc3cd.nq.gz
│   ├── f85d8d6e37afe1e175b3a2dc639198a91c5cbc4c.nq.gz
│   ├── fb604eea899b3943fbee483397eca23d1944330b.nq.gz
│   ├── fb936d6b5fc6daa30c54496db3aa6dcc17d748b0.nq.gz
│   ├── fe086c64f40977c8e4910f7392bd6dbba525b732.nq.gz
│   ├── ff27d6c823d6659018cf252d9ba2c509a054a891.nq.gz
│   └── ffe452167d54039d1ac54d15570e5c30555e6105.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d5314206ef8e24800486ab8c491246219a31eac0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 154 files
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

[deepmind/distrax](https://github.com/deepmind/distrax)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
