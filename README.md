# Repolex Knowledge Graph of MagicStack/uvloop

RDF knowledge graph data for [MagicStack/uvloop](https://github.com/MagicStack/uvloop), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download MagicStack/uvloop
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 74f4c96d3fc5281b1820491d2568de771ea7851b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 74f4c96d3fc5281b1820491d2568de771ea7851b.nq.gz
│   └── repolex
│       └── 74f4c96d3fc5281b1820491d2568de771ea7851b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0043c666323cb3d845c96436319df7def64fa588.nq.gz
│   ├── 01e39ae12e24acfabfc6631acbbef55e32c473ce.nq.gz
│   ├── 02605a08e0d8cdcd56b6a42524e47996f7468450.nq.gz
│   ├── 03733756d0b5161738019c705b6d903342d9424a.nq.gz
│   ├── 0447c0adf58a45c19402f697f3569ece0b8e9096.nq.gz
│   ├── 07b0d05bef5840c65518b32080fbd7fcca509261.nq.gz
│   ├── 0c408c9e78d316ad9e7dbd75c26d3dbbf5b8259e.nq.gz
│   ├── 0d670e39689e2e7c5918571c201d8556fadbaad2.nq.gz
│   ├── 10a1ad602e8307e655aa9247c4d2eef045bbe6b2.nq.gz
│   ├── 1683952f2318a6116cf4eb3d81fb6970ee7cb46b.nq.gz
│   ├── 1a61c4e91bdd30a8cc238adca2c3d7c158afbfe0.nq.gz
│   ├── 1f7127a4b025aa23323193f06cf1773a560e3810.nq.gz
│   ├── 2071b36f58625fb8d3b16760c5053748819083c2.nq.gz
│   ├── 24cb795cc0c2d2f12cf1109b8201d340c8179e39.nq.gz
│   ├── 28b30794799249c3af2d3274fbbac95b07ae8f4e.nq.gz
│   ├── 28fd17369de3d0490b077c1dd2f4535f61511486.nq.gz
│   ├── 2914b42e38ca2240a48fe64ac384f1eb5e065a56.nq.gz
│   ├── 2c96458b1c897fd9a88211b683dd44d2d329ec09.nq.gz
│   ├── 2ccf9cae31016b266b5a8a656b3aea0c3e571fc9.nq.gz
│   ├── 2ed1f272d4c9a06976f53c4ded923a4caaec96c1.nq.gz
│   ├── 30b7646af68c8ee5bfd877b065ff19a85c7816bd.nq.gz
│   ├── 32d94ae83a6f824f6563ecea1dc97777a03adf8e.nq.gz
│   ├── 367fedd1811b0978cd3431b89bbb0ab922166e48.nq.gz
│   ├── 370ec6ff4ee48c77f84288c23c0c2e76decadf0d.nq.gz
│   ├── 3a32428506f73dc54c77088d50e602aa088596ce.nq.gz
│   ├── 3b8ea62a78ccdbc931f332baf36ea5c9a24024be.nq.gz
│   ├── 3da10f00cf56ee227c7cda6212f73ca0acd34a1b.nq.gz
│   ├── 3ef7a028e292cc76f50423499d062f7386a87f0b.nq.gz
│   ├── 40fd0230d7010bf08f207bf92874e3166d10f647.nq.gz
│   ├── 42bb76447ce9b36506a7f494ce6b0825503d389a.nq.gz
│   ├── 4b95ed6e9deb41bf3f014b06af673f1a18a55557.nq.gz
│   ├── 510b14988ed20fd911d618adb9dd5ee42faed5c0.nq.gz
│   ├── 514d0177804cc4479e323ebb6f5182738f2975a7.nq.gz
│   ├── 5292fba739a1a18c2f295e96de8f617bc8beae65.nq.gz
│   ├── 56fc2658bb1e223bbc342283bdf641aba77d4733.nq.gz
│   ├── 583d5dad0cca7790de1753b664a3747243971a98.nq.gz
│   ├── 5884d0ff2c8d182dba3365fffe7a6bc359a2712b.nq.gz
│   ├── 5af1c14cfcedbae283422797dfc7b1f1eb97af60.nq.gz
│   ├── 5c740cfeb9c97339f2e2c0de840bec2cac2dd9c6.nq.gz
│   ├── 5f0d820166b68ce1ab1ffaf4f5c3d43eadbdd895.nq.gz
│   ├── 5f66d4ee6e85dc68fc36a027dddb2368e3f71fb4.nq.gz
│   ├── 638b874c0d4e7483de59350fee0a674f11ab1b91.nq.gz
│   ├── 63b982ae597695edb63ac9b17740393bc5399786.nq.gz
│   ├── 66500a18c5580da379de4117356f602c7b134c03.nq.gz
│   ├── 67aeb595e951e26914458508c4963cdeafcadd9f.nq.gz
│   ├── 6a0475a956bffc894020068dbf72b0691b2ed0da.nq.gz
│   ├── 6bc573a65addfe6cf75bba8dfa8cfa320ab5c16d.nq.gz
│   ├── 6ed6433ca410e829ef997f8dc519608e1948bea8.nq.gz
│   ├── 6f612397ae7000b598d1c17007dec39c7d41f65d.nq.gz
│   ├── 711b2f116f1c10be84a977e18d31a8711db79bd7.nq.gz
│   ├── 71fe914d4447a809c94e7cfb68693059486f651c.nq.gz
│   ├── 743589b515348dffe48c91bcbc1835426d9528e5.nq.gz
│   ├── 753ac76a3b12ff0a3eb1ebace082571d44466c9f.nq.gz
│   ├── 75d38f2b9cc90843a768144099272322bcd32cb9.nq.gz
│   ├── 7e8ed220218e928c2b7cb1b9adf56d0ce1c781e3.nq.gz
│   ├── 80584a86a3c8944e51f2cea2afe88f29833ab7d8.nq.gz
│   ├── 82f3c327fb26ed84ed81cc7d8422f3bf1359c49e.nq.gz
│   ├── 845bcfda451ebae9a0ac4c62dbca8f62443d0a59.nq.gz
│   ├── 86cfd8fb8e065bc3f662395d571a4b43eaae2a87.nq.gz
│   ├── 86d46ef02a76296c792f32be3b43182cc0937684.nq.gz
│   ├── 87751525b4746e546dfd474e7d06995eafbc65b1.nq.gz
│   ├── 89a82fe41e9b12742c07c25d17c316a8367a1af5.nq.gz
│   ├── 8ca87437429dd3c3f474cb54712f43afffd1b7c5.nq.gz
│   ├── 8d388ef065f5fe3722abf53a4518c7a66d8b7aec.nq.gz
│   ├── 906ca85a923df244fb9d6fe0f2f3a646473f8e45.nq.gz
│   ├── 90b84beeb629b3e3b3c9af94a5a6f15b1434a4da.nq.gz
│   ├── 91c641f6c0170de4cb9e7797a1179a2621198ef7.nq.gz
│   ├── 94007e537381bb41af0749b1e67896db84e0266e.nq.gz
│   ├── 970abcfc84d73ea41516a81959f131ef507cb593.nq.gz
│   ├── 99933177953ec00d138126634598abb32e034d24.nq.gz
│   ├── 9c8c46239f8256e93f709ec81524345420ce1b85.nq.gz
│   ├── 9d3573ae7ee6f0242c075cfcca8549a4f09b6e58.nq.gz
│   ├── 9db8f5015120c9767c8681b19452fb0e20bab2b4.nq.gz
│   ├── a004efd9b8df19cda9e2cb04eb9794e8f4a14487.nq.gz
│   ├── a825def3c27511d9d860c2f4d0110fcb6561a8ff.nq.gz
│   ├── a8b0f3222462033f5759d5b73473ef03c79019ad.nq.gz
│   ├── b194aa4237f15723544e78431de32e18ab8c6f12.nq.gz
│   ├── b1c26f38e96675a9a07ef9ac3149c21274efc452.nq.gz
│   ├── b8fdec101c8d674c5207d100f74b6a72424cb529.nq.gz
│   ├── ba356a789441c8c58baf9f6ddb0c5a0e5b821ff9.nq.gz
│   ├── bafa51dc6e6ec54440415560957c50b3a0cf344b.nq.gz
│   ├── bfc14dccbb926df611d002a4a7620510a55d8be6.nq.gz
│   ├── bfcbba170ea136d640603081f270cfa422c2f161.nq.gz
│   ├── c220540269cde4f7a32d4170c966af05d046501d.nq.gz
│   ├── c279822e2808a36eb88d2e5e3aa1e41104c0af99.nq.gz
│   ├── c2b8a01631c42c5f44723a98e90c5416ed65b74f.nq.gz
│   ├── c502457ec0510f4366688d67a0e2c528a7746b34.nq.gz
│   ├── c585360f61534c56620b64454f743f84a5d0fa7d.nq.gz
│   ├── c793bb90bdd177ec55e8d9fa86a3392a877133b8.nq.gz
│   ├── c905e9b0b7ee9668099b98aea1db9ad2bbf53f4a.nq.gz
│   ├── cb672cecc6d562631b8ff8151d89bc4f8747227d.nq.gz
│   ├── cc7ea1dbc8aade8807a511daf6ea89521a07a13f.nq.gz
│   ├── cf7b19f64b46551d815c4e6d4f6545e3d70b2636.nq.gz
│   ├── d56b45856dd87116249e1b2fb9f8ccca20bc5133.nq.gz
│   ├── d5fe827a07547be356976983dd93162620594f17.nq.gz
│   ├── d810d65ee58ad1dc40c33e2d54f5a3e8fcc1e64f.nq.gz
│   ├── daa9a1beeb99cab30a00ad4f5aae76ef67f0c576.nq.gz
│   ├── dd739650b0b93d1ea7572f1675e7281da4e7464b.nq.gz
│   ├── e594b133128fa7ca2c1321b7faa8a5412ffec5a7.nq.gz
│   ├── e620e1584546dc62fc367a6c502fc82f894addea.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c335e111868901e508c537ccd70bb274bd6bf5.nq.gz
│   ├── ec325e5ff0d73aa3cd1bc537cb5e066f606f37dd.nq.gz
│   ├── ef10f8131014516df68ef1a669811fbd63ff5b5b.nq.gz
│   ├── ef20c3f7cca717376c7e3ba7c259f8b980c33bd7.nq.gz
│   ├── f15103ada859b5d12d6268a3b5efbf2deb811a02.nq.gz
│   ├── f22f1a7a541cb681b4c6f0f034bb1be248d189f1.nq.gz
│   ├── f42069b719f8eb2a861ab05105a66f2ec462702c.nq.gz
│   ├── fd39b782cb9dff51ddaff9ac7c983877fb012bce.nq.gz
│   └── fda23b67c1f3e2987e67a956f77c9ca867836ac9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 74f4c96d3fc5281b1820491d2568de771ea7851b.nq.gz
├── filetree
│   └── 74f4c96d3fc5281b1820491d2568de771ea7851b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 120 files
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

## Source repository

[MagicStack/uvloop](https://github.com/MagicStack/uvloop)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
