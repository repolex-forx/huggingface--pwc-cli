# Repolex Knowledge Graph of huggingface/pwc-cli

RDF knowledge graph data for [huggingface/pwc-cli](https://github.com/huggingface/pwc-cli), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/pwc-cli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 125ffe07aad3d268bc2e3ddd8d79f159b4bc2f2b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 125ffe07aad3d268bc2e3ddd8d79f159b4bc2f2b
│           └── chunk-001.nq.gz
├── blob
│   ├── 03d2d3df0e5e88c6971c7168152e665c1afbfa7b.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 167b96b7afd3c89ddf0c41a05ad266fcbc1fb9d3.nq.gz
│   ├── 19bd1c4c6587d8fb490a32d02b9114272ecc8e6b.nq.gz
│   ├── 1d2df5496aaae960841affa82e973764b2510818.nq.gz
│   ├── 311d343482dcf350edb44289a861fd9b5879d1de.nq.gz
│   ├── 330f6187a3227164de3fac6f80bee42fb6046967.nq.gz
│   ├── 4027929daf47f7be727889c24647f2cbe5c876a8.nq.gz
│   ├── 4380d3860274920b3337f8f071b99c1eaa4f1b9e.nq.gz
│   ├── 4494c951143f02a901ffa281856090d87e63bb00.nq.gz
│   ├── 45d04e18258331a67e3f2e36f62f139abba156aa.nq.gz
│   ├── 4c8ea95f0c44792f3345f3edb5b14f3bc07cc675.nq.gz
│   ├── 4f037dd04d74e7d2c6be16c41f322bffda15031f.nq.gz
│   ├── 52764f056998629f92e3dbd9a682eee0a788c720.nq.gz
│   ├── 54cfdaab01d5f88efc6adf09ee81b2e312025f27.nq.gz
│   ├── 5521ccb9a562ff01bd89c7b1f0bab2fed34d7349.nq.gz
│   ├── 57db0a85cda3da57a07e68796d848ef582a8ecf8.nq.gz
│   ├── 63175bb7e34ca69c703dd77029c3060e5b182c65.nq.gz
│   ├── 76864184e269c163bc9691f379b8115fde25793e.nq.gz
│   ├── 7da20f0d71f7b075b94b9374f29c151f7cf35537.nq.gz
│   ├── 83a2cdc492f5c09c007233f5cc273af18f39c810.nq.gz
│   ├── 90c7b6dd942644eb0d529fcc644440497bd95028.nq.gz
│   ├── 947e1bf84facd470df623aca1b6f8f38ced9e10a.nq.gz
│   ├── 9b6a172318359e5a6f2a1b3cf1dad364bbebce91.nq.gz
│   ├── a0fd9ce35811395e1e58216d4723ae302cce8a5f.nq.gz
│   ├── a8a9e59b56f841984a9b39d4793f3a71b61802c0.nq.gz
│   ├── ab3e5249277b4c5b95c8421f1ff2a62257c4667a.nq.gz
│   ├── aec23e02c98b1da30acf0e2b9764980cccd521e7.nq.gz
│   ├── b4ebdcdeb88694eacd812c6f24014fef6eef0b35.nq.gz
│   ├── ba6145f0df7d34102f08b1ed1f86ee0a470d0186.nq.gz
│   ├── bf27b0fc1d0c3c1a658bd2e182efaf39a3854109.nq.gz
│   ├── bf825221b2409a008fd51dc38100954d41846265.nq.gz
│   ├── d51f4d91d83ace42dc34ac0f15d0772950efe7e3.nq.gz
│   ├── d5adfecd2a7cc3d8d5813228edbc12290d1ead52.nq.gz
│   ├── ddfef66fd5ffa54e53974feb42b6beca06daa6aa.nq.gz
│   ├── ecb6e634eb7dbd4af312c532a48d857608a23fab.nq.gz
│   ├── ed2c336015efdbc416478d1761897134d9d39c42.nq.gz
│   ├── f8a7a051cb1f19a3e9311b5172be17bc11b6508e.nq.gz
│   ├── fa0e182639b1e7c393ff48e42c74fafe168c3a5f.nq.gz
│   ├── fc1f7fd3126b6c0139ba50ca2af8dab369fb50e1.nq.gz
│   ├── fcca315b8fb8fad17afa071c783491dd82e3039c.nq.gz
│   ├── fd4c8331d3f1d71d3b2719dc64e1a747b1095b0c.nq.gz
│   └── fe20b9a32736d6b703d0327839516c4f0179fd2c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 125ffe07aad3d268bc2e3ddd8d79f159b4bc2f2b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[huggingface/pwc-cli](https://github.com/huggingface/pwc-cli)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
