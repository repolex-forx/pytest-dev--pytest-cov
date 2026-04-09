# Repolex Knowledge Graph of pytest-dev/pytest-cov

RDF knowledge graph data for [pytest-dev/pytest-cov](https://github.com/pytest-dev/pytest-cov), parsed by [repolex](https://repolex.ai).

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
lexq download pytest-dev/pytest-cov
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 66c8a526b1246b5eb8fb1bc218878131bc628622
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 66c8a526b1246b5eb8fb1bc218878131bc628622.nq.gz
│   └── repolex
│       └── 66c8a526b1246b5eb8fb1bc218878131bc628622
│           └── chunk-001.nq.gz
├── blob
│   ├── 07548537011604080be58009e170d36ab79966d1.nq.gz
│   ├── 08936d99094e1b728f76a1a13bc81ce1cdbe0cb7.nq.gz
│   ├── 08f90d1b24817399b8e3b6b00f79c6446b88c5e2.nq.gz
│   ├── 0f32c842fcedaa6682f3ca62f7451b37db6fe52f.nq.gz
│   ├── 15a028dd784cfdba3a2b88e467f49f5bdbb2be64.nq.gz
│   ├── 20717284b347b5e44e7e91942e6e3e3e2660822f.nq.gz
│   ├── 23d9fdea207884f87505d1dd7ad7298413591864.nq.gz
│   ├── 281ebb4a3f0af66b81adf196c6d18ebba68bdf9e.nq.gz
│   ├── 2b447463200750ac3225e24b5fb13f82e91a3f34.nq.gz
│   ├── 2d87ca04d3e7968b7dc98f9bacdcaf6e1938135b.nq.gz
│   ├── 2f137982465415225e1d35ac0ce4437442e94071.nq.gz
│   ├── 2fb0f9b71821fce2e7dbf8a8b00a56dc0e7c622f.nq.gz
│   ├── 3032344df5a3e43cc71d9e8435bd6942c4e500f7.nq.gz
│   ├── 3291067a6b678a16b78f5bad9cc36a584424b67b.nq.gz
│   ├── 32fb1cafe047466865adc2984bdee92cf4579c97.nq.gz
│   ├── 36b78a3d11bc0d93d09a3a7d55e49eca4d7c4e70.nq.gz
│   ├── 3e7da4bbe00c8724073b1ccc6d6040a2dd0d1624.nq.gz
│   ├── 4c1e3b7d9d935b2e76c5cde8d60bbe20f8bb46aa.nq.gz
│   ├── 502b9bfb2c40b81f116fe7761453aaef1d43845b.nq.gz
│   ├── 54c3902a128c5ab60aab4280cd67768ebc6bdfd5.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5b3634b4a49bb7016910e5a3d8d5467f4c1fa350.nq.gz
│   ├── 5e7d56e14bbb172877be276d1e4f8c85b5fb55b4.nq.gz
│   ├── 603119bb2c2f210606e6ac825f246e8d74d1595b.nq.gz
│   ├── 6287ac5e8e9da21de4534a92b579d03f1bb05d32.nq.gz
│   ├── 6c5031793e05d6600a45b5ddcbe2a6019da68ed7.nq.gz
│   ├── 6c6b1c13ea6a386a77ac1058811b23533361cde1.nq.gz
│   ├── 6e57a6014ea2e0c503d6d27dc1323057a05ad543.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 7e12f6de277acf96ddcf045c9a2bec7ae72da296.nq.gz
│   ├── 7e552c45b6513f3ecc3f490fd29e3106f6714ad6.nq.gz
│   ├── 7ea731e6e052aab76c3cccb36d6f0b9661c274f9.nq.gz
│   ├── 83a43fdbd87fb9e83cd486c18168dfd391f85222.nq.gz
│   ├── 86a4bf68ec7200c37a17f5ce2a8fbe8b24e70fe9.nq.gz
│   ├── 8cdb37370ba930026ff4cec29003eb7604da5bfb.nq.gz
│   ├── 8f8054d37b6daa5aacc507f0e5907b86d0de3d6f.nq.gz
│   ├── 978cd510f315d9dfe0368c006897de169d2ffc2c.nq.gz
│   ├── 9f5c3f7607217f72b409f897f7135e2dc2bf61dd.nq.gz
│   ├── a232f2a0685ab76021833c8c17324054a63b989c.nq.gz
│   ├── a2d480bb79405d1371da3c20e8fe0f3999995624.nq.gz
│   ├── a2da50e9ed4a9688781b96d611195c14cdcd8a9a.nq.gz
│   ├── a6a465fa92c9bc1bc687c3a58538665940ac7d90.nq.gz
│   ├── b291f432e8ed8853c8c858d9fe62a5419c1439cd.nq.gz
│   ├── b5c833436c2184641e7d644fc2dd6add27c3fe4c.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── c1641b1045252f270e8a73f8bb148beb1e9f0f77.nq.gz
│   ├── c8ded81818ab256501f6f21ee5c3b3a464e17616.nq.gz
│   ├── d0eef23da39578fad205a1d2ee73d5a9f76d8a95.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e19232070fad774e84c30b0d44b1dff92c653101.nq.gz
│   ├── e44de028487d1ee52cd91f034a2d6a6235919ff1.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── ef8754e27059e6019c5f85f1c4bfa23dfacd9744.nq.gz
│   ├── f4948e66740016a5f7acb251cd4567e37197400c.nq.gz
│   ├── f76d6a15b7b6904c9cf9f83bb09a606580470a2d.nq.gz
│   ├── f95eb78d8a603b0fe5d17560d0dd04877d55c71c.nq.gz
│   └── fdb6b93a73605df8d6ba84b42c2e80011cf0afff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 66c8a526b1246b5eb8fb1bc218878131bc628622.nq.gz
├── filetree
│   └── 66c8a526b1246b5eb8fb1bc218878131bc628622.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 68 files
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

[pytest-dev/pytest-cov](https://github.com/pytest-dev/pytest-cov)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
