# Repolex Knowledge Graph of allenai/olmix

RDF knowledge graph data for [allenai/olmix](https://github.com/allenai/olmix), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/olmix
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9586977981e01b60c8b20330f623047f0b693fe3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9586977981e01b60c8b20330f623047f0b693fe3
│           └── chunk-001.nq.gz
├── blob
│   ├── 0049bd8792905d47e71b49594f2b785bd7a75a13.nq.gz
│   ├── 01226b1de84490e2b4f3fefa3b15d9798169bcea.nq.gz
│   ├── 02f9a9527528e47ef43ef1e5a5edc9fc04883bb9.nq.gz
│   ├── 06773178a932dde93d6b8c1c885664b05dec4609.nq.gz
│   ├── 0734d4978b82b3487851e515e5187be0b7c7c575.nq.gz
│   ├── 0b099f67bc6e94d7c6e0810d963e011ecbe94245.nq.gz
│   ├── 0c080d84d56416915433c24dfa01b97b1445b67e.nq.gz
│   ├── 0fa53c8a7d25657bddc0cd86705923e715fc5c41.nq.gz
│   ├── 131050defcbd7fdbaa8aeb7cb5b75b13b29b31ee.nq.gz
│   ├── 136b15e73d71d2aa731c8aaed577f2ff4cdfd252.nq.gz
│   ├── 1740b5063361400ac56b9adfdcc65007f6a70846.nq.gz
│   ├── 177d1ae3714fb0142a22be9f25fac5fae67656f8.nq.gz
│   ├── 22b9a6f54792bc9bc2dace14a9473ceea2e38fa3.nq.gz
│   ├── 22fe93243bf7ef7ffb53a9da077cacafa0a67ece.nq.gz
│   ├── 238b53bc69e7c316695eb5da2b13f83f525f2649.nq.gz
│   ├── 24ae3e180835cd39b8045b2cf6d9d7f3a6efe37b.nq.gz
│   ├── 27c8e58c6b51e2a0f392fd4afbaa898c77367acf.nq.gz
│   ├── 2ae2499ff3f8ee674a979badd6ae6454452ee415.nq.gz
│   ├── 301d684fdabe1563f1480cecc30fe94e33ea23b3.nq.gz
│   ├── 30e74bf3a77e5a02e935969c6f52a8505a3104ae.nq.gz
│   ├── 3466812d68496171dda46486f9a3167c18def4d7.nq.gz
│   ├── 365a81e12e812000ea3439c16983b7a06da6539f.nq.gz
│   ├── 36abb777fdaf734fc74b0b25c9ad593145995a45.nq.gz
│   ├── 36fe91f2ae5106b49e4c982716313737dae345bb.nq.gz
│   ├── 3705c406852dd27fc8bae944c092e8048c50e3d0.nq.gz
│   ├── 3b435ec553af55fe6749208fd81bc874a7723dae.nq.gz
│   ├── 3f914df6e1105aac1604776921c02938c3593e98.nq.gz
│   ├── 484ccb71f3a88cb09146a8300ceb71e283a439c1.nq.gz
│   ├── 48900091e159677eb40e9698996ecccce101b155.nq.gz
│   ├── 494037166f463a243cd69206161eacf3d94e20f5.nq.gz
│   ├── 4bd9b5706a5e9d390bf8cdee83f9cd6888c04387.nq.gz
│   ├── 5050cb5954019f62dd0ea1eec57b8aad63cba283.nq.gz
│   ├── 50e49ad55eb255f0a0c907b7a1fa8bc89933610e.nq.gz
│   ├── 522e56ad954a56e25df155fec4a00f9673b5f107.nq.gz
│   ├── 534602c6199f7b18c276f803e0cf4980ab58fcfc.nq.gz
│   ├── 55f09a7a26d375940933dc48458aa9cf74b287d3.nq.gz
│   ├── 562a8a846e6014920e37e94b5998a592dc3f258f.nq.gz
│   ├── 5c2b81d01451e0f41a0692eedd1fb0acc69ee3c0.nq.gz
│   ├── 5c7e3e8248719ca5982decd06229ff20c8fa62c6.nq.gz
│   ├── 5cb914e081a031bfc24d4787c6dbab84289edada.nq.gz
│   ├── 5e5eb6eb62efc5368e54f4f4a3f12f4d086954f6.nq.gz
│   ├── 61f96c570b461e3592bbccb67a04024c293a7383.nq.gz
│   ├── 66f0f35d968621fd4ba0a1ce6fdb3abf87c83219.nq.gz
│   ├── 677ff7e70ff745fb3b4c7b00d5f52a047fc8fdd5.nq.gz
│   ├── 68de7cf1b6df0c60b068d5bdd3405fa10933d908.nq.gz
│   ├── 6bfacb44ffd6946b68a11783ecca13858fed69dc.nq.gz
│   ├── 6c6b2b9b585ef3a9fafc4551df80ca64cc1af343.nq.gz
│   ├── 6e743cd78669ff94cd945a088c0254bd6d6aee97.nq.gz
│   ├── 788a224f59d39f9abc4cca1ae8b9c60a18b9e4e6.nq.gz
│   ├── 79e0a87ab36fbf680af0b672ad60fb1caed56d19.nq.gz
│   ├── 7f68aa1c73ab618b5c18721468f74aa922198f11.nq.gz
│   ├── 801bae8c604d0850dc38fa12c52e0981abe4d684.nq.gz
│   ├── 83b48d5d1934838dfe7c9554ccd4bb581fbf36bf.nq.gz
│   ├── 853c3ba4b9b5c4f73e9ec923029d173fa9efafa9.nq.gz
│   ├── 87535a40ccf1c93c9180870440d646ad01aa0886.nq.gz
│   ├── 87de68dcb0329dc379745b21ec906779f8ae45cc.nq.gz
│   ├── 883a5f0e0dfe460e55b66629f26d1b762c45d7c5.nq.gz
│   ├── 8884ce37857378b4524db6067838266fe3d9f25d.nq.gz
│   ├── 8c02c47bb0774e3808090dbf55cf127afb7082f8.nq.gz
│   ├── 8c38e664b98c0ca4d1a0f8618a8bf0bab4511974.nq.gz
│   ├── 908b5e46aa9a8c55aad3b3c24ccd2ba625b82236.nq.gz
│   ├── 917136b668d121777f6dc047002d99e8b50fe798.nq.gz
│   ├── 919f4def84b508b371ab268e6a23366e3ee435a6.nq.gz
│   ├── 92a2b854b9fc16f396080650e18e1e811f5ba81e.nq.gz
│   ├── 941576e678474b69ee9c2123957715ca73815140.nq.gz
│   ├── 9495350bd0f608335c42d85c2c10270af491a891.nq.gz
│   ├── 957f18a5599b4f6c683e0bddfd10c41ded2e0cff.nq.gz
│   ├── 95878870bae402bcf3bd778de053b3f366c85fe1.nq.gz
│   ├── 961c8bfc310e83032fc4a68feefacaeb4d4b8404.nq.gz
│   ├── 970b42d75bed2f0ea9a50ddd5144de7646b12369.nq.gz
│   ├── 98cf2592c2a5c6405393191a57c4a50ed89fb27b.nq.gz
│   ├── 98fd59a3f816032ccad6dadaf49c15b031311018.nq.gz
│   ├── 9b1cff3c4a10ec35dbf253ffdcf7b2fee4f4be90.nq.gz
│   ├── a17bfdbe29ef38f9907f48900b37a6b9478d88b3.nq.gz
│   ├── a5d64c5546624133dd3f7f6f9a5b694cd38af032.nq.gz
│   ├── a62f340ce97c99b562154a92d1da8bd2c8f25bad.nq.gz
│   ├── a7d76250bab63db3232efb517e77a2862dd27e8c.nq.gz
│   ├── a8f146b839a19cbbc713bcb340f8aeadbd5cbaab.nq.gz
│   ├── aaad85c6e5146f2490536e1aa0a1986c0b3ffb06.nq.gz
│   ├── aaf87e5caa16cc51c703fe9461f09063659a5498.nq.gz
│   ├── ab2b1b1e98e14dba58800cc8fe3be63ea382a89e.nq.gz
│   ├── ae1ae8fac34e89658dcd43b793d5c367df4627af.nq.gz
│   ├── af1cb24234a9b096c6cc728c2c32d3fa4229e97e.nq.gz
│   ├── b0ae1f29bdfb0043a6fa699d328af5727732d700.nq.gz
│   ├── b594cda22fed31174fe2c2288ce1a9f738d585a2.nq.gz
│   ├── b830e1339492bf50c1f610b240d0f56a13f50a84.nq.gz
│   ├── beda7160ce37b5db3f900a06b607ea80758fe791.nq.gz
│   ├── c03f154e5aac15cc0079043c9ebba739005cb6ae.nq.gz
│   ├── c538d7aca6970911bc3702f322de45a3834ed0c1.nq.gz
│   ├── c5572d3074ca62d86a2cf2fbe7d639a0ba80265f.nq.gz
│   ├── c58ff435e45c68a4e5f07ee22de62b8c293355fc.nq.gz
│   ├── c7046e12c9805f5065d96ef3b1ac63fcfa84cd09.nq.gz
│   ├── c885b180dd3eac9c035f2919165bf7797bd4f497.nq.gz
│   ├── c8887c268d87d39301157aa463d9d7a76f9f7932.nq.gz
│   ├── c93cb5181c51a70c8824f805561c485934d49cb8.nq.gz
│   ├── ce74b3ca7c647bfc1916ad80121af8e9cd0ed340.nq.gz
│   ├── d591bdda2a106be94279bf701bb9b6cfd1b1c880.nq.gz
│   ├── d99145121f13d6d732c44794084befc1aa9c4a7c.nq.gz
│   ├── da7c09fc9574f3961f20e189e788eb25a336ec09.nq.gz
│   ├── ddea42aaa48cc7153d10fa57898058bb904508ba.nq.gz
│   ├── df601a570cd7260e6ca0acea730e88b0dfe58916.nq.gz
│   ├── e08c48f986b3c344234dcc43a86969f167c2ac0e.nq.gz
│   ├── e0c9e14ddb565371192dee11c84f8267da46af32.nq.gz
│   ├── e3dff0bab01de6fe98a9cf65fce6446e753e03aa.nq.gz
│   ├── e49efc4b4fb6be5ff4eaf253f3aebc7bf3f8e029.nq.gz
│   ├── e5ed5f7725a50552e6186e86f5d17d10f7997ac3.nq.gz
│   ├── e64951cfe5f425c9768d83aba917b65355e70bb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f39a0bcccac73fe55e7ed77a168116f89fb2c0.nq.gz
│   ├── e8aea9c8cbe6b797a0bdcc54d191d6651b8541c5.nq.gz
│   ├── e8c8950704c4dedf12c9d049255fa4fcb99cfb85.nq.gz
│   ├── e90971883f5fddaff59fd583a58bb47fa8c04a1e.nq.gz
│   ├── eb2a191b7fc8671bfcf50a821764e7df08e45a3c.nq.gz
│   ├── eb51671497662d11165a38b7e1de79436f4847d2.nq.gz
│   ├── ec8656a19228f90e50b1b18a4ef8512a02590054.nq.gz
│   ├── edbb6c6af8d0675e2b95c2668789b7641bdcb76f.nq.gz
│   ├── edcef48d6f5decb7f955080b0ef7ef3b410d0eaf.nq.gz
│   ├── f0015d03a8349533cc91f36695562e0127da44d4.nq.gz
│   ├── f0cd6fd360e93e22e07b3bc608a0bb958e4f6a2e.nq.gz
│   ├── f1665ec4076667d6137c715ed4fa2e5060514816.nq.gz
│   ├── f644eaf3aedd0159b2a42349da55aae623147cc2.nq.gz
│   ├── f687f257f8ce7894726bc2102ab15a7749695bb2.nq.gz
│   ├── f749a8ef9f35c00e3eedaf6b4e5e026af10aa219.nq.gz
│   ├── f8703da90bd1c7e6938037d8a3e431ee0d8c0b07.nq.gz
│   ├── f8ebfa8e9d11694f3a52cbdbb3992dae5b33c725.nq.gz
│   ├── f9d518f907cd11c8026ab88cbd87de295eeb60b6.nq.gz
│   ├── f9ed3d81b125d791ebae10540512b2843ee404fb.nq.gz
│   ├── fc2dad40fc0d36b21cf6ea00ec50d244859044a3.nq.gz
│   └── fe1a78cb728a4fa689e8b6d4eeb6efaf5762cbfa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9586977981e01b60c8b20330f623047f0b693fe3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 137 files
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

[allenai/olmix](https://github.com/allenai/olmix)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
