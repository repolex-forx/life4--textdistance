# Repolex Knowledge Graph of life4/textdistance

RDF knowledge graph data for [life4/textdistance](https://github.com/life4/textdistance), parsed by [repolex](https://repolex.ai).

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
rlex download life4/textdistance
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d6a68d61088a40eef5c88191ccf79323dbf34850
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d6a68d61088a40eef5c88191ccf79323dbf34850
│           └── chunk-001.nq.gz
├── blob
│   ├── 077e6f4a26b74f962e7e655cb7ef439b5c46d963.nq.gz
│   ├── 0a6e02f00872822ad4dd2408c41856b26a135e5b.nq.gz
│   ├── 10856ac0e9839fa4fe8b5307fbca4808ea92f404.nq.gz
│   ├── 1548cb6ca7c08c549b2177f91dfb760567ddbb17.nq.gz
│   ├── 1ed057131c90190b6e515d68e3c97da8f10dcfa5.nq.gz
│   ├── 229b7d33f92ba0a6e1a8d7cc6da14c628bd08ecb.nq.gz
│   ├── 2659a4ea9535d08e022be9c2cb7777286bb9aebe.nq.gz
│   ├── 28f8948909bdb5c66ea01650e0766550e227fcf2.nq.gz
│   ├── 28fd15174c7e6a19af19e515ebee36d092a8c29e.nq.gz
│   ├── 29109654b400d69ecfd8770adc407526ab1108a7.nq.gz
│   ├── 3252569cf7362729d17ee436fb320186d76df0e3.nq.gz
│   ├── 33b1f800598642529b03fee8b92e04acf69d549e.nq.gz
│   ├── 380a632e309c2ddb3c8dffef4c50380513549249.nq.gz
│   ├── 3b9bc1ca3a85d9fc4880e8e2a3b88048070eff42.nq.gz
│   ├── 3ea60406e35a0bda7a95521562717e2fe5b4d52d.nq.gz
│   ├── 3eb1cb4bc55bd4a4ad8ff948d01430f1d13c0d7d.nq.gz
│   ├── 49588afee30973053150aedab6c15f6616ef9bca.nq.gz
│   ├── 4a3621ab24459d3f787e564958c0355ff3db62d2.nq.gz
│   ├── 4b710b5539a77d01e0bc0f55906e799f95121ca4.nq.gz
│   ├── 4c243bfd84a42042d07da6e3fe8d89fc3c6b5994.nq.gz
│   ├── 4caedaada4c684d18c310bf00286e3631cc45feb.nq.gz
│   ├── 4d01e422cbef06cc7614dac48232a568ed1c4da3.nq.gz
│   ├── 534449bd3c970ac1c04dd092519921999cb6e5e4.nq.gz
│   ├── 53cbc0dea4e939535e26ae324f79ac8b15bf1381.nq.gz
│   ├── 5630e92181b5d2de141e200db665648d8182f24f.nq.gz
│   ├── 5734419e257284316f55f744e068e11b2d101900.nq.gz
│   ├── 59e689e11d064551fe0750bd23e4aadf9192f536.nq.gz
│   ├── 5c518b8f5e3e7c09d7e4166b1b2bb98e58b6b106.nq.gz
│   ├── 5ce8cc7029aba4568f84278acba39c3c86671b6c.nq.gz
│   ├── 5f63dc7573b8563b936c290d47bd09ce2862d517.nq.gz
│   ├── 66438b757a204398b5780d45114ad24534faf53e.nq.gz
│   ├── 6e8176498496759dce77e3fa696b401571ce6705.nq.gz
│   ├── 6e9113f508ab1d429a3d77b880e31f9104ce83cc.nq.gz
│   ├── 6f9c747b720a045a921e2325ae40a99a8aa498f3.nq.gz
│   ├── 79ce4b6c20960427583ca104575e24aed0b3c3a1.nq.gz
│   ├── 7a7afee3e75824e561e1c30a9fa4d5a18562376f.nq.gz
│   ├── 7d84acb462956120fefd703be003679ffccd2441.nq.gz
│   ├── 808d2a61ca73a3be79974d79f3384aee88377832.nq.gz
│   ├── 89d06113adc9a8ce73a3f12bb115be75723129a3.nq.gz
│   ├── 8b4cb5893921e6334d116f4f1c5e6774981222f6.nq.gz
│   ├── 8b94bc430f0c07727c8eaa67d2d83b7c9e292eda.nq.gz
│   ├── 8d0b0aebe295ab8373de11be030771f2f1ad1705.nq.gz
│   ├── 908a36221437a88557cebd836797094f1499ec70.nq.gz
│   ├── b1fd7afc4ff45c051e2d4f27cef0e986c71d4cb7.nq.gz
│   ├── b20b33bcdae06a6861ee86ce62ea27a3eef0f5dd.nq.gz
│   ├── b384bd62c50da8ad03f06ca59f6a0e84b87a131b.nq.gz
│   ├── b8b42e24c5eadd9bcc6bcf529b26f61b29638036.nq.gz
│   ├── c007c59f9afab688dd05ef9b2b2f5a9a157a6687.nq.gz
│   ├── c0e19faf2e94bef195bb5e23784716302652ed0a.nq.gz
│   ├── c1cd59cc47f2043567d64e732fbc34597154708c.nq.gz
│   ├── c4fe3ceda3479080cc3f8dcfb3ea902a648c76ce.nq.gz
│   ├── c6bd195b21dbc128172c69431a0666c231751fb5.nq.gz
│   ├── cadb074632c7d50bba06be4523cd5cdb4a6772ca.nq.gz
│   ├── cbeca15f3e2495d8d5e3f7fdbbadabe26331b04e.nq.gz
│   ├── cd5181c8d947316fd1617a927ffab774c6ad9eab.nq.gz
│   ├── cd7fddb80e5370fc9a1ab322b0cea1dd8d7d10e9.nq.gz
│   ├── ce78544a9bbc929798911c981a14e20a1adef255.nq.gz
│   ├── ce7cddcb03b733bcf76f6326c84e19b3a710d488.nq.gz
│   ├── d25c4b56770161df7de54f0fb3cfdb0a85c8b45f.nq.gz
│   ├── d7ded1d4131e98d375e0d9ded2d7c6b31cbf131d.nq.gz
│   ├── e37aa63b6b3fd809e541d57139ec5dce79a15d36.nq.gz
│   ├── e6284512554a9f58f6d102be8d9996a66c43b842.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f6c2e8dc3d7d2d2228855e128539f9b306b3c2b9.nq.gz
│   ├── f925dace30d009149d72d925ea3d0024482b8ecc.nq.gz
│   └── fa24ea6663d0900dd86c0fcf21d884fdedc90a75.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d6a68d61088a40eef5c88191ccf79323dbf34850.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 73 files
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

[life4/textdistance](https://github.com/life4/textdistance)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
