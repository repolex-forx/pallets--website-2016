# Repolex Knowledge Graph of pallets/website-2016

RDF knowledge graph data for [pallets/website-2016](https://github.com/pallets/website-2016), parsed by [repolex](https://repolex.ai).

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
rlex download pallets/website-2016
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9f97f1ead3bae18fe5faf41c2031254182f16de8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9f97f1ead3bae18fe5faf41c2031254182f16de8
│           └── chunk-001.nq.gz
├── blob
│   ├── 06e9fb70c91493e5e0427f1efc038ccd553cd055.nq.gz
│   ├── 07bc90b807a0b96761e5e14b5bdc798a74365f8c.nq.gz
│   ├── 07bcc3e87be508a9dc0a841125295d159b4c9779.nq.gz
│   ├── 08e098f35871c0575e950ed90803f9941c2fcf60.nq.gz
│   ├── 09f064f5811a2a349860103e02ccb1a4bae33b2e.nq.gz
│   ├── 0a77514fd0091f5d041bea499194c777ba5d4c64.nq.gz
│   ├── 0c442fe590504c6f911731f0004c30c0d15fd4e9.nq.gz
│   ├── 0cb469bda2ae7e4fceca9ed69dac30ac63cb6837.nq.gz
│   ├── 0f82c7083c83c904d99ccc6bd02c0b6e09a23abc.nq.gz
│   ├── 134900a31f19d8aa94f3b422556bb093b21becd0.nq.gz
│   ├── 13b6e1c61393d3c5c560be0b2cada2241431b09c.nq.gz
│   ├── 13e48084e1fec8f85f12e52a970b9bcdf4079455.nq.gz
│   ├── 14bc092d9915d92a7334946ae306d61aabdf2e57.nq.gz
│   ├── 14e36184f65a3e7abbc2d079c1d7a4c37f5f3ff0.nq.gz
│   ├── 17490865c0138ef854890506040fe128e5270208.nq.gz
│   ├── 1858a365f9ee07be798e1b529d125b826c42a86d.nq.gz
│   ├── 1beaf5bcbc76bb7b3f96416dfd96e98e346d21e6.nq.gz
│   ├── 1c25e6720fe0f4fec356b9fb32a035d1f4241aaf.nq.gz
│   ├── 1ec25dbeba3c1755c1c0905a75166584f54812e0.nq.gz
│   ├── 26954adafc53fa6326f2b0f3306709918470d326.nq.gz
│   ├── 2b19709974723b22c8b56a1732958d9e003c10d9.nq.gz
│   ├── 2b3f41a1646588944502de6c207a1755891140ab.nq.gz
│   ├── 2c09c229f5ed05a5b0f3a3c89b8eeb6a6b8627a9.nq.gz
│   ├── 2d3e761d110820cadd3cfce904c3cccf934caad7.nq.gz
│   ├── 2dae8fa776581eec28bb08f7197032becb9eaa24.nq.gz
│   ├── 37678ae0e1571eab0854b783a55ff0bfee13c392.nq.gz
│   ├── 39b5d9070c3ea8163dfa8fc4a4a7e684234d89e2.nq.gz
│   ├── 3ace613967ee7fb2cdb36946a1004996a7fabc65.nq.gz
│   ├── 3b1271235698fb20e48776a07ed3d912fcd0dad1.nq.gz
│   ├── 3b37bda990eaf2cbf4a0aee4dfc638cda24d3773.nq.gz
│   ├── 4efae834f0d80b41c8c6b751e5553abe9799c203.nq.gz
│   ├── 5008ddfcf53c02e82d7eee2e57c38e5672ef89f6.nq.gz
│   ├── 5459489d33b2a772df295da85e9f9e3cdaa05e57.nq.gz
│   ├── 562eed41b47d125d7f5c64a97a0f506630086333.nq.gz
│   ├── 56b621299807ac08727f32ccf74abbe18be61425.nq.gz
│   ├── 56be89d6e2e127fae58906693fd4d0ce4b65cb33.nq.gz
│   ├── 58717e8f13d1991dbc1cdff82500b0e03bd756b0.nq.gz
│   ├── 59b0e1748ac084b491765e47bdccf3c8072a3107.nq.gz
│   ├── 5a94185e14947fd011fd29aa7c301a379b8b30f1.nq.gz
│   ├── 5b013c111db9f43aba4555e169ac59d1c1ad5414.nq.gz
│   ├── 5c0dbf35b3f76be30dd1981268a328d9722f12fb.nq.gz
│   ├── 5c622096e15acbd0fd48f120e1c078fdc32a1f5a.nq.gz
│   ├── 5ca325b5b26453e25f244e5f0c1b1e8dece983de.nq.gz
│   ├── 5d49dd78539c62f6d21a3fa049aaea7095bcecc8.nq.gz
│   ├── 5d94325f308df91c6d7dbfb00805b47c0df73c6f.nq.gz
│   ├── 5dd9da6ec9db4dbb3362a0103302f93bb4a68d91.nq.gz
│   ├── 5e4bdcfb1aa2fcecae946c67169336644dee47d1.nq.gz
│   ├── 5fdc360bba189e3328a145e01c9378c8e44b18fd.nq.gz
│   ├── 66b4a8bc0e914c7965624241fdfae7d618c88ba9.nq.gz
│   ├── 6b11a448a8f107324d863d709ef4ac8c51ebef83.nq.gz
│   ├── 7556b82e63e40a9366a66c71dcbafc3194e03f36.nq.gz
│   ├── 770329a79f24d8c14d1f6ee10e3624678b2ce4a4.nq.gz
│   ├── 770bdf72b68e5bd84ce9ec36ba3fddf118e07085.nq.gz
│   ├── 7a4ac63bac2620249852d928dbca7d15dd0dd632.nq.gz
│   ├── 7d1162330ab3a20934204da4cb37ba85e507837b.nq.gz
│   ├── 7d9e6c2668e8342a41a41f82a2c445b7b7cad119.nq.gz
│   ├── 7dc196132b324d6bd038dc342ea0074aa2e2dde1.nq.gz
│   ├── 7f118d83d12432acf025efbe40c1209ee244b307.nq.gz
│   ├── 813cbc2aa90af77c658b2c5ce36889f3a6b436e8.nq.gz
│   ├── 836d9dc104cfdb216fe13ed5406b9e106aa07c0d.nq.gz
│   ├── 83795c405a8a1f911785b295792266b8f95e2fd5.nq.gz
│   ├── 83dd6b5e652315cb5d2292cd314bb8dc79ca6c7b.nq.gz
│   ├── 86f69e58d7055fd28aee1ff06c3733a242593630.nq.gz
│   ├── 9049db938a94384ada7df15958330c238314068d.nq.gz
│   ├── 963075a200790907ddb25e164857f7334c614d21.nq.gz
│   ├── 9711f998c9101902b4fd2a9ff2807f87dcf76094.nq.gz
│   ├── 97880a1b8522c2efc2913e33418b8f36be3f9a90.nq.gz
│   ├── 9aae0d72ccb3a4feaee061e0b142de46ea1b0c87.nq.gz
│   ├── 9cba1ecb274255b9ca03e9e3d4f3fa040cc183d5.nq.gz
│   ├── 9edb4d5058f7249d011d370522f140798e10736a.nq.gz
│   ├── a40af60e01bcf8a4d829127158becbfb4c55c3b2.nq.gz
│   ├── a7ffceee621f5726682143ee9261c44265c36525.nq.gz
│   ├── aada9bdc774f48e141d417fa4494f70405b19137.nq.gz
│   ├── ace805f5c4244cbd9dfc8259e8e6646e09e63a1b.nq.gz
│   ├── ad4e6f7e568bfb6f847d5d52e2db182073975400.nq.gz
│   ├── ada729a2e3f99a156133504deb8f343ade920ca5.nq.gz
│   ├── b1b9d02042e9c558a2763aa329c5419fbaa32b57.nq.gz
│   ├── b4a575c1fed12f2eed7f4872994cf143df30d03f.nq.gz
│   ├── b5bb3f41d4321a061ff35379f11f78c9f0b6a69b.nq.gz
│   ├── b7952e8d2512965bbed10a55f8897b31840d492e.nq.gz
│   ├── b89ac8c67b87883f7ffecc13b86e8411d4e44746.nq.gz
│   ├── ba2df0c14196486b7246e8c810a6f9f7a7181415.nq.gz
│   ├── bb380c798ab4045a6cb15a2c8a64666eecdc62ee.nq.gz
│   ├── bc2362fba596ba81a0604948f8539ea32bb13cde.nq.gz
│   ├── be7d67ecace9fb6da01ab7476473378906eb9f1f.nq.gz
│   ├── c1b3f7591eb801b642200e06ce2215cb71c8a87b.nq.gz
│   ├── c50eabd1a76399961a3412b5ede7b98b7d3f9a4b.nq.gz
│   ├── c686cafc5d9d8cae9b7d6d67e170858a09c40b9f.nq.gz
│   ├── ca49a6671747affe5dd322a2464ecc15e312c29e.nq.gz
│   ├── cb264cf9969913b886f8562a8abc4e3f5352b437.nq.gz
│   ├── cc1923a40b1a5e8c7fbdb8f9f6c6bbe26c35604b.nq.gz
│   ├── cfc83fd5950f1dcb093d40f97612b6233441c14f.nq.gz
│   ├── d7946509b565663ffe838a8c5b4e680fc6fc5e52.nq.gz
│   ├── d8b320aa5acbca65a78ef233b79df47595fa773e.nq.gz
│   ├── da14aa952cfb98835bb37636343c746e990af366.nq.gz
│   ├── dcddfe824c483415bba19a16899bb2705b968d5c.nq.gz
│   ├── de42242500e8ae6be7a7b6c7357a378f466642fa.nq.gz
│   ├── e013b40925b68b6dcf6f28341cfa4502ce77a1d2.nq.gz
│   ├── e097b6ca1f39ea5cc02eaa7371e9d077b9e8daa3.nq.gz
│   ├── e2d99b9a58f98926f1218a44acf443124cb090f9.nq.gz
│   ├── e689fa1dc65cbc9eebd1c3f0e71525a4d66f62f9.nq.gz
│   ├── ecde2148039bd91e98728ed1df8157ad35a011e4.nq.gz
│   ├── f0a8676624d2de7ea5542a147ae695c6e6e764bb.nq.gz
│   ├── f89dd2eb0dfe2367f4558dc28ef44567505987aa.nq.gz
│   ├── f970fa6c999e28f6a28a34cdc6fcc632b4c6319e.nq.gz
│   ├── fbfc881afbb8354922a1e6f06baa9de29f260afa.nq.gz
│   ├── fd18f78bee2eeaaa4173cb9efb07ed4b878b61ab.nq.gz
│   └── fd72377d4598465f1542dbf8b9be579bd4a74231.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9f97f1ead3bae18fe5faf41c2031254182f16de8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 116 files
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

[pallets/website-2016](https://github.com/pallets/website-2016)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
