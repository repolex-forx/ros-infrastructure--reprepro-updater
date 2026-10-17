# Repolex Knowledge Graph of ros-infrastructure/reprepro-updater

RDF knowledge graph data for [ros-infrastructure/reprepro-updater](https://github.com/ros-infrastructure/reprepro-updater), parsed by [repolex](https://repolex.ai).

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
rlex download ros-infrastructure/reprepro-updater
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1ade02f3d773e0122a3347a6eea4455025b96d83
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1ade02f3d773e0122a3347a6eea4455025b96d83
│           └── chunk-001.nq.gz
├── blob
│   ├── 02187a627e903a465b2c47b0574bdd5d7ee773de.nq.gz
│   ├── 05873413b1417270fca9c0ee48209c090d2b98e8.nq.gz
│   ├── 05f3697c5ce9e411f64731ed9ac0dafb9a993b82.nq.gz
│   ├── 089cc8d5c80ffe70b3e6f96d45907b35afe04554.nq.gz
│   ├── 0c77d57ddfa5593b8e165a219b0d434a0637e56b.nq.gz
│   ├── 0f9737f56b007732f5938259cc37cebcf703ee4a.nq.gz
│   ├── 0fe2abcfb873321af9d3c4c217aa9c11d73a50d7.nq.gz
│   ├── 147efbac5e5020ef342b9647a46ce5e368f88aa7.nq.gz
│   ├── 1acf7d61973439e92fbf74c17dee3350559f4fc2.nq.gz
│   ├── 27679b311945a349c39c62643cc3eca7bcadb234.nq.gz
│   ├── 294d3bbefbcc043afa96983c3aff0ff3c7985fb4.nq.gz
│   ├── 2e9a83f7a81e384a29e21aabe1bc2fbc7d2c86fb.nq.gz
│   ├── 2f836aacf266b3e7fc17ec2d8a99aa68c904c1b9.nq.gz
│   ├── 31cc0c6b8627ac05d0507bec4b6d99775facb43c.nq.gz
│   ├── 38f2c4d56ea1045ab5970ab9b2d7b0629de4e3de.nq.gz
│   ├── 3b624ba396873bb1df88d19fcf635e6ac9a67772.nq.gz
│   ├── 42cc725d9741e64300aa79456f895555ad431c58.nq.gz
│   ├── 43780aa401c438d9692e463f930f7b078d42aab6.nq.gz
│   ├── 43c15fd1f2a74bc503c3556cca3c8f432a6c5eea.nq.gz
│   ├── 4460517e8fa310a1fe6e8a455f10e993d5397c57.nq.gz
│   ├── 454702aee42726afb653ec692694858e9d7386a9.nq.gz
│   ├── 47e95b0448b0ad6ccc94d892c05e28ee0494a230.nq.gz
│   ├── 4980b41c29af4c1497ab566bdda9f61f0c4be13e.nq.gz
│   ├── 4b157278aa1959a81aaf1319f8a9d0b65646c2cf.nq.gz
│   ├── 4ceff2da7b4f030ecec1e613222885e1c73cfc7b.nq.gz
│   ├── 4d509c4fb72fc9aa50293cd86f362bce68145a01.nq.gz
│   ├── 502efc658861b86286f1a650171c4ea5fc203239.nq.gz
│   ├── 544f99a35ff92533f75a1fecb90fb5680ef9e291.nq.gz
│   ├── 54d04e4654f43245755659a42e632f33fdd33d65.nq.gz
│   ├── 57fd77a1442034b4eabd766013285c9f0c9bc788.nq.gz
│   ├── 582569f3a04fcf6b5acf5956d7ad4d4b91c0824e.nq.gz
│   ├── 5841014bd95e67c62024c8424dc9e17e6599116c.nq.gz
│   ├── 65a6b0a11b8490e923344ec9808ff8c0c7c91317.nq.gz
│   ├── 6f6bbc6c16541807878ae60b064108d8275fdf45.nq.gz
│   ├── 7700221898d42c20f53434a56143c6c8daff5f1e.nq.gz
│   ├── 7ef0f327acb81a346d464ee0388288c9939f0b63.nq.gz
│   ├── 82b5277dcb9fb22b6e825214cd5f95e1031cff66.nq.gz
│   ├── 844807d78c7259639b7fbe0a9c0673bb0aa3086b.nq.gz
│   ├── 8716df41a53c1f9ee2c80f9a6e9636c57680153b.nq.gz
│   ├── 89dd229f619295882b6a782a1c94ed7dba0601d8.nq.gz
│   ├── 8be262bb266f4a83230e778fe76fa63688f20b55.nq.gz
│   ├── 8cdd6b4e4242977ee39b4d51078383299f117df0.nq.gz
│   ├── 9578bda261eecb04b22bb221382772aa61fc91fa.nq.gz
│   ├── 958c2c6cf6cc1988ee56232b0fc31cf25458aa19.nq.gz
│   ├── 9939ca87fed7bf022cc76f7533a141b98a3e6436.nq.gz
│   ├── a18871610a608621202a79a9691206b655af58ae.nq.gz
│   ├── a4de02c8a873e356121c4dfb71b8c4bda607ccbe.nq.gz
│   ├── aaf6f6b89c8328422681de016054f0ac7750cdf4.nq.gz
│   ├── b3844c3f1eeef28a6a76ca81642dff9d54ef0cbc.nq.gz
│   ├── b597adf901f100bfa31269fe18f6334d40601908.nq.gz
│   ├── bc78cfb84395f9b04f213fa2c5a03fdc7a347829.nq.gz
│   ├── bd6900829ec26237e4f53422604ae503839dcba7.nq.gz
│   ├── be13f1ca54d35f607983f89a27230ffb000d3de3.nq.gz
│   ├── be28e72645c48bcde080a6fdd87a8f6f22d46ce8.nq.gz
│   ├── c126aa34d4c61d6189a395557fbb6e842ac78eab.nq.gz
│   ├── c2a6682a9a9e45b3eed9f712460e8c7ed46cd89c.nq.gz
│   ├── ca1de177b8bf9996881bf241ddc759bab5cf3f7b.nq.gz
│   ├── ccd3c2b5a2e0fe5a0600407ee4761c9f832cfb46.nq.gz
│   ├── ce172cd3bd28a0ec5b370ede101ae063d587ef85.nq.gz
│   ├── d27c5ebd4d32aa5b0657b356f9a166460787f2f0.nq.gz
│   ├── d4a36a114cabb7ed920f2fe6d2c63208f338b1a1.nq.gz
│   ├── d74a3d2178c16faf289479fe27feaa48f9411a9f.nq.gz
│   ├── dc77f4edfe63f8c52202ca14568c0e39ccc903d2.nq.gz
│   ├── ddfe447ec07d69cae01c9a19c2f0edbcfada2623.nq.gz
│   ├── df009eaf2d1f611efa8bf6cbfeddbf06a653bd90.nq.gz
│   ├── e38d913ca4febb0d40b4921151959c54a1c13648.nq.gz
│   ├── e39d959a2d212b95a3830431285e262e2162a83d.nq.gz
│   ├── e48fdce2c6bff9f7b482ea72998022259c9a6003.nq.gz
│   ├── e5b005f59ad456dba16b276a8272c8a649109307.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74bb1186d850a78ad01b20a1a3206e6f26cdfd0.nq.gz
│   ├── e7a3761570a857fbf3519fea6b4268609cd551b0.nq.gz
│   ├── ea175e4047e1e168504e0ac88275c5df68f8fc9f.nq.gz
│   ├── eaccf7e62e015b2ba1a0ba994786fddbe2939eb7.nq.gz
│   ├── ee3e222a3c1fab2b6484c94ef72b883c9b23e2a7.nq.gz
│   ├── f7861be7e00ed9dcdf240c2a922bff5d1cbf3c45.nq.gz
│   ├── f9362eefef96a3622a3703404b4052b02ff1a28f.nq.gz
│   ├── f9fcc7f7353afb8159a91c304d9b0ec298cc7251.nq.gz
│   └── ff4f9e951ae8dd9a844a7046217de429ed5b443c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1ade02f3d773e0122a3347a6eea4455025b96d83.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[ros-infrastructure/reprepro-updater](https://github.com/ros-infrastructure/reprepro-updater)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
