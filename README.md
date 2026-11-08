# Repolex Knowledge Graph of zenml-io/template-e2e-batch

RDF knowledge graph data for [zenml-io/template-e2e-batch](https://github.com/zenml-io/template-e2e-batch), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/template-e2e-batch
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b6d727e6f0fedff6f37f5ac43c1f4949480d1160
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b6d727e6f0fedff6f37f5ac43c1f4949480d1160
│           └── chunk-001.nq.gz
├── blob
│   ├── 016509f9facf81fa074b220463ae05a6f99967a7.nq.gz
│   ├── 027f1dceacd4a45bb4313691c9e0ad884e849357.nq.gz
│   ├── 0313aa12258ee4ac9d5c3d567421cde4443c5a5d.nq.gz
│   ├── 146ea8c93a17a4cf4ef65a9a03e7b14d5861a2cd.nq.gz
│   ├── 1604345c1c810bb5449c9884c9034b737d25a946.nq.gz
│   ├── 17859ea12f54cbee0b269c6008c20ac31efe723d.nq.gz
│   ├── 1c99e51fc9ad83100e725421bebc50455df28c5d.nq.gz
│   ├── 1dacd03291aa35883485a2a04cf8fa019d6e2396.nq.gz
│   ├── 261ab71777e164c6214dae2b3396efe5cf87ad49.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2b99d7fabed4663b42ce6bffbbf92e8ef828d688.nq.gz
│   ├── 2d5bb1cf9b2a5573f77b62d4bd26383a64c69ddc.nq.gz
│   ├── 3101aa80d6dd7de8e4c86e72123ef5a05a939a16.nq.gz
│   ├── 31351d37f4a47e636d170ada094d00e9c1ca5bba.nq.gz
│   ├── 3697641bee1afa5bf5627fcb4720e0440004f8ab.nq.gz
│   ├── 3804b9538aed1f0e5c38855303633cefe6c92052.nq.gz
│   ├── 3968c6455f4693fc65375a01ba46b0ec4a8d980c.nq.gz
│   ├── 3de332b9d2a2301d4400a47e60efdd74fa880ffa.nq.gz
│   ├── 3ed55803292e78132747c22bcf5de667b4d8a6ad.nq.gz
│   ├── 455f4d7aed45e1272b330a2054eab17dbff9fd12.nq.gz
│   ├── 4c1c80e8b91699db5c46dbb265558f10eec5e0c8.nq.gz
│   ├── 4d98719fc62567338698346819ab7a9f7ef24286.nq.gz
│   ├── 4e09b06103067efcb6046cf052cd82458e34f8c7.nq.gz
│   ├── 56ca367c3dbde058272c0c25a4d38ca8c6052d3a.nq.gz
│   ├── 56db09b7377d0909e010f757b5c9c7de45774ed3.nq.gz
│   ├── 5a8fcea9ab3895cb153c480c19a53443cb75ec34.nq.gz
│   ├── 5b35ecff35062e9e388b5043ec18e357a2ad34c4.nq.gz
│   ├── 5cd1de160d5794f82af77869129000733a24705d.nq.gz
│   ├── 623727e3a0a38a6cf0289a824f640b01e8f88717.nq.gz
│   ├── 682457e99f2df2aa72e0dfa1cc2dc5bfc559801c.nq.gz
│   ├── 784cb1b659392b6fa765222b9389762f0011f45e.nq.gz
│   ├── 7c5ab09ed3397a8e43741ea99abe987a2e31446e.nq.gz
│   ├── 7fda505b5e2adbef616b854ab7a9485363a59816.nq.gz
│   ├── 8260987346b4d91e8d42744d362bf7a4b898e582.nq.gz
│   ├── 8c717d2dc187aeb8c65aa0e0acde3ecd85a74591.nq.gz
│   ├── 8d25de6987860b4c448cd51a9b83521397d15565.nq.gz
│   ├── 92414584885703a3b4b264d29567126cc8d4a7e1.nq.gz
│   ├── a01f0679270304290332e6463c7602f2561a1905.nq.gz
│   ├── a3b1f630c6fcc723842cbfb1e430aa4855f04053.nq.gz
│   ├── ac1e395381418fb151ae7273f80e4d2fdb748de2.nq.gz
│   ├── ae71ac2cf59072c6dda4dc7eeab900c9024b13c7.nq.gz
│   ├── b22e8a7f176adba05176cc3ad5220bfe7938cef1.nq.gz
│   ├── b353fa8b2422f5d58ce8654c64578839258c1a6d.nq.gz
│   ├── b599ca3d3bae9ebea17aa842186aca3d27985914.nq.gz
│   ├── b8472f2c4ff1a7717b44fee42f3a245cfeaf1cbe.nq.gz
│   ├── b9cf678fd6a754881547b05c72a2f7ec4ac235e2.nq.gz
│   ├── c8b45f6347fff958cf2d5791decef373293e0968.nq.gz
│   ├── ca7144beb3bf4e1cd8594d8c07b28eace9dfd9d3.nq.gz
│   ├── cc653b61a703a2c1887717b362d052e24323764c.nq.gz
│   ├── cfac2dcf09b687e361b8f443eaa212fabd9ad5d9.nq.gz
│   ├── d490ca16d5ba4f950d41e628107aa4ca335ef8fe.nq.gz
│   ├── d9fe9e9c660a5fbc2e61c89311e7fb9507d91485.nq.gz
│   ├── dddbd1e9d3bb041d4048f76ebb140ea30e5ab488.nq.gz
│   ├── de3fa5681f9cf1dd70b458c010be73f9618a6345.nq.gz
│   ├── e2835ddc4e451d1c278dda0dcca9b790cb5df06e.nq.gz
│   ├── e6a1b71a86be53ff22d5d33eeb22ea71552c3e73.nq.gz
│   ├── ea97bd4b12a690fd2c6913f7416615273b572593.nq.gz
│   ├── eecd4a7e9e3a47b8a6c4ec87aba47440e3c8fd80.nq.gz
│   ├── efe229bec47ec746af855dade6f26737b92c0a85.nq.gz
│   ├── f0cb5788849fbea15c899f25dbf408b98835c4aa.nq.gz
│   ├── f4c9ca5aae2de8ad1bfce93649e5c3c666dbb276.nq.gz
│   ├── f50395412b51a74e3d452974b00b1da7c5857feb.nq.gz
│   ├── f8b0cdd08cf60d7ed47c4cf10f4b4960bf6c18d1.nq.gz
│   └── ffe678d62411a111b23b7a4d83d26520af5b9de2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b6d727e6f0fedff6f37f5ac43c1f4949480d1160.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[zenml-io/template-e2e-batch](https://github.com/zenml-io/template-e2e-batch)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
