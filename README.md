# Repolex Knowledge Graph of canonical/sdcore-udm-operator

RDF knowledge graph data for [canonical/sdcore-udm-operator](https://github.com/canonical/sdcore-udm-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-udm-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5b405fc2e36fd881b77a899abfdc9558583c6172
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5b405fc2e36fd881b77a899abfdc9558583c6172
│           └── chunk-001.nq.gz
├── blob
│   ├── 037e596f5f08f478a56a934f71b3bb249ab08837.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0ff992b299b3f0224c0a4575fb68ea04de62af99.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 2055a28de90818ffa33b0a2ff4e1fdbd93eb1473.nq.gz
│   ├── 26713fa691a51630ec6ad503ed365e74e1bb354e.nq.gz
│   ├── 26d8f21d982d0ff9e2d50df2fd4d8e4b23191148.nq.gz
│   ├── 2f6c019048d137df85cd9e162595cda8e444f8de.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 4593872e8ef740e65e8a2ad3a12d7dabff1efad3.nq.gz
│   ├── 46fdfb6ff31d8f845aa61ec8d9c441011982757c.nq.gz
│   ├── 47b0171737a78ba8eb83d44a3deb6c89d2cbbee6.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 57c9e68726d50480993f9dd3eebdc46fab3ad607.nq.gz
│   ├── 5acd26022e2976b032c21702ee4f936cc0cc4de4.nq.gz
│   ├── 5fb779b31718c99c447084b6623e77b54cca8935.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 7bbbdf45bed96dd74d8c9566653b60262bd9277d.nq.gz
│   ├── 7f83dc94a64fe58ece6921f770e899afb83b8c74.nq.gz
│   ├── 84b5bcc11b994afbd779ec3e68c3a9a92293b2b4.nq.gz
│   ├── 898a0338baa31d89da0cd6f92f02afd88f1119ee.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a084eed0aa58e22d34ac2dcb337e7b7a88a5684e.nq.gz
│   ├── a293554fcb29f3e37070966f473b6305202e2f52.nq.gz
│   ├── a7019cb8b7101c74d54aeedb6262099f954dd211.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── ac406406130d20bd29bdcb548eea70a6a041876d.nq.gz
│   ├── aea18dd9984e8f48abcf073e53510144e3e4b482.nq.gz
│   ├── b07ecad96c255990654a7fc870540c2cbcb58be8.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── bc4b5a46de8057cbc11051996964b8cca6173a9a.nq.gz
│   ├── bd418d4c38a2ac7224a9d96b73029764359b499a.nq.gz
│   ├── c20bbb358d62687650e9ff3890269062b78454a5.nq.gz
│   ├── cd4a3f7e90fc729c4364222a48508762de7a5602.nq.gz
│   ├── d01d3ec218c3341b0efcc04120cea0290c5f3ca3.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── dc84f60847b59992b0e3b3a1626bdad3e95129b6.nq.gz
│   ├── ebf108892050223ca7565b02c12ce993a5e0e52a.nq.gz
│   ├── ed67d9f62e5efc1621f0c0e8ae8ee293fdde7856.nq.gz
│   ├── f0571dc2b05049fc3780efcdffbafae38febe7a8.nq.gz
│   ├── f87b5261528025f1e53689d5d79c8a1e085ad1ee.nq.gz
│   └── fe6675268cfb1a87217e3ea7893a365c6e26ca6f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5b405fc2e36fd881b77a899abfdc9558583c6172.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[canonical/sdcore-udm-operator](https://github.com/canonical/sdcore-udm-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
