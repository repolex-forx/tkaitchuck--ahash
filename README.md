# Repolex Knowledge Graph of tkaitchuck/ahash

RDF knowledge graph data for [tkaitchuck/ahash](https://github.com/tkaitchuck/ahash), parsed by [repolex](https://repolex.ai).

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
lexq download tkaitchuck/ahash
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 10c4f487e85c62bb12618ab5a4bb84b16802cdad
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 10c4f487e85c62bb12618ab5a4bb84b16802cdad.nq.gz
│   └── repolex
│       └── 10c4f487e85c62bb12618ab5a4bb84b16802cdad
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ba76da01203d6095c794c4a8cf0f46a94160b1a.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 197ded321ba8112d91e2c2d31a88ce57451dba79.nq.gz
│   ├── 26c4a688e3b5ba36fad11b0735d103558c5627ad.nq.gz
│   ├── 28f49307b49bbe36bdd2c96e6a94b981277a64a3.nq.gz
│   ├── 294a8d49ae6d080d5d44e008592dbe376c430233.nq.gz
│   ├── 2effe93a4246bdb2ecdfef5ad07a96d1ba171ddb.nq.gz
│   ├── 2fecef3b5430dc162702419eba93e6b4d8570d32.nq.gz
│   ├── 386f136c87adbe7c3f8ae22720cc0fe0b2a627cd.nq.gz
│   ├── 42edb5795d90048a7451886860d7fef8ea10b0dd.nq.gz
│   ├── 46edc2df02e52a8f63f6670560454fd50411e842.nq.gz
│   ├── 49513b38b63e8aefa16fa572db612569cd889af2.nq.gz
│   ├── 56f754cbee4bfe8950e13a5ea5a826033bc7c742.nq.gz
│   ├── 5de367d1106d1122083963a9c30545122dca954e.nq.gz
│   ├── 70fcee54f2c033678d38bf4b5c4e9c6ebf7113c9.nq.gz
│   ├── 75306517965a54731b94dca8bace640e856af115.nq.gz
│   ├── 7e28cdabe36cd4cefd10518cd8bff24a3335125a.nq.gz
│   ├── 826806b662321c12c5834006dca5a66954f4bd0a.nq.gz
│   ├── 89e67ee124857ad5143e7b9e066bedfe5c35c2a6.nq.gz
│   ├── 8b6040b381fae44b708e214a867360f8abba0930.nq.gz
│   ├── 9a2956d6c467fcd528fb47882a45ef4a66d65764.nq.gz
│   ├── a725380d3c8d0a52874479941c4498a2e08727bb.nq.gz
│   ├── aa071cf51dc649270fa61cdbc0b4c26435952b51.nq.gz
│   ├── ac307767935147f47e929766af3d354a470fea7b.nq.gz
│   ├── b1c7d40838452f2579871be0004445616ba05cd8.nq.gz
│   ├── b2a0b98c1e20bca8eafe6378baf9adebc9a673d0.nq.gz
│   ├── b50060dbb8ae4a00019a0098f8e77163a363f4fc.nq.gz
│   ├── b50d4d8de6b775ce517b5af1472199f6fc458c50.nq.gz
│   ├── c426036a7e30da83ddb3bfe7322cc3794cc48502.nq.gz
│   ├── cba20106dd50f630db04a2c2da0cb4067400bf2f.nq.gz
│   ├── cd13526ec860d3cee981cfeef590152d0475ec28.nq.gz
│   ├── dd6f925bb22d6143c2cf2241c13e1d8727bd365e.nq.gz
│   ├── e12d8b0a24c28821c6f20debf72e6fceb755d698.nq.gz
│   ├── e638ae6bf99c984b6cdf55ed6ea386ee4ddb77bf.nq.gz
│   ├── e7a6c536b038dda171c0199f0e15dc12e08037bc.nq.gz
│   ├── e828f122ccae44bbc6f06f4edf5501d1271d2210.nq.gz
│   ├── eb0ebd67b09ff72a85e9d84e05202161059109ed.nq.gz
│   ├── f0cc0271470a9b2ece5203df07edfc6d8dcdbb25.nq.gz
│   ├── f4b8748b6de88e6a3a658d24ebb5cc688304cf3c.nq.gz
│   ├── f59538cfbb1d9fe571d0164d9aabd2969ab52ade.nq.gz
│   ├── f98379ee2e7c39c643aa43135dbf0b5305454c5a.nq.gz
│   └── fc89f1b28dbf07ff86d422fa85b595e07ede93d0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 10c4f487e85c62bb12618ab5a4bb84b16802cdad.nq.gz
├── filetree
│   └── 10c4f487e85c62bb12618ab5a4bb84b16802cdad.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 52 files
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

[tkaitchuck/ahash](https://github.com/tkaitchuck/ahash)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
