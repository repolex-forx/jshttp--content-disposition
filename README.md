# Repolex Knowledge Graph of jshttp/content-disposition

RDF knowledge graph data for [jshttp/content-disposition](https://github.com/jshttp/content-disposition), parsed by [repolex](https://repolex.ai).

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
lexq download jshttp/content-disposition
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 2a08417377cf55678c9f870b305f3c6c088920f3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 73bf21e7c3f55f754932844584061027767289f4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7a6b472197c3a4336d6ba2ce3c6b570d62d7868a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7b391db3af5629d4c698f1de21802940bb9f22a5
│   │   │   └── chunk-001.nq.gz
│   │   ├── b56faefa036f1f78502b978bcb716aa75190eaa4
│   │   │   └── chunk-001.nq.gz
│   │   ├── f09cb955eb1ed0db2d0ed2708a5c95e6f119ad50
│   │   │   └── chunk-001.nq.gz
│   │   ├── f3c915f0c9d9f5ec79713dba24c8c6181b73305d
│   │   │   └── chunk-001.nq.gz
│   │   └── f6d7cba7ea09dfea1492d5ffe438fe2f2e3cc3bb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 2a08417377cf55678c9f870b305f3c6c088920f3.nq.gz
│   │   ├── 73bf21e7c3f55f754932844584061027767289f4.nq.gz
│   │   ├── 7a6b472197c3a4336d6ba2ce3c6b570d62d7868a.nq.gz
│   │   ├── 7b391db3af5629d4c698f1de21802940bb9f22a5.nq.gz
│   │   ├── b56faefa036f1f78502b978bcb716aa75190eaa4.nq.gz
│   │   ├── f09cb955eb1ed0db2d0ed2708a5c95e6f119ad50.nq.gz
│   │   ├── f3c915f0c9d9f5ec79713dba24c8c6181b73305d.nq.gz
│   │   └── f6d7cba7ea09dfea1492d5ffe438fe2f2e3cc3bb.nq.gz
│   └── repolex
│       └── f09cb955eb1ed0db2d0ed2708a5c95e6f119ad50
│           └── chunk-001.nq.gz
├── blob
│   ├── 0fa6951f088d91e437ea25699ee715cc6cf462a0.nq.gz
│   ├── 1192551edfa62ccb8831e623b64db867fdbd8d79.nq.gz
│   ├── 13d666115cffc9c7e837ef5a1810f336f4833263.nq.gz
│   ├── 17c705f6c72b975a5fdcc3ac26dc357479cefe1b.nq.gz
│   ├── 18efc43aa11ee236d6a4c2abca220ba4d7e54e5a.nq.gz
│   ├── 1a3b308b5ccc1e13b1a24b255faf0766cefa5e10.nq.gz
│   ├── 1eece14ad8cb98de2093fac5eef5ccee89472ff8.nq.gz
│   ├── 2166c7bf4e21d106b1a02b664b8b676edf15fba0.nq.gz
│   ├── 29c15b08432d05cdf6bdc4b9cd1dbd78348408d5.nq.gz
│   ├── 3092a4dc39e7c0b2ee6516099cd1ddc4405ac5e9.nq.gz
│   ├── 3739ff42ccc5315db05f73be8c4218a53a2df846.nq.gz
│   ├── 39f1eb6941ec50c79439005c35bc876bb16071e0.nq.gz
│   ├── 3a0bb055949cdaed008f0f85e111624214213873.nq.gz
│   ├── 3bfd85a781a3738609cbf0fa57a1e9bda276b9ec.nq.gz
│   ├── 3cd27afdb6d88edd8bd83ee7adbc7313084a48e7.nq.gz
│   ├── 3f469cca5db60a72b5e1ca29bc9553523b8876bd.nq.gz
│   ├── 43c70ce24a45a9a8f9eec7c6b6a30e0324d3078d.nq.gz
│   ├── 44f1d51f897d17edc707be84f4c44f60621c7ee3.nq.gz
│   ├── 488effa0c9440f4e214102980665781a62ba7059.nq.gz
│   ├── 4a352dc89b70f72f8201983e1624714cd95cb343.nq.gz
│   ├── 4b746b3fa1c9c071bb9c1caa03582afc6666ecc6.nq.gz
│   ├── 4d0d88a1d2c1c3a8a18f9005fd2b0c0892002095.nq.gz
│   ├── 53849b61894bbb5ecd56522feacf8ffd5718111b.nq.gz
│   ├── 5892c943e71f2c16800f6d55afbfff266244bb2a.nq.gz
│   ├── 5c1d2b8d01094a5d3d4b66143e52d45ed1514957.nq.gz
│   ├── 5c521d653858c3ff5c729f58490e9608c87ef8f7.nq.gz
│   ├── 5cea50ba00024fd3272ed83643ca6219d5873223.nq.gz
│   ├── 5cebce49a48f2258aea2805054a28f4a9398e7e3.nq.gz
│   ├── 62562b74a3b5a79e82ca417b02e0f597d85f5e2f.nq.gz
│   ├── 63a3d08c7350b7a6fffebe51513abb2c22717ea8.nq.gz
│   ├── 6704b7010237b62ad3d42d6dcce9fee93f0126c9.nq.gz
│   ├── 76d494c62ee0fb613e259a3235d35b8c3fcc0914.nq.gz
│   ├── 814f7f3f40ee18fc650bb83e3e7de8d3462077c8.nq.gz
│   ├── 84441fbb5709262c2bfc9b5ff0166ad4f024a1b8.nq.gz
│   ├── 8803847e3c51f2b91949c1b0468272f670464c14.nq.gz
│   ├── 88a0d0a23ede02f73486778ed93a144b567ca4c8.nq.gz
│   ├── 9808c3b2b6602da61eb4afcb4caf33368e3e2bd4.nq.gz
│   ├── 992d19a62fe59bf49fb2d95b441f38f3375727d5.nq.gz
│   ├── 9c90255d761f5cf21ea0b2d3346d921788c6d195.nq.gz
│   ├── a201a9522db4edcfdbc08f425355e1da1915e9f2.nq.gz
│   ├── a44034cf9e2f5109a13c02dcaacadd99603c7285.nq.gz
│   ├── b7dce6cf9a0edc74d1d1624b04cb7b2182b856a6.nq.gz
│   ├── b85a9b8c38c097f93d94691c3ccb15599d215313.nq.gz
│   ├── cf018a5540f8e7d7a5af7acc0ef235de52ebb8fa.nq.gz
│   ├── cf3015fb3b6ee818a7e76aff5854cde130fc5fe0.nq.gz
│   ├── d265431c250ac07635f45e616c9a4eb4457f8555.nq.gz
│   ├── e1b932e14f1847704d2e65429c4cc94533b1a012.nq.gz
│   ├── e3578aadfd3a97c6ef9d74f46e07314d775c9c61.nq.gz
│   ├── e6b6ff442bd2bdd577ce64d8a207302d71d07f24.nq.gz
│   ├── ecec899a992d46f2e903a87475b1c342f2ce4d30.nq.gz
│   ├── eebef13d43af84760137a643f6d94893b1e93bfc.nq.gz
│   ├── efcd9ca7513e9a04aeecedf875f47b1ad3aacce9.nq.gz
│   ├── f034de0b90215ed0ef3594eae12173fe760f9d06.nq.gz
│   ├── f1423bc696f2acae29378e005ee70b1327f467f2.nq.gz
│   ├── f263008b93a30f92851835dc7bf41178226e03f9.nq.gz
│   ├── fa3bc7415209dbb6855a4a32d794f899b195b319.nq.gz
│   ├── fbedc2f85ebfc13317208745cc52d952b71a2ee2.nq.gz
│   ├── fcbc2323d463b0750ebac62c7af6253bc8e3d4be.nq.gz
│   └── ff0b68bb11ca3f5d9149e3d5f57cd2571e88d255.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 2a08417377cf55678c9f870b305f3c6c088920f3.nq.gz
│   ├── 73bf21e7c3f55f754932844584061027767289f4.nq.gz
│   ├── 7a6b472197c3a4336d6ba2ce3c6b570d62d7868a.nq.gz
│   ├── 7b391db3af5629d4c698f1de21802940bb9f22a5.nq.gz
│   ├── b56faefa036f1f78502b978bcb716aa75190eaa4.nq.gz
│   ├── f09cb955eb1ed0db2d0ed2708a5c95e6f119ad50.nq.gz
│   ├── f3c915f0c9d9f5ec79713dba24c8c6181b73305d.nq.gz
│   └── f6d7cba7ea09dfea1492d5ffe438fe2f2e3cc3bb.nq.gz
├── filetree
│   ├── 2a08417377cf55678c9f870b305f3c6c088920f3.nq.gz
│   ├── 73bf21e7c3f55f754932844584061027767289f4.nq.gz
│   ├── 7a6b472197c3a4336d6ba2ce3c6b570d62d7868a.nq.gz
│   ├── 7b391db3af5629d4c698f1de21802940bb9f22a5.nq.gz
│   ├── b56faefa036f1f78502b978bcb716aa75190eaa4.nq.gz
│   ├── f09cb955eb1ed0db2d0ed2708a5c95e6f119ad50.nq.gz
│   ├── f3c915f0c9d9f5ec79713dba24c8c6181b73305d.nq.gz
│   └── f6d7cba7ea09dfea1492d5ffe438fe2f2e3cc3bb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

22 directories, 97 files
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

[jshttp/content-disposition](https://github.com/jshttp/content-disposition)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
