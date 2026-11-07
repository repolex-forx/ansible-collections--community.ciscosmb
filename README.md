# Repolex Knowledge Graph of ansible-collections/community.ciscosmb

RDF knowledge graph data for [ansible-collections/community.ciscosmb](https://github.com/ansible-collections/community.ciscosmb), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.ciscosmb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5279c8390289ce921ba3bc721406c9bc571d1bb8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5279c8390289ce921ba3bc721406c9bc571d1bb8
│           └── chunk-001.nq.gz
├── blob
│   ├── 05198c68d87b63ceefa14956a2e3401867be69ac.nq.gz
│   ├── 0e01496bce6f0c3f4b01f77ce9850c222237140f.nq.gz
│   ├── 0f797b014a314ea64c863d0889fe3e475cda9d9e.nq.gz
│   ├── 1205f86e89643c7b5e92c5096dbc33985752d6fc.nq.gz
│   ├── 1ca8a665f2015dd6a3ced50dcb7abced3ced8117.nq.gz
│   ├── 1d476001adca8b93a681f5ed9ef6aa4f9e12e9b9.nq.gz
│   ├── 1d4e7303917480b07c59c61eabc65403642c12c0.nq.gz
│   ├── 2d0bf0562f18330e8b5635682b94a6fde9353815.nq.gz
│   ├── 2e85462537fa85dd28e3dc7eacb92c984fc1b8a3.nq.gz
│   ├── 2ee1309f8f4fd16887df2393747e969d088fdc3b.nq.gz
│   ├── 348f3f892dfadf12cc204830119b10cbd9065a98.nq.gz
│   ├── 34c53caf0658611594966b7f25db2fbe2718a62d.nq.gz
│   ├── 34cc62be0c51a6a5786da72fb5c03bf363efa13d.nq.gz
│   ├── 3758db46e3896ec0e6a58b3c70429623242c1e83.nq.gz
│   ├── 3d5285c7965e9084145b3975a083e91bad2ec154.nq.gz
│   ├── 415916a4021de3c14e293dc9e9162995a302af4f.nq.gz
│   ├── 45e26f35d5a975401928f76ec4fd8a755ad1fbff.nq.gz
│   ├── 4aafdc06e638568f516e42835eea2778f256d8c3.nq.gz
│   ├── 54a9e4c1cae8a1da2cb2e857d81e1511f602afd5.nq.gz
│   ├── 5b2722ac723cb08b77271ccf2dc6db6b9d2ac8b4.nq.gz
│   ├── 5d25fbe160665db71fbe3efd85fd93cff67e574d.nq.gz
│   ├── 61b5b1d0dbcd84013ce8aa5fae7bbe486b3c3e47.nq.gz
│   ├── 657a2d200dae2ec5f421dd7bd63d8d904128df74.nq.gz
│   ├── 684a747f4590dc0062b15f59a94527f7805657c2.nq.gz
│   ├── 6d79e27e5c57a9458f84434a6bb911b9859764b3.nq.gz
│   ├── 73037a26972d83fa75e57619942dad4bdadef390.nq.gz
│   ├── 77ec3b50f64a7286acf413cad3876783730cd8f0.nq.gz
│   ├── 7d6f1b463bfab063f04c6fb40e00d74d3ca2a3b2.nq.gz
│   ├── 810b9de3949514aadc107ed15487fde85e2e185a.nq.gz
│   ├── 82d8d43dbd42407e698b0f81d5401b5bbd0023cf.nq.gz
│   ├── 8441e2672a0469cf4043605c0bb478b2a49de695.nq.gz
│   ├── 88cbc0ad84a5fe99df9ebb4d45664d2c4c92d8fb.nq.gz
│   ├── 8bb80c45e49fa2c60df3d7786d40bb94835d7ef9.nq.gz
│   ├── 8be6a5c6c54dd1e2aa9467e75fcc624406c41e6b.nq.gz
│   ├── 8c7135e9bea0b3b416ba5b6586e5b16e4fe74394.nq.gz
│   ├── 90726eafc50673b3aa43d5ce72aae692e5946e46.nq.gz
│   ├── 912add2c94b947b75b4bd546f2e19951545a6b57.nq.gz
│   ├── 964565d79e7fc48ff80855ec5d9880e7416ab7d5.nq.gz
│   ├── 973bb7fe219bed68445fa61a84012089e814033e.nq.gz
│   ├── 98f08ad6a8474fbcc3e338436bae46663d4aa4ae.nq.gz
│   ├── 9bbaaa252d23f51c3ea2aab168c16d57c75635be.nq.gz
│   ├── a2146db036a7271fa11c5996f288c825ad4e85ee.nq.gz
│   ├── a26f165e0ad7d410d6a136fc226004fb80c88e06.nq.gz
│   ├── a327d67accc29ac2c91c41072c7069fadf32bcfe.nq.gz
│   ├── a6f1af870ecb229340cf675411ffad2aebe206db.nq.gz
│   ├── a9d49c95b9c57eae550e633db476a19f9fd3d204.nq.gz
│   ├── a9fad825a5e96aba276403dd8d6f78d6b04c372d.nq.gz
│   ├── aaee0dd330dd5ad983a885a91d1be5eebdc35117.nq.gz
│   ├── ab4458f5cc145a345b068b4c42f5a997064438aa.nq.gz
│   ├── ad02aa9a80f285219234f3b45ad4b344050c440d.nq.gz
│   ├── b1f39bc238778f30f74fe27ec69cd185a8f4a08c.nq.gz
│   ├── b2fae4d92e6a6aa1f98eed9df27e3c4b6a4b98d5.nq.gz
│   ├── b33aa5e0e09880ceb7963bb779f678b57598c06b.nq.gz
│   ├── b4a5c336013e53c1224ac889bbd9737cdf0d8049.nq.gz
│   ├── b5efce713973efe1826eda7feff579a3833e5501.nq.gz
│   ├── b6b389cc4d632a83d31e5c6fbaeebcc49d9b10fa.nq.gz
│   ├── b71e330f2367a1a5c06ae23c5b0602559791165a.nq.gz
│   ├── b9b719f67eb0d50ea6f3aa0753b2567ebed79df1.nq.gz
│   ├── bcb9b2d5a988787ebc388b1f7db4e5a13018bbfd.nq.gz
│   ├── bdece2632a60bc4ff621c9202023a671d0ec26e3.nq.gz
│   ├── bea9188b89bceeb34e4aeb628abb31f288dc176e.nq.gz
│   ├── c07201a6cc367d4b453ec2966a7c475d151d8c83.nq.gz
│   ├── c17f21e07f8ac672c0b9a415a4a40544ba578c0e.nq.gz
│   ├── c61804f01ec0ace423d1545641b4ce463bb0a304.nq.gz
│   ├── c8ab639f7f28bf8c9ddf851628c3a07753364fe2.nq.gz
│   ├── c9a1463d2c0c5ccd711c6efa74a9a86b3ed02b30.nq.gz
│   ├── cad1010d1be0a6c5bbbfb1b39f5e6da6571c22d1.nq.gz
│   ├── cb6a3da145c1f2c8afee1af9628995e27a773cb9.nq.gz
│   ├── d02708e020b1c49fe458027c8dc7ec6c081f43d3.nq.gz
│   ├── d25715528ebd9d4d0d2ff4245bc71261f548632b.nq.gz
│   ├── d292d2b216692a4e93555f1f1659aa822a6c6dde.nq.gz
│   ├── d53ea4805ff69b9340457b35c557d02acd969038.nq.gz
│   ├── d786c0085a005933ab6dc587fc8c340e77686a03.nq.gz
│   ├── da446e95caa1ed62d6f3824ddd58957bb6548f83.nq.gz
│   ├── db19edec65ebc50c21bea7769ea2daae37003209.nq.gz
│   ├── db8fb6c5d2b07a44ab441639fa5e2129691624de.nq.gz
│   ├── dc84dc097c9a709231aa38b3faf1459b12124f85.nq.gz
│   ├── dcf5e44c7862f3786633970819e3972fc8bfeb2c.nq.gz
│   ├── df459703e94cb857a734f36eca715b52b772a102.nq.gz
│   ├── e0afb663fbdf0caf172b77610f221a1d2a05e2d6.nq.gz
│   ├── e1b1b0dd2c383ff42317f1b977966a1aa36aff77.nq.gz
│   ├── e2a4ba8f78080787bb44ad40f56b1c9a1c851557.nq.gz
│   ├── e33eb402e1866db8cbb02e43c367a3087d85fe6b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a0a6308d2157e4c75d855e697e75d924529622.nq.gz
│   ├── e6eee7ef7237b6a3326a13b881cce589cbee9adc.nq.gz
│   ├── e7002821aaa01ddd1c18a2ba1ee433be00af28f8.nq.gz
│   ├── e81df5e54d75a7a0e26de32df3348c145611267b.nq.gz
│   ├── ec3112a7a4dcbebd34f55b9437ec368cbbf10d83.nq.gz
│   ├── ec372e236a84eaa0d8ee9bca2dfa7edfe1eefc5a.nq.gz
│   ├── f08275b47a792f5ce098b77bf0835abe9513738e.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   └── f996b84b3a5f4cd532c0d3a4cce05bf233f93cd6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5279c8390289ce921ba3bc721406c9bc571d1bb8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 101 files
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

[ansible-collections/community.ciscosmb](https://github.com/ansible-collections/community.ciscosmb)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
