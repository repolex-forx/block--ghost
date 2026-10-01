# Repolex Knowledge Graph of block/ghost

RDF knowledge graph data for [block/ghost](https://github.com/block/ghost), parsed by [repolex](https://repolex.ai).

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
rlex download block/ghost
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 02914848d94d692c288e4eaac666bedcd65bcd80
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 02914848d94d692c288e4eaac666bedcd65bcd80.nq.gz
│   └── repolex
│       └── 02914848d94d692c288e4eaac666bedcd65bcd80
│           └── chunk-001.nq.gz
└── blob
    ├── 000559bef3f54ca7bb57ab38b892fd753ee83ecd.nq.gz
    ├── 002bf175bbad686788c86c4bc5ec01e1dad2f658.nq.gz
    ├── 00c145da8aa15cb4ba89681e4f6a50068cbf0ba1.nq.gz
    ├── 010ae2913f015f7ab60d8abaf7a5e09628593e30.nq.gz
    ├── 0143ed7b94e4ae20bcae8deb8fec1249b82760f4.nq.gz
    ├── 018eccb737848f523e6339c6a09ec58cee4be496.nq.gz
    ├── 019ff912a503e80cb5bbb12e05bbaad8456ba32e.nq.gz
    ├── 0218736494213b3fb56472eecc2642ff58b6d9f0.nq.gz
    ├── 03bcb1273ea153c549a06f5ffbd8809b935bd2dd.nq.gz
    ├── 04059bd075cf5a436830a552fdb52b2d27fde7b4.nq.gz
    ├── 04f36a72a241733ee76da10cc3833aadacff5d85.nq.gz
    ├── 053b7702908fdb610d4f0871823832959be1e1e9.nq.gz
    ├── 055ac76763ed966520c0b2202fee0e569c6d4a2d.nq.gz
    ├── 05db719347b27aa03d2a0ba2c2d5926580d41554.nq.gz
    ├── 06d97bf679e15e743184a0363a07254d7fcf5d69.nq.gz
    ├── 0874c58a0dee02395903b1e97eb4a25bad0f2dde.nq.gz
    ├── 08fa2537c339eac7fbdc9dc8221fe80d9abad546.nq.gz
    ├── 09d8fba21b29dd75a5cea32d24966a73d759b6c5.nq.gz
    ├── 0a1a6ab8c2b40352f19521698a430eb3083ffb66.nq.gz
    ├── 0a30eb2d6530ce39cd30f97a961aa5a99916fc5f.nq.gz
    ├── 0b42472b43dce98e5a1672a4970ff08ed23c12c3.nq.gz
    ├── 0b4620f47f4fcf64260f01d2a2573f5edc959ddc.nq.gz
    ├── 0c86503dd15ae7b21ba8fd45483fa424f17d0f5e.nq.gz
    ├── 0d743a659fcdf4a3986aec953c4b2936ec8e0549.nq.gz
    ├── 0da31aa0e2d83fef3be3548ef467cf62e262f78f.nq.gz
    ├── 0dc9df01f9dcad2384cdb6635c2d4950446f3221.nq.gz
    ├── 0e5a0737c3d5f8cdae53ed5c19176cb26ecf3721.nq.gz
    ├── 0ee7f88d782014bc3680dfd9e9f05a1b77836618.nq.gz
    ├── 0f68f22328c97adf0eaaee8d78c387ac8aee5e7c.nq.gz
    ├── 0f851074ad47c4f6c5a59512318f556190cfacd9.nq.gz
    ├── 1038448561ac50de5e21ecdb4e5558db216eae81.nq.gz
    ├── 10e825d41a883547de2348ced7d45c7bab9ce361.nq.gz
    ├── 114d1c32973ed7dc04e93b7d7eddab0a608fb9b5.nq.gz
    ├── 116226836095533a71229fdd2acefe899bc22f12.nq.gz
    ├── 1182fd23183e1f2dc4db4cce00f90ddf196d493b.nq.gz
    ├── 11a9e28851a6541c5a4ac91995acb8fceabca996.nq.gz
    ├── 11b7bd8fb3c505a1b1dba99fd1ae2021c987ff9f.nq.gz
    ├── 11b9a4bf6456612b4105782170312a752e766c0f.nq.gz
    ├── 11cf753c2f01ec05f663149e547b0891bb2884ae.nq.gz
    ├── 12f6b4d673e9e93de94e0dfb1afa028b7e959c37.nq.gz
    ├── 13213370c42cc5c83b4768ba30fcc8142c872a5b.nq.gz
    ├── 1334bfd9fb1d52a7dbd03da5f9e15bba2bbd9277.nq.gz
    ├── 13c8854ba8a9ccb09d78b26058ecdfc8bb656edb.nq.gz
    ├── 142b75cca35dc613f9353031539c2c318181f82b.nq.gz
    ├── 144bba8e141b8879147df28f4ca0f1a2466baa58.nq.gz
    ├── 1486a16a127fe5cce8d2a31e3f0420455a612b6c.nq.gz
    ├── 16bf091b7af6322333b97e98a62dade78b0e163c.nq.gz
    ├── 16e7b7d839108f2fd219d7708d54216b00996fe2.nq.gz
    ├── 181f6fd53d0f878b04a95f0f932d3a5df9e91420.nq.gz
    ├── 18310eb643b35252e6db96e775f1cbc66ee745c0.nq.gz
    ├── 18b0d58d6a849f58a10f212d6e4c3af947f7b862.nq.gz
    ├── 18b96d9c71d31876645cbf5a1a09388514646ae1.nq.gz
    ├── 1a66e69e9c77553880647bd67a1b8205654de5a9.nq.gz
    ├── 1a9771edc8f1c58ec0dea6d7561cd8c5584d67e2.nq.gz
    ├── 1b2c7cb08e8aa7260f1bae1cd33b2e4f6189b738.nq.gz
    ├── 1c1389e16a4a0481ebc1d478b0c3b401e2da9551.nq.gz
    ├── 1cd829119becc6aea7be3bb383bfd947c31396f0.nq.gz
    ├── 1ddfdc35c049adf22012390aad095e972b87f938.nq.gz
    ├── 1df2ea2e617409ce6c388ac61b756675e61fbc7c.nq.gz
    ├── 1df9a71997c430fbc02855d4ac9eab296bd8b890.nq.gz
    ├── 1e10c3956c4eb9882ae97c911acef42cff94138e.nq.gz
    ├── 1e597a7fa289d34d3805d71f0e64dcd95a26caa8.nq.gz
    ├── 1ea8addb0ea8f16e1156cb9d0df75bbf9fa7504f.nq.gz
    ├── 1f1820ce7dc058692bb2890adbd21974268f19d3.nq.gz
    ├── 20ad5b71ea78d8314992671dab067beb39fa8914.nq.gz
    ├── 20c37c26e8a943d0234d0e8f99239d9947e340bd.nq.gz
    ├── 21df4d35cf0ef164ba568e234a47deb21ff01390.nq.gz
    ├── 220e76f93058ae59187eddc8f6601ac3843afcfe.nq.gz
    ├── 2215dd16e549e30a847a21712faee032ab56fef5.nq.gz
    ├── 221eaf641fdcd0a92611f1929b379b82772a696e.nq.gz
    ├── 2266e4997b1ab1f3c57ce382526c5a36b6c70569.nq.gz
    ├── 226beb07dca370243179e9d1e7fe09da74e976ad.nq.gz
    ├── 22aaeae10fa6b5c26f30d0a8313b9a24d394a8f5.nq.gz
    ├── 22b9f78663597c24235a0e78e50f7b749ff777e5.nq.gz
    ├── 237c5b3a2985398d2b56187351e779c7dd1210c2.nq.gz
    ├── 248a7cf01e73df9e2f6c5c13b4496540fcdc1447.nq.gz
    ├── 24962d92a6be225a7419705d15783203472bcf2a.nq.gz
    ├── 24beef0f87d9f6017d746d538336aa93e47ae893.nq.gz
    ├── 252d7e88b7fe570b8aa2f5e1e04939ee78ca0745.nq.gz
    ├── 255bdeac3ddcba5cc397936e3ff73746b51252f5.nq.gz
    ├── 259e10a42c182e86875df324af4a3ce9f15c991a.nq.gz
    ├── 263fe68da79c5776714a32821be66e10afbbdaef.nq.gz
    ├── 27bcc585181188b89bc0f47eef559dcf90841073.nq.gz
    ├── 27d40700471e802730633e824210e530590e70dc.nq.gz
    ├── 27d44af27ca9edc2cd6a26e37174193542d04cff.nq.gz
    ├── 296062760eec90a6e49ccc5b00832b0fc677103b.nq.gz
    ├── 296f22eca5de73a6bf51e3317dc7bd0fbaa38a38.nq.gz
    ├── 2a748bf623c843df71f3c9ff3439affc827ecd76.nq.gz
    ├── 2b84d8c3a0954f6354b8088fca4eea2402cb219e.nq.gz
    ├── 2b9b76486e562694630384456fbc340921569982.nq.gz
    ├── 2c6b05a68b3e6698215e630e91f442c542665096.nq.gz
    ├── 2ca5bf0362d1074674bbc17a0270deb0b50f5286.nq.gz
    ├── 2cbf7691aa93573d9a140fe72abc7b7c1ef4890c.nq.gz
    ├── 2cc1f95e02deb9bd295a053cd9c12c5ff410ca0c.nq.gz
    ├── 2d01465d416e61f265c029b4b5a7225ed4c68925.nq.gz
    ├── 2d454390c276100c82847f7c47a2c52a7f3559f8.nq.gz
    ├── 2eddd7bee3364ed0239203f2919a5c9263db030d.nq.gz
    ├── 2f59c7eee3e07813066b4f8fce580e66ab86814f.nq.gz
    ├── 301ab8e710dd747a26aec0fd5a85df8649cb7701.nq.gz
    ├── 302393f75cf9c70034b301157719f99cd318df94.nq.gz
    ├── 30a4f01b012282fade36e7cf43efa7aa5e19dd02.nq.gz
    ├── 30d0d95e7abc58029a29d300c7c387a5aa14c154.nq.gz
    ├── 3129b8a062d9c6dde3036bd1b918f0676e1a84b2.nq.gz
    ├── 31a6c28b2ab88bf5990840bf8a22bac8ea721868.nq.gz
    ├── 31ea76f0fd57159af342c93d71b23b4e211a0229.nq.gz
    ├── 31fde3f74faa2739b0e1d023d0b0d1feae24ff48.nq.gz
    ├── 32a636b3b92c47b694c47bfbcc772130e5385699.nq.gz
    ├── 331d0e24eca5aa5004d7745c9897c581089da2e5.nq.gz
    ├── 340d4d6a073b60105c70e597c5319de473263802.nq.gz
    ├── 3497075c7fd30b8c09958057bc452d9310e98581.nq.gz
    ├── 34adc3e61e844cbb4f6bad14f6fbc61b1b3f019e.nq.gz
    ├── 34bfd70da996ef61c090c24e1082be3cfd7ffaac.nq.gz
    ├── 34ec40decf0610e0e682beb4c3b9688e5ad9f2fd.nq.gz
    ├── 35665f7aa7f004381abe96c77f6be699e5073910.nq.gz
    ├── 35cdb2a7bb438189543c962497cd50759e5230a4.nq.gz
    ├── 368abd37063a55f897c7ed778d0c3202d3cee21e.nq.gz
    ├── 369ea1b22f29e3f5986a5347aa817ef562759231.nq.gz
    ├── 36bf94abd9f1a05e4ecc1980fe86527a898074e5.nq.gz
    ├── 36d9a06f64aedc62eae065258df9d8f37cc73c2a.nq.gz
    ├── 37792d4adc89b365ee6a12c69ba7ed9100d97512.nq.gz
    ├── 3784f9e4679a0fa4439f4cd97e5908b2a6288764.nq.gz
    ├── 37e82944166271820403b62494ea676c9a09f0ef.nq.gz
    ├── 395b2c435cc3933adbdf718d5e5b626e2fb44ca4.nq.gz
    ├── 39c0f1fd6f592e456400a082dbfd7fec06784cc5.nq.gz
    ├── 3a4949a867126d7cd9283e0763fd5a7fe3a7460b.nq.gz
    ├── 3b6b7d6aeec5b36192d1b769280aa8d3a77c17eb.nq.gz
    ├── 3b84b31f8d7f83d5b09e40f9dacc6b59808dd52b.nq.gz
    ├── 3c1357b3525e46d837d37fbfd6677c15f5432bfc.nq.gz
    ├── 3d26f73db9c2d7b46b7e42b2694b402394291c2a.nq.gz
    ├── 3d56f1d0f276ee95fb5dec9327663332fd233563.nq.gz
    ├── 3d9bcae357b30e15d7c8d9dd3d579830e1d4cb89.nq.gz
    ├── 3db20797a6c80b17f3ce6c76f40a407b6faa1986.nq.gz
    ├── 3ea8dee843fc7e2bc6b27af2855a99a01de26906.nq.gz
    ├── 3f1190c7b11ac7aaa0906ee44e2c163e51a41f51.nq.gz
    ├── 3fc55fa22dc4e9f8c1d653d86a072ca8fe846e0e.nq.gz
    ├── 3fe0a52dd042f0f4a1048c182596dab13a357769.nq.gz
    ├── 401366d7266cbccbb2433330a1c07e855166bcad.nq.gz
    ├── 40311a7a5eff825d3eba3dd8a8ef40e15729d014.nq.gz
    ├── 404b1e4f8ff557687ec605fd5abe430eb6fc5f00.nq.gz
    ├── 410331f140989d0800a84846fa3742e37adcb9de.nq.gz
    ├── 41954d66c3cebb86cb7de5fdb2f2f8bd11e06ca3.nq.gz
    ├── 423da0cd7024f3a656cb1b8a7c36017b17386594.nq.gz
    ├── 42e237bfe504e2b6ec10231a108caa301349b8d9.nq.gz
    ├── 433c9c749a34ebe3c0309f22a6d202bc931ffc2c.nq.gz
    ├── 434f5ac7e6f3c1698bd4f617c2163aa2ffc3d344.nq.gz
    ├── 436fab88bd8199db8f8f7a0f88639ec6a99547e3.nq.gz
    ├── 4395da72e7ae4a03dee5ddd71a06045522874773.nq.gz
    ├── 448679b521ba38151a35cfc59b5bf873f88b4e15.nq.gz
    ├── 45010817406ce673ed39f19a65212a2134dd6305.nq.gz
    ├── 451384d52538a3a5472e6658532692a52b64a656.nq.gz
    ├── 456bf6e56c13842676bc218028c2b5c684117cf6.nq.gz
    ├── 45a3535dc2630e5c755b59ed145bfd0ca82cdeac.nq.gz
    ├── 45c031f6e33170788e8498a5002ff76fbf18b2e0.nq.gz
    ├── 45fd41935a46a43b4fd9c56297ad4413c0fc4a36.nq.gz
    ├── 4671348faf2bb46eeb98adbb7fe4b80c6203465e.nq.gz
    ├── 467d7ff4bc3af4069772b68b338fdd89a16676fc.nq.gz
    ├── 46acc44821516cb8ef3e454294a1671611b3c724.nq.gz
    ├── 46b3aabf768875eb728e19d19b92c83a759804ea.nq.gz
    ├── 47a95df7e038dd7a21ed8a1d4abe3514e294fe16.nq.gz
    ├── 49ee73c39bf612c9830cb11f4595f0c0e1db43a5.nq.gz
    ├── 4adecd909443ac9699558ca3bc96c1fcf2ede28a.nq.gz
    ├── 4b38c5221beadbfed048c5a25d149a6b722f0b06.nq.gz
    ├── 4bd5de83658286f717b1e1ab83fbc0e0745b3c1d.nq.gz
    ├── 4c0d487be575d0956173915a21f7d2d21f7b4bfd.nq.gz
    ├── 4c7d96af728d58f0842ed2a7d00b1e1fd3fb5312.nq.gz
    ├── 4c7e89a061f8eb0f2825a4fc2885fc84e95514e8.nq.gz
    ├── 4da6153a11c90832b9d8d2d13d1f80bcf588ad38.nq.gz
    ├── 4e034a13051a8da067d790f1f2748de4ac378a27.nq.gz
    ├── 4ecf181a0f3aa95b351a1996ce54dd9401643855.nq.gz
    ├── 4fb0783dd8b9132dd80138481b0723d046fc8451.nq.gz
    ├── 50f51918708c3cde6df9a5e0eabf3d0ee3a79805.nq.gz
    ├── 50f6c0bd3504289a5a456fb19f87ea57f1973148.nq.gz
    ├── 51aca97383e983cfb8f9f4716d4fc1177aeec933.nq.gz
    ├── 51ba7efcb9a7ebec661e8318b409fff327872511.nq.gz
    ├── 525e4715e9bceadfe1e4d6b7130ec84950994150.nq.gz
    ├── 538d25cd6f7da21a17b5c59170e240dee63ed7ab.nq.gz
    ├── 53b3012bb55ef5cda8b5aed5fb233836fef26e07.nq.gz
    ├── 53f75a7b957181b288140cdb03a93dfac76de5fb.nq.gz
    ├── 53fe3b5c1c855045419d63794a7b1db2d077acb7.nq.gz
    ├── 546e8a93d6d80faefb257d98f065f918cf723be0.nq.gz
    ├── 561d5d7354e6e6efb51b27f0c909a63c11d071f4.nq.gz
    ├── 561deca509dcbf101663640bcbac402359bf23e3.nq.gz
    ├── 58127d244e0d5a093ca0deff1ca2a74c9e486b8c.nq.gz
    ├── 581b1fbf5c09078c51e4c3439646ef9b7ca6e48c.nq.gz
    ├── 58a2ac20a5572a62714dfa7bc634eb57bcd8e030.nq.gz
    ├── 58e658a5bea1e1633092e3c5b47b75ce4cf21713.nq.gz
    ├── 58ee955271c5f49a91881efad7b6c91d84021093.nq.gz
    ├── 5903c45216782b1c1c165903953898f74be6c4bd.nq.gz
    ├── 596f7619d642cd17c0676f130a5f9e6756bad541.nq.gz
    ├── 59ea53ccbb963f6af305f53bf8354b73fcb5a9d5.nq.gz
    ├── 5a0ff2d16f7217c6e8770405da6184f91ea0d89e.nq.gz
    ├── 5a55c8c35d1ab642bef4d792c14c5aff4e822baf.nq.gz
    ├── 5ae0bf7b4b064650b425c5ccb5c09a2750a33a92.nq.gz
    ├── 5ae11a942fcf80f29cd71258c991231dda221046.nq.gz
    ├── 5b0ba24c2e3073de8e9e544fc2b10d7eeb10333e.nq.gz
    ├── 5b4278bd693f1aeac91579df432945e2f33accbf.nq.gz
    └── 5bb9bd07e501ca790887b6c80e8ee3773e43337a.nq.gz

8 directories, 200 files
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

[block/ghost](https://github.com/block/ghost)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
