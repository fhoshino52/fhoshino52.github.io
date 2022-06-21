<!--
|リンク          |説明                                                |
|:--------------:|:--------------------------------------------------:|
|[表紙][this]    |このページ                                          |
|[github][gitrep]|github repository                                   |

[this]:https://fhoshino52.github.io
[gitrep]:https://github.com/fhoshino52/fhoshino52.github.io
-->

# Publication List 
## Fumitaka Hoshino

1. [On some variants of lossy trapdoor function][2022/1A4-1]
  Fumitaka Hoshino.
  SCIS 2022 Proceedings, 1A4-1,<br>
  Peikert と Waters は STOC 2008 において lossy trapdoor function (LTDF) の概念を提唱し, その具体的構成と応用を提案した. その後 LTDF の構成法や拡張および応用などに関して様々な研究が行われている. ところで LTDF の拡張は方式を構成する多項式時間アルゴリズムの数が比較的多く, 複雑すぎて様々なプロトコルへの流用が難しいという問題があり, オーダーメイド的に LTDF の亜種が構成される傾向がある. ところが, 実際にはそうした拡張を具体的に構成する際は Peikert-Waters の DDH による構成をベースに機能を追加していくことが多い. そうした状況を鑑み, 本稿では様々な応用が出来そうな LTDF の比較的シンプルな亜種について考察を行いたい.

1. [On the Restriction of Asymmetric Pairing based on Symmetric Pairing.][2021/scis2021]
  Fumitaka Hoshino.
  SCIS 2021 Proceedings, 3B1-2,<br>
  対称ペアリングを用いて非対称ペアリングに似た性質を持つ暗号プリミティブを構成できる事が知られている. そのように構成した暗号プリミティブは対称ペアリングと非対称ペアリングを折衷したような性質を持ち, 高機能な暗号方式への適用が期待できる. しかし, そのようなプリミティブが, どのような制約を持つかは, それほど明確になっていない. 本稿ではそのような暗号プリミティブの適用限界について論じる.

1. [Asymmetric Pairing based on Symmetric Pairing.][2020/scis2020]
  Fumitaka Hoshino and Tetsutaro Kobayashi.
  SCIS 2020 Proceedings, 3B1-2, pp.1385-1392<br>
  対称ペアリングを用いて非対称ペアリングに似た性質を持つ暗号プリミティブを構成できる事が知られている . そのように構成した暗号プリミティブは対称ペアリングと非対称ペアリングを折衷したような性質を持ち , 高機能な暗号方式への適用が期待できる . 本発表ではそのような暗号プリミティブの構成について解説し , 教科書的な各種の離散対数ベースの応用プロトコルに対して、本プリミティブの適用性を評価し , 様々な問題点を議論する.

1. [On an Application of a Variant of Trapdoor DDH Group.][2019/IPSJCSS2019216]
  Fumitaka Hoshino and Tetsutaro Kobayashi.
  CSS 2019 Proceedings, pp.1535-1542<br>
  対称ペアリングを用いて非対称ペアリングに似た性質を持つ暗号プリミティブを構成できる事が知られている . そのように構成した暗号プリミティブは対称ペアリングと非対称ペアリングを折衷したような性質を持ち , 高機能な暗号方式への適用が期待できる . 本論文ではそのような暗号プリミティブの応用について考察する

1. [Opcount: A pseudo-code performance estimation system for pairing-based cryptography.][2019/E102.A_1285.pdf]
  Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,
  IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E102.A(9):1285-1292,<br>
  高速なペアリングライブラリの実装は特定の曲線やパラメータ限られることが多く、個別の暗号方式の効率を様々な曲線やパラメータに対して実装評価することは多大な労力・コストを要する。本稿では，ペアリング群上の暗号方式の様々な曲線およびパラメータ設定におけるパフォーマンスを簡易的に評価するフレームワーク 'Opcount' を提案する。擬似コードによる暗号方式の記述と、評価対象の曲線における基本演算のパフォーマンスを記録した実装情報データベースから、その暗号方式のパフォーマンスを見積もることで、適切な曲線やパラメータの選択を可能とした。

1. [Theory of Type Conversion for Pairing-based Crypto Schemes.][2019/thesis.pdf]
  Fumitaka Hoshino,
  Department of Mathematical and Computing Science, School of Computing, Tokyo Institute of Technology, 2019<br>
  対称ペアリング群上設計された暗号方式を，非対称ペアリング群上のなるべく効率的な方式に，安全性を損なわずに変換するアルゴリズムをペアリング型変換と呼ぶ。本論文ではペアリング型変換に関して考察し，次の3つの結果を得た。 (1) 標準的な計算量仮定の下，最悪の入力でも多項式時間で最適解を見つけるアルゴリズムは存在しない事を証明した。 (2) 整数計画法を用いた実用的なアルゴリズムを提案した。 (3) 暗号学的に興味深い変換例を示した。これらの結果により、2014年に提案されたペアリング型変換に関するオープン問題を解決した。

1. [Fast and Scalable Bilinear-Type Conversion Method for Large Scale Crypto Schemes.][2019/e102-a_1_251.pdf]
  Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,
  IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E102.A(1):251-269,<br>
  対称ペアリング群上設計された暗号方式を，非対称ペアリング群上のなるべく効率的な方式に，安全性を損なわずに変換するアルゴリズムをペアリング型変換と呼ぶ。本論文ではペアリング型変換に関して考察し，次の3つの結果を得た。 (1) 標準的な計算量仮定の下，最悪の入力でも多項式時間で最適解を見つけるアルゴリズムは存在しない事を証明した。 (2) 整数計画法を用いた実用的なアルゴリズムを提案した。 (3) 暗号学的に興味深い変換例を示した。これらの結果により、2014年に提案されたペアリング型変換に関するオープン問題を解決した。

1. [Optimization of Batch Verification for Pairing Product Equations.][2019/1B2-1.pdf]
  Fumitaka Hoshino.
  SCIS 2019 Proceedings 1B2-1, pp.106-113<br>
  高機能暗号方式では, 大量のペアリング積等式の検証がしばしば必要となる. それらの等式は各個に検証するより一括して検証する方が効率的である. しかし, ペアリング積等式の一括検証には沢山の計算方法が存在し, その数は一般にペアリングの数に対して指数関数的に増大する. そして計算方法により計算の効率が大きく変わる事が知られている. 本研究の目的は, 上記のように大量にある各々の検証式の型が全て既知である場合, 指数的多数の計算方法の候補から最も良い, あるいはそれに匹敵するくらい良い計算方法を見つけ出すアルゴリズムを与える事である.

1. [Designated Agent Anonymizable Signature][2019/4A2-2.pdf]
  Tetsutaro Kobayashi and Fumitaka Hoshino.
  SCIS 2019 Proceedings 4A2-2, pp.2070-2074<br>
  匿名化可能署名 (Anonymizable Signature) とは リング署名 (Ring Signature) の拡張である. 匿名化可能署名を用いることで, 任意のエンティティが通常の署名から匿名署名に変換することができる. 言い換えると, 署名を代理人に託し, 匿名化を依頼することが可能である. 匿名化可能署名に残存する課題として, 匿名化する前の署名が通常の署名であるため, 誰でも検証可能という点がある.本発表では,匿名化可能署名を匿名化する前の時点で検証できる者を限定化する, という拡張を行った. この拡張により, 匿名化前の署名が流出した場合のリスクを軽減することが可能となる.

1. [Pairing Type Optimization Problem and Its Hardness.][2018/1B1-3.pdf]
  Fumitaka Hoshino, Masayuki Abe, and Miyako Ohkubo.
  SCIS 2018 Proceedings 1B1-3, pp.100-107<br>
  非対称ペアリングは非対称の入力ペアを必要とする。即ち、非対称ペアリングには入力に二つの入力データ型が存在する。このことは、暗号方式設計者が各変数に対して矛盾なくデータ型を選択する必要があることを意味する。場合によってはそうしたデータ型の割り当てが実際には不可能な事もある。たとえ割り当てが可能だったとしても、割り当て方の選択が方式の効率に大きな影響を与える。従ってこの割り当ての充足方法および最適化方法に研究的関心がある。この論文ではそういた割り当ておよび最適化の包括的理論を与える。

1. [Pseudo-Code Performance Estimation for Pairing-Based Cryptographic Schemes.][2018/3A3-4.pdf]
  Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,
  SCIS 2018 Proceedings 3A3-4, pp.1448-1454<br>
  高速なペアリングライブラリの実装は特定の曲線やパラメータ限られることが多く、個別の暗号方式の効率を様々な曲線やパラメータに対して実装評価することは多大な労力・コストを要する。本稿では，ペアリング群上の暗号方式の様々な曲線およびパラメータ設定におけるパフォーマンスを簡易的に評価するフレームワーク 'Opcount' を提案する。擬似コードによる暗号方式の記述と、評価対象の曲線における基本演算のパフォーマンスを記録した実装情報データベースから、その暗号方式のパフォーマンスを見積もることで、適切な曲線やパラメータの選択を可能とした。

1. [Dynamic Multi-Cast Key Distribution with KEM.][2018/3A2-1.pdf]
  Koha Kinjo, Yuki Okano, Tsunekazu Saito, Keita Xagawa, Tetsutaro Kobayashi, and Fumitaka Hoshino.
  SCIS 2018 Proceedings 3A2-1, pp.1376-1383<br>
  Yoneyama らは, 多人数での通信における ユーザエンドでの End-to-End 暗号化 (E2EE) を実現するために, 通信効率の良い動的多者鍵配布 (DMKD) プロトコルの具体的な方式を提案している. しかし, この DMKD プロトコルは量子コンピュータの解読に耐性のない Diffie-Hellman(DH) 鍵交換を利用している. 本研究では量子コンピュータの実用化に備え, Yoneyama らの DMKD プロトコルをモデルとした, これに耐性のあるプロトコルの構築を目的とした.本稿では二者間鍵交換を KEM で記述し, 格子暗号をはじめとしたポスト量子暗号が適用可能な DMKD プロトコルの一般的な構成を提案する.

1. [Faster Bilinear-Type Conversion.][2017/1B1-4.pdf]
  Fumitaka Hoshino,
  SCIS 2017 Proceedings 1B1-4, pp.102-109<br>
  非対称ペアリングは対称ペアリングと比較して代数的構造は複雑だが実装の効率はずっと良い. 従って, ペアリングに基づく暗号方式を構成する際， 一旦は対称ペアリング上で設計を行い，しかる後に非対称ペアリングの代数的構造に合わせ再設計し実装を得る事が多くなっている. 2016年, 阿部らは方式の安全性を維持したまま, このタスクを自動実行する効率的なアルゴリズムを発表した. 本研究ではこのアルゴリズムを簡素化して, 幾分高速化する.

1. [[Invited Talk] Fast and Scalable Bilinear-Type Conversion Using Integer Programming.][2016/ISEC2016-73.pdf]
  Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,
  Technical Report of IEICE. Vol.116(380), ISEC2016-73, p.23, Dec. 2016.<br>
  本公演では, 2016年8月14日から18日にカルフォルニア大学サンタバーバラ校(UCSB)にて開催された第36回国際暗号学会議(CRYPTO 2016)で発表された, 双線型型変換に関する最近の結果を紹介する.

1. [Software-based Modification Detection of ECU for Automotive Network System Attestation.][2016/ICSS2016-39.pdf]
  Takuma Koyama, Junko Takahashi, Fumitaka Hoshino, Masashi Tanaka,
  Technical Report of IEICE. Vol.116(328), ICSS2016-39, pp.3-8, Nov. 2016.<br>
  本稿では車載ネットワークに接続する制御機器（ECU）のソフトウェアの改竄検知方式を提案する．車外ネットワークと通信するコネクテッドカーおよび自動運転技術の研究開発が進む中，車載ネットワークに対する脅威として遠隔からのECUのソフトウェア改竄が指摘されている．提案方式では既存方式が見逃しうる改竄を検知可能とするためにECUのメモリの空き領域に検証領域を拡張した．ソフトウェアがメモリサイズの約9割以上を占める条件下では既存方式より高速に検証可能である．

1. [Design in Type-I, Run in Type-III: Fast and Scalable Bilinear-Type Conversion Using Integer Programming.][2016/978-3-662-53015-3_14.pdf]
  Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,
  CRYPTO 2016 Proceedings Part III, LNCS 9816 pp 387-415.<br>
  対称ペアリング群上設計された暗号方式を，非対称ペアリング群上のなるべく効率的な方式に，安全性を損なわずに変換するアルゴリズムをペアリング型変換と呼ぶ。本論文ではIPConv と呼ばれる 0-1整数計画法を用いた新しいペアリング型変換を導入する。広く使われている IPソルバを使うと、IPConv は既存の複雑な方式を即座にペアリング型変換することができる。そうした高速で大規模化可能なペアリング型変換が使えると、対称ペアリング上の暗号方式の設計に関する新たなアプローチが可能となる。

1. [Optimal Conversion from Symmetric Pairing-based Scheme to Asymmetric One.][2016/2D1-1.pdf]
  Fumitaka Hoshino, Masayuki Abe, and Miyako Ohkubo.
  SCIS 2016 Proceedings 2D1-1, pp.833-840<br>
  2014年阿部らは方式の安全性を維持したままペアリングの型変換を自動実行するフレームワークを発表した. 2015 年に整数計画法を直接用いるアルゴリズムが提案されたことにより, かなり大規模な暗号方式の自動変換が可能となった (未発表). 一方 Groth-Sahai 証明などを用いて設計された大規模な方式を対称ペアリングを使って具体的に記述すると, 方式自体が証明する述語の数に対して指数的多数の変種を持ってしまう事がある. 本発表ではそのような場合でも最適な変換を見つけるアルゴリズムを提案する.

1. [On Barreto-Naehrig Curves.][2015/1F2-4.pdf]
  Fumitaka Hoshino
  SCIS 2015 Proceedings 1F2-4, pp.345-349<br>
  本論文では, 最も代表的な pairing-friendly 楕円曲線の一つである Barreto-Naehrig 曲線における hash to point に関して考察し、高速化の検討を行なった.

1. [Attribute based authenticate key exchange scheme.][2015/3F2-2.pdf]
  Tetsutaro Kobayashi, Fumitaka Hoshino, and Koutarou Suzuki.
  SCIS 2015 Proceedings 3F2-2, pp.1766-1767<br>
  インターネットで通信を行う際に、認証と鍵交換を行う SSL/TLS などのプロトコルが多く使われている。 従来の認証鍵交換プロトコルは、通信相手を指定してその相手とのみ鍵共有を行うものであった。 これを拡張し、通信相手の条件を指定して条件を満たす相手と鍵共有を行う方式を提案する。従来の ID ベース認証鍵交換方式と同様の eCK 安全性に加え、鍵共有相手の ID に関する情報を得ることがないという匿名性についての議論を行う。

1. [A Variant of Diffie-Hellman Problem and How to Prove Independency.][2014/2B3-4.pdf]
  Fumitaka Hoshino
  SCIS 2014 Proceedings 2B3-4, pp.645-652<br>
  本論文では , 楕円曲線の暗号学的な模型およびある Diffie-Hellman 問題の変種を考察し, 対称ペアリング群を使用して , 非対称ペアリング群に似た暗号プリミティブの設計を行った . 対称ペアリング群上のDLIN 仮定の下で新しい暗号プリミティブは trapdoor DDH 群の性質と XDH 群のような性質を両方満たす .

1. [id-eCK Secure ID-Based Authenticated Key Exchange on Symmetric and Asymmetric Pairing.][2013/e96-a_6_1139.pdf]
  Atsushi Fujioka, Fumitaka Hoshino, Tetsutaro Kobayashi, Koutarou Suzuki, Berkant Ustaoglu, and Kazuki Yoneyama.
  IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E96.A(6):1139-1155,<br>
  対称および非対称ペアリング上のIDに基づく認証鍵交換プロトコルを提案する。提案プロトコルは双線形Diffie-Hellman仮定の下、ランダムオラクルモデルにおけるIDに基づくCanetti-Krawczyk (id-eCK)モデルで安全である。

1. [On Decentralized Multi-Authority Functional Encryption.][2013/4F1-1.pdf]
  Fumitaka Hoshino.
  SCIS 2013 Proceedings 4F1-1, pp.2074-2081<br>
  結託攻撃を防ぐ為 , 安全な分権複数局関数型暗号(DMA-FE)では大域検証可能識別子(GID) と呼ばれる受信者毎に固有の識別子が用いられ, 秘密鍵は必ず GID と結びつけられて発行される. 同じ GID を持つ秘密鍵は組み合わせて復号に使用する事が可能だが, 異なる GID を持つ秘密鍵は組み合わせて使用出来ないよう暗号文が構成される. ところで, 一般にある鍵生成局が単一の受信者に対して異なる属性を持つ複数の秘密鍵を発行する事がある .このような状況で, 一つの鍵生成局が 2 つ以上の属性を管理している場合を考えると単一の受信者が同じ GID の 2 つ以上の秘密鍵を持っているので結託攻撃と全く同じ攻撃が可能となる. このような鍵再発行攻撃を防ぐ為, 更新の度に異なる GID を用いると, 新たな秘密鍵は元々の GID を持つ他の鍵と組み合わせて使用する事が出来なくなってしまう. 本論文ではこの問題に対し簡易なアプローチを考察する.

1. [Fully Secure Ciphertext-Policy Functional Encryption with O(1) Pairings.][2013/4F1-3.pdf]
  SCIS 2013 Proceedings 4F1-3, pp.2090-2097
  Reo Yoshida, Fumitaka Hoshino, and Tetsutaro Kobayashi.<br>
  O(1)ペアリングのフル安全な暗号文ポリシー関数型暗号

1. [Fast Implementation of Pairing-based Cryptosystems on Android with NEON.][2013/3E1-2.pdf]
  Yuto Kawahara, Reo Yoshida, Fumitaka Hoshino, and Tetsutaro Kobayashi.
  SCIS 2013 Proceedings 3E1-2, pp.1586-1592<br>
  本稿では，高速なペアリング暗号の構成である BN 曲線上の Optimal Ate ペアリングに対して， NEON と呼ばれる ARM アーキテクチャでの SIMD 命令を利用した Android 端末上の高速実装の結果を示す．我々は， NEON を用いることで素体 Fp 上の高速な乗算アルゴリズムを構成し，ペアリングの高速化を図った．実験結果として， Android 端末上での 126-bitセキュリティ相当のペアリングの計算は約 6.77 ミリ秒となり， C による実装と比較し約 4.5 倍高速であった．また暗号システムへの応用として，本実装を関数型暗号へ適応し， Setup, Keygen, Encrypt, Decryptの計算時間を評価した．

1. [Cryptographic Techniques that Combine Data Protection and Ease of Utilization in the Cloud Computing Era.][2012/ntttechnical.pdf]
  Hitoshi Fuji, Atsushi Fujioka, Tetsutaro Kobayashi, Koji Chida, Fumitaka Hoshino, Toshiyuki Miyazawa, and Koutarou Suzuki.
  NTT Technical Review, 10(10), 2012. pp.26-31<br>
  データ保護とクラウドコンピューティング時代の利用の容易さを併せ持つ暗号技術

1. [Application of Functional Encryption: Key-Insulated Encryption.][2012/1A1-5.pdf]
  Fumitaka Hoshino and Atsushi Fujioka.
  SCIS 2012 Proceedings 1A1-5, pp.22-29<br>
  本稿では関数型暗号を用いた鍵隔離暗号の構成について考察する. 関数型暗号とは属性ベース暗号や述語暗号を含む ID ベース暗号の一般化概念で近年活発に研究されているものである . Crypto 2010 において , 岡本らが標準的な暗号学的仮定の下, 任意の述語に関して適応的 payload-hiding な関数型暗号を提案した事により, 属性ベース暗号などの関数型暗号を他の暗号の部品として用いる事に実装上の問題はほとんど無くなった. 本稿では岡本らの関数型暗号を用いた 2 つの鍵隔離暗号の構成方法を提案する. これらの構成では鍵更新の間隔を公開鍵とは独立に設定出来るため柔軟な運用が可能となる.

1. [Functional Encryption: Current State of Implementation and Prospects for Practical Applications.][2012/1B1-3.pdf]
  Katsumi Takahashi, Fumitaka Hoshino, Tetsutaro Kobayashi, Go Yamamoto, Tomohide Yamamoto, Toshiyuki Miyazawa, Reo Yoshida, Hitoshi Fuji, Masatoshi Yokomori, and Akira Nagai.
  SCIS 2012 Proceedings 1B1-3, pp.105-112<br>
  関数型暗号は属性ベース暗号や述語暗号を含む ID ベース暗号の一般化概念として近年活発に研究されている．本論文の前半では，関数型暗号の概念および構成について概説し，典型的な使用方法とネットワークで必要となる機構を説明する．さらに岡本らの関数型暗号を， x86 プロセッサ上で実装した結果とその評価について報告する．後半では，関数型暗号の応用に関して，どのような応用が可能か具体的に考え，加えて普及に向けて解決すべき課題について考察する．

1. [A study on id-eCK security of ID-based authenticated key exchange using asymmetric pairing.][2012/1D2-3.pdf]
  Koutarou Suzuki, Atsushi Fujioka, Kazuki Yoneyama, Tetsutaro Kobayashi, and Fumitaka Hoshino.
  SCIS 2012 Proceedings 1D2-3, pp.337-341<br>
  ID を用いて相互認証し鍵交換を行う ID ベース認証鍵交換（ ID-based authenticated key exchange ）に関して、非対称ペアリングを用いて ID ベース eCK （ ID-based extended Canetti-Krawczyk ）安全性を実現する方法について考察する。従来の ID ベース eCK 安全性を実現する ID ベース認証鍵交換方式は、対称ペアリングを必要としており、より効率のよい非対称ペアリングを用いて eCK 安全性を実現する方式は知られていなかった。本研究では、非対称ペアリングを用いて ID ベース eCK 安全性な ID ベース認証鍵交換方式を実現する際に問題となる点について考察し、 ID ベース eCK 安全性な ID ベース認証鍵交換方式を提案する。

1. [Symmetric Pairing based on Asymmetric Pairing.][2012/1A1-2.pdf]
  Tetsutaro Kobayashi, Fumitaka Hoshino, and Koutarou Suzuki.
  SCIS 2012 Proceedings 1A1-2, pp.5-8<br>
  楕円曲線のペアリングを応用した ID ベース暗号の提案以来、数多くのペアリングを利用した暗号技術が提案されてきた。楕円曲線のペアリングには大きく分けて非対称ペアリングと対称ペアリングがある。近年、非対称ペアリングの典型的な例である BN 曲線上のペアリング高速実装技術の研究が進んだことと、対称ペアリングの典型的な例である超特異曲線上のペアリング向け曲線への攻撃研究が進んだことから、非対称ペアリングが主流となりつつある。一方、ペアリング利用技術の中には対称ペアリングを前提とした方式もある。このようなアルゴリズムのために、非対称ペアリングを用いて対称ペアリングを実現する研究が行われているが、従来はハッシュ値を楕円曲線上の点に変換する関数 (MapToPoint) を行うことができなかった。本稿は、非対称ペアリングを用いて対称ペアリングを実現する際に MapToPoint を行う方法を提案し、性能の評価を行う。

1. [An Application of Functional Encryption: Verifiable Timed-Release Encryption.][2011/2A4-1.pdf]
  Fumitaka Hoshino and Atsushi Fujioka.
  SCIS 2011 Proceedings 2A4-1, pp.474-481<br>
  時限式暗号とは , 暗号文の正規の受信者であっても送信者が指定した開封時刻になるまで暗号文が復号できないような特殊な暗号のことである. 本論文では開封時刻以降に時報局より放送される指数的多数の如何なる時報トークンを使用しても暗号文が復号出来る時限式暗号について考察する. そのような時限式暗号は関数型暗号を用いて容易に実現可能である. さらに本論文では上記のような時限式暗号について, 敵対的送信者に関するさまざまな問題点を研究し, 時限式暗号の拡張として検証可能時限式暗号の概念を提案する. そして敵対的送信者に関するさまざまな安全性定義をカバーできる安全性である平文拘束の定義を行う. また強秘匿の概念である IND-TR-CCA をこの設定で定義し, 平文拘束および IND-TR-CCA を実現する汎用構成戦略を考える. 最後に DLIN 仮定および強偽造不可能 One-Time署名の存在の元で, 平文拘束および IND-TR-CCA が証明できる検証可能時限式暗号の効率的実装方法を提案する.

1. [Anonymizable Signature and Its Construction from Pairings.][2010/978-3-642-17455-1_5.pdf]
  Fumitaka Hoshino, Tetsutaro Kobayashi, and Koutarou Suzuki.
  Pairing 2010 Proceedings,　LNCS 6487 pp.62-77.<br>
  リング署名の拡張である匿名化可能署名の概念を提案する。匿名化署名を使うと、署名されたメッセージを持つ者は誰でもその署名を匿名署名に変換する事ができる。つまり署名されたメッセージを、あとで匿名化してくれる適当なエージェントに預けることが出来る。定義および簡易な構成の方法論および証明可能安全な具体的な方式を提案する。

1. [Message Dependently Relinkable Ring Signature.][2010/3A1-1-b.pdf]
  Fumitaka Hoshino, Koutarou Suzuki, and Tetsutaro Kobayashi.
  SCIS 2010 Proceedings 3A1-1, pp.982-987<br>
  再リンク可能リング署名とは, 署名生成能力からリング生成能力を分離できる特殊なリング署名である. この署名を用いると, 署名者から特別な秘密(再リンク鍵)を得た第三者(代理人)が, 再リンクと呼ばれる手続きにより, 既存のリング署名からメンバーを変更したリング署名を生成する事が出来る. 本論文ではこの署名系が持つ様々な制約を緩和するため, 文書依存再リンク可能リング署名の概念を提案し, その汎用的構成の方法論を与え, 2 つの具体的方式を得た.

1. [CRYPTREC Report 2009 暗号方式委員会報告.][2009/cryptrec-rp-2000-2009.pdf]
  CRYPTREC Report,
  CRYPTREC,<br>
  本報告書は、総務省及び経済産業省が主催している暗号技術検討会の下に設置されている暗号方式委員会の 2009 年度活動報告である。

1. [Relinkable Ring Signature.][2009/978-3-642-10433-6_35.pdf]
  Koutarou Suzuki, Fumitaka Hoshino, and Tetsutaro Kobayashi.
  CANS 2009, Proceedings, LNCS 5888, pp.518-536.<br>
  リングを再構成できるリング署名である再リンク可能リング署名の概念を提案する。再リンク可能リング署名を用いると、署名者はリングを再構成する能力を、署名能力から分離して代理人に付与する事ができる。定義および証明可能安全な具体的な方式を提案する。

1. [A Flexible Ring Signature.][2009/3B4-1.PDF]
  Fumitaka Hoshino, Koutarou Suzuki, and Tetsutaro Kobayashi.
  SCIS 2009 Proceedings 3B4-1, pp.1250-1255<br>
  署名者の匿名性を守るための署名技術には大別して 2 つの方法がある. 一つは 1991年に Chaum らが提案したグループ署名の概念で, この方法にはグループ管理者と呼ばれる信頼できる第三者 (TTP) が登場する. もう一つは 2001 年に Rivest らが提案したリング署名の概念で, この方法にはグループ管理者が存在しない. 著者らは, このグループ署名とリング署名の間の中間に位置するような署名を提案している. 本論文では, この中間的な署名方式を改造して署名者がリング署名を生成した後にグループ管理者がリング署名の参加メンバーを変更したりリング署名を普通の署名に変換したりできる事を実現する.

1. [CRYPTREC Report 2008 暗号技術監視委員会報告.][2008/cryptrec-rp-2000-2008.pdf]
  CRYPTREC Report,
  CRYPTREC,<br>
  本報告書は、総務省及び経済産業省が主催している暗号技術検討会の下に設置されている暗号技術監視委員会の 2008 年度活動報告である。

1. [A Point Compression Method for Subfield Curves.][2008/178_b.pdf]
  Fumitaka Hoshino and Tetsutaro Kobayashi.
  SCIS 2008 Proceedings 2D3 178_b, pp.745-750<br>
  大きな平文空間を持つ再暗号化可能な ElGamal 暗号は, 巡回群の元に直接平文を埋め込んだり, 巡回群の元から平文が容易に復元出来るような特別な性質を巡回群に要求する . 巡回群として楕円曲線を用いる場合, 曲線の位数が素数であるときは, 平文を x 座標の部分情報に埋め込み, x の残りの部分情報を適当に選んで, 楕円曲線の定義式を満たす y を見つければ十分である. しかし, 楕円曲線の位数が合成数で, コファクター c を持つような場合は上記のようにして見つけた (x,y) が目的の巡回群に載る確率はおよそ 1/c である. c が小さい場合はこの埋め込みアルゴリズムは機能するが, OEF で部分体曲線を使う場合のように曲線に大きなコファクターがあると機能しない. コファクターが大きい時は必要としている部分群のサイズに比べて点を定義するデータ (x 座標 ) のサイズが冗長なため, 部分群の点を効率的に見つけられない事が問題の本質である. 従って部分群の点を小さい情報量で表現する事 ( 即ち点圧縮 ) が可能であればこの問題は解決する . 以上の工学的動機に基づき、本稿では比較的大きい部分体で定義された楕円曲線の点圧縮の方法を提案する.

1. [Efficient GF(3m) Multiplication Algorithm for ηT Pairing.][2008/416_b.pdf]
  Gen Takahashi, Fumitaka Hoshino, and Tetutaro Kobayashi.
  SCIS 2008 Proceedings 3D1 416_b, pp.1384-1389<br>
  ηTペアリングの為の効率的なGF(3m)乗算アルゴリズム

1. [Security consideration on the signature scheme 3IC-.][2008/403_b.pdf]
  Toshiyuki Miyazawa, Fumitaka Hoshino, and Tetutaro Kobayashi.
  SCIS 2008 Proceedings 3B1 403_b, pp.1149-1153<br>
  2007 年に Dubois らは NESSIE で採択されたデジタル署名方式 SFLASH (C^∗−) の公開鍵の差分をとることにより C^∗ の公開鍵を復元する方式を示し，これによって C^∗− の公開鍵が与えられれば署名を偽造できることを示した． C^∗− のほかにも，多変数非線型方程式に基づくデジタル署名方式に対して， Dubois らの用いた差分による攻撃の有効性を評価することは重要である．本稿では， 2007 年に Ding らによって提案されたデジタル署名方式 3IC- (Delta Invertible cycle) に対して，差分を用いた攻撃の有効性を評価した． 3IC- は，多変数 2 次多項式暗号 3IC の公開鍵から (C^∗− と同様に ) 幾つかの 2 次式を削除することによって構成されるデジタル署名方式であるが，本稿では， 3IC- の公開鍵の差分を取ることによって， 3IC の公開鍵を復元できることを示す．

1. [Efficient GF(3m) Multiplication Algorithm for ηT Pairing.][2007/2007-463.pdf]
  Gen Takahashi, Fumitaka Hoshino, and Tetsutaro Kobayashi.
  Cryptology ePrint Archive: Report 2007/463<br>
  ηTペアリングの為の効率的なGF(3m)乗算アルゴリズム

1. [Revocable Ring Signature using Revocable DDH Assumption.][2007/2B4-2.pdf]
  Koutarou Suzuki, Fumitaka Hoshino, and Tetsutaro Kobayashi.
  SCIS 2007 Proceedings 2B4-2, pp.516-521<br>
  本論文では revocable DDH群の応用として署名者が署名生成能力から匿名性を取り消す能力を分離して委譲可能なRevocable リング署名を提案する.

1. [On the Invalid Point Attack of Pairing Based Cryptography.][2007/4A1-1.pdf]
  Fumitaka Hoshino, Gen Takahashi, and Tetsutaro Kobayashi.
  SCIS 2007 Proceedings 4A1-1, pp.1715-1719<br>
  暗号系に不正な入力が行われた時に , 暗号系がどのような挙動を示すかは実装に強く依存する. そのため実装の詳細を抽象した暗号プロトコルに於いては , 入力は何らかの集合に収まっていると仮定し , 入力が集合に含まれなかった場合の系の挙動は捨象しがちである. Lim らは不正な入力を用いて離散対数に基づく暗号系攻撃する Small Subgroup 攻撃を提案した. また Antipa らは不正な楕円曲線上の点を用いて楕円曲線暗号系を攻撃する Invalid Curve 攻撃を提案した. 本論文ではAntipa らの Invalid Curve 攻撃を pairing に基づく暗号系 (PBC) へ拡張した Invalid Point 攻撃を考察し, pairing の型による, 対策コストの軽減を検討する.

1. [Compressed Jacobian Coordinates.][2007/2E3-3.pdf]
  Tetsutaro Kobayashi, Fumitaka Hoshino, and Kazumaro Aoki.
  SCIS 2007 Proceedings 2E3-3, pp.844-847<br>
  VietCrypt2006 で発表された OEF 上の楕円曲線の座標、Compressed Jacobian coordinates の一般化を行う. Compressed Jacobian coordinates は, 拡大体上で定義された楕円曲線上の点の加算・二倍算を高速に行える座標であり、特に OEF(拡大次数 5)においては従来の Jacobian coordinates よりも 28% 程度高速となり、ベースポイントの位数が 244bit の楕円曲線のスカラー倍が 41.9 µsec per operation on a 2.82-GHz Athlon 64 FX PC という速度が示されている。本稿では、 OEF 以外の楕円曲線暗号への Compressed Jacobian coordinates の適用を考察する。

1. [Compressed Jacobian Coordinates for OEF.][2006/Hoshino2006_Chapter_CompressedJacobianCoordinatesF.pdf]
  Fumitaka Hoshino, Tetsutaro Kobayashi, and Kazumaro Aoki.
  VIETCRYPT 2006 Proceedings, LNCS 4341, pp.147-156.<br>
  最適拡大体(OEF)上の楕円加算および楕円二倍算を高速化する新しい座標系を提案する. 楕円暗号を高速化する為に沢山の座標系が提案されているが, 提案座標系はそれら従来の座標系の自然な拡張であり, 楕円曲線が OEF 上で定義されている時は新しい座標系は従来の座標系よりもずっと高速である. 本論文では q = 2^61-1, m = 5 として, 楕円曲線が GF(q^m),上で定義されている時,トータルの計算コストが28%削減される事を示した.そして2.82-GHz Athlon 64 FX PC上で楕円スカラ倍演算の速度が41.9μ秒となった事を報告する.

1. [Candidate One-Way Functions on Non-Supersingular Elliptic Curves.][2006/e89-a_1_144.pdf]
  Taiichi Saito, Fumitaka Hoshino, Shigenori Uchiyama, and Tetsutaro Kobayashi.
  IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E89.A(1):144-150,<br>
  非超特異楕円曲線上のある特別な型の自己準同型で構成された新しい一方向性関数の候補を提案する. 提案関数の一方向性はco-Diffie-Hellman 仮定のある特別な場合と同値である事が示せる.また, 本論文では提案関数を使ったデジタル署名方式を厳密に記述した.

1. [Realtime Receipt Free Schnorr Identification.][2006/1A3-5.pdf]
  Fumitaka Hoshino, Tetsutaro Kobayashi, and Koutarou Suzuki.
  SCIS 2006 Proceedings 1A3-5, pp.54-58<br>
  本研究では 認証プロトコルに於いて honest な検証者と観察者を仮定しても通信記録が認証成功の証拠とならない性質 ”リアルタイム無証拠性”の概念を提案する. さらに Schnorr 認証において リアルタイム無証拠性と 他の安全性要件である健全性が一見両立困難 なように思えるが , 使用する巡回群に構造を持ったモデルを導入するとプロトコルを変更せずに両立できる事を示す . そして 特殊な楕円曲線で生成した群の系列を用い, 使用する群の選択がプロトコルの安全性にどのような影響をあたえるか検討し, 構造を持った群でプロトコルを構成する場合, 群の安全性は DDH安全だけでは不十分である事を示す.

1. [Revocable DDH by using Pairing and It’s Application.][2005/3D4-3.pdf]
  Fumitaka Hoshino, Koutarou Suzuki, and Tetsutaro Kobayashi.
  SCIS 2005 Proceedings 3D4-3, pp.1394-1397<br>
  DDH に関する witness を CDH に関する witness から分離できるような群の family である revocable DDH group を提案し , そのセキュリティについて考察する . またそのアプリケーションとして , 任意の暗号文の同一性検証が可能となる検証鍵を秘密鍵から分離出来る暗号系を提案する . また楕円曲線上の点のある同型写像の一方向性に着目し 非 trace-2 の non-supersingular 楕円曲線を用いて安全な revocable DDH group を構成する方法を提案する.

1. [Privacy enhanced active RFID tag.][2005/echise2005-s02-PrivacyEnhancedActiveRFIDTag-Kinoshita+etal.pdf]
  Shingo Kinoshita, Fumitaka Hoshino, Tomoyuki Komuko, Akiko Fujimura, and Miyako Ohkubo.
  Proc. of International Workshop on Exploiting Context Histories in Smart Environments, 2005,<br>
  プライバシ強化されたアクティブRFIDタグ.

1. [RFID Privacy Protection Protocol for Libraries with the Unidentifiable Anonymous ID Scheme.][2004/2B-3.pdf]
  Gembu Morohashi, Shingo Kinoshita, and Fumitaka Hoshino.
  CSS 2004 Proceedings 2B-3,<br>
  近年流通業界を中心に業務に RFID を取り入れる動きが進んでいる．一方で RFID が付随したモノが消費者の手に渡ることから生じるプライバシの侵害が深刻な問題になっており， RFID の導入に対する障害の一因になっている．こうした問題に対し，我々はこれまでに低コストでプライバシ問題を解決する基盤技術として可変秘匿 ID 方式を開発してきた．本論文では，所有者／利用者，利用期間といった点において，いわゆる消費財と異なる特性をもつレンタル分野，特に図書館分野におけるプライバシ問題の考察するとともに，可変秘匿 ID 方式の適用プロトコルを提案する．提案プロトコルでは，可変秘匿 ID 方式のID 再暗号化方法（再暗号化を行う端末や契機）や復号方法などを図書館業務プロセスに最適となるように具体化している．また，図書館以外のレンタル分野への適用性についても考察する．

1. [Low-cost RFID privacy protection.][2004/IPSJ-JNL4508022.pdf]
  Shingo Kinoshita, Fumitaka Hoshino, Miyako Ohkubo, Gembu Morohashi, Osamu Shionoiri, and Atsushi Kanai.
  IPSJ Journal 45, 8 (Aug. 2004), pp.2007-2021<br>
  将来，到来するであろうユビキタス社会において，RFID タグはあらゆるアイテムに装着され，さまざまな応用サービスへと発展していく基盤技術として期待されている．一方では，RFID の優れた追跡能力が悪用された場合の消費者プライバシー侵害が問題視されはじめている．本論文では，漠然とした不安がもたれている RFID のプライバシー問題を整理するとともに，その普及条件として最も重要となる低コスト化を考慮した解決方式を提案する．また，将来の標準技術として最も注目されている MIT Auto-ID システムへの適用方式もあわせて紹介する

1. [Non-Supersingular Elliptic Curves for Pairing-Based Cryptosystems.][2004/e87-a_5_1203.pdf]
  Taiichi Saito, Fumitaka Hoshino, Shigenori Uchiyama, and Tetsutaro Kobayashi.
  IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E87.A(5):1203-1205,<br>
  本論文では非超特異楕円曲線に基づいて, ペアリングに基づく暗号系を構成する方法を与える.

1. [Applying Auto-ID to the Japanese Publication Business To Deliver Advanced Supply Chain Managment, Innovative Retail Applications, and Convenient and Safe Reader Services.][2003/None_KEI-AUTOID-WH004.pdf]
  Toshiharu Ishikawa, Yukiko Yumoto, Michio Kurata, Makoto Endo, Shingo Kinoshita, Fumitaka Hoshino, Satoshi Yagi, and Masatoshi Nomachi.
  AUTO-ID Center white paper<br>
  高度なサプライチェーンマネジメント、革新的なリテールアプリケーション、便利で安全な読取サービスを実現する為の日本の出版ビジネスへのAuto-IDの適用.

1. [Nonidentifiable Anonymous-ID Scheme for RFID Privacy Protection.][2003/78.pdf]
  Shingo Kinoshita, Fumitaka Hoshino, Tomoyuki Komuko, Akiko Fujimura, and Miyako Ohkubo.
  CSS 2003 Proceedings,<br>
  将来，到来するであろうユビキタス社会において，RFID タグはあらゆるアイテムに装着され，さまざまな応用サービスへと発展していく基盤技術として期待されている．一方では，RFID の優れた追跡能力が悪用された場合の消費者プライバシー侵害が問題視されはじめている．本論文では，漠然とした不安がもたれている RFID のプライバシー問題を整理するとともに，その普及条件として最も重要となる低コスト化を考慮した解決方式を提案する．また，将来の標準技術として最も注目されている MIT Auto-ID システムへの適用方式もあわせて紹介する．

1. [A Cyclic Window Algorithm for Elliptic Curves over OEF.][2003/e86-a_1_121.pdf]
  Tetsutaro Kobayashi, Fumitaka Hoshino, and Kazumaro Aoki.
  IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E86.A(1):121-128,<br>
  最適拡大体のような, フロベニウス写像が高速な拡大体上定義された楕円曲線に適した、新しいスライディングウインドウアルゴリズムを提案する.OEF上の楕円スカラー倍に関しては, PKC2000で報告されたLim-Hwangの結果が従来は最速であったが, このアルゴリズムはLim-Hwangの結果から楕円曲線上の群演算をおよそ15% 削減する.実装の結果,スカラー倍はPentium II (450 MHz), 21164A (500 MHz), and 21264 (500 MHz)の計算機上でそれぞれ 573 μs, 595 μs, and 254 μs を達成した. この論文はICICS 2001 で発表された同タイトルの論文の内容に, その後の研究成果を追加して改訂した論文である.

1. [Lenient/Strict Batch Verification in Several Groups.][2003/e86-a_1_64.pdf]
  Fumitaka Hoshino, Masayuki Abe, and Tetsutaro Kobayashi.
  IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E86.A(1):64-72,<br>
  一括検証は暗号学的な大量の等式を同時に全て検証する為の便利な道具である. 特に法指数演算に基づく述語を検証する時に効果が大きい. しかしながら, 場合によっては, 一括検証が等式をまとめて判定する時, 正しいと判定するにも関わらず, 実際には幾つかの等式が正しくない事がある. 実は, そのような判定の緩さは, あらかじめ等式の要素の定義域をチェックする事によって排除する事ができる. この事実を念頭に, 本論文では厳密一括検証の概念を導入し, 厳密一括検証が等式を個別に検証するよりも、やはり効率的であるか否かを調査した. 様々なタイプの群上の厳密一括検証の効率を見積もり, 群とパラメタの選択に依存して, 効率が大きく変化する事が示された.この論文はISC 2001 で発表された同タイトルの論文の内容に, その後の研究成果を追加して改訂した論文である.

1. [Non-Supersingular Elliptic Curves for Pairing-Based Cryptosystems.][2003/ISEC2003.pdf]
  Taiichi Saito, Fumitaka Hoshino, Shigenori Uchiyama, and Tetsutaro Kobayashi.
  Technical Report of IEICE. Vol.103(315), ISEC2003-64, pp.95-101, Sep. 2003.<br>
  本稿は、非超特異楕円曲線上のある種の自己準同型写像を用いて構成した一方向性関数を提案し、その一方向性の傍証をいくつか与える。

1. [On the Fast DL Verification.][2003/15C-3.pdf]
  Fumitaka Hoshino and Tetsutaro Kobayashi.
  SCIS 2003 Proceedings 15C-3, pp.1185-1188<br>
  高速離散対数検証法は署名, ゼロ知識証明等の検証コストを削減するアルゴリズムである . 本論文では高速離散対数検証法の有意性について安全性と演算コストの観点から検討する .

1. [Attacks on Implementations of Elliptic Curve Cryptsystems.][2003/7D-1.pdf]
  Tetsutaro Kobayashi, Fumitaka Hoshino, and Hideki Imai.
  SCIS 2003 Proceedings 7D-1, pp.523-525<br>
  実装環境によって公開鍵暗号を攻撃することができることが明らかとなっている。実装に依存する攻撃法のひとつに、演算時間を測定することによる攻撃法(Timing Attack)がある。本稿では、楕円曲線暗号系に対するTiming Attackについて考察する。

1. [Batch Verification and Multiple Exponentiation Algorithm.][2002/3a-1_1483.pdf]
  Fumitaka Hoshino and Masayuki Abe.
  SCIS 2002 Proceedings 3a-1, pp.53-57<br>
  Multiple Exponentiation は署名 , ゼロ知識証明 あるいは 暗号文のような暗号アイテムの検証コストを大幅に削減する Batch 検証等を実現する為のアルゴリズムである . 本論文では現在, 楕円離散対数ベースの暗号として利用可能な最も高速なソフトウェア実装の一つである 61 bit OEF 上での Multiple Exponentiation の実装結果を報告し , Batch 検証の有意性について検討する. また同じ群上で Domain Test を実装し Strict Batch Verification の有意性についても考察する . また 61 bit OEF のような高速実装技術を出来るだけ使って , Batch 検証や電子投票のようなプロトコルが , 現時点でどのレベルの規模まで実現可能か検討する.

1. [Checking Q = kP.][2002/15a-1_1475.pdf]
  Tetsutaro Kobayashi and Fumitaka Hoshino.
  SCIS 2002 Proceedings 15a-1, pp.1057-1059<br>
  Q = kP を kP を計算せずに検証する方法を提案する. また Q= k1 P1 + k2 P2 あるいは　Q = Σki Pi を検証する方法も提案する. これらの方法は特定の群に依存しないので, 検証関数を使うほとんどすべての離散対数に基づくシステムで利用可能である. これらの方法は検証を従来のシステムよりおよそ2倍高速化する.

1. [A High-speed Verification Method for Mix-net Using Pre-computations.][2002/14a-2_1447.pdf]
  Koji Chida and Fumitaka Hoshino.
  SCIS 2002 Proceedings 14a-2, pp.1000-1005<br>
  本論文ではネットワーク上で匿名を実現する Mix-net について，正当性が第三者に対しても検証可能な一方式を提案する．従来このような研究は，電子投票などのアプリケーションに利用可能なことから，様々な形で高速化が検討されているが，特に最近 CRYPTO'01 で古川，佐古により報告された方式は，証明が完全でないことが指摘されているものの，従来の O (m n log n) に対して O (m n) で実現されることから注目を集めている（m: サーバ数， n: ユーザ数）．本論文で示す提案法は，選挙のように予めおおよそのユーザ数が与えられ，証明者と検証者が事前処理できる場合に特に有効であり，その場合事前処理を除いた実処理は証明検証合わせてべき乗演算約11 m n となる．これは古川らの約 18 m n よりも効率が良い．また本論文では提案法の安全性が Decision Diffie-Hellman 問題に帰着できることを証明し，更に提案法の処理演算に， ICICS'01 で青木らにより報告された楕円暗号の高速化技法と， SCIS 2002 で星野，阿部により報告された高速一括処理技法を用いることで， Mix-net を用いた電子投票がどれだけのユーザ数に対して適用できるか実装により確認する．

1. [Electronic Voting System with MIX-net using Elliptic Curve.][2002/14a-1_1474.pdf]
  Hiroyuki Kito, Fumitaka Hoshino, and Koji Chida.
  SCIS 2002 Proceedings 14a-1, pp.994-999<br>
  電子投票システムでは、処理の正当性と匿名性の両立が必要になるため、全体検証可能な MIX-netが有用な技術となる。しかし一般に全体検証可能 MIX-net は処理が重く、実用化が困難であった。そこで本稿では、入力暗号文に依存しない べき乗演算を開票開始前に行ない、さらに MIX サーバの処理を並列化する方式を提案する。 これにより、 MIX サーバの台数によらず、 開票開始から2 (N log N - N + 1) 回のべき乗演算の時間で、全 MIX サーバの証明生成処理を完了することができる。また、 OEF を用いた楕円暗号実装技術による実装評価も行なう。

1. [A Cyclic Window Algorithm for ECC Defined over Extension Fields.][2001/3-540-45600-7_8.pdf]
  Kazumaro Aoki, Fumitaka Hoshino, and Tetsutaro Kobayashi.
  ICICS 2001 Proceedings, LNCS 2229, pp.62-73.<br>
  最適拡大体のような, フロベニウス写像が高速な拡大体上定義された楕円曲線に適した、新しいスライディングウインドウアルゴリズムを提案する.OEF上の楕円スカラー倍に関しては, PKC2000で報告されたLim-Hwangの結果が従来は最速であったが, このアルゴリズムはLim-Hwangの結果から楕円曲線上の群演算をおよそ15% 削減する.実装の結果,スカラー倍はPentium II (450 MHz), 21164A (500 MHz), and 21264 (500 MHz)の計算機上でそれぞれ 573 μs, 595 μs, and 254 μs を達成した.

1. [Lenient/Strict Batch Verification in Several Groups.][2001/3-540-45439-X_6.pdf]
  Fumitaka Hoshino, Masayuki Abe, and Tetsutaro Kobayashi.
  ISC 2001 Proceedings, LNCS 2200, pp.81-94.<br>
  一括検証は暗号学的な大量の等式を同時に全て検証する為の便利な道具である. 特に法指数演算に基づく述語を検証する時に効果が大きい. しかしながら, 場合によっては, 一括検証が等式をまとめて判定する時, 正しいと判定するにも関わらず, 実際には幾つかの等式が正しくない事がある. 実は, そのような判定の緩さは, あらかじめ等式の要素の定義域をチェックする事によって排除する事ができる. この事実を念頭に, 本論文では厳密一括検証の概念を導入し, 厳密一括検証が等式を個別に検証するよりも、やはり効率的であるか否かを調査した. 様々なタイプの群上の厳密一括検証の効率を見積もり, 群とパラメータの選択に依存して, 効率が大きく変化する事が示された.

1. [Elliptic Curve Arithmetic Using SIMD.][2001/3-540-45439-X_16.pdf]
  Kazumaro Aoki, Fumitaka Hoshino, Tetsutaro Kobayashi, and Hiroaki Oguro.
  ISC 2001 Proceedings, LNCS 2200, pp.235-247.<br>
  多くの署名や暗号文を処理するサーバ向けソフトウェアに焦点を当てて, 本論文では, 楕円曲線上のスカラー倍演算の速度を大幅に向上するSIMDを使った並列計算向けの2つのテクニックを提案する. そして, SIMDアーキテクチャを持つ Pentium III 上の実装に基づき評価を行った. 結果として提案法はSIMDを使わない方法と比較して4.4倍高速となった.

1. [Remarks on Mix-Network Based on Permutation Networks.][2001/3-540-44586-2_23.pdf]
  Masayuki Abe and Fumitaka Hoshino.
  PKC 2001 Proceedings, LNCS 1992, pp.317-324.<br>
  置換ネットワークに基づくMix-netの安全性と効率の問題に焦点を当てる.このMix-netの元々の構成が, 偏りのある置換を生むMix-netとなり, 従って攻撃者に何らかの優位性を与える事を示す. そして簡単な改善法を与える.この改善によって, 元の方式が改善され, サーバと検証者の計算量と通信料が効率化される.

1. [Cryptanalysis of the Finite State - Chaotic Encryption System.][2001/chaos.pdf]
  Fumitaka Hoshino.
  SCIS 2001 Proceedings pp.151-152<br>
  カオスを用いたブロック暗号が幾つか発表されている.本論文では, 差分攻撃に耐え得るカオス暗号とされるFS-CES に対して暗号学的な解析を行い, FS-CES が差分攻撃ではない他の攻撃に対しては脆弱であることを示す.

1. [Software Implementation of Parallel Elliptic Curve Cryptosystem.][2001/parallel.pdf]
  Tetsutaro Kobayashi, Kazumaro Aoki, Fumitaka Hoshino, and Hiroaki Oguro.
  SCIS 2001 Proceedings pp.299-303<br>
  GF(2^m)上の楕円スカラー倍のビットスライス実装法を提案する. この方法はソフトウェア実装に適している. 並列計算の数はCPUのワードサイズ(例えば 32, 64 など) である. この方法を用いるとビット毎の演算が効率的に実行できる. 理論的には従来の実装よりおよそ2倍高速化できる. 本論文では理論的効率およびビットスライス法および従来の方法のPentium III PC上の実装について議論する.

1. [Electronic Voting Schemes using MIX-net.][2000/NTT_R_and_D.pdf]
  Masayuki Abe, Atsushi Fujioka, Fumitaka Hoshino, Miyako Ohkubo, and Koutarou Suzuki.
  NTT R&D, 49(11), 2000 pp.685-693<br>
  本論文では, 電子投票方式において匿名性を保つために重要な役割を果たすMIX-netについて概説し, それを用いた電子投票方式について述べる. MIX-net については, 長さ不変性を満たす MIX-net と, 全体検証可能性を満たす MIX-net を提案する. また, 投票の買収・脅迫を防止するために重要な無証拠性について概説し, これを実現する電子投票方式を提案する.

1. [OEF Using a Successive Extension.][2000/scis2000b02.pdf]
  Tetsutaro Kobayashi, Kazumaro Aoki, and Fumitaka Hoshino.
  SCIS 2000 Proceedings B02<br>
  新しいOEFのクラスを提案する.このOEFは逐次拡大を使って構成される. 本論文の解析によればこのOEF上の逆元アルゴリズムはGF(p^m)乗算1.5回分とGF(p)逆元1回分の計算コストしか要しない.一方Bailey および Paar のアルゴリズムGF(p^m) 乗算3回分とGF(p)逆元1回分を要する.

1. [The Fastest ECC Implementations.][2000/scis2000b05.pdf]
  Kazumaro Aoki, Tetsutaro Kobayashi, and Fumitaka Hoshino.
  SCIS 2000 Proceedings B05,<br>
  本論文では, 次数2の多項式用Karatsuba-Ofman 乗算を最適化し, 結果をGF(p^3)-型OEFに適用した. 結果として21164A(500MHz)上で816μ秒の楕円暗号化実現した. この結果は PKC2000で提示されたLim-Hwangの結果よりおよそ6% 高速である. また提案アルゴリズムは 21264(500MHz)上では354μ秒の楕円暗号化実現した. さらに本論文では並列乗算を使った楕円曲線アルゴリズムを提案する. このアルゴリズムはIntel の MMX テクノロジーに良く適合しGF(p^13)-型OEFに適用された. 結果としてLim-Hwangの結果より楕円加算と楕円スカラー倍が14%高速化した.

1. [An Electronic Voting Scheme with Revocable Threshold Blind Signatures.][2000/scis2000b25.pdf]
  Masayuki Abe, Miyako Ohkubo, Atsushi Fujioka, and Fumitaka Hoshino.
  SCIS 2000 Proceedings B25<br>
  本論文では物理的な匿名通信路を排除する為, (必ずしも検証可能ではない) 単純なMix-netと追跡可能ブラインド署名を用いて電子投票方式を構成した.提案方式は半数より少ないmix-サーバのメモリイメージを入手可能で最大 n 人中の n-2 人の投票者を操作できる攻撃者に耐性を持つ.

1. [More efficient mix-network on permutation networks.][2000/scis2000b28.pdf]
  Fumitaka Hoshino and Masayuki Abe.
  SCIS 2000 Proceedings　B28<br>
  阿部が提案した,小中規模無記名電子投票向きUniversally Verifiable Mix-net の 2 つの構成法 (1-pass 方式 と2-pass 方式)の,それぞれの利点を継承する方式を提案する. 新しい方式は従来同様,検証性, 匿名性, 頑健性などの安全性の要件を満たしている. さらに新しい方法は阿部の 2-pass 方式と計算量的に同等でありながら, 1-pass を実現している. 本論文ではさらに演算方法の検討も行い,現実的にどこまで速くプロトコルを実行できるか追求する.

1. [An Implementation and an Experiment of a Practical and Secure Voting Scheme.][2000/scis2000c48.pdf]
  Atsushi Fujioka, Masayuki Abe, Miyako Ohkubo, and Fumitaka Hoshino.
  SCIS 2000 Proceedings　C48<br>
  最近, 世界中で試験的に実装されている電子投票方式 (FOO方式) の投票者の利便性 (非待機時) を向上させた方式を紹介し, その実装 (および公開実験) について述べる. この方式では, 開票者を複数おき, 投票内容を開票者が分散復号可能な閾値暗号で暗号化することにより, 公平性と非待機性を両立させている. また, この方式の実装を試み, 方式全体の評価や実用性についての検討を行い, 今後予定している公開実験について述べる.

1. [Fast Elliptic Curve Algorithm Combining Frobenius Map and Table Reference to Adapt to Higher Characteristic.][1999/3-540-48910-X_13.pdf]
  Tetsutaro Kobayashi, Hikaru Morita, Kunio Kobayashi, and Fumitaka Hoshino.
  EUROCRYPT99 Proceedings, LNCS 1592, pp.176-189.<br>
  新しい楕円スカラー倍アルゴリズムを提案する.フロベニウス写像とφ進展開に基づくテーブル参照法を組み合わせる事により、本アルゴリズムは従来の最適拡大体(OEF)に基づくアルゴリズムと比較して、およそ２倍高速となった. さらに、このアルゴリズムは 16,32,および64bit といった良く使用される計算単位に適しており, その定義体 GF(p^m) はソフトウェア実装においては素体あるいは2の拡大体よりも効率が良い事が期待できる.

1. [Elliptic Curve Algorithm on OEF with Frobenius Map.][1999/scis1999.pdf]
  Tetsutaro Kobayashi, Kazumaro Aoki, Hikaru Morita, Kunio Kobayashi, and Fumitaka Hoshino.
  SCIS 99 Proceedings pp.289-292<br>
  新しい楕円スカラー倍アルゴリズムを提案する.フロベニウス写像とφ進展開に基づくテーブル参照法を組み合わせる事により、本アルゴリズムは従来の最適拡大体(OEF)に基づくアルゴリズムと比較して、およそ２倍高速となった. さらに、このアルゴリズムは 16,32,および64bit といった良く使用される計算単位に適しており, その定義体 GF(p^m) はソフトウェア実装においては素体あるいは2の拡大体よりも効率が良い事が期待できる. 提案アルゴリズムの効率を明らかにする為, 本論文では実装結果を報告する。

1. [Spherical cavity-mode laser with self-organized CuCl microspheres.][1997/ol-22-21-1630.pdf]
  Masaya Nagai, Fumitaka Hoshino, Susumu Yamamoto, Ryo Shimano, and Makoto Kuwata-Gonokami.
  Optics Letters, 22(21):1630-1632.<br>
  低温におけるサブピコ秒紫外レーザ励起の下での半導体微小球中の励起子ポラリトンの球空洞モードレーザ発振を報告する. CuCl の小さいバルク結晶を溶融し、直径数～数十マイクロメータの溶融微小球を形成した.レーザ発信の閾値は 1nJ/pulse で, これは109光子/pulse に相当する. レーザ励起に応答して双励起子から縦波励起子への遷移が起こるする事を発見した.

[2022/1A4-1]:2022/1A4-1.pdf
[2021/scis2021]:2021/scis2021.pdf
[2020/scis2020]:2020/scis2020.pdf
[2019/IPSJCSS2019216]:2019/IPSJCSS2019216.pdf
[2019/E102.A_1285.pdf]:2019/E102.A_1285.pdf
[2019/thesis.pdf]:2019/thesis.pdf
[2019/e102-a_1_251.pdf]:2019/e102-a_1_251.pdf
[2019/1B2-1.pdf]:2019/1B2-1.pdf
[2019/4A2-2.pdf]:2019/4A2-2.pdf
[2018/1B1-3.pdf]:2018/1B1-3.pdf
[2018/3A3-4.pdf]:2018/3A3-4.pdf
[2018/3A2-1.pdf]:2018/3A2-1.pdf
[2017/1B1-4.pdf]:2017/1B1-4.pdf
[2016/ICSS2016-39.pdf]:2016/ICSS2016-39.pdf
[2016/ISEC2016-73.pdf]:2016/ISEC2016-73.pdf
[2016/978-3-662-53015-3_14.pdf]:2016/978-3-662-53015-3_14.pdf
[2016/2D1-1.pdf]:2016/2D1-1.pdf
[2015/1F2-4.pdf]:2015/1F2-4.pdf
[2015/3F2-2.pdf]:2015/3F2-2.pdf
[2014/2B3-4.pdf]:2014/2B3-4.pdf
[2013/e96-a_6_1139.pdf]:2013/e96-a_6_1139.pdf
[2013/4F1-1.pdf]:2013/4F1-1.pdf
[2013/4F1-3.pdf]:2013/4F1-3.pdf
[2013/3E1-2.pdf]:2013/3E1-2.pdf
[2012/ntttechnical.pdf]:2012/ntttechnical.pdf
[2012/1A1-5.pdf]:2012/1A1-5.pdf
[2012/1B1-3.pdf]:2012/1B1-3.pdf
[2012/1D2-3.pdf]:2012/1D2-3.pdf
[2012/1A1-2.pdf]:2012/1A1-2.pdf
[2011/2A4-1.pdf]:2011/2A4-1.pdf
[2010/978-3-642-17455-1_5.pdf]:2010/978-3-642-17455-1_5.pdf
[2010/3A1-1-b.pdf]:2010/3A1-1-b.pdf
[2009/cryptrec-rp-2000-2009.pdf]:2009/cryptrec-rp-2000-2009.pdf
[2009/978-3-642-10433-6_35.pdf]:2009/978-3-642-10433-6_35.pdf
[2009/3B4-1.PDF]:2009/3B4-1.PDF
[2008/cryptrec-rp-2000-2008.pdf]:2008/cryptrec-rp-2000-2008.pdf
[2008/178_b.pdf]:2008/178_b.pdf
[2008/416_b.pdf]:2008/416_b.pdf
[2008/403_b.pdf]:2008/403_b.pdf
[2007/2007-463.pdf]:2007/2007-463.pdf
[2007/2B4-2.pdf]:2007/2B4-2.pdf
[2007/4A1-1.pdf]:2007/4A1-1.pdf
[2007/2E3-3.pdf]:2007/2E3-3.pdf
[2006/Hoshino2006_Chapter_CompressedJacobianCoordinatesF.pdf]:2006/Hoshino2006_Chapter_CompressedJacobianCoordinatesF.pdf
[2006/e89-a_1_144.pdf]:2006/e89-a_1_144.pdf
[2006/1A3-5.pdf]:2006/1A3-5.pdf
[2005/3D4-3.pdf]:2005/3D4-3.pdf
[2005/echise2005-s02-PrivacyEnhancedActiveRFIDTag-Kinoshita+etal.pdf]:2005/echise2005-s02-PrivacyEnhancedActiveRFIDTag-Kinoshita+etal.pdf
[2004/2B-3.pdf]:2004/2B-3.pdf
[2004/IPSJ-JNL4508022.pdf]:2004/IPSJ-JNL4508022.pdf
[2004/e87-a_5_1203.pdf]:2004/e87-a_5_1203.pdf
[2003/ISEC2003.pdf]:2003/ISEC2003.pdf
[2003/None_KEI-AUTOID-WH004.pdf]:2003/None_KEI-AUTOID-WH004.pdf
[2003/78.pdf]:2003/78.pdf
[2003/e86-a_1_121.pdf]:2003/e86-a_1_121.pdf
[2003/e86-a_1_64.pdf]:2003/e86-a_1_64.pdf
[2003/15C-3.pdf]:2003/15C-3.pdf
[2003/7D-1.pdf]:2003/7D-1.pdf
[2002/3a-1_1483.pdf]:2002/3a-1_1483.pdf
[2002/15a-1_1475.pdf]:2002/15a-1_1475.pdf
[2002/14a-2_1447.pdf]:2002/14a-2_1447.pdf
[2002/14a-1_1474.pdf]:2002/14a-1_1474.pdf
[2001/3-540-45600-7_8.pdf]:2001/3-540-45600-7_8.pdf
[2001/3-540-45439-X_6.pdf]:2001/3-540-45439-X_6.pdf
[2001/3-540-45439-X_16.pdf]:2001/3-540-45439-X_16.pdf
[2001/3-540-44586-2_23.pdf]:2001/3-540-44586-2_23.pdf
[2001/chaos.pdf]:2001/chaos.pdf
[2001/parallel.pdf]:2001/parallel.pdf
[2000/NTT_R_and_D.pdf]:2000/NTT_R_and_D.pdf
[2000/scis2000b02.pdf]:2000/scis2000b02.pdf
[2000/scis2000b05.pdf]:2000/scis2000b05.pdf
[2000/scis2000b25.pdf]:2000/scis2000b25.pdf
[2000/scis2000b28.pdf]:2000/scis2000b28.pdf
[2000/scis2000c48.pdf]:2000/scis2000c48.pdf
[1999/3-540-48910-X_13.pdf]:1999/3-540-48910-X_13.pdf
[1999/scis1999.pdf]:1999/scis1999.pdf
[1997/ol-22-21-1630.pdf]:1997/ol-22-21-1630.pdf
