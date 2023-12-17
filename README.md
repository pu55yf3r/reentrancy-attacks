# ⚔️ A Historical Collection of Reentrancy Attacks

[![👮‍♂️ Sanity checks](https://github.com/pcaversaccio/reentrancy-attacks/actions/workflows/checks.yml/badge.svg)](https://github.com/pcaversaccio/reentrancy-attacks/actions/workflows/checks.yml)
[![License: AGPL-3.0-only](https://img.shields.io/badge/License-AGPL--3.0--only-blue)](https://www.gnu.org/licenses/agpl-3.0)

**📌 Definition of a Reentrancy Attack**

> Unsafe _external_ call(s) that allow(s) malicious manipulation of the internal and/or associated external contract state(s).

**📚 Types of Reentrancy Attacks**

- Single-Function Reentrancy
- Cross-Function Reentrancy
- Cross-Contract Reentrancy
- Cross-Chain Reentrancy
- Read-Only Reentrancy

**📜 Reentrancy Attacks List**

A chronological and (hopefully) complete list of reentrancy attacks to date.

- [WETH white hat attack](https://github.com/pcaversaccio/reentrancy-attacks/issues/1#issuecomment-1188680199) – 10 June 2016 | [Victim contract](https://etherscan.io/address/0xd654bDD32FC99471455e86C2E7f7D7b6437e9179), [Exploit contract](https://etherscan.io/address/0x4AfB544Eb87265cF7Fc8fdB843c81d34F7E2A369), [Exploit transaction](https://etherscan.io/tx/0x8d8404d056607815c04dd286858da123c6e6aea29a1197e21a803fa67ebedd7c)
- [The DAO attack](https://medium.com/@zhongqiangc/smart-contract-reentrancy-thedao-f2da1d25180c) – 17 June 2016 | [Victim contract](https://etherscan.io/address/0xBB9bc244D798123fDe783fCc1C72d3Bb8C189413), [Exploit contract](https://etherscan.io/address/0xC0ee9dB1a9E07cA63E4fF0d5FB6F86Bf68D47b89), [Exploit transaction](https://etherscan.io/tx/0x0ec3f2488a93839524add10ea229e773f6bc891b4eb4794c3337d4495263790b)
- [SpankChain attack](https://medium.com/swlh/how-spankchain-got-hacked-af65b933393c) – 9 October 2018 | [Victim contract](https://etherscan.io/address/0xf91546835f756DA0c10cFa0CDA95b15577b84aA7), [Exploit contract](https://etherscan.io/address/0xc5918a927C4FB83FE99E30d6F66707F4b396900E), [Exploit transaction](https://etherscan.io/tx/0x21e9d20b57f6ae60dac23466c8395d47f42dc24628e5a31f224567a2b4effa88)
- [imBTC Uniswap pool attack](https://milkroad.com/news/imbtc-uniswap-hack) – 18 April 2020 | [Victim contract](https://etherscan.io/address/0xFFcf45b540e6C9F094Ae656D2e34aD11cdfdb187), [Exploit contract](https://etherscan.io/address/0xBD2250D713bf98b7E00c26E2907370aD30f0891a), [Exploit transaction](https://etherscan.io/tx/0x9437dde6c06a20f6d56f69b07f43d5fb918e6c57c97e1fc25a4162c693f578aa)
- [Lendf.Me attack](https://slowmist.medium.com/slowmist-details-of-lendf-me-reentrancy-attack-3e168ab5f2b1) – 19 April 2020 | [Victim contract](https://etherscan.io/address/0x0eEe3E3828A45f7601D5F54bF49bB01d1A9dF5ea), [Exploit contract](https://etherscan.io/address/0x538359785a8D5AB1A741A0bA94f26a800759D91D), [Exploit transaction](https://etherscan.io/tx/0xced7ca813081fb594181469001a6aff629c5874bd672cca44075d3ec768db664)
- [Akropolis attack](https://peckshield.medium.com/akropolis-incident-root-cause-analysis-c11ee59e05d4) – 12 November 2020 | [Victim contract](https://etherscan.io/address/0x73fC3038B4cD8FfD07482b92a52Ea806505e5748), [Exploit contract](https://etherscan.io/address/0xe2307837524Db8961C4541f943598654240bd62f), [Exploit transaction](https://etherscan.io/tx/0xe1f375a47172b5612d96496a4599247049f07c9a7d518929fbe296b0c281e04d)
- [ValueDeFi attack](https://inspexco.medium.com/value-defis-invalid-share-calculation-exploit-in-depth-analysis-1c8f97c1416e) – 7 May 2021 | [Victim contract](https://bscscan.com/address/0xD4BBF439d3EAb5155Ca7c0537E583088fB4CFCe8), [Exploit contract](https://bscscan.com/address/0x4269e4090FF9dFc99D8846eB0D42E67F01C3AC8b), [Exploit transaction](https://bscscan.com/tx/0x9dab872598ee7a6290ed7d6f3a903f44a8794246c3089cc91d6cfb69be4d58b4)
- [Rari Capital attack](https://nipunp.medium.com/5-8-21-rari-capital-exploit-timeline-analysis-8beda31cbc1a) – 8 May 2021 | [Victim contract](https://etherscan.io/address/0x67B66C99D3Eb37Fa76Aa3Ed1ff33E8e39F0b9c7A), [Exploit contract](https://etherscan.io/address/0x2f755e8980f0c2E81681D82CCCd1a4BD5b4D5D46), [Exploit transaction](https://etherscan.io/tx/0x1655592eda3ebbba7c530ab3327daeae95fa95d05c3dec40338471245da10cfe)
- [BurgerSwap attack](https://quillhashteam.medium.com/burgerswap-flash-loan-attack-analysis-888b1911daef) – 27 May 2021 | [Victim contract](https://bscscan.com/address/0x7ac55ac530f2C29659573Bde0700c6758D69e677), [Exploit contract](https://bscscan.com/address/0xAE0F538409063e66ff0E382113cb1a051fC069cd), [Exploit transaction](https://bscscan.com/tx/0xac8a739c1f668b13d065d56a03c37a686e0aa1c9339e79fcbc5a2d0a6311e333)
- [Iron Finance attack](https://thedefiant.io/not-just-a-bank-run-new-evidence-shows-iron-finance-crashed-due-to-code-exploit) – 16 June 2021 | [Victim contract](https://polygonscan.com/address/0xa37DD1f62661EB18c338f18Cf797cff8b5102d8e), [Exploit contract](https://polygonscan.com/address/0x9E0bB84c39227755b76e286665f0a2B0bD3Bcc96), [Exploit transaction](https://polygonscan.com/tx/0x05d5c121251cb7cea91a89aaa164451639acb328b4a0a8001470aea531d77a7a)
- [PolyDEX attack](https://polydex.medium.com/plx-locker-smart-contract-incident-post-mortem-75342124a3e8) – 20 June 2021 | [Victim contract](https://polygonscan.com/address/0x28151Ba48963019ddB509FbB6D5761F3494b3828), [Exploit contract](https://polygonscan.com/address/0x287F8Cf077666e60e2d238bF77a525051481D769), [Exploit transaction](https://polygonscan.com/tx/0x6b3f057683083d7f0a25e4d3898ca68308cfe2335878143466f84b3003ebe3a2)
- [DeFiPie attack](https://medium.com/defipie/hacking-investigation-85e07454f1c9) – 12 July 2021 | [Victim contract](https://bscscan.com/address/0xd6eAC7cf547002d289dC85954Ec0ABE217A9b80D), [Exploit contract](https://bscscan.com/address/0x6d741523F1FcBa87Bb8ddA1Ab85D765a9544E6a6), [Exploit transaction](https://bscscan.com/tx/0x45f6f792638d114f31f6608dca4c79b1216bd5c7c45218a5fd8f1c2e309c6d75)
- [Sanshu Inu attack](https://sanshunft.medium.com/woofdate-2-2-0-keanu-compensation-mfund-rebase-update-bcac09707e19) – 20 July 2021 | [Victim contract](https://etherscan.io/address/0x35C674C288577Df3e9b5dafEF945795b741c7810), [Exploit contract](https://etherscan.io/address/0xe30DC9B3c29534E9b4e9A166c2f44411163aD59F), [Exploit transaction](https://etherscan.io/tx/0x00edd68087ee372a1b6e05249cc6c992bb7b8478cc0ddc70c2a1453428285808)
- [XSURGE attack](https://medium.com/@Knownsec_Blockchain_Lab/knownsec-blockchain-lab-comprehensive-analysis-of-xsurge-attacks-c83d238fbc55) – 16 August 2021 | [Victim contract](https://www.bscscan.com/address/0xE1E1Aa58983F6b8eE8E4eCD206ceA6578F036c21), [Exploit contract](https://www.bscscan.com/address/0x1514AAA4dCF56c4Aa90da6a4ed19118E6800dc46), [Exploit transaction](https://www.bscscan.com/tx/0x7e2a6ec08464e8e0118368cb933dc64ed9ce36445ecf9c49cacb970ea78531d2)
- [C.R.E.A.M. Finance attack](https://inspexco.medium.com/reentrancy-attack-on-cream-finance-incident-analysis-1c629686b6f5) – 30 August 2021 | [Victim contract](https://etherscan.io/address/0xD06527D5e56A3495252A528C4987003b712860eE), [Exploit contract](https://etherscan.io/address/0x2E95B91FA678b47660aBA811B74a28Ca1F4ED111), [Exploit transaction](https://etherscan.io/tx/0xd7ec3046ec75efbd04b3eea8752a8a6373a92c0dd813d08b655661054d3239c5)
- [Siren Protocol attack](https://web.archive.org/web/20221215032356/https://medium.com/siren/siren-incident-report-264e57f16d7)[^1] – 3 September 2021 | [Victim contract](https://polygonscan.com/address/0xC3F7250f458E86a4BD19D0819550aC0b17902BdC), [Exploit contract](https://polygonscan.com/address/0x685b121BBB80E89c232f0Ea1755794F14CfC9822), [Exploit transaction](https://polygonscan.com/tx/0xf95fd54b4b1ed0bc109a04df16d1d75106a4d007b186543467c975df94cd3276)
- [CreatureToadz attack](https://medium.com/@ItsCuzzo/exploitedtoadz-a-technical-deepdive-9ceabf46d0ce) – 21 October 2021 | [Victim contract](https://etherscan.io/address/0xA4631A191044096834Ce65d1EE86b16b171D8080), [Exploit contract](https://etherscan.io/address/0xdFF832F6988E4a9E3FCfBfF4cc24d052143aba0E), [Exploit transaction](https://etherscan.io/tx/0x125581f9551c0ae1098e132823cd5cffc0c942be4e6fed6cd447bde017e87130)
- [Grim Finance attack](https://rekt.news/grim-finance-rekt) – 18 December 2021 | [Victim contract](https://ftmscan.com/address/0x660184CE8AF80e0B1e5A1172A16168b15f4136bF), [Exploit contract](https://ftmscan.com/address/0xb08cCb39741d746Dd1818641900f182448Eb5e41), [Exploit transaction](https://ftmscan.com/tx/0x19315e5b150d0a83e797203bb9c957ec1fa8a6f404f4f761d970cb29a74a5dd6)
- [Visor Finance attack](https://sharkteam.org/report/analysis/20211223001A_en.pdf) – 21 December 2021 | [Victim contract](https://etherscan.io/address/0x3a84aD5d16aDBE566BAA6b3DafE39Db3D5E261E5), [Exploit contract](https://etherscan.io/address/0x10C509AA9ab291C76c45414e7CdBd375e1D5AcE8), [Exploit transaction](https://etherscan.io/tx/0x69272d8c84d67d1da2f6425b339192fa472898dce936f24818fda415c1c1ff3f)
- [HypeBears attack](https://blocksecteam.medium.com/when-safemint-becomes-unsafe-lessons-from-the-hypebears-security-incident-2965209bda2a) – 3 February 2022 | [Victim contract](https://etherscan.io/address/0x14e0a1F310E2B7E321c91f58847e98b8C802f6eF), [Exploit contract](https://etherscan.io/address/0x49AB6aBd4be00Df45E5C8e8949Dd41389c34A704), [Exploit transaction](https://etherscan.io/tx/0xfa97c3476aa8aeac662dae0cc3f0d3da48472ff4e7c55d0e305901ec37a2f704)
- [Bacon Protocol attack](https://coincodecap.com/bacon-protocol-hacked-reportedly-1m-lost) – 5 March 2022 | [Victim contract](https://etherscan.io/address/0xb8919522331C59f5C16bDfAA6A121a6E03A91F62), [Exploit contract](https://etherscan.io/address/0x580CaC65C2620D194371ef29Eb887A7D8DCc91Bf), [Exploit transaction](https://etherscan.io/tx/0x7d2296bcb936aa5e2397ddf8ccba59f54a178c3901666b49291d880369dbcf31)
- [Paraluni attack](https://coincodecap.com/paraluni-hacked-reportedly-1-7m-lost) – 13 March 2022 | [Victim contract](https://bscscan.com/address/0x633Fa755a83B015cCcDc451F82C57EA0Bd32b4B4), [Exploit contract](https://www.bscscan.com/address/0x4770b5cb9d51EcB7AD5B14f0d4F2cEe8e5563645), [Exploit transaction](https://www.bscscan.com/tx/0x70f367b9420ac2654a5223cc311c7f9c361736a39fd4e7dff9ed1b85bab7ad54)
- [Agave Finance attack](https://twitter.com/Mudit__Gupta/status/1503783633877827586) – 15 March 2022 | [Victim contract](https://gnosisscan.io/address/0x95a21fCbb57ed54D3a5a706068b06cEE8637998a), [Exploit contract](https://gnosisscan.io/address/0xF98169301B06e906AF7f9b719204AA10D1F160d6), [Exploit transaction](https://gnosisscan.io/tx/0xa262141abcf7c127b88b4042aee8bf601f4f3372c9471dbd75cb54e76524f18e)
- [Hundred Finance attack](https://slowmist.medium.com/another-day-another-reentrancy-attack-5cde10bbb2b4) – 15 March 2022 | [Victim contract](https://gnosisscan.io/address/0x8e15a22853A0A60a0FBB0d875055A8E66cff0235), [Exploit contract](https://gnosisscan.io/address/0xdbf225e3d626ec31f502d435b0f72d82b08e1bdd), [Exploit transaction](https://gnosisscan.io/tx/0x534b84f657883ddc1b66a314e8b392feb35024afdec61dfe8e7c510cfac1a098)
- [Revest Finance attack](https://slowmist.medium.com/revest-finance-incident-analysis-6fcd9b6be207) – 27 March 2022 | [Victim contract](https://etherscan.io/address/0x2320A28f52334d62622cc2EaFa15DE55F9987eD9), [Exploit contract](https://etherscan.io/address/0xb480Ac726528D1c195cD3bb32F19C92E8d928519), [Exploit transaction](https://etherscan.io/tx/0xe0b0c2672b760bef4e2851e91c69c8c0ad135c6987bbf1f43f5846d89e691428)
- [Voltage Finance attack](https://rekt.news/voltage-finance-rekt) – 31 March 2022 | [Victim contract](https://explorer.fuse.io/address/0xa722c13135930332Eb3d749B2F0906559D2C5b99), [Exploit contract](https://explorer.fuse.io/address/0x632942c9BeF1a1127353E1b99e817651e2390CFF), [Exploit transaction](https://explorer.fuse.io/tx/0x1b3e06b6b310886dfd90a5df8ddbaf515750eda7126cf5f69874e92761b1dc90/token-transfers)
- [BNB Brokers attack](https://twitter.com/BlockSecTeam/status/1519249933832171520) – 27 April 2022 | [Victim contract](https://bscscan.com/address/0x2C67f86D91BA3cA559c6d2825d9dbD00C5A90e4B), [Exploit contract](https://bscscan.com/address/0x02C05Ed9e8fda290ba88225eaDce4146Bde7C80A), [Exploit transaction](https://bscscan.com/tx/0x74907b06cacbe77a5af64f8cc16ff49ff7fefc672c5d68909637caa7f9466dca)
- [Fei Protocol attack](https://certik.medium.com/fei-protocol-incident-analysis-8527440696cc) – 30 April 2022 | [Victim contract](https://etherscan.io/address/0x26267e41CeCa7C8E0f143554Af707336f27Fa051), [Exploit contract](https://etherscan.io/address/0x32075bAd9050d4767018084F0Cb87b3182D36C45), [Exploit transaction](https://etherscan.io/tx/0xadbe5cf9269a001d50990d0c29075b402bcc3a0b0f3258821881621b787b35c6)
- [Bistroo attack](https://bistroo.medium.com/post-incident-review-bist-single-asset-staking-binancesmartchain-security-breach-5194590605f) – 7 May 2022 | [Victim contract](https://www.bscscan.com/address/0x2987B3983bfA7E2698b4C10A361ca5119697a080), [Exploit contract](https://bscscan.com/address/0x70B31bB9859E88ddb3Ac04bc205575992EdAd3FA), [Exploit transaction](https://bscscan.com/tx/0x8c96b3314e30cf62bdfd4f94df38a2f040e171e849208b328dcd4ac2cdbcb748)
- [Ownly attack](https://twitter.com/ownlyio/status/1524362090940895234) – 10 May 2022 | [Victim contract](https://www.bscscan.com/address/0x421f30419D6c1D7573C1F57546A631f2f89D7E92), [Exploit contract](https://www.bscscan.com/address/0xA81eA095e0c3708E4236c71146748FA15B620386), [Exploit transaction](https://www.bscscan.com/tx/0x2cbe47edb040c710b7f139cbea7a4bced4d6a0d6c5aa4380f445880437ea072f)
- [Omni attack](https://twitter.com/BlockSecTeam/status/1546141457933025280) – 10 July 2022 | [Victim contract](https://etherscan.io/address/0x2F131C4DAd4Be81683ABb966b4DE05a549144443), [Exploit contract](https://etherscan.io/address/0x3C10E78343c475b99d20fA544dd30b43C0cBa26f), [Exploit transaction](https://etherscan.io/tx/0x264e16f4862d182a6a0b74977df28a85747b6f237b5e229c9a5bbacdf499ccb4)
- [Stader Labs NearX attack](https://medium.com/quillhash/decoding-a-830-000-exploit-quillaudits-c70d1ecfd562) – 16 August 2022 | [Victim contract](https://nearblocks.io/address/nearx.stader-labs.near), [Exploit contract](https://nearblocks.io/address/gregoshes.near)[^2], [Exploit transaction](https://nearblocks.io/txns/BexQuhmdtr745g5fSqvVnCDvXCms14XFJXAZPKWzFc4o)
- [Thunder Brawl attack](https://twitter.com/peckshield/status/1575890733373849601) – 30 September 2022 | [Victim contract](https://bscscan.com/address/0xae191Ca19F0f8E21d754c6CAb99107eD62B6fe53), [Exploit contract](https://bscscan.com/address/0xfeD1B640633Fd0A4d77315d229918ab1f6E612f9), [Exploit transaction](https://bscscan.com/tx/0x57aa9c85e03eb25ac5d94f15f22b3ba3ab2ef60b603b97ae76f855072ea9e3a0)
- [QuickSwap Lend attack](https://quillaudits.medium.com/decoding-220k-read-only-reentrancy-exploit-quillaudits-30871d728ad5) – 23 October 2022 | [Victim contract](https://polygonscan.com/address/0x3dC7E6FF0fB79770FA6FB05d1ea4deACCe823943), [Exploit contract](https://polygonscan.com/address/0xEb4c67E5BE040068FA477a539341d6aeF081E4Eb), [Exploit transaction](https://polygonscan.com/tx/0xb8efe839da0c89daa763f39f30577dc21937ae351c6f99336a0017e63d387558)
- [n00dleSwap attack](https://twitter.com/BlockSecTeam/status/1584959295829180416) – 25 October 2022 | [Victim contract](https://etherscan.io/address/0x3561081260186E69369E6C32F280836554292E08), [Exploit contract](https://etherscan.io/address/0x9C5A2A6431523fBBC648fb83137A20A2C1789C56), [Exploit transaction](https://etherscan.io/tx/0x8037b3dc0bf9d5d396c10506824096afb8125ea96ada011d35faa89fa3893aea)
- [DFX Finance attack](https://web.archive.org/web/20221130161503/https://blog.audit.haechi.io/dfx_finance_attack_overview) – 10 November 2022 | [Victim contract](https://etherscan.io/address/0x46161158b1947D9149E066d6d31AF1283b2d377C), [Exploit contract](https://etherscan.io/address/0x6cFa86a352339E766FF1cA119c8C40824f41F22D), [Exploit transaction](https://etherscan.io/tx/0x6bfd9e286e37061ed279e4f139fbc03c8bd707a2cdd15f7260549052cbba79b7)
- [Defrost Finance attack](https://twitter.com/PeckShieldAlert/status/1606276020276891650) – 23 December 2022 | [Victim contract](https://snowtrace.io/address/0xfF152e21C5A511c478ED23D1b89Bb9391bE6de96), [Exploit contract](https://snowtrace.io/address/0x792E8f3727cad6e00c58d478798F0907c4cEC340), [Exploit transaction](https://snowtrace.io/tx/0xc6fb8217e45870a93c25e2098f54f6e3b24674a3083c30664867de474bf0212d)
- [Jaypeggers attack](https://twitter.com/BlockSecTeam/status/1608372475225866240) – 29 December 2022 | [Victim contract](https://etherscan.io/address/0xf2919D1D80Aff2940274014bef534f7791906FF2), [Exploit contract](https://etherscan.io/address/0xed42Cb11b9D03c807ED1ba9c2eD1d3BA5Bf37340), [Exploit transaction](https://etherscan.io/tx/0xd4fafa1261f6e4f9c8543228a67caf9d02811e4ad3058a2714323964a8db61f6)
- [Midas Capital attack](https://twitter.com/AnciliaInc/status/1614705804468424704) – 15 January 2023 | [Victim contract](https://polygonscan.com/address/0xe150e792e0a18C9984a0630f051a607dEe3c265d), [Exploit contract](https://polygonscan.com/address/0x757E9F49aCfAB73C25b20D168603d54a66C723A1), [Exploit transaction](https://polygonscan.com/tx/0x0053490215baf541362fc78be0de98e3147f40223238d5b12512b3e26c0a2c2f)
- [2Pi Network attack](https://2pinetwork.medium.com/lessons-learned-from-exploit-incident-postmortem-70ad1a079b38) – 15 January 2023 | [Victim contract](https://optimistic.etherscan.io/address/0x6a5143b943578C18b9D28e7Acc123BBd7aac3282), [Exploit contract](https://optimistic.etherscan.io/address/0x0058a31Ac6F54175876c0C74C65Bd1B901A8a025), [Exploit transaction](https://optimistic.etherscan.io/tx/0x21449ae15ea6ccd737d9436426413388a6f4290cef93b8ed7f0eaa51f500d5df)
- [Abracadabra Money white hat attack](https://mirror.xyz/0x5744b051845B62D6f5B6Db095cc428bCbBBAc6F9/47LK6nUpMrVsYzfCYBTyZsc_7t5Sh5onxO8sSEotNMY) – 16 January 2023 | [Victim contract](https://arbiscan.io/address/0x1aDDD80E6039594eE970E5872D247bf0414C8903), [Exploit contract](https://arbiscan.io/address/0x3816A80F324B8f6F34cF76E5Ba9A256130d37f50), [Exploit transaction](https://arbiscan.io/tx/0x3f0aa143886f873a73ee9f1584c5f0d5043c5dff7e4f5c2ed34664dbe2fe9d25)
- [Orion Protocol attack](https://twitter.com/peckshield/status/1621337925228306433) – 2 February 2023 | [Victim contract](https://etherscan.io/address/0xb5599f568D3f3e6113B286d010d2BCa40A7745AA), [Exploit contract](https://etherscan.io/address/0x5061F7e6dfc1a867D945d0ec39Ea2A33f772380A), [Exploit transaction](https://etherscan.io/tx/0xa6f63fcb6bec8818864d96a5b1bb19e8bd85ee37b2cc916412e720988440b2aa)
- [dForce Network attack](https://twitter.com/BlockSecTeam/status/1623901011680333824)[^3] – 9 February 2023 | [Victim contract](https://arbiscan.io/address/0x2cE498b79C499c6BB64934042eBA487bD31F75ea), [Exploit contract](https://arbiscan.io/address/0xEe29b6AEE6E4783Db176946e4e8F1E5fDCD446A7), [Exploit transaction](https://arbiscan.io/tx/0x5db5c2400ab56db697b3cc9aa02a05deab658e1438ce2f8692ca009cc45171dd)
- [Dynamic attack](https://neptunemutual.com/blog/how-was-dynamic-finance-exploited) – 22 February 2023 | [Victim contract](https://bscscan.com/address/0xa7B5eabC3Ee82c585f5F4ccC26b81c3Bd62Ff3a9), [Exploit contract](https://bscscan.com/address/0xd360b416cE273AB2358419b1015aCf476a3b30d9), [Exploit transaction](https://bscscan.com/tx/0xc09678fec49c643a30fc8e4dec36d0507dae7e9123c270e1f073d335deab6cf0)
- [Sentiment attack](https://quillaudits.medium.com/decoding-sentiment-protocols-1-million-exploit-quillaudits-f36bee77d376) – 4 April 2023 | [Victim contract](https://arbiscan.io/address/0x0dDB1eA478F8eF0E22C7706D2903a41E94B1299B)[^4], [Exploit contract](https://arbiscan.io/address/0x9f626F5941FAfe0A5b839907d77fbBD5d0deA9D0), [Exploit transaction](https://arbiscan.io/tx/0xa9ff2b587e2741575daf893864710a5cbb44bb64ccdc487a100fa20741e0f74d)
- [Paribus attack](https://twitter.com/Phalcon_xyz/status/1645742620897955842) – 11 April 2023 | [Victim contract](https://arbiscan.io/address/0x375Ae76F0450293e50876D0e5bDC3022CAb23198)[^5], [Exploit contract](https://arbiscan.io/address/0xcd31E27F0A811de7139938b1972b475697f8c50b), [Exploit transaction](https://arbiscan.io/tx/0x0e29dcf4e9b211a811caf00fc8294024867bffe4ab2819cc1625d2e9d62390af)
- [MuratiAI attack](https://twitter.com/PeckShieldAlert/status/1666110220404428800) – 6 June 2023 | [Victim contract](https://bscscan.com/address/0x69C2fcAe7e30b429166BD616A322e32BeC036bCf), [Exploit contract](https://bscscan.com/address/0x5a4216E0990CaFEB540a253AD79b09ac2Acd3AD1), [Exploit transaction](https://bscscan.com/tx/0x62dbb9d5967d735ebf6fcfbbf3b7121194d4a7d61c85627388064cb8fe0ad65f)
- [Sturdy attack](https://twitter.com/BlockSecTeam/status/1668084629654638592) – 12 June 2023 | [Victim contract](https://etherscan.io/address/0xB1ebF8F77ae002d487e7Bde22c6180be0AF6a3d4), [Exploit contract](https://etherscan.io/address/0x0B09c86260C12294e3b967f0D523B4b2bcdFbeab), [Exploit transaction](https://etherscan.io/tx/0xeb87ebc0a18aca7d2a9ffcabf61aa69c9e8d3c6efade9e2303f8857717fb9eb7)
- [Arcadia Finance attack](https://arcadiafinance.medium.com/post-mortem-72e9d24a79b0)[^6] – 10 July 2023 | [Victim contract](https://optimistic.etherscan.io/address/0xD417c28aF20884088F600e724441a3baB38b22cc), [Exploit contract](https://optimistic.etherscan.io/address/0x01a4d9089C243CCaEbE40AA224ad0CaB573B83c6), [Exploit transaction](https://optimistic.etherscan.io/tx/0xca7c1a0fde444e1a68a8c2b8ae3fb76ec384d1f7ae9a50d26f8bfdd37c7a0afe)
- [Libertify attack](https://twitter.com/peckshield/status/1678688731908411393)[^7] – 11 July 2023 | [Victim contract](https://polygonscan.com/address/0x9c80a455ecaca7025A45F5fa3b85Fd6A462a447b), [Exploit contract](https://polygonscan.com/address/0xdFcDB5A86b167B3A418F3909D6f7A2f2873F2969), [Exploit transaction](https://polygonscan.com/tx/0x7320accea0ef1d7abca8100c82223533b624c82d3e8d445954731495d4388483)
- [Conic Finance attack](https://medium.com/@ConicFinance/post-mortem-eth-and-crvusd-omnipool-exploits-c9c7fa213a3d) – 21 July 2023 | [Victim contract](https://etherscan.io/address/0xBb787d6243a8D450659E09ea6fD82F1C859691e9), [Exploit contract](https://etherscan.io/address/0x743599BA5CfA3cE8c59691aF5ef279AaaFA2E4EB), [Exploit transaction](https://etherscan.io/tx/0x8b74995d1d61d3d7547575649136b8765acb22882960f0636941c44ec7bbe146)
- [EraLend attack](https://twitter.com/BeosinAlert/status/1683880646811299853) – 25 July 2023 | [Victim contract](https://explorer.zksync.io/address/0x00A1C271df375660f47293fd84B53572fded0107), [Exploit contract](https://explorer.zksync.io/address/0x7d8772DCe73cDA0332bc47451aB868Ac98F335F0), [Exploit transaction](https://explorer.zksync.io/tx/0x99efebacb3edaa3ac34f7ef462fd8eed85b46be281bd1329abfb215a494ab0ef)
- [Curve attack](https://hackmd.io/@LlamaRisk/BJzSKHNjn)[^8] – 30 July 2023 | [Victim contract](https://etherscan.io/address/0xC4C319E2D4d66CcA4464C0c2B32c9Bd23ebe784e), [Exploit contract](https://etherscan.io/address/0x30FB95794a2051ABe30A67892B3A1FA73947aEE5), [Exploit transaction](https://etherscan.io/tx/0xb676d789bb8b66a08105c844a49c2bcffb400e5c1cfabd4bc30cca4bff3c9801)
- [Earning.Farm attack](https://twitter.com/BeosinAlert/status/1689205260102094853) – 9 August 2023 | [Victim contract](https://etherscan.io/address/0x12Df0C95D2c549bbBC96cf8FbA02cA4Bc541aFD9), [Exploit contract](https://etherscan.io/address/0xFe141C32E36Ba7601D128F0C39DEdBE0F6aBb983), [Exploit transaction](https://etherscan.io/tx/0x6e6e556a5685980317cb2afdb628ed4a845b3cbd1c98bdaffd0561cb2c4790fa)
- [Defiway attack](https://twitter.com/AnciliaInc/status/1709352941541630049) – 3 October 2023 | [Victim contract](https://bscscan.com/address/0x6705d8196D06DA351371b6E0692fC18504ed4864), [Exploit contract](https://bscscan.com/address/0x0Bb02653ca1C3C4915CAE217aa02c16E68Ae381a), [Exploit transaction](https://bscscan.com/tx/0x6becb186ea8d701b2309da51e3420814036b9324dc56b9fb31bfbf96f7958e60)
- [Stars Arena attack](https://twitter.com/peckshield/status/1710555944269292009) – 7 October 2023 | [Victim contract](https://snowtrace.io/address/0xA481B139a1A654cA19d2074F174f17D7534e8CeC), [Exploit contract](https://snowtrace.io/address/0x7F283EDc5EC7163de234E6a97fDFb16FF2D2C7ac), [Exploit transaction](https://snowtrace.io/tx/0x4f37ffecdad598f53b8d5a2d9df98e3c00fbda4328585eb9947a412b5fe17ac5)
- [0x0 attack](https://twitter.com/MetaSec_xyz/status/1717854153324781709) – 27 October 2023 | [Victim contract](https://etherscan.io/address/0x3EBAA7507556F878ed62532143d5D344207b00f8), [Exploit contract](https://etherscan.io/address/0xfEb3390244A00253Daa61650dA20D2be85f0617c), [Exploit transaction](https://etherscan.io/tx/0x9d6d355db13361c0862f7d51913d7d31ea724dc25228782ea052f955a1d5b79d)
- [Peapods Finance attack](https://twitter.com/0xaxxe/status/1735027744436547702) – 13 December 2023 | [Victim contract](https://etherscan.io/address/0xdbB20A979a92ccCcE15229e41c9B082D5b5d7E31), [Exploit contract](https://etherscan.io/address/0x928B2DAe97FC5d40Cb0552815fb5ab071103e20a), [Exploit transaction](https://etherscan.io/tx/0x98d8237027797a51b1251aa239d1a85b7a209d15c9f7895b44b4ee7ee0c754fb)
- [NFT Trader attack](https://twitter.com/0xCygaar/status/1736056050816876626) – 16 December 2023 | [Victim contract](https://etherscan.io/address/0x13d8faF4A690f5AE52E2D2C52938d1167057B9af), [Exploit contract](https://etherscan.io/address/0xc446e0A1E22B54e18303022FF8C5c8AB364d6ebb), [Exploit transaction](https://etherscan.io/tx/0x906d06acd236c48a8c8708d7dc50d968b8faad7c7c393e7c01549adf4922b180)
- [GoodDollar attack](https://twitter.com/MetaSec_xyz/status/1736428284756607386) – 16 December 2023 | [Victim contract](https://etherscan.io/address/0x0c6C80D2061afA35E160F3799411d83BDEEA0a5A), [Exploit contract](https://etherscan.io/address/0xF06Ab383528F51dA67E2b2407327731770156ED6), [Exploit transaction](https://etherscan.io/tx/0x726459a46839c915ee2fb3d8de7f986e3c7391c605b7a622112161a84c7384d0)

> Some of the exploits carried out involve multiple separate transactions as well as multiple victim and exploit contracts. For each attack, I have listed the most affected victim contract, the most critical exploit contract, and the most devastating exploit transaction.

## 💢 Disclaimer

<img src=https://user-images.githubusercontent.com/25297591/167394075-1813e258-3b03-4bc8-9305-69126a07d57e.png width="1050"/>

[^1]: To prevent the article from constantly reloading, deactivate JavaScript in your browser.
[^2]: We list the attacker's address here for the sake of completeness, but technically the attack was executed with a Near-specific transaction type called ["Batch Transaction"](https://nomicon.io/RuntimeSpec/Transactions#batched-transaction) and not with a specific exploit contract.
[^3]: We list the victim contract, the exploit contract, and the exploit transaction on Arbitrum. However, the same exploit was carried out on Optimism with almost the same amount of loss: [Victim contract](https://optimistic.etherscan.io/address/0xDFeC2EA848Cf8fdA096503f8D9F37AFac6E0ECF2), [Exploit contract](https://optimistic.etherscan.io/address/0xEe29b6AEE6E4783Db176946e4e8F1E5fDCD446A7), [Exploit transaction](https://optimistic.etherscan.io/tx/0x6c19762186c9f32c81eb2a79420fc7ad4485aa916cab37ec278b216757bfba0d).
[^4]: The same exploit hit another victim with almost the same amount of loss: [Victim contract](https://arbiscan.io/address/0x4c8e1656E042A206EEf7e8fcff99BaC667E4623e).
[^5]: The same exploit hit two other victims with almost the same amount of loss: [Victim contract 2](https://arbiscan.io/address/0x367351F854506DA9B230CbB5E47332b8E58A1863), [Victim contract 3](https://arbiscan.io/address/0xD3e323a672F6568390f29f083259debB44C41f41).
[^6]: We list the victim contract, the exploit contract, and the exploit transaction on Optimism. However, the same exploit was carried out on Ethereum, albeit with a smaller loss amount: [Victim contract](https://etherscan.io/address/0x9aa024D3fd962701ED17F76c17CaB22d3dc9D92d), [Exploit contract](https://etherscan.io/address/0x56A35FAe9b0416360e1752A9abE78D89F51517CF), [Exploit transaction](https://etherscan.io/tx/0xefc4ac015069fdf9946997be0459db44c0491221159220be782454c32ec2d651).
[^7]: We list the victim contract, the exploit contract, and the exploit transaction on Polygon. However, the same exploit was carried out on Ethereum, albeit with a smaller loss amount: [Victim contract](https://etherscan.io/address/0x429032A407aed3D5fF84caf38EFF217eB4d322A9), [Exploit contract](https://etherscan.io/address/0xdFcDB5A86b167B3A418F3909D6f7A2f2873F2969), [Exploit transaction](https://etherscan.io/tx/0xcb0ad9da33ecabf75df0a24aabf8a4517e4a7c5b1b2f11fee3b6a1ad9299a282).
[^8]: The technical post-mortem on the reentrancy lock vulnerability from Vyper can be found [here](https://hackmd.io/@vyperlang/HJUgNMhs2).
