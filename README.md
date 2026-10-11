# Repolex Knowledge Graph of samuelcolvin/jinjahtml-vscode

RDF knowledge graph data for [samuelcolvin/jinjahtml-vscode](https://github.com/samuelcolvin/jinjahtml-vscode), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/jinjahtml-vscode
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d8daf5fd43941deec8803be2335b35922e3e1eeb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d8daf5fd43941deec8803be2335b35922e3e1eeb
│           └── chunk-001.nq.gz
├── blob
│   ├── 1129e9096f1bda16ff9d00d6b2824c8f48f4ccee.nq.gz
│   ├── 156132d358606bb7fd84637e35c4dc4d5bcfe2c7.nq.gz
│   ├── 180c903e8d64ece89423375fcc2a199a0cbd4549.nq.gz
│   ├── 1bd9a0ae0c5b69b64769e65207297554fce00c6f.nq.gz
│   ├── 223290f3dc816d76a39604389dd82d8d4becd6dd.nq.gz
│   ├── 22c8610e33bd106b98e2da3d9298b4a82f6f699f.nq.gz
│   ├── 22ead7677833d504236c52f775da41ac062f6777.nq.gz
│   ├── 270f1a707679f4c654fd47ba3d7345e5434161b4.nq.gz
│   ├── 2974f0d4a6163d44fe76b86f600352b30ab35563.nq.gz
│   ├── 2f95f42043caaecd7c58f001e2fdeb19dc011529.nq.gz
│   ├── 3054aa4d9d6664a763c32ad3442831f761165578.nq.gz
│   ├── 341774698cbd4ff30d2863adb3d8d4473e4d9679.nq.gz
│   ├── 37e83400f6d99a14c7db47f3e0550e5fd3c12c6b.nq.gz
│   ├── 3f031029f2c9cc9c2e15b1ca78169415972aea78.nq.gz
│   ├── 42ba6540d841acfcb4b123d8d10d6243b8630f06.nq.gz
│   ├── 455963f41782c79a8b56535770d474fc3decb00c.nq.gz
│   ├── 4cbcdc1710431e0a20f33ebde74cbfbd84d01ba7.nq.gz
│   ├── 4e04f15712693e686e98f7cc4267a8d74fb6cde0.nq.gz
│   ├── 536ca95136e89d5698a045747a16193f7a4a7530.nq.gz
│   ├── 53a7b44b4cc53ada660c7963c7395d25185cfed4.nq.gz
│   ├── 561ca8efc574b54e2d56a80298147cfecfbdefb0.nq.gz
│   ├── 57ce26f0626281987f8d21b8d4f03522fe72bcc3.nq.gz
│   ├── 5bbea056ed5faef4e89633444eddfdf3544bbf7e.nq.gz
│   ├── 5c30f282e8e482655190bfa368b68bb1aa092466.nq.gz
│   ├── 5d61ae1f9f462acdfc432f3aff4a231f06858c91.nq.gz
│   ├── 641bf1e07720ff354939a3e3eef1aa9d275fc735.nq.gz
│   ├── 67742f624284d2307c98cf9c5c9501715ee2a6d9.nq.gz
│   ├── 6ab1dd2e4a2f4557f25712dae6022e14a66039a5.nq.gz
│   ├── 6c32287f89a57990054d500ac9e12cf1afdb2fc0.nq.gz
│   ├── 7142c6d92030445dbe0464a2cd56ae7436b9945f.nq.gz
│   ├── 7567eb9bf8ef0b3f5ebfb893fe9c51ba6ef342cc.nq.gz
│   ├── 83ca36fe28aa7a0e0e66530b8ab550f0f3808feb.nq.gz
│   ├── 899538a0e483331e23c9f50e65e096e8e1f0d1a8.nq.gz
│   ├── 9bf79b240e84408cd43d0763c0f49e1aa612c3b0.nq.gz
│   ├── 9d60cc2d52f82944a1a4564d6e4d814adb7f6f2e.nq.gz
│   ├── a3934f70d3aab321bc51c95a28984cb46cb8e419.nq.gz
│   ├── a89a90af8b964edc6fdd4e425cdf27524de28494.nq.gz
│   ├── ab16e61a1689c59d3240bc2fd2f2db6679b22c2e.nq.gz
│   ├── ad186a64e9f2e6190610511cc81cf6294fd31cbf.nq.gz
│   ├── ae538ff7358c6bf70b051ac2f58c808ecd11e635.nq.gz
│   ├── b4bc366d5b5be71ad5198655a0ef89603b911daf.nq.gz
│   ├── bae89a1e33da853054ba25f39809d9b910cab1fc.nq.gz
│   ├── c87d43f7c2478bf401afbcbae52f49fec39110c7.nq.gz
│   ├── c934faafd50dbf2e013510eceb860f819b15bda4.nq.gz
│   ├── c9f7c2cef389c2f5d2bc0c0bc7c7fe1704454b06.nq.gz
│   ├── cd820e2631fe4a4fd55c2c191bce9a255e34d0e9.nq.gz
│   ├── d96ab981e48adeccf8a7411d89b729dda00c7370.nq.gz
│   ├── da873451449c37fb8accfa7e6eb3e9ae92cd9e36.nq.gz
│   ├── dfc3b5df38aeb528181bcba5c6f119d8f42c870a.nq.gz
│   ├── dfc74b56a6452d04daa39c83f209f1d85557dcf1.nq.gz
│   ├── e0caed7e7e3d03c9df9ef255cfeda1dc9241e454.nq.gz
│   ├── e454054c57471ec5d489b5e649d2b51267b34edb.nq.gz
│   ├── e91f869c9beb74f6d79bde8777ce8d79d258dffe.nq.gz
│   ├── e95339ee7f6dd083b71e145aca6b192e74b955a8.nq.gz
│   ├── eae1c0e571636b195fa1761d3f5eb858c2e90a9b.nq.gz
│   ├── ee9a3daa2b65df314c4f8cbf53bad3ecb6cbad1c.nq.gz
│   └── f187dd6f750de180818ced61f5abb147c3a4a090.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d8daf5fd43941deec8803be2335b35922e3e1eeb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[samuelcolvin/jinjahtml-vscode](https://github.com/samuelcolvin/jinjahtml-vscode)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
