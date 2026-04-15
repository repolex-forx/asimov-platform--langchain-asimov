# Repolex Knowledge Graph of asimov-platform/langchain-asimov

RDF knowledge graph data for [asimov-platform/langchain-asimov](https://github.com/asimov-platform/langchain-asimov), parsed by [repolex](https://repolex.ai).

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
lexq download asimov-platform/langchain-asimov
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 17116ff7c9013772e6815b6b6dd16583d1518591.nq.gz
│   │   ├── 90c1df130145921a302340b33dd61ac6db03ed6f.nq.gz
│   │   └── ba387079a4100bdd97270bf71dcf5654864b5a60
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 17116ff7c9013772e6815b6b6dd16583d1518591.nq.gz
│   │   ├── 90c1df130145921a302340b33dd61ac6db03ed6f.nq.gz
│   │   └── ba387079a4100bdd97270bf71dcf5654864b5a60.nq.gz
│   └── repolex
│       ├── 17116ff7c9013772e6815b6b6dd16583d1518591.nq.gz
│       ├── 90c1df130145921a302340b33dd61ac6db03ed6f.nq.gz
│       └── ba387079a4100bdd97270bf71dcf5654864b5a60
│           └── chunk-001.nq.gz
├── blob
│   ├── 056fce806d0b314ebd074d1a664a6fa90e135f89.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 16142092cffb31638681b80a3e07a625c7e4e6dd.nq.gz
│   ├── 1aa98b95fcf75c385626e50cd45101cbc3912360.nq.gz
│   ├── 1b39a795a6f8b392552e440fe4bad3937129d0cb.nq.gz
│   ├── 1d013ff92fa855fb03f148d15f9488c339392020.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 3984f7e89af35e81dddc77f0e33dc1d1396add42.nq.gz
│   ├── 3c905ce487710ea29b557db189f1208dca5bc599.nq.gz
│   ├── 4e379d2bfeab6461d0455bf5bbb8792845d9bbea.nq.gz
│   ├── 5247f6f2ed57d73bee8eeccbcefe181e1a0278e5.nq.gz
│   ├── 569ecd49f1338e1cf402d1dcadb747ce78cce5af.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 68cc1aff852ad9b3c36e773655519b187b05eba1.nq.gz
│   ├── 6a10eba8ce29de61a2a24e50e917d2dd54b35332.nq.gz
│   ├── 6d5b7fb377404a734b6a409c4876d1125cf0d0d1.nq.gz
│   ├── 7322ee2613af6e327b71ac06f4c7167651da91fe.nq.gz
│   ├── 746b6aa27bf30acef6641ef0de631e028511bb4a.nq.gz
│   ├── 77d6f4ca23711533e724789a0a0045eab28c5ea6.nq.gz
│   ├── 78f04604d5dc75234484700454d5035442609fe8.nq.gz
│   ├── 81340c7e72d5c852585d0faea06985a720d4c2df.nq.gz
│   ├── 87a47c9b36dcc6bf42f400f7a6cc47403949a4ae.nq.gz
│   ├── 8b265cc167d538e85fcb9013e9488d98cd011ffe.nq.gz
│   ├── a52f175fd3987546ba419897ee5ec6147e3eca1d.nq.gz
│   ├── af9bf8c44cd7ea092465c1ff001165029d8c3fcf.nq.gz
│   ├── b737a205c9bebf19b9e3c639397d993da76b14bd.nq.gz
│   ├── cd8caa246424c5cee3d81c5c9b2537385483e940.nq.gz
│   ├── db27009dcf3c348caf0fdb576d780d84a74b6935.nq.gz
│   ├── dd865084475765347f714a163bfd0163829dcefd.nq.gz
│   ├── de0b624cdc78436e6cdc228def44a6164086418d.nq.gz
│   ├── de9c924e91908cd7e2aa4fae5b1ba134e5c62f4a.nq.gz
│   ├── dfb651a483c245bf8a0a645a2a928d7224d89e6f.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee4d9362508d63f9e156fe9ee1b11ebc1a3e86d6.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── f327ec7a88a24263021c6f50eeb2ad230821ceb0.nq.gz
│   ├── f368f2f71ba312b593285d3009e727a7a9e868b5.nq.gz
│   ├── f89f7ae9e13c7df6f5e664c954572ece48365fe6.nq.gz
│   ├── fa2caf1d080209e34436e105351f3696c99dff6e.nq.gz
│   └── fcc146e041723ee14c113ad1979ec94c23a0c803.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 17116ff7c9013772e6815b6b6dd16583d1518591.nq.gz
│   ├── 90c1df130145921a302340b33dd61ac6db03ed6f.nq.gz
│   └── ba387079a4100bdd97270bf71dcf5654864b5a60.nq.gz
├── filetree
│   ├── 17116ff7c9013772e6815b6b6dd16583d1518591.nq.gz
│   ├── 90c1df130145921a302340b33dd61ac6db03ed6f.nq.gz
│   └── ba387079a4100bdd97270bf71dcf5654864b5a60.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 62 files
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

[asimov-platform/langchain-asimov](https://github.com/asimov-platform/langchain-asimov)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
