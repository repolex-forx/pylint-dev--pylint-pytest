# Repolex Knowledge Graph of pylint-dev/pylint-pytest

RDF knowledge graph data for [pylint-dev/pylint-pytest](https://github.com/pylint-dev/pylint-pytest), parsed by [repolex](https://repolex.ai).

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
rlex download pylint-dev/pylint-pytest
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fefad1b9ac04728d72f395de55bb3aa2bbcdfba6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fefad1b9ac04728d72f395de55bb3aa2bbcdfba6
│           └── chunk-001.nq.gz
├── blob
│   ├── 032863cc850d2eeee48848a6a26cf1742b0dd0ea.nq.gz
│   ├── 0ea4731d12f224d20490428a21a31030e3b4f3d4.nq.gz
│   ├── 15e652e5491b3e27dbf6830ac24f0cb06f8ca496.nq.gz
│   ├── 16631bcafacea6a35c6e76d70fcb32db54a34024.nq.gz
│   ├── 19d1d2c3bae945370e421e810e85289f8b1be69c.nq.gz
│   ├── 1ec1f5c1cdaa9acc95267202ba6b0537c2614a10.nq.gz
│   ├── 23cbe8235e46428b62bb8c613609a57699d67834.nq.gz
│   ├── 28f55315085a70256bb9c31daa6f3d89597f52e0.nq.gz
│   ├── 2b22469919fba334c960b8ff0bda10c50542129a.nq.gz
│   ├── 49add62cc382449727346e884d76db576c395cd1.nq.gz
│   ├── 49e9d3222c2aabca2b860be4f0898bbdcf02e2fc.nq.gz
│   ├── 4bb86455b07334d985cf0a3875a78ddeec65083d.nq.gz
│   ├── 4fce7721367e263cc341ddf8e1212a42d54ede4b.nq.gz
│   ├── 53f0592eaf781f8c6552458f30bfbe3fd5d0372d.nq.gz
│   ├── 5557f246538e12f4ceb986f42d7685fc9594df9a.nq.gz
│   ├── 564f429c0da8e22905f948a2f322be1939fd2568.nq.gz
│   ├── 56694cc03cd3c387b101c53b354939bfa5681296.nq.gz
│   ├── 5683e61740291b022ebd2ac14d9c9d8b214164d3.nq.gz
│   ├── 568e7e861cd278c67ca0f82f8d3e39355e6c89d7.nq.gz
│   ├── 573618309c13ccfe6af2997afa69026bc535017d.nq.gz
│   ├── 58674d24f841ba0d006f753541aeeda176ea118d.nq.gz
│   ├── 595601d4ff7864609496f2089b93aead09190f9b.nq.gz
│   ├── 5c51cd5a4755d7761d68b7800c5d0852c9e52a87.nq.gz
│   ├── 60d3841554b0f069b29eb2bb2a12697cf6082677.nq.gz
│   ├── 64e3e7ccc186f42696371735aa7f5a34bbd9e463.nq.gz
│   ├── 652d908d11e10d7e4de88b09372268f0de6de38a.nq.gz
│   ├── 682475157ac151e1bb4b56f97f638b6a82366339.nq.gz
│   ├── 76fe6b150df96a24a7e50a287682e0c309d18b77.nq.gz
│   ├── 7873b2ff4df7edd625751c50d00c28351e888562.nq.gz
│   ├── 79c54fbadc15eca26c6395ec176c1770a1d17745.nq.gz
│   ├── 7a01c4fa6e0d53bfc035846e233ab80cc8b9d4a9.nq.gz
│   ├── 7c4078b20e77d8078dbe6af3ce7482d967822953.nq.gz
│   ├── 828c27ad68d554236336afc17b6c9c2760c5dc9b.nq.gz
│   ├── 82aaea4f91c783928fa69d48ba2909c35455d66f.nq.gz
│   ├── 82b1864a87b3a384fd4a9a0172f1edb30241b242.nq.gz
│   ├── 8708479a675a627c1668be95489f71bdbaebd6fe.nq.gz
│   ├── 89f514e6d955cf35d0ba67f1035e054a2a991360.nq.gz
│   ├── 8b5b9d6fbd268293d90906855bf1d3e9a22f08af.nq.gz
│   ├── 90f0404f9580715a299333d3e3c2c0f53ae1fa33.nq.gz
│   ├── 93a2da3223e163b04150b2deb0b8af1ddabb3ef1.nq.gz
│   ├── 93b0afcd9316b7e93c246e6eda9a5d7d57b5cf6f.nq.gz
│   ├── 95417b5aac481b17fb37c50d3b55cb65082118cf.nq.gz
│   ├── 95438af0d194b74239e93606c7b3a58066501c8b.nq.gz
│   ├── 95fa0b6f418cb0a285aae51c822a9ce0ddfa8e53.nq.gz
│   ├── 96e9ed1ab01709edb795a18cbd6db7884772f38c.nq.gz
│   ├── 985a51992728ad6059656d9fa9d13f834256e901.nq.gz
│   ├── 9ad5b8f82fca61f89597ccc8fab505478e2c9243.nq.gz
│   ├── 9d853bcb1461156274dc5b781b5e05c71063390e.nq.gz
│   ├── 9e869164de801d143bec3fc28e3288d9049b73d9.nq.gz
│   ├── a0dbe55b7c611c69708fe3ead6d2d2f4ed4fcdcb.nq.gz
│   ├── a59d06e07eab023d56ce56ccb8eebd856ed9cf82.nq.gz
│   ├── aef2fe3120f2c971868c4ca99d8f5dbfdb390e48.nq.gz
│   ├── aef5a323d4355ac71de085f32c594b67958cfb77.nq.gz
│   ├── b044569da5958bf500f226fb8abd2c6926bfb728.nq.gz
│   ├── b2a4a1808fc201d3148f5832cc75ca4cb2ae3b0a.nq.gz
│   ├── b67b7f0b1b4e64b282a982c1b44054c15de25e57.nq.gz
│   ├── b8344587c551a67678c79ece13c3ca0bdf513791.nq.gz
│   ├── be6dbfbdd64ed5f9b980edcebb01c4544a096ce6.nq.gz
│   ├── c08b6d4fc403dccf89ea5f75e67d6db701ec8751.nq.gz
│   ├── c1d7d36bc6aca1b5a820b15a78d32922c4751f13.nq.gz
│   ├── c2f823b9b0bee964eb38c92003699d81454dc124.nq.gz
│   ├── c96894025c9795a1d06d0b6d06495e72d216156d.nq.gz
│   ├── cbd2698ff0e7bc62c30be5000d8402385142ea52.nq.gz
│   ├── cc32ed6534c6b6e6382b06f9d1d5b03e6a29a9cd.nq.gz
│   ├── cd1cb879b7c938a6393aaab97878234451ca40f2.nq.gz
│   ├── cf3e30e9c68826ae8b035c5d46867f0a7d34df3d.nq.gz
│   ├── d44d1e14a291245b8211c8a64c2c9ab870def8e8.nq.gz
│   ├── d9260949573fd6dedf5d1b558a3b50a2eec7d3f5.nq.gz
│   ├── daecf905cd0b04091cbf34f1103f503cb2e73941.nq.gz
│   ├── dc8cf3a8639333b8c528925bf37cb97611e36192.nq.gz
│   ├── dcf91508c698ae453c21b86e9a78efbc7b8535b3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e88c63536f5c985787c6817869f21e2c56675ccf.nq.gz
│   ├── ead1bf3fcfa1da12fc5e02923de358350341e547.nq.gz
│   ├── f1559f66688d3fc4375a77e19efe042044c6f3a2.nq.gz
│   ├── f4344c601b5725bd2417e5a6f1486dd102fed0e2.nq.gz
│   ├── f6fecc496a5ec348c54ccb667d6792980268f14e.nq.gz
│   ├── f9a7a41b6a148753430b55ffab60acd9f2839392.nq.gz
│   ├── f9b179a723dd678344b886bb555cc89c04c68b4a.nq.gz
│   └── fad41859a32ed1e819499433f99843c78e5357b0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fefad1b9ac04728d72f395de55bb3aa2bbcdfba6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[pylint-dev/pylint-pytest](https://github.com/pylint-dev/pylint-pytest)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
