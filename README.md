# Repolex Knowledge Graph of wbond/oscrypto

RDF knowledge graph data for [wbond/oscrypto](https://github.com/wbond/oscrypto), parsed by [repolex](https://repolex.ai).

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
rlex download wbond/oscrypto
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76bfdcb7285d856c44f8d0fbafe0ecca1c6d2f8b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 76bfdcb7285d856c44f8d0fbafe0ecca1c6d2f8b
│           └── chunk-001.nq.gz
└── blob
    ├── 00b03c00511d399696b7922989ba99b605ea510d.nq.gz
    ├── 018b68c1bb59aecdea36a2f967240336da90bb8a.nq.gz
    ├── 0194426ca844534c859f6869792a3c44e7ef49a0.nq.gz
    ├── 0566cd5abb9ff426a5f6df671219c862f1064445.nq.gz
    ├── 06b61a11f194bfb6796833d5723c32cca1d38d21.nq.gz
    ├── 0721c34e0ac1e7ca28782fbc1164e2a83146f15a.nq.gz
    ├── 0751d92e7c7978a976dff07db22e50d00beb72c1.nq.gz
    ├── 07b49ae99bb3a01a0014a2e03ce6af351da2c0f9.nq.gz
    ├── 084195e933ba07dc297018cfb7e0e3e2ccaad9af.nq.gz
    ├── 08a23e68b679a2c9fe7a22d97010e383ea8e810b.nq.gz
    ├── 08ae8b75d5642c843125132718ef0ebe0eb15fcb.nq.gz
    ├── 09b58d596cda3b76d873032802c46de7f282eda8.nq.gz
    ├── 0a43a0bca8ea02b810e7911013b3cf8cee11a871.nq.gz
    ├── 0bf8901ccedc4b079fbdbaf4425c41e2b42d3f8d.nq.gz
    ├── 0c6b90b573af26573577f1a98d0e607f8b61a196.nq.gz
    ├── 0e1f71ca8dbfb0168b73f7d3ade43dd19fcde2a0.nq.gz
    ├── 0e64455c39e6c4d1f9970fbc66ec27852d89c804.nq.gz
    ├── 0eb02d74fd8abd7d945f541680696868b5392ed2.nq.gz
    ├── 0f7aa3c9d98d0c81ee83288406724a2c2708739c.nq.gz
    ├── 0fd689b6cf2098baaa124b5f062f78c48681c258.nq.gz
    ├── 101c6917d9049b01950f863d2b5969e296b72721.nq.gz
    ├── 11715c2c570f52b46fca92ea7f40b383790c0da5.nq.gz
    ├── 14c487191591b0076b0301d70da4a48ae38a95de.nq.gz
    ├── 15ae627c1fee61c27c539e96881bd85e9c4575b6.nq.gz
    ├── 17326d8b69a91280efb263672122e47f17afd468.nq.gz
    ├── 174892885f30acff64983a01fff140d0337e1778.nq.gz
    ├── 1aa7f40f2526274373eb2c692e128e89ed0cbf14.nq.gz
    ├── 1d21ab0358da75185d76317ceae14e74172fee9e.nq.gz
    ├── 1ddbae599deb2ed2fca7e7f1d78e9228f3dc2317.nq.gz
    ├── 1de8e298e6117ab04b1054ba472206dbd29e4324.nq.gz
    ├── 1e5d6510c5298a4b605f6fce6695388a63a333a0.nq.gz
    ├── 1fcb3e8ee3c0de39569c9b50435061744115389d.nq.gz
    ├── 223390e787b1dc344eeeaa93351c0fede7bca547.nq.gz
    ├── 22a67741d6313ec12d078097a50c4d0cdfbaf1bb.nq.gz
    ├── 22aac9e3a45b51aee24f08ca82fab92e95ec4df1.nq.gz
    ├── 24c058cbab072beb5e2549a9823c6cba9acd4456.nq.gz
    ├── 298c6b3c8410ebe917df66310cd35c3f8509b8f5.nq.gz
    ├── 2b21ce9b428da6b14298ef5b25498480b5542047.nq.gz
    ├── 2b4ee8c8440167b163ffbfb4d7cc5c664be567c2.nq.gz
    ├── 2c75d81826b183f48c203ced960dfe89fedd3737.nq.gz
    ├── 2d76a1d54a448f389cd95e9da7da079e4e1a9eaf.nq.gz
    ├── 2d80e2b759f35b0fae7cf02274d92610edafb9ea.nq.gz
    ├── 2e6c839d4faf2361284a917aebb11ff9353898b0.nq.gz
    ├── 2ea3479b1210cf8d96df5bf9ced21f687d1b79d5.nq.gz
    ├── 2ec254933cf5cc07d929c39637d04ee68d5d3556.nq.gz
    ├── 2f4cdb8521c6834e4f5737cd0d8d8eda9be0e520.nq.gz
    ├── 2f532214afff6a90341a6d14eb624db6ce157a90.nq.gz
    ├── 30c768b168aeab2626378e729ddb3f0c9effefcb.nq.gz
    ├── 335e956ef34c1418a7d24f29c699e4732e4d93e0.nq.gz
    ├── 34cc8c0edbd46745b597cb2d9e9077b305e2c709.nq.gz
    ├── 36fc18033a36d7274911872b7ef3869d2b2c637d.nq.gz
    ├── 3952682afa78585cf502f27f6e8fd5d83e34ff05.nq.gz
    ├── 3ae721d52acb7757ebcc3f1935b1ffabd8a308a0.nq.gz
    ├── 3b16ccc1253ef24872e723a191b4ca5a93f1e08b.nq.gz
    ├── 3b290b8939bce07049c061fcb9dde74dd8700231.nq.gz
    ├── 3dfdefa7fdd14eddb7010dde7c99d7295b5e282a.nq.gz
    ├── 3e01bf3a14304a657afb38dfbb1b75a12baea61a.nq.gz
    ├── 3e20f4c3ee132f4822d27c5b1ed2a43f8f6df52c.nq.gz
    ├── 3e9d5ceca1594998263dc889fa55f799a89e24f0.nq.gz
    ├── 405d4191d20abc9351a357ca481acc0ebdbaa13b.nq.gz
    ├── 40a8b8125544d5103fe7776fb9d73abf3a58e8bf.nq.gz
    ├── 42aefa2d0c23bc2a9b1dd1fc2c55bdc523324d89.nq.gz
    ├── 431fef27fb39f3744a99c21d656ee21323939bc4.nq.gz
    ├── 432be7990e10aa45d67602f25e3e1a609f70dcf0.nq.gz
    ├── 44a47e7ed74dd0d990f3374566aa7f3e337e8e11.nq.gz
    ├── 4527d99b935743de75abbf9ce073bc43bd544b70.nq.gz
    ├── 46ef82cee7c311f7f803ad0ed76aa39caf6b91b9.nq.gz
    ├── 47b07e5b1d68bbdbf8a6f71302a8ffef566435bf.nq.gz
    ├── 47e5c55468b5d0305ab2522171a7f31b55ac9bb1.nq.gz
    ├── 493a11dbb835ea8b0a46ed92531b4c3d97ff74f6.nq.gz
    ├── 49932ffbb99f79df801575697daebaea36b96070.nq.gz
    ├── 4a78f036b958345666b8cf36eb7acfa131ceccdf.nq.gz
    ├── 4cce32b81156b2f74aebf6b426b75e36c3ab1b4d.nq.gz
    ├── 4d6c452426824cd6d0b61ffd46497d2bf74feb80.nq.gz
    ├── 4e2ac629da30f9eb8aaba2689f2218984ccbe5d6.nq.gz
    ├── 4e729283e4db4b7190832a603117f93972044a77.nq.gz
    ├── 4eb464e264a6d26e6f140e9d70a9ac7bb08546dc.nq.gz
    ├── 4f390e6dcea01192e964223007c117fa06bd1dd7.nq.gz
    ├── 4f4185ec27bfcac8bc487a404211fd422efe24c4.nq.gz
    ├── 4f6c986c744e5f7775bd44ceeaa44619c1b8c7f1.nq.gz
    ├── 5042f8c62b1011ffe671ed8d954e12cbde4a94be.nq.gz
    ├── 5382c673f85a88f745939fa516d6b42497710312.nq.gz
    ├── 53ec3166f5ec474b8ed4e83e53fbbb670670f932.nq.gz
    ├── 5563d4d052df78cc58f8e38fa0a3170c50cc44ba.nq.gz
    ├── 55af5961cf6e61e52e29806e00e154626466b928.nq.gz
    ├── 55faf9eebf04e3f8bf390153a4d9408b807687dc.nq.gz
    ├── 56143cdfc6a8e7de6f2df21e5063bda9d7111e7f.nq.gz
    ├── 561c246d44fbc74bcf204e1a5373555b9cf48754.nq.gz
    ├── 575ab807816d2cc79d5f5762e63eb85d7d1c7dc0.nq.gz
    ├── 581b76f377d7b40f3fe77dc3f85b2608bf62aeee.nq.gz
    ├── 59082b626cc3fd19175d684fda42b28613a896b7.nq.gz
    ├── 59531cd4bb3774273fa6fd465199a121f07a631c.nq.gz
    ├── 5cc257a890c57a229bd7dd027f10fa98c6f888fc.nq.gz
    ├── 5d636ec7330c7b87441eaa11dc22c0c294c5d6d1.nq.gz
    ├── 5e2fa5bc921a70960132cee677e7918092080b3b.nq.gz
    ├── 5eef343995161bf93c068530dd6b80dd385dfa93.nq.gz
    ├── 5f2c8be31cc6af363906aeea8ae8947b3e81a81c.nq.gz
    ├── 5f60c1f24357506b1bcad613a253c677cd5448a2.nq.gz
    ├── 610ca5bc40e2d7375f068a7fa20a00b231756d61.nq.gz
    ├── 6119a9cfa5536175f3b94efa371672bd48b2c967.nq.gz
    ├── 6380cb5496209bae8809202438ae1a91637c61ac.nq.gz
    ├── 644391ee468281e9c8425b9fb51721ecc0d742e3.nq.gz
    ├── 653e7be8f6849e8bcc5231cc01f8e553d3906cb5.nq.gz
    ├── 6622597f2f9abb398dce612762e1d2ae623703ea.nq.gz
    ├── 667b5fd661024e2deee64ab32214833d6916d138.nq.gz
    ├── 66cbbeec04d975c35eacdef999235a6d86ec9af1.nq.gz
    ├── 66e0f636caf4cfe9c34731a72fbcba4e1f3914fd.nq.gz
    ├── 67c965c4a0352318cc60d83a6e73afa153c7b78f.nq.gz
    ├── 683934e7c65e67a7f631835edfb7598ecee2bfbe.nq.gz
    ├── 6a15e6e92730ce55d4aa722f3d0e33931d9f6bc5.nq.gz
    ├── 6c98561fb490aeb4d7c904a869fc949458dae496.nq.gz
    ├── 6e4d48738f50de8f9271a1e04c7783afa701153b.nq.gz
    ├── 6e7a6e77a84751b669ac8405032fa3c4cf958e4c.nq.gz
    ├── 6fba56207a129da99dd9284a8c9cb022d0433cb4.nq.gz
    ├── 733b4f4f9d728b439b855a3dfa21066a44ee251e.nq.gz
    ├── 73a3288a5733676a923ba8000aad28a9207d07f0.nq.gz
    ├── 799b9ed2ae9742b3a3e61d9f9d4664ea5571ce23.nq.gz
    ├── 79ff14a1cce6734f61e3d578c1c188d6c95095a8.nq.gz
    ├── 7a93268e0aa41dcd21457e9760d4ae6f4472ab99.nq.gz
    ├── 7b7ab871d730386268e45834faa02613261c56c2.nq.gz
    ├── 7b898546111301a856b3b120d3038b49000a9695.nq.gz
    ├── 7bae696197ccbc6fcffb8100a410dac9c0e23410.nq.gz
    ├── 8038d9a71ffd803fb428b0acc5dc25a43a4dbbd0.nq.gz
    ├── 805e2cd4a9fe08c22635b5a32b0b37ea2e6f0ce2.nq.gz
    ├── 80a4f89d7a4c16a9e047c1ac4dfab0d1a67b25bb.nq.gz
    ├── 80da5a24edfbc07167a8a2a08e18e985ee76b50c.nq.gz
    ├── 86b55f8ce24b64a90ee8c3f3af6501b8cb4302ba.nq.gz
    ├── 89881a847ce609c34dc14f95c8ec840d63106e3d.nq.gz
    ├── 8acb2fb9ea258ffaf897d5b254b97367384ec1fd.nq.gz
    ├── 8ecaa5b9dbcf3b0765f491f349e0ae0cc3a64927.nq.gz
    ├── 8fc5e181d44d53ce0b1df7f8eb33efa159d6e751.nq.gz
    ├── 92ca6da10923ac68b85db4783a002dab77386c90.nq.gz
    ├── 9364a48ab5f9ee468a7da58bf66faa5bbcae3cea.nq.gz
    ├── 93943f00cc1c13d0cf2237b63e76901030878efb.nq.gz
    ├── 93a9c310afe93426d1fedca8b35f7e3dc8ce5a64.nq.gz
    ├── 93cb6b387c812363b9e6598aef3244d94f052a2e.nq.gz
    ├── 94b560fd096701d1f4937e5a853494a7a9ea76b0.nq.gz
    ├── 95ec0e839c19e76aaaa222a97b354320699021eb.nq.gz
    ├── 961f1055728a5f95ca8d99b467c6934d187eac91.nq.gz
    ├── 96544aacc96ccc0ab2a3034e6f28621569c206c3.nq.gz
    ├── 970c6e60c4c44cd2ffa509321400e4502e1aaf06.nq.gz
    ├── 98b9a9d2356d8995966c601ef29e87917310e55f.nq.gz
    ├── 999047c4002d31a937dbeec5631d2d949156329a.nq.gz
    ├── 9a12e6c88f80b895036e374ba70388b86737a575.nq.gz
    ├── 9c13b8d78ef462fc6788680ab42e3527530bf59c.nq.gz
    ├── 9c831525efe49ce8bcbcdd2c110e397a8c693814.nq.gz
    ├── 9da600722a8f44560d546b828b4ae440a607ccee.nq.gz
    ├── 9dbc788ffd7cf685c7aa7093d5cd4ee335a87cac.nq.gz
    ├── a01e55a76b29c6c4736b3cb5092e155b23ef439d.nq.gz
    ├── a03c35355035d6f3dc4f950403a7c87a1705b1c2.nq.gz
    ├── a16fe3b4fcca9061e8f72a64649a60e126d8856a.nq.gz
    ├── a18cf5e910ac699a527225afe37db11753352cb9.nq.gz
    ├── a1f846426d320a2c2645f76eb4ce5e292da8874a.nq.gz
    ├── a256dd7f486d72a62e53cda4f16acb855d0af954.nq.gz
    ├── a384c4ef9f18392d3253904f1bec8d3c564ea7b9.nq.gz
    ├── a41e0647f8432a70e1adcac7e104ba98a7811179.nq.gz
    ├── a5c7330cf52f5b2ad2c63e05e7efd8d51342f1c9.nq.gz
    ├── a854196b0e4a9f72762f7824e884e8192c10ef4b.nq.gz
    ├── a85794732a1001ab7daf34cc12c02b6960b741fc.nq.gz
    ├── a8ee19272a132a4a8ddc8e6ff00d2739cf918839.nq.gz
    ├── aa42013088cadc58f701872daf7e4526c314f00d.nq.gz
    ├── ab09906e96d1b06b8eb7c194b68b7b5289276a05.nq.gz
    ├── adef788e67b1b96e638cba7742f95e723c24e380.nq.gz
    ├── adf8ae924cfb06dc615864962bad6a8ab6179746.nq.gz
    ├── ae257aaf3dd1b1db7c7b17f44cf8c018598f9b3e.nq.gz
    ├── b03ed61b9aea7fc878cee57553e57f2cb0765cc3.nq.gz
    ├── b40345a426a7ad8498aefc695102c08a19b6c04a.nq.gz
    ├── b66384bf187bfa933186db15b8e188b5073ab95a.nq.gz
    ├── b77f9f93cbaab8b3d4b0b88ec7937e1a34bb3861.nq.gz
    ├── b78817891bf5f56958af370158a9db981d0994b4.nq.gz
    ├── b7c352cee290a4eac835fac13e4c23e33ac8b1e8.nq.gz
    ├── ba5ee10c15bbc79547aed6386063ed0066df8766.nq.gz
    ├── bb389b1f3afe86a50c3dc46b8f28748c519f4855.nq.gz
    ├── bbf2fb9249a581149454ca5e176c2a6800ebc50c.nq.gz
    ├── bc6e8559671c59fb001cbf6fcd3ef75da5901982.nq.gz
    ├── bf8f154b0318ce29299a0fd003c8610442cdcbfd.nq.gz
    ├── c0a1983640240edace13058fe661aa6aa72c0808.nq.gz
    ├── c19ff876777bc8747a44a100b7608ddfffa3faa8.nq.gz
    ├── c1b723a485eaf0086f9e98df9f7cfe7b566c80a0.nq.gz
    ├── c4f7888fb2a0fee121c8cd6bc1fa2f8f4fbe4913.nq.gz
    ├── c4f988a0bf09ce3f3cb5495aa268b8c85236e8ad.nq.gz
    ├── c5d3ad5f4a87d897e168ffc1dcae63176108ee89.nq.gz
    ├── c671770053078cbb878d2be0ef8c8e980fc81a37.nq.gz
    ├── c7cdea981cf8ea8378e66cdc9d4d91d78522993a.nq.gz
    ├── c9d2f8d459e0bbe24983de17dd20b6e23bcfb4b4.nq.gz
    ├── cac08b41a140af4f77f24da013d6da091a0554e5.nq.gz
    ├── cbfa9a7c0263f5110140f80e77c9990b53b42d48.nq.gz
    ├── cc4e529c0eca5dc4a1a05727eff1666eb2aeff76.nq.gz
    ├── cd0fa888d094027ea6efce3acd0eae3c914df730.nq.gz
    ├── cdb399997d3132df9c83a7a7e027ca5ab980661a.nq.gz
    ├── ce0c5f9f3ddc6215d0ef5b45ec2da5f3f7a70ab7.nq.gz
    ├── cefa1a2f51a87ed50e115eedc6aa94d672c80564.nq.gz
    ├── cfb8f99bbac8ff6563d847438c303d74b3a8215a.nq.gz
    ├── d0c79513ac7afb113a2a92cae0fad959a4cc433c.nq.gz
    ├── d2703a6681b2955fcfcf2da2ec732ae0083d57ea.nq.gz
    ├── d28dd0ffeb3927410399027eff61fcf5902b3ad2.nq.gz
    ├── d390f894e72131ca56247f5bc3b06aae7592b571.nq.gz
    └── d47dd45746659f1762b68bc335979a76200211ab.nq.gz

7 directories, 200 files
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

[wbond/oscrypto](https://github.com/wbond/oscrypto)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
