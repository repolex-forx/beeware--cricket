# Repolex Knowledge Graph of beeware/cricket

RDF knowledge graph data for [beeware/cricket](https://github.com/beeware/cricket), parsed by [repolex](https://repolex.ai).

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
rlex download beeware/cricket
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0aa8e6a7fff2d44f8cf774ca1945cbdbb4ff529d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0aa8e6a7fff2d44f8cf774ca1945cbdbb4ff529d
│           └── chunk-001.nq.gz
├── blob
│   ├── 007c26ff1b8fd405e695cf10d046e9726f57b68a.nq.gz
│   ├── 0230f2375b83d19dc3fc189dba574f4268ac29c0.nq.gz
│   ├── 04446f706861f979b37b0482f8d3653d108b10d1.nq.gz
│   ├── 0f7d6598cffc6c015ff78347018df55414cfe8ed.nq.gz
│   ├── 110e5d6c9caabd1259cc2eada33056522f791e81.nq.gz
│   ├── 193ea31d9cbf6db03905dae6f285167e7b44feb5.nq.gz
│   ├── 19f3b6dec4572804ca902ce1b3130b9c5f16ecbc.nq.gz
│   ├── 1ac5241b042cc4f71a4fc400fb1e412ad1dfbed4.nq.gz
│   ├── 1f07ef01b89d6865bc18f2a3f57bbd4762080a62.nq.gz
│   ├── 22691a53c42b62185aa97a8364c9ec58a4492ed2.nq.gz
│   ├── 24ebff824458b4e67f955f4912d1c431df9cdefd.nq.gz
│   ├── 26472c2f3703afc9a5a9cd95533fffc1f0397422.nq.gz
│   ├── 28c063ac5d0773ba473a4822e8a4542318d39216.nq.gz
│   ├── 2dab7783f4c2fc4682957b08d8cc909a733974c2.nq.gz
│   ├── 348124ed35aa65083de139812005288c79cb6873.nq.gz
│   ├── 365deb489a15504563d10bbc12bbf2c8dc5124a2.nq.gz
│   ├── 36d8b774364999c7ad29d3f92a69105664ae174b.nq.gz
│   ├── 38ffdc7d9eebfc65438fb7d4448bf172dc6d49cd.nq.gz
│   ├── 3a51c9ddeb447217710b9e2403f3be1d502e0c92.nq.gz
│   ├── 3c178d36b49c29b7ed456dd1280e1dbd2c122a62.nq.gz
│   ├── 3ca9898a83b7b428a801a7f3b9dd802c423ea981.nq.gz
│   ├── 4284aa3d6394421eed453373c512ab3ee74fdbb6.nq.gz
│   ├── 43bdffca5254b3faf3d4255c9859b9274caad694.nq.gz
│   ├── 4557903af972a60ae2fe16a12db5ea5000643b92.nq.gz
│   ├── 46d432a5250ecff607f37a94a802c0230d5177eb.nq.gz
│   ├── 47f832f87cd030d2d7391da270ed738aafd41527.nq.gz
│   ├── 48b5fa365b10a674d9e51e7e79cbce96ef159ee2.nq.gz
│   ├── 4a09c81e23ca735b7d235c71f9ed7feca8081af3.nq.gz
│   ├── 4a9b05514514e9e8c271890d8bd2fd592aed75a1.nq.gz
│   ├── 50101972e70ca4779206a5b6328903df47cb1423.nq.gz
│   ├── 5135968888acb5f5754e50e48cd3ede3c73d6dd7.nq.gz
│   ├── 53af714f034fcd4f419419d08387819d6313a5f7.nq.gz
│   ├── 558a9303111f36c9746c85e2cc6faa3e96892649.nq.gz
│   ├── 5618a59b652d5b55b4bd19c9d3c1d2e7396ceb29.nq.gz
│   ├── 56eca7a708084759ed3ca222471a1b2012d34903.nq.gz
│   ├── 56ffce702a88e3eed868549d89f29c1fb22ee34c.nq.gz
│   ├── 5aff7df452064782c507caa41012a97044598b25.nq.gz
│   ├── 63391b9005028479f9da4492ce41beb62e65b970.nq.gz
│   ├── 64783cdfb8569065e96971f93b1845e74d8a88cc.nq.gz
│   ├── 69c232c0dbd99ac35c4d9f3161b5823bad2dc569.nq.gz
│   ├── 6b1dc3d9af23dd2a6e778d43c98008a7fd74099a.nq.gz
│   ├── 6d26605c18828a2d6a4deb2951bb0f26f82d3727.nq.gz
│   ├── 70a3c6f65ef57ffa78673114c6fa7ae7e6ee3b1c.nq.gz
│   ├── 75086fcbd8f78a84529d7cd903df98ab74275864.nq.gz
│   ├── 783bd58e505cd3658576f52dcd654027e6a824e0.nq.gz
│   ├── 7f39387542e42f431ec87f1873034c009e844620.nq.gz
│   ├── 8050b8a92bbaa4c01c0c822cd29c1a9e3fef2f41.nq.gz
│   ├── 82311fe644c264acafe77cc08ca1c582870ef47c.nq.gz
│   ├── 8242624ce44c4ca38f7ccb2bbdade39814a90ed6.nq.gz
│   ├── 896dd58a2870e9aa62a27042babc8fb2380cd32a.nq.gz
│   ├── 89fddd784ec6bd3692f77918f087f47fde424a56.nq.gz
│   ├── 902d96326c5e6a9506e784aa4b9181ec144f6283.nq.gz
│   ├── 92ebd8843d92ba75266a9029f0715cecd89f190f.nq.gz
│   ├── 93a18465366f298f2032ea8c44b433d73266f7a9.nq.gz
│   ├── 96d7c7de08b2d3b18df9b27cc036e6f248b429f0.nq.gz
│   ├── 989625e73ab342c17cedce8b678e8849c7add59e.nq.gz
│   ├── 9977fabd76f233f09b64b38803abbe525ac54ac5.nq.gz
│   ├── 9b0be600b92993c3f70856a174865691fd31de5a.nq.gz
│   ├── 9ba988e206065ddfa0fa91cd02fe9596f6c55471.nq.gz
│   ├── 9d46eb3e3d19e4d974938eca180f5efbeda43920.nq.gz
│   ├── 9d49f4e161903564c9652c52ce66d3f2675c9aaf.nq.gz
│   ├── 9ffae6fe5714292f65978fe3d3c7fcdfccbc417b.nq.gz
│   ├── a01a96baeccccdb1130a28eed84f17b5cf823dad.nq.gz
│   ├── a0d1885cf2c88911db4dd81bb8011b123ec20b20.nq.gz
│   ├── a1e7ff8dc490f0ab166c66532ef0d808eadb647c.nq.gz
│   ├── ae66283452861a1cf113a2c6ebe0cb117c333d73.nq.gz
│   ├── ae96a20bd09722940b2e76720a0be7d085c46fb2.nq.gz
│   ├── af1faf5616571cf3d194bc95c0dfd7f5c9d4335f.nq.gz
│   ├── b30590a113b9ad74faac4325f142432ed1ee59bb.nq.gz
│   ├── b3e7829df39980dee8f1212f75bad705374e9481.nq.gz
│   ├── b5af3acbee0dae96afea08c6202b14e63f472ed1.nq.gz
│   ├── b5d2efa96eef895533f36d9de9d957fdcf364f00.nq.gz
│   ├── b7282e997ad151385296ab3f107b56879052c21e.nq.gz
│   ├── b834affdddcf5014398ca9c16aafe3ea7f2d0422.nq.gz
│   ├── b9bcff9ce67bcb72d9851a1e080f12c3c1d9a710.nq.gz
│   ├── b9fb4e8523668f48328e0203531666689f3d387a.nq.gz
│   ├── ba9f9e6880e5afdffbf8ec03471646e84e240395.nq.gz
│   ├── bd26d83508060c0a53a0ce1221058c001aecb3f4.nq.gz
│   ├── bd91c99649c0399ba610e43b2014e8e26dc00694.nq.gz
│   ├── c052cedac8f1b6a59aaf422ac68412ec27c09f4d.nq.gz
│   ├── c4d88e8173e484996f9c1fe716bd0fb7e4c8a73b.nq.gz
│   ├── c55b65b2dd212be06049a10e292f53e7426d5265.nq.gz
│   ├── c75df40385b52de338d8f832d0202ce13591f6b5.nq.gz
│   ├── ca57d466761b919fbd3918e377a195c3c6ba5561.nq.gz
│   ├── cb58673a09d3ea3a4d7728561b5daa8d176d908d.nq.gz
│   ├── cf4f23e3a1c445493f24cd7d4fb9a769466f4d6e.nq.gz
│   ├── cfc01492196843984d9c50d5f14df2467f5c17b7.nq.gz
│   ├── d2009be924edd5fa62440dce993788d273610990.nq.gz
│   ├── d47f63a6912f6ed4d935d5959693f751b45e0914.nq.gz
│   ├── d4eee58e3ebea70f9ee234dddbef716e349ccf83.nq.gz
│   ├── d515149046a7ff6201036c2985a7759d2a850a62.nq.gz
│   ├── db8434515334ada4da8dc7848d06b37577577bd6.nq.gz
│   ├── dcf508835604096e3e7252fd97210f663b87ceb3.nq.gz
│   ├── df1f7d5c7ddaaad736c6f02e5c302fc40463e9a3.nq.gz
│   ├── df21be27523499900a7d8789eb6fc69cce8c9c62.nq.gz
│   ├── e266108cc5475cc2e33a767df2c41700911fc9e6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e828b1f1a19365a2dfff348555c2c69fb5274476.nq.gz
│   ├── ea3615e59ee939cf8f0fd3f17bb035ccc5e271d3.nq.gz
│   ├── eb3b5c611c2dc1028dcd660e329f9b5c58458a81.nq.gz
│   ├── ed00a98b3575ed23b729dc7b8ad5780492f95eac.nq.gz
│   ├── f3230bb316025b3ff2880053353ef85fee98cdd5.nq.gz
│   ├── f37e86793df0e3c2d0b1fe7ec1a25ca7d81a2004.nq.gz
│   ├── fa0af6ef369035b2f6b71248c4d644e029b5e7a1.nq.gz
│   ├── fc45b3494fd783c156bc6a21499e519b25fd120f.nq.gz
│   ├── fd8851afcca372ccdebb64771be1a50f559349f7.nq.gz
│   └── fff3256061847fee8241cdb4d5d5f22e84adbcc9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0aa8e6a7fff2d44f8cf774ca1945cbdbb4ff529d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 115 files
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

[beeware/cricket](https://github.com/beeware/cricket)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
