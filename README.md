# Repolex Knowledge Graph of apache/pulsar-client-python

RDF knowledge graph data for [apache/pulsar-client-python](https://github.com/apache/pulsar-client-python), parsed by [repolex](https://repolex.ai).

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
rlex download apache/pulsar-client-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e0cff2cbd6769f2839b56e2f89391255ab0be1ca
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e0cff2cbd6769f2839b56e2f89391255ab0be1ca
│           └── chunk-001.nq.gz
├── blob
│   ├── 01554a9ace273eb8a4cb9c7c6073a33f03a10a5d.nq.gz
│   ├── 06e3f284139849610dacc87238df929ed22c1603.nq.gz
│   ├── 09b341bff51ba97d6e97eabea0fceaffe518fad1.nq.gz
│   ├── 0ab818e8f93876a7fcb6f29ab9357209056b360d.nq.gz
│   ├── 0be801564066a736bde330018331ea17c54597de.nq.gz
│   ├── 0c7c0e6d88d12796ce0ae20b420562ff37b2e914.nq.gz
│   ├── 107d25db15e38f549bc3756935cef378ada24a61.nq.gz
│   ├── 1411ebcc3e98b6d55143ba42db8d6f647721ec6a.nq.gz
│   ├── 168ae0d0073bdb989c549e2f4cac5d519ddb3b44.nq.gz
│   ├── 174a39b21f13d5edeef16b45f6351a84bd644bcb.nq.gz
│   ├── 1852cd973f0afe4d53084cd657c6cc2cceb04385.nq.gz
│   ├── 1b425c8591f80113a8463f5f2c269207ba3f4636.nq.gz
│   ├── 267991cd231052983052ed2bd0c6cc6d5fb46445.nq.gz
│   ├── 277b7e227f694b7f86fd9273e2e42ca16777e1ac.nq.gz
│   ├── 28a930d1f33c5a62bbbc7d7486734f147876e59d.nq.gz
│   ├── 28b377c4af872f9fb538854643e805869eed380e.nq.gz
│   ├── 29438a25c85fd4febadce13e3b3ed2f12a1453f2.nq.gz
│   ├── 2aa3a4772abba67f90d1b18fe14aedd02657716e.nq.gz
│   ├── 30c8859fe63abad2b6124de2ba3637d8d792d4c5.nq.gz
│   ├── 32b4b1ff2012c0538a48db7e244a68ef5ec5d450.nq.gz
│   ├── 370205dfb581202986e663b60931e07e0fdd5c7f.nq.gz
│   ├── 372e5491bf717e05af508e96413573dcb77c5488.nq.gz
│   ├── 3c9949429d2ac46e40cfc6bc76dab675f09ab119.nq.gz
│   ├── 3e2831ae8a39895f8d2ada47d698c644e382f643.nq.gz
│   ├── 42b659054e11877a30310cf239c90f78fe751d95.nq.gz
│   ├── 45941ea7759fcc45a359b106b7204988351f86d0.nq.gz
│   ├── 45f3cde215fe5c40874139fcd7ec34044cc85870.nq.gz
│   ├── 47c179a51ede902842ae5ac2a603f09ef39c6fc2.nq.gz
│   ├── 4b8fc18e4ec65950048e30fa971e17caef71b995.nq.gz
│   ├── 4dd3163172f4f1a2d7bec9cf17fccc9704576e00.nq.gz
│   ├── 587d6c61718ebb17a2182927fb82d15fc6a298e1.nq.gz
│   ├── 58ab3d4ff9be8e993ac85fa862520aa19b35a140.nq.gz
│   ├── 5a1ff5b62a547980718023686408c884f3f128ce.nq.gz
│   ├── 5aeb429a3d695f7a79864e53adf20fa5a25f1080.nq.gz
│   ├── 5fb186092182bb84501610d7e062869b1ccb99a1.nq.gz
│   ├── 608d16fc77435bec274bd572fedfb663d44d9498.nq.gz
│   ├── 624cfcb19d5d1acf0f16adb0ba16578c294ee048.nq.gz
│   ├── 6252937d83a447ccd9987cf7871f14192c10149d.nq.gz
│   ├── 68eb499fea89dcfa1c3c31c0daadc28adeb220c6.nq.gz
│   ├── 6a9b1a547cf19187eb26e57ecb8d4b8d424052a5.nq.gz
│   ├── 6ab3abb1c694a8e1d60fc854fc930cd1dd1d6f32.nq.gz
│   ├── 6abfc2d80c12301878082614ae3ae762df57fdf3.nq.gz
│   ├── 6c42f8cde83e746950f550005f98e9a02910dc7f.nq.gz
│   ├── 6ca73b11089772893228bf11dc150d21214d6cea.nq.gz
│   ├── 6d61f99176c5b2a81d5ab6f332adbc86d57e987d.nq.gz
│   ├── 6d8672b60a96959bd664ad985372e113dd5faa1b.nq.gz
│   ├── 6fc427b1b19dc654211841faa5635b1a7ed79869.nq.gz
│   ├── 702bb5b03302c8764d924c461248822eed110fb3.nq.gz
│   ├── 747f4765e2de8507e04900b1f7b480b0824742eb.nq.gz
│   ├── 7670bb9ec69d50291c6b1e084e5c7734525fbf1e.nq.gz
│   ├── 89bb4603b6b8f00bac8e295cf9e5e79fee7b387f.nq.gz
│   ├── 8d0a02f24214fdac1428a00e81456ab0462b2c51.nq.gz
│   ├── 8ed4875cb948b10738e5c066dff7702182b84a31.nq.gz
│   ├── 8fb04671589eb771cdb1cbbb3649f903bccc1316.nq.gz
│   ├── 910f0cde60924039f67e7d20e9e1add5b0e090d5.nq.gz
│   ├── 94c677451678d7dd032d17cfaed3c28049382f00.nq.gz
│   ├── 978fc21d95e555f23bc55b93f23d3371f02c92eb.nq.gz
│   ├── 9d3bf4e2c346dfea04a88317917978f51efc12fc.nq.gz
│   ├── a04ff0bad7001c3f841d18fffdb6dc5e3a8b7024.nq.gz
│   ├── a0d589e0e2a4c1dfa1668442d5955d675413cf1f.nq.gz
│   ├── a6981d397d870e66eae0a152650d947947535088.nq.gz
│   ├── a90eb86150542c0283e6e7a9c45ceef1ec376b0c.nq.gz
│   ├── ac543a27744e5413c07184c0122c4240298463ef.nq.gz
│   ├── b01979fe784e7f27a0fc95ea29326f1cc33a793f.nq.gz
│   ├── b3ec77558024c0696b36a55447f0f99f2f1b84f5.nq.gz
│   ├── bb687ae6883690f7be5f9d41938637ba609f7824.nq.gz
│   ├── bbbe4fab89b56a88383855358d829ba3fa9c69f5.nq.gz
│   ├── bbf389f965a56fc5f114663fc47a9a0231cf94c8.nq.gz
│   ├── c1600f29c3b0adde21d77db9fb23ed9ed8ecd8c3.nq.gz
│   ├── c33780d68a6b949731f66ace73bf2a4837d1cbdb.nq.gz
│   ├── c57f9ab74b94ef7ea3e8864696086b300862e363.nq.gz
│   ├── c9c8ca1f83ddf6ed45c530b2fa9e65ef4450f96b.nq.gz
│   ├── cb40b5069841e2efbe5460d55555da47f8b637eb.nq.gz
│   ├── cd068a3a33eefa61d4d8307bddbfb3dedad9ab5b.nq.gz
│   ├── d19b2802b79880520d4f299da49925ddbe8b912a.nq.gz
│   ├── d2796d2ffb474337396d9b5e139c04642e79b1a5.nq.gz
│   ├── d3adcd4116cf61e0e64bec34b045f76c434985b5.nq.gz
│   ├── d4bde6a0155c5dfc8fe412353f62a81a440ffcc3.nq.gz
│   ├── d5c445f929b29891f06286b0371c6e09d8b4e089.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d698f489ddaef276b143a6b84667a166c255ba91.nq.gz
│   ├── d6d504dbc58ad1c976d7a9391486aef8c5c95adc.nq.gz
│   ├── d7fcd7a5a6f4e178abb32040ad81bb1641830441.nq.gz
│   ├── db1eccd8eb67871b29c4a97435c5ee8d6e074260.nq.gz
│   ├── dcf8e28b82773067f439950f06d9ea4fc69026ec.nq.gz
│   ├── e12697c966a9c1022487b867fc89245286337829.nq.gz
│   ├── e16f8e969355a4cfad2c92636e248068276b95a3.nq.gz
│   ├── e3fa49e83838f5269ecc4f473399687aceee9429.nq.gz
│   ├── ebc8e599e1c93e1c41ad695dac850ff7b277af2a.nq.gz
│   ├── ec16b525b6d7b39050901f300a78ed0ff8094a77.nq.gz
│   ├── ee03e754beee19c7fe130cd26c441a9103eef5d9.nq.gz
│   ├── f2854f9e7b4fc458a8d56c07d581bbe95f39d0c6.nq.gz
│   ├── f3bdd75bacb1192fdbb9e5968ba6fd44ac14edb9.nq.gz
│   ├── f45b801d5ce9d907971e86ae857097bb8a6b50f6.nq.gz
│   ├── f9e45f6473692b10729784dbb7ba6ecc55ca51fc.nq.gz
│   ├── fceac5480f41285591bae0314a1bfc4f1cbc9488.nq.gz
│   └── fe95886d5c104d4c78cbd3615bec9bd56364a7cc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e0cff2cbd6769f2839b56e2f89391255ab0be1ca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[apache/pulsar-client-python](https://github.com/apache/pulsar-client-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
