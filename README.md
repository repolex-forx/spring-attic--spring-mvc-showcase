# Repolex Knowledge Graph of spring-attic/spring-mvc-showcase

RDF knowledge graph data for [spring-attic/spring-mvc-showcase](https://github.com/spring-attic/spring-mvc-showcase), parsed by [repolex](https://repolex.ai).

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
rlex download spring-attic/spring-mvc-showcase
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 71d8c7e3432b226f09092dd13a7cfe2298fdd265
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 71d8c7e3432b226f09092dd13a7cfe2298fdd265
│           └── chunk-001.nq.gz
├── blob
│   ├── 05faff3751fe78092362ed64c84ca4b29c9e797f.nq.gz
│   ├── 07aa6d61d5eb6979826186f64504987f7bf48f11.nq.gz
│   ├── 085801768f69acdead83d814810f8a8a67c2039b.nq.gz
│   ├── 09da254ab7b50b6c275995252aded97013386e19.nq.gz
│   ├── 0a2c727f27d552f144b15014d50b0a6a26964887.nq.gz
│   ├── 0b54e1d9b71abc7f352efa2bb88e2a87d8d90026.nq.gz
│   ├── 0cd4ae73336fe6e835fabeb7921f1011133ea80d.nq.gz
│   ├── 0ce05ec972297739f31a1cc548c0b74267c0fbc5.nq.gz
│   ├── 0fa649434f95cafe960e2f53bd70fa767c1dac51.nq.gz
│   ├── 103489cd45f11ab3e370901ebf12b551023a5301.nq.gz
│   ├── 10d5da8cebe15f0a717ec165e382fd5a0da8cd61.nq.gz
│   ├── 150f08feee33c9bed04fa5a0e9a8d9ceef49663e.nq.gz
│   ├── 174b6b68efccf27d8187a56850da7adda493ae7b.nq.gz
│   ├── 1b9da2dbba3f6c57306a175cccbdf963b77ade05.nq.gz
│   ├── 1c6b8eb0fb39720842be86b0343adfdcbf929982.nq.gz
│   ├── 296415e2f6c565b38c2bfa0edd53f0b11ffa5cf3.nq.gz
│   ├── 2985749386d1ceb4f678ec6fb1337d023b2b4640.nq.gz
│   ├── 2ad3e34e94892eb9d8dbee4be7e237264713ac36.nq.gz
│   ├── 2e1fe1d3ab552c00ead02f49a2aea66e0207a005.nq.gz
│   ├── 347a8ffd6dde4cf3339fa2a32f14dc92171b3ebb.nq.gz
│   ├── 35a8b43bc4c4ac772d99b1985eda834ec743c703.nq.gz
│   ├── 3753add814aba0288cf3e5d63bf838ef88a8d71e.nq.gz
│   ├── 4014ced5b8b62387a392ba12fbcf27a6c0bb7d4e.nq.gz
│   ├── 41edfe72b51e978f407a3b0cb0beff352a6e5aa1.nq.gz
│   ├── 42ccba269b6e91bef12ad0fa18be651b5ef0ee68.nq.gz
│   ├── 42dab04da21ff31f1a702cacd6a3441078015e12.nq.gz
│   ├── 42de0145454f1fb3af813ec8358103fd4a58c259.nq.gz
│   ├── 4443fdc1a156babad4336f004eaf5ca5dfa0f9ab.nq.gz
│   ├── 449d95e7fd86c19f2328980f0627bce950544e3d.nq.gz
│   ├── 45e8928e5284adacea3f9ec07b9b50667d2ac65f.nq.gz
│   ├── 47bd522afe00e16ba17818e2d423b58c4d906b28.nq.gz
│   ├── 4a916d5b7cc6859689bfcf46b0e47c53dac6f37e.nq.gz
│   ├── 4c57a6d9ade9ab80cc0a201e7da29db69724cefe.nq.gz
│   ├── 4e31be891b97173854030d3537bcfb41b53aca18.nq.gz
│   ├── 4fc91fb7f612f6ed8141e804cbd5d288a879bbc6.nq.gz
│   ├── 4fe396aee8a3bde37923bed502828e33e03e3d6e.nq.gz
│   ├── 5321b2d9bdc8fff73451ddee772eb118a6884e75.nq.gz
│   ├── 59ba7fbf68d44930ee9e956923df0a0c494c66b9.nq.gz
│   ├── 5a46b47cb16631068aee9e0bd61269fc4e95e5cd.nq.gz
│   ├── 5b5dab2ab7b1c50dea9cfe73dc5a269a92d2d4b4.nq.gz
│   ├── 5ba708c39172a69e069136bd1309c4322c61f571.nq.gz
│   ├── 6053f876e1c6db4552db7e24f57b696d7d49fe71.nq.gz
│   ├── 650623392fa521a92e32ab2e7cf502576cc76b4a.nq.gz
│   ├── 66368fa34fe152b476ed4d6c83427481cefd1418.nq.gz
│   ├── 6cd90c2b265a1c2249c4e5ad7a0e244d26da3d75.nq.gz
│   ├── 7126a84aa4db2e828a4f091585c002d60b975de1.nq.gz
│   ├── 743ef89c3a48cb65d51f0efb7305be9f2beba401.nq.gz
│   ├── 7798ee19eeb1e0a25a70621ee330434e85eee994.nq.gz
│   ├── 77f6c09333f670727a903d252ccbbae8ab18d6a5.nq.gz
│   ├── 780e67df5a6572fe8fc3e4d5025d38811d7bfaf0.nq.gz
│   ├── 7930a558099bc8d92b4264eb67a0f040460f4a4f.nq.gz
│   ├── 7b3e0d61602242e7b7da94008261959ecc92b608.nq.gz
│   ├── 7bac24115ed60968c5f6d4c1347962d737425246.nq.gz
│   ├── 7c9bfa278c97661a6b3f2d96edff7b4f59d705af.nq.gz
│   ├── 7c9fa6c6edcfcdd3e5b77e6f547b719e6fc66e30.nq.gz
│   ├── 7ec70d11bfb2f77374dfd00ef61ba0c3647b5a0c.nq.gz
│   ├── 814b7bd9b9e7d871ca17e24a04efcda9351f8b99.nq.gz
│   ├── 823d9ad0b4a95cef0865fa431ac7ddbbae04633f.nq.gz
│   ├── 83de6545870d0e0af384f39f59b6a05c7277a3b9.nq.gz
│   ├── 861093fe2a83923e00975cfde64df9540c447e99.nq.gz
│   ├── 86c2baa655eac8539db34f8d9adb69ec1226201c.nq.gz
│   ├── 89b5b647dfa37ce2c3cce75bb7f00f227759c892.nq.gz
│   ├── 8d2c259fbca765ceafcec13e8f4e2b2067445a3e.nq.gz
│   ├── 8f5bc8a22c34ace2ce43320349c068739cb210bd.nq.gz
│   ├── 900d42021f9c3722fab51e3b7cc31ccb0b1a0eb7.nq.gz
│   ├── 91bdcab81e26257cb173751a7caff33866e10d51.nq.gz
│   ├── 97992e323d04b8c9143349eeff203b245d301b2c.nq.gz
│   ├── 9d0b7e99c0bf79b590e9189fb7e7ded47a030a16.nq.gz
│   ├── 9ff77c5d09b2ebed2067c19fca3ca028302a4d97.nq.gz
│   ├── a3339d1201baf5a3db4b940f711741a280f5c460.nq.gz
│   ├── a35c1e955a581ab0d3adeed141fb280a1a2f9cdc.nq.gz
│   ├── a3f0ddf58fe46aee7fd59b55b0201d108605a9d7.nq.gz
│   ├── a7c6d4d97a0882061c50238e620ea8d920cb5c5c.nq.gz
│   ├── a8fb3757fc28e31889741f2d37f59d926f846476.nq.gz
│   ├── ac8b229af950c29356abf64a6c4aa894575445f0.nq.gz
│   ├── ad3d6346e00f246102f72f2e026ed0491988b394.nq.gz
│   ├── b1f9ab1b26fb0b97065a9cee06e3d69612368974.nq.gz
│   ├── b49489a3c8eb8ce5722c4d1a9bfbd5ad6296991b.nq.gz
│   ├── b5837b9fed5d3445ba72973a64a7048b421d987d.nq.gz
│   ├── b73729309203735025a98982a04e70d7d4c18718.nq.gz
│   ├── bd7ab0c4c6d40c231d0cc9b75858039ceb400518.nq.gz
│   ├── c450135dbf29cd83f23129870f0a6ee6d877f31e.nq.gz
│   ├── c5276ae91ebf267071d1131f2edafe1a4065e11f.nq.gz
│   ├── c5440d63c795f721538d651595f51858503c66c0.nq.gz
│   ├── d370d7c319d246791974d7c0c35ce4bc9c1245b8.nq.gz
│   ├── d687e8e994b3d8d03457d9129425503eb628bf84.nq.gz
│   ├── d7ac2f7d624932bdc2a891f545d6ff73d67f5f5b.nq.gz
│   ├── d829fa3e6007b2950c1e7b0576384b3751d799b1.nq.gz
│   ├── da5e62170bde6b9e14c2a4391dd284f11520e033.nq.gz
│   ├── dac22b58233920c24039ded71d7152d47f15746f.nq.gz
│   ├── dafa6d1a36cf7db7e163f4634e4d90410d550ea5.nq.gz
│   ├── dc5864eb43ed722288b2b9a4e3bd84cd6efa0acb.nq.gz
│   ├── e8a9a5a78cd77d9a956e7d2d9b367e1584f50cbd.nq.gz
│   ├── e8c9473fd13abc2cbabaa1a1ddf7db20feaa9dd9.nq.gz
│   ├── ee039dc096a38a3753f92519546eee94bcfbeffa.nq.gz
│   ├── ef95195acce57c9b31c6db038801bcc58588e7fd.nq.gz
│   ├── f0c83853baf759cd9a694ab897dd73090beeb41a.nq.gz
│   ├── f52ee39b9595d9aa943a1f45ddfb163b30e1e2eb.nq.gz
│   ├── fb9889ce4934f44e415db17c8c98bdc7f9d92a88.nq.gz
│   └── fe4c6ba5b38ae4c417ff958c562b831fec6499ab.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 71d8c7e3432b226f09092dd13a7cfe2298fdd265.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 108 files
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

[spring-attic/spring-mvc-showcase](https://github.com/spring-attic/spring-mvc-showcase)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
