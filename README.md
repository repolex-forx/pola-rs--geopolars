# Repolex Knowledge Graph of pola-rs/geopolars

RDF knowledge graph data for [pola-rs/geopolars](https://github.com/pola-rs/geopolars), parsed by [repolex](https://repolex.ai).

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
rlex download pola-rs/geopolars
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eebad68a3c0175dd496f66b40765a7ab9eb1122f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eebad68a3c0175dd496f66b40765a7ab9eb1122f
│           └── chunk-001.nq.gz
├── blob
│   ├── 00110e7b764c7edbc5ae5b8daf7ec65bcb49c63d.nq.gz
│   ├── 05ad8c451285809dc750480de6264c08573b4364.nq.gz
│   ├── 0972ad20a66685d4811aee3f2ffac6602114c8fa.nq.gz
│   ├── 0c7d5f5f5d7616cda050ab6139fbb6893a43288a.nq.gz
│   ├── 0e77cf84587d0b06af377402cd63c4a0a9ac886e.nq.gz
│   ├── 1028ddfcbc2c02cf05fc42c785103244126f5d91.nq.gz
│   ├── 10a86c7b50155b35caf789c947cc0b4c2e815077.nq.gz
│   ├── 13433cac744472a6c19e3a1a40ca18ac828c524e.nq.gz
│   ├── 1c6fca062538fc432a5e6cc5ee0294afa1b8d693.nq.gz
│   ├── 20cf4619dbcb8c6a0164d8dc99cdf86af653e4c0.nq.gz
│   ├── 2595d75e385c957df5f275297c16abe56000b489.nq.gz
│   ├── 28b714f01b33c6cdfc47782dd2c4feac02ed2a79.nq.gz
│   ├── 29912a1be378d99e0cf76bae4ab4e8f36b3f9af7.nq.gz
│   ├── 2ab8c65b4d23160bdfb45bb6cb5bc6c26bb0fc6c.nq.gz
│   ├── 2ae56756597312fb87b0413b60f30d02d6d6024d.nq.gz
│   ├── 2c6a382a8918b987bca71b9beca66f4153908382.nq.gz
│   ├── 2fb85049b6f689023494d38c77d3e226ceabe728.nq.gz
│   ├── 34619aaac79a0a45cee7bc2c5e1e5a7a889d2f65.nq.gz
│   ├── 350efa0dce729352b691052976d615cf3b3c34bc.nq.gz
│   ├── 3912cfd42212d6db451ff0bfc0fa29ee02ab3cac.nq.gz
│   ├── 39d0ea314202c0c6b44469124db9d5a795e3e6c3.nq.gz
│   ├── 3a82328d0b8fbab81a1a7028dbb3a3e46ff23f12.nq.gz
│   ├── 3e902baf1613f6d7a7d82b7b3d285ab2824fe67f.nq.gz
│   ├── 402c4d48d37a1bb724c1a783c9a18e6c612f9897.nq.gz
│   ├── 4635e79682568065a708377b3bd4715a8e21bc86.nq.gz
│   ├── 471d314aada4ef957a02fdab8d9d450ecede50c3.nq.gz
│   ├── 48032726a2a49276bbfa84c114ba564c883afd58.nq.gz
│   ├── 4941d6960476f05a00480eb0c7163f47fba54e3b.nq.gz
│   ├── 4b3b68bff6efc6b6ef663d9e6458bc5f9b086721.nq.gz
│   ├── 4ba649410cfcafae09876031d73379be180d6027.nq.gz
│   ├── 4e6b19cba8b1327f92c808f77cede309bbbb0790.nq.gz
│   ├── 527613f1f63788d77db2b8a1eeeda712a0e61506.nq.gz
│   ├── 5fcef8cd49df8eb5fd0d0965d7e6bfb7d2916bb3.nq.gz
│   ├── 609bc093ddc0d8422b6f1aa7bc9ade6a0a93f6cd.nq.gz
│   ├── 633317202a7f7f7146f7a549811432eb04cc7094.nq.gz
│   ├── 671757cf1a44b2fc507dbb71f9e060942f54f9d4.nq.gz
│   ├── 68eeb2eed02a9c79829ed594de756196a8422bcb.nq.gz
│   ├── 69005431e979c7625b384c0b9d1b55dd7731318a.nq.gz
│   ├── 6c603532758c55c37c77c4b65bda9b7ad286a9cc.nq.gz
│   ├── 6f1a2c8fb6b0b107d27334df8d4a5e5f822ccedc.nq.gz
│   ├── 6f1ab4244ba75c87432b545716ae9db765158bc7.nq.gz
│   ├── 7402be14cd0e3fac2cf2017323ea9f0846dcd1b9.nq.gz
│   ├── 7804826f8a856d82d6132d646208e637a917e508.nq.gz
│   ├── 7ac05d6870485254ce6b47f34594e9bd89d187cc.nq.gz
│   ├── 828ea47198327a6772880dd5faf9265a15df700c.nq.gz
│   ├── 87e38ea6690b3c4d730cb2841c150e1efccda054.nq.gz
│   ├── 8d53615e3d1733798005fbd8faa46f3da08f2ccd.nq.gz
│   ├── 8e0554f5e205652908d4e02b3ea56902d6f1b440.nq.gz
│   ├── 90abcd6a92614149ba46063b89c8ea3170bbeca3.nq.gz
│   ├── 90bfd83a45845e25033bc4dbb2c5588ab619090a.nq.gz
│   ├── 911d6cf1568cfd060a18b18fc37774152ab1a49e.nq.gz
│   ├── 98b037e52d332e8c1679c5c679af23008a91cded.nq.gz
│   ├── 9c66270114e97d357aa26adb6a05b319580caacc.nq.gz
│   ├── 9d476868755cdc41a228d26abd3b215be5f220eb.nq.gz
│   ├── 9e007425e75486b32d879a052b417cc2298f50bf.nq.gz
│   ├── a5f899005244e8818257935880e3618691ba4f85.nq.gz
│   ├── a7b720801bad9e0e5ef9eee6ae6d6979c6245811.nq.gz
│   ├── aa66e5aaff38652197379de823ec8b2ddc0332fa.nq.gz
│   ├── ab784ec9bc2fe4236594c52686b92e42d01e3832.nq.gz
│   ├── ad97b25306ea69184a8b4ed3f75bdb927d8fafe2.nq.gz
│   ├── af428f06815ee32a8de55b541ba75ba5531a621b.nq.gz
│   ├── b2f8c5f5edea6c9c27630de77ca3147022957a98.nq.gz
│   ├── b6510f036bd8111d47292f87d790301efdf507f0.nq.gz
│   ├── b72b2420aa23b58e4b4ed39642b37dcb148dbbee.nq.gz
│   ├── bc4eff8138891788adf6e2badcbcfaa14542c9e6.nq.gz
│   ├── bdb91f445f55764633322b459de58104f888065a.nq.gz
│   ├── d09a2ad1715a5209d747bb74f66c71af21d655d1.nq.gz
│   ├── d0ccc0254440e8fc4077cb6886eec00f394c0494.nq.gz
│   ├── d2850b21e4e70391425090cd9c049303a70224eb.nq.gz
│   ├── d2d0f8851b17604d914e6870929ef104c03cf25d.nq.gz
│   ├── d532409aee5eb14f6609d42393f260343b302fb6.nq.gz
│   ├── d7528f766eae9d9cf503233c3b0e5201e516941a.nq.gz
│   ├── db3a35cf45c111cb3d8258ef797ebacc7ad6e8ae.nq.gz
│   ├── dc4b81b72b41debd995e218167ad46bbedeb1f0c.nq.gz
│   ├── dc7feb11d088aa4d83a9eaba969f3fa4d1c3cfa5.nq.gz
│   ├── de89d3f2cd29a85464cf90db7195033c3f3d04b6.nq.gz
│   ├── e3db4226b5195ef0469e52959965bcdb3cb13666.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e954524eaaa10b9664225eb9d5eb2d176b66c764.nq.gz
│   ├── f2cc28f7249a2dc95b1b04d95578454e77d131a9.nq.gz
│   └── fb3986ba1760aa45a32f792d8c93442bfd01d483.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eebad68a3c0175dd496f66b40765a7ab9eb1122f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 89 files
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

[pola-rs/geopolars](https://github.com/pola-rs/geopolars)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
