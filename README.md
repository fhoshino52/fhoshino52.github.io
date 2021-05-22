|リンク          |説明                                                |
|:--------------:|:--------------------------------------------------:|
|[表紙][this]    |このページ                                          |
|[github][gitrep]|github repository                                   |

[this]:https://fhoshino52.github.io/
[gitrep]:https://github.com/fhoshino52/fhoshino52.github.io

|タイトル|著者|書誌情報|概要           |
|:------:|:--:|:------:|:-------------:|
|Spherical cavity-mode laser with self-organized CuCl microspheres.|Masaya Nagai, Fumitaka Hoshino, Susumu Yamamoto, Ryo Shimano, and Makoto Kuwata-Gonokami.|Optics Letters, 22(21):1630–1632.|低温におけるサブピコ秒紫外レーザ励起の下での半導体微小球中の励起子ポラリトンの球空洞モードレーザ発振を報告する. CuCl の小さいバルク結晶を溶融し、直径数～数十マイクロメータの溶融微小球を形成した.レーザ発信の閾値は 1nJ/pulse で, これは109光子/pulse に相当する. レーザ励起に応答して双励起子から縦波励起子への遷移が起こるする事を発見した.|
|Elliptic Curve Algorithm on OEF with Frobenius Map.|Tetsutaro Kobayashi, Kazumaro Aoki, Hikaru Morita, Kunio Kobayashi, and Fumitaka Hoshino.|SCIS 99 Proceedings pp.289-292|新しい楕円スカラー倍アルゴリズムを提案する.フロベニウス写像とφ進展開に基づくテーブル参照法を組み合わせる事により、本アルゴリズムは従来の最適拡大体(OEF)に基づくアルゴリズムと比較して、およそ２倍高速となった. さらに、このアルゴリズムは 16,32,および64bit といった良く使用される計算単位に適しており, その定義体 GF(p^m) はソフトウェア実装においては素体あるいは2の拡大体よりも効率が良い事が期待できる. 提案アルゴリズムの効率を明らかにする為, 本論文では実装結果を報告する。|
|Fast Elliptic Curve Algorithm Combining Frobenius Map and Table Reference to Adapt to Higher Characteristic.|Tetsutaro Kobayashi, Hikaru Morita, Kunio Kobayashi, and Fumitaka Hoshino.|EUROCRYPT99 Proceedings, LNCS 1592, pp.176-189.|新しい楕円スカラー倍アルゴリズムを提案する.フロベニウス写像とφ進展開に基づくテーブル参照法を組み合わせる事により、本アルゴリズムは従来の最適拡大体(OEF)に基づくアルゴリズムと比較して、およそ２倍高速となった. さらに、このアルゴリズムは 16,32,および64bit といった良く使用される計算単位に適しており, その定義体 GF(p^m) はソフトウェア実装においては素体あるいは2の拡大体よりも効率が良い事が期待できる.|

4.	An Implementation and an Experiment of a Practical and Secure Voting Scheme.
（実用的な電子投票方式の実装および実験）	共著	平成12年
1月	SCIS 2000 Proceedings　C48	最近, 世界中で試験的に実装されている電子投票方式 (FOO方式) の投票者の利便性 (非待機時) を向上させた方式を紹介し, その実装 (および公開実験) について述べる. この方式では, 開票者を複数おき, 投票内容を開票者が分散復号可能な閾値暗号で暗号化することにより, 公平性と非待機性を両立させている. また, この方式の実装を試み, 方式全体の評価や実用性についての検討を行い, 今後予定している公開実験について述べる.

共著者：Atsushi Fujioka, Masayuki Abe, Miyako Ohkubo, and Fumitaka Hoshino.

5.	More efficient mix-network on permutation networks.
(Permutation Network を利用したより効率的な Mix-net)	共著	平成12年
1月	SCIS 2000 Proceedings　B28	阿部が提案した,小中規模無記名電子投票向きUniversally Verifiable Mix-net の 2 つの構成法 (1-pass 方式 と2-pass 方式)の,それぞれの利点を継承する方式を提案する. 新しい方式は従来同様,検証性, 匿名性, 頑健性などの安全性の要件を満たしている. さらに新しい方法は阿部の 2-pass 方式と計算量的に同等でありながら, 1-pass を実現している. 本論文ではさらに演算方法の検討も行い,現実的にどこまで速くプロトコルを実行できるか追求する.

共著者：Fumitaka Hoshino and Masayuki Abe.
6.	An Electronic Voting Scheme with Revocable Threshold Blind Signatures.
（追跡可能ブラインド署名に基づく電子投票方式）	共著	平成12年
1月	SCIS 2000 Proceedings B25	本論文では物理的な匿名通信路を排除する為, (必ずしも検証可能ではない) 単純なMix-netと追跡可能ブラインド署名を用いて電子投票方式を構成した.提案方式は半数より少ないmix-サーバのメモリイメージを入手可能で最大 n 人中の n-2 人の投票者を操作できる攻撃者に耐性を持つ.

共著者：Masayuki Abe, Miyako Ohkubo, Atsushi Fujioka, and Fumitaka Hoshino.

7.	The Fastest ECC Implementations.
(楕円曲線暗号の最高速実装)	共著	平成12年
1月	SCIS 2000 Proceedings B05,	本論文では, 次数2の多項式用Karatsuba-Ofman 乗算を最適化し, 結果をGF(p^3)-型OEFに適用した. 結果として21164A(500MHz)上で816μ秒の楕円暗号化実現した. この結果は PKC2000で提示されたLim-Hwangの結果よりおよそ6% 高速である. また提案アルゴリズムは 21264(500MHz)上では354μ秒の楕円暗号化実現した. さらに本論文では並列乗算を使った楕円曲線アルゴリズムを提案する. このアルゴリズムはIntel の MMX テクノロジーに良く適合しGF(p^13)-型OEFに適用された. 結果としてLim-Hwangの結果より楕円加算と楕円スカラー倍が14%高速化した.

本人担当部分：実装および計算機実験
特筆すべき貢献：21164A 及び 21264上で本アルゴリズムのソフトウェア実装を行い, スカラー倍演算の最速記録を更新した.
共著者：Kazumaro Aoki, Tetsutaro Kobayashi, and Fumitaka Hoshino.

8.	OEF Using a Successive Extension.
(逐次拡大OEF)	共著	平成12年
1月	SCIS 2000 Proceedings B02	新しいOEFのクラスを提案する.このOEFは逐次拡大を使って構成される. 本論文の解析によればこのOEF上の逆元アルゴリズムはGF(p^m)乗算1.5回分とGF(p)逆元1回分の計算コストしか要しない.一方Bailey および Paar のアルゴリズムGF(p^m) 乗算3回分とGF(p)逆元1回分を要する.

共著者：Tetsutaro Kobayashi, Kazumaro Aoki, and Fumitaka Hoshino.

9.	Electronic Voting Schemes using MIX-net.
(MIX-netを用いた電子投票)	共著	平成12年
11月	NTT R&D, 49(11), 2000
pp.685-693	本論文では, 電子投票方式において匿名性を保つために重要な役割を果たすMIX-netについて概説し, それを用いた電子投票方式について述べる. MIX-net については, 長さ不変性を満たす MIX-net と, 全体検証可能性を満たす MIX-net を提案する. また, 投票の買収・脅迫を防止するために重要な無証拠性について概説し, これを実現する電子投票方式を提案する.

共著者：Masayuki Abe, Atsushi Fujioka, Fumitaka Hoshino, Miyako Ohkubo, and Koutarou Suzuki.

10.	Software Implementation of Parallel Elliptic Curve Cryptosystem.
(楕円曲線暗号のソフトウェア並列実装)	共著	平成13年
1月
	SCIS 2001 Proceedings
pp.299-303	GF(2^m)上の楕円スカラー倍のビットスライス実装法を提案する. この方法はソフトウェア実装に適している. 並列計算の数はCPUのワードサイズ(例えば 32, 64 など) である. この方法を用いるとビット毎の演算が効率的に実行できる. 理論的には従来の実装よりおよそ2倍高速化できる. 本論文では理論的効率およびビットスライス法および従来の方法のPentium III PC上の実装について議論する.

本人担当部分：暗号実装の専門家として本研究の
理論の一部を担当し、条件分岐をSIMD上で実行する、核心的アイディアを与え、論文が抱えていた問題を解決した。 
共著者：Tetsutaro Kobayashi, Kazumaro Aoki, Fumitaka Hoshino, and Hiroaki Oguro.

11.	Cryptanalysis of the Finite State - Chaotic Encryption System.
(有限状態カオス暗号系の暗号解析)	単著
	平成13年
1月
	SCIS 2001 Proceedings
pp.151-152	カオスを用いたブロック暗号が幾つか発表されている.本論文では, 差分攻撃に耐え得るカオス暗号とされるFS-CES に対して暗号学的な解析を行い, FS-CES が差分攻撃ではない他の攻撃に対しては脆弱であることを示す.

12.	Remarks on Mix-Network Based on Permutation Networks.
(Permutation Network に基づく Mix-net に関する注意)
(査読付)	共著
	平成13年
2月
	PKC 2001 Proceedings, LNCS 1992, pp.317-324.	置換ネットワークに基づくMix-netの安全性と効率の問題に焦点を当てる.このMix-netの元々の構成が, 偏りのある置換を生むMix-netとなり, 従って攻撃者に何らかの優位性を与える事を示す. そして簡単な改善法を与える.この改善によって, 元の方式が改善され, サーバと検証者の計算量と通信料が効率化される.

本人担当部分：暗号実装の専門家として本研究の
理論の一部を担当し、元の方式を改善するアイディアを与えた。 
共著者：Masayuki Abe and Fumitaka Hoshino.
13.	Elliptic Curve Arithmetic Using SIMD.
(SIMDを使った楕円曲線算術)
(査読付)	共著
	平成13年
10月
	ISC 2001 Proceedings, LNCS 2200, pp.235-247.
	多くの署名や暗号文を処理するサーバ向けソフトウェアに焦点を当てて, 本論文では, 楕円曲線上のスカラー倍演算の速度を大幅に向上するSIMDを使った並列計算向けの2つのテクニックを提案する. そして, SIMDアーキテクチャを持つ Pentium III 上の実装に基づき評価を行った. 結果として提案法はSIMDを使わない方法と比較して4.4倍高速となった.

本人担当部分：暗号実装の専門家として本研究の
理論の一部を担当し、条件分岐をSIMD上で実行する、核心的アイディアを与え、論文が抱えていた問題を解決した。 
共著者：Kazumaro Aoki, Fumitaka Hoshino, Tetsutaro Kobayashi, and Hiroaki Oguro.
14.	Lenient/Strict Batch Verification in Several Groups. 
(幾つかの群における寛容/厳密一括検証)
(査読付)	共著
	平成13年
10月
	ISC 2001 Proceedings, LNCS 2200, pp.81-94.
	一括検証は暗号学的な大量の等式を同時に全て検証する為の便利な道具である. 特に法指数演算に基づく述語を検証する時に効果が大きい. しかしながら, 場合によっては, 一括検証が等式をまとめて判定する時, 正しいと判定するにも関わらず, 実際には幾つかの等式が正しくない事がある. 実は, そのような判定の緩さは, あらかじめ等式の要素の定義域をチェックする事によって排除する事ができる. この事実を念頭に, 本論文では厳密一括検証の概念を導入し, 厳密一括検証が等式を個別に検証するよりも、やはり効率的であるか否かを調査した. 様々なタイプの群上の厳密一括検証の効率を
見積もり, 群とパラメータの選択に依存して, 効率が大きく変化する事が示された.

本人担当部分：理論、システム全体の設計、実装、実験、論文執筆、責任著者
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆した。
共著者：Fumitaka Hoshino, Masayuki Abe, and Tetsutaro Kobayashi.

15.	A Cyclic Window Algorithm for ECC Defined over Extension Fields. 
(OEF上の楕円曲線の為の巡回ウインドウアルゴリズム)
(査読付)	共著
	平成13年
11月
	ICICS 2001 Proceedings, LNCS 2229, pp.62-73.
	最適拡大体のような, フロベニウス写像が高速な拡大体上定義された楕円曲線に適した、新しいスライディングウインドウアルゴリズムを提案する.OEF上の楕円スカラー倍に関しては, PKC2000で報告されたLim-Hwangの結果が従来は最速であったが, このアルゴリズムはLim-Hwangの結果から楕円曲線上の群演算をおよそ15% 削減する.実装の結果,スカラー倍はPentium II (450 MHz), 21164A (500 MHz), and 21264 (500 MHz)の計算機上でそれぞれ 573 μs, 595 μs, and 254 μs を達成した.

本人担当部分：実装および計算機実験
特筆すべき貢献：21164A 及び 21264上で本アルゴリズムのソフトウェア実装を行い, スカラー倍演算の最速記録を更新した.
共著者：Kazumaro Aoki, Fumitaka Hoshino, and Tetsutaro Kobayashi.

16.	Electronic Voting System with MIX-net using Elliptic Curve
(楕円暗号による MIX-net を用いた実用的な電子投票システム)	共著	平成14年
1月
	SCIS 2002 Proceedings 14a-1, pp.994-999
	電子投票システムでは、処理の正当性と匿名性の両立が必要になるため、全体検証可能な MIX-netが有用な技術となる。しかし一般に全体検証可能 MIX-net は処理が重く、実用化が困難であった。そこで本稿では、入力暗号文に依存しない べき乗演算を開票開始前に行ない、さらに MIX サーバの処理を並列化する方式を提案する。 これにより、 MIX サーバの台数によらず、 開票開始から2 (N log N - N + 1) 回のべき乗演算の時間で、全 MIX サーバの証明生成処理を完了することができる。また、 OEF を用いた楕円暗号実装技術による実装評価も行なう。

共著者：Hiroyuki Kito, Fumitaka Hoshino, and Koji Chida.

17.	A High-speed Verification Method for Mix-net Using Pre-computations.
(事前処理を仮定した Mix-net の高速検証方式)	共著	平成14年
1月
	SCIS 2002 Proceedings 14a-2, pp.1000-1005
	本論文ではネットワーク上で匿名を実現する Mix-net について，正当性が第三者に対しても検証可能な一方式を提案する．従来このような研究は，電子投票などのアプリケーションに利用可能なことから，様々な形で高速化が検討されているが，特に最近 CRYPTO'01 で古川，佐古により報告された方式は，証明が完全でないことが指摘されているものの，従来の O (m n log n) に対して O (m n) で実現されることから注目を集めている（m: サーバ数， n: ユーザ数）．本論文で示す提案法は，選挙のように予めおおよそのユーザ数が与えられ，証明者と検証者が事前処理できる場合に特に有効であり，その場合事前処理を除いた実処理は証明検証合わせてべき乗演算約11 m n となる．これは古川らの約 18 m n よりも効率が良い．また本論文では提案法の安全性が Decision Diffie-Hellman 問題に帰着できることを証明し，更に提案法の処理演算に， ICICS'01 で青木らにより報告された楕円暗号の高速化技法と， SCIS 2002 で星野，阿部により報告された高速一括処理技法を用いることで， Mix-net を用いた電子投票がどれだけのユーザ数に対して適用できるか実装により確認する．

共著者：Koji Chida and Fumitaka Hoshino.

18.	Checking Q = kP.
(Q = kP の検証)	共著
	平成14年
1月
	SCIS 2002 Proceedings 15a-1, pp.1057-1059

	Q = kP を kP を計算せずに検証する方法を提案する. また Q= k1 P1 + k2 P2 あるいは　Q = Σki Pi を検証する方法も提案する. これらの方法は特定の群に依存しないので, 検証関数を使うほとんどすべての離散対数に基づくシステムで利用可能である. これらの方法は検証を従来のシステムよりおよそ2倍高速化する.

共著者：Tetsutaro Kobayashi and Fumitaka Hoshino.

19.	Batch Verification and Multiple Exponentiation Algorithm.
(Batch 検証と大規模冪乗アルゴリズムについて)	共著
	平成14年
1月
	SCIS 2002 Proceedings 3a-1, pp.53-57
	Multiple Exponentiation は署名 , ゼロ知識証明 あるいは 暗号文のような暗号アイテムの検証コストを大幅に削減する Batch 検証等を実現する為のアルゴリズムである . 本論文では現在, 楕円離散対数ベースの暗号として利用可能な最も高速なソフトウェア実装の一つである 61 bit OEF 上での Multiple Exponentiation の実装結果を報告し , Batch 検証の有意性について検討する. また同じ群上で Domain Test を実装し Strict Batch Verification の有意性についても考察する . また 61 bit OEF のような高速実装技術を出来るだけ使って , Batch 検証や電子投票のようなプロトコルが , 現時点でどのレベルの規模まで実現可能か検討する.

共著者：Fumitaka Hoshino and Masayuki Abe.
20.	Attacks on Implementations of Elliptic Curve Cryptsystems.
(楕円曲線暗号の実装攻撃)	共著
	平成15年
1月
	SCIS 2003 Proceedings 7D-1, pp.523-525
	実装環境によって公開鍵暗号を攻撃することができることが明らかとなっている。実装に依存する攻撃法のひとつに、演算時間を測定することによる攻撃法(Timing Attack)がある。本稿では、楕円曲線暗号系に対するTiming Attackについて考察する。

共著者：Tetsutaro Kobayashi, Fumitaka Hoshino, and Hideki Imai.

21.	On the Fast DL Verification.
(高速離散対数検証法について)	共著
	平成15年
1月
	SCIS 2003 Proceedings 15C-3, pp.1185-1188
	高速離散対数検証法は署名, ゼロ知識証明等の検証コストを削減するアルゴリズムである . 本論文では高速離散対数検証法の有意性について安全性と演算コストの観点から検討する .

共著者：Fumitaka Hoshino and Tetsutaro Kobayashi.

22.	Lenient/Strict Batch Verification in Several Groups.
(幾つかの群における寛容/厳密一括検証)
(査読付)	共著
	平成15年
1月
	IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E86.A(1):64-72,
	一括検証は暗号学的な大量の等式を同時に全て検証する為の便利な道具である. 特に法指数演算に基づく述語を検証する時に効果が大きい. しかしながら, 場合によっては, 一括検証が等式をまとめて判定する時, 正しいと判定するにも関わらず, 実際には幾つかの等式が正しくない事がある. 実は, そのような判定の緩さは, あらかじめ等式の要素の定義域をチェックする事によって排除する事ができる. この事実を念頭に, 本論文では厳密一括検証の概念を導入し, 厳密一括検証が等式を個別に検証するよりも、やはり効率的であるか否かを調査した. 様々なタイプの群上の厳密一括検証の効率を
見積もり, 群とパラメタの選択に依存して, 効率が大きく変化する事が示された.この論文はISC 2001 で発表された同タイトルの論文の内容に, その後の研究成果を追加して改訂した論文である.

本人担当部分：理論、システム全体の設計、実装、実験、論文執筆、責任著者
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆した。
共著者：Fumitaka Hoshino, Masayuki Abe, and Tetsutaro Kobayashi.
23.	A Cyclic Window Algorithm for Elliptic Curves over OEF. 
(OEF上の楕円曲線の為の巡回ウインドウアルゴリズム)
(査読付)	共著
	平成15年
1月
	IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E86.A(1):121-128,
	最適拡大体のような, フロベニウス写像が高速な拡大体上定義された楕円曲線に適した、新しいスライディングウインドウアルゴリズムを提案する.OEF上の楕円スカラー倍に関しては, PKC2000で報告されたLim-Hwangの結果が従来は最速であったが, このアルゴリズムはLim-Hwangの結果から楕円曲線上の群演算をおよそ15% 削減する.実装の結果,スカラー倍はPentium II (450 MHz), 21164A (500 MHz), and 21264 (500 MHz)の計算機上でそれぞれ 573 μs, 595 μs, and 254 μs を達成した. この論文はICICS 2001 で発表された同タイトルの論文の内容に, その後の研究成果を追加して改訂した論文である.

本人担当部分：実装および計算機実験
特筆すべき貢献：スライディングウインドウアルゴリズムのソフトウェア実装を行い, スカラー倍演算の最速記録を更新した.
共著者：Tetsutaro Kobayashi, Fumitaka Hoshino, and Kazumaro Aoki.

24.	Nonidentifiable Anonymous-ID Scheme for RFID Privacy Protection.
(RFID プライバシー保護を実現する可変秘匿 ID 方式)	共著
	平成15年
10月
	CSS 2003
Proceedings,	将来，到来するであろうユビキタス社会において，RFID タグはあらゆるアイテムに装着され，さまざまな応用サービスへと発展していく基盤技術として期待されている．一方では，RFID の優れた追跡能力が悪用された場合の消費者プライバシー侵害が問題視されはじめている．本論文では，漠然とした不安がもたれている RFID のプライバシー問題を整理するとともに，その普及条件として最も重要となる低コスト化を考慮した解決方式を提案する．また，将来の標準
技術として最も注目されている MIT Auto-ID システムへの適用方式もあわせて紹介する．

本人担当部分：理論
特筆すべき貢献：暗号の専門家として論文執筆に参加し、論文の核心となる可変秘匿ID方式を提案した.
共著者：Shingo Kinoshita, Fumitaka Hoshino, Tomoyuki Komuko, Akiko Fujimura, and Miyako Ohkubo.

25.	Applying Auto-ID to the Japanese Publication Business To Deliver Advanced Supply Chain Managment, Innovative Retail Applications, and Convenient and Safe Reader Services.
(高度なサプライチェーンマネジメント、革新的なリテールアプリケーション、便利で安全な読取サービスを実現する為の日本の出版ビジネスへのAuto-IDの適用)	共著
	平成15年
10月
	AUTO-ID Center white paper
	共著者：Toshiharu Ishikawa, Yukiko Yumoto, Michio Kurata, Makoto Endo, Shingo Kinoshita, Fumitaka Hoshino, Satoshi Yagi, and Masatoshi Nomachi.

26.	Non-Supersingular Elliptic Curves for Pairing-Based Cryptosystems.
(ペアリングに基づく暗号系の為の非超特異楕円曲線)
(査読付)	共著
	平成16年
5月
	IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E87.A(5):1203-1205,
	本論文では非超特異楕円曲線に基づいて, ペアリングに基づく暗号系を構成する方法を与える.

本人担当部分：理論
特筆すべき貢献：論文の核心となる暗号系を構成するアイディアを与えた。
共著者：Taiichi Saito, Fumitaka Hoshino, Shigenori Uchiyama, and Tetsutaro Kobayashi.

27.	Low-cost RFID privacy protection
(ローコストRFIDプライバシ保護方法)
(査読付)	共著
	平成16年
8月	IPSJ Journal 45, 8 (Aug. 2004), pp.2007-2021	将来，到来するであろうユビキタス社会において，RFID タグはあらゆるアイテムに装着され，さまざまな応用サービスへと発展していく基盤技術として期待されている．一方では，RFID の優れた追跡能力が悪用された場合の消費者プライバシー侵害が問題視されはじめている．本論文では，漠然とした不安がもたれている RFID のプライバシー問題を整理するとともに，その普及条件として最も重要となる低コスト化を考慮した解決方式を提案する．また，将来の標準
技術として最も注目されている MIT Auto-ID システムへの適用方式もあわせて紹介する

本人担当部分：理論
特筆すべき貢献：暗号の専門家として論文執筆に参加し、論文の核心となる可変秘匿ID方式を提案した.
共著者：Shingo Kinoshita, Fumitaka Hoshino, Miyako Ohkubo, Gembu Morohashi, Osamu Shionoiri, and Atsushi Kanai.

28.	RFID Privacy Protection Protocol for Libraries with the Unidentifiable Anonymous ID Scheme.
(可変秘匿ID方式を用いた図書館向けRFIDプライバシ保護プロトコル)	共著	平成16年
10月
	CSS 2004
Proceedings 2B-3,
	近年流通業界を中心に業務に RFID を取り入れる動きが進んでいる．一方で RFID が付随した
モノが消費者の手に渡ることから生じるプライバシの侵害が深刻な問題になっており， RFID の導入に対する障害の一因になっている．こうした問題に対し，我々はこれまでに低コストでプライバシ問題を解決する基盤技術として可変秘匿 ID 方式を開発してきた．本論文では，所有者／利用者，利用期間といった点において，いわゆる消費財と異なる特性をもつレンタル分野，特に図書館分野におけるプライバシ問題の考察するとともに，可変秘匿 ID 方式の適用プロトコルを提案する．提案プロトコルでは，可変秘匿 ID 方式のID 再暗号化方法（再暗号化を行う端末や契機）や復号方法などを図書館業務プロセスに最適となるように具体化している．また，図書館以外のレンタル分野への適用性についても考察する．

共著者：Gembu Morohashi, Shingo Kinoshita, and Fumitaka Hoshino.

29.	Privacy enhanced active RFID tag.
(プライバシ強化されたアクティブRFIDタグ)
(査読付)	共著
	平成17年
	Proc. of International Workshop on Exploiting Context Histories in Smart Environments, 2005	共著者：Shingo Kinoshita, Fumitaka Hoshino, Tomoyuki Komuko, Akiko Fujimura, and Miyako Ohkubo.

30.	Revocable DDH by using Pairing and It’s Application.
(Pairing を用いた Revocable DDH とその応用)	共著
	平成17年
1月
	SCIS 2005 Proceedings 3D4-3, pp.1394-1397
	DDH に関する witness を CDH に関する witness から分離できるような群の family である revocable DDH group を提案し , そのセキュリティについて考察する . またそのアプリケーションとして , 任意の暗号文の同一性検証が可能となる検証鍵を秘密鍵から分離出来る暗号系を提案する . また楕円曲線上の点のある同型写像の一方向性に着目し 非 trace-2 の non-supersingular 楕円曲線を用いて安
全な revocable DDH group を構成する方法を提案する .

共著者：Fumitaka Hoshino, Koutarou Suzuki, and Tetsutaro Kobayashi.

31.	Realtime Receipt Free Schnorr Identification.
(リアルタイム無証拠 Schnorr 認証)	共著
	平成18年
1月
	SCIS 2006 Proceedings 1A3-5, pp.54-58	本研究では 認証プロトコルに於いて honest な検証者と観察者を仮定しても通信記録が認証
成功の証拠とならない性質 ”リアルタイム無証拠性”の概念を提案する. さらに Schnorr 認証において リアルタイム無証拠性と 他の安全性要件である健全性が一見両立困難 なように思えるが , 使用する巡回群に構造を持ったモデルを導入するとプロトコルを変更せずに両立できる事を示す . そして 特殊な楕円曲線で生成した群の系列を用い, 使用する群の選択がプロトコルの安全性にどのような影響をあたえるか検討し, 構造を持った群でプロトコルを構成する場合, 群の安全性は DDH安全だけでは不十分である事を示す.

共著者：Fumitaka Hoshino, Tetsutaro Kobayashi, and Koutarou Suzuki.
32.	Candidate One-Way Functions on Non-Supersingular Elliptic Curves. 
(非超特異楕円曲線上の一方向関数候補)
(査読付)	共著
	平成18年1月
	IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E89.A(1):144–150,	非超特異楕円曲線上のある特別な型の自己準同型で構成された新しい一方向性関数の候補を提案する. 提案関数の一方向性はco-Diffie-Hellman 仮定のある特別な場合と同値である事が示せる.また, 本論文では提案関数を使ったデジタル署名方式を厳密に記述した.

本人担当部分：理論
特筆すべき貢献：論文の核心となる一方向性関数のアイディアを与えた。
共著者：Taiichi Saito, Fumitaka Hoshino, Shigenori Uchiyama, and Tetsutaro Kobayashi.

33.	Compressed Jacobian Coordinates for OEF. 
(OEF向き圧縮ヤコビ座標)
(査読付）	共著
	平成18年9月
	VIETCRYPT 2006 Proceedings, LNCS 4341, pp.147-156.
	最適拡大体(OEF)上の楕円加算および楕円二倍算を高速化する新しい座標系を提案する. 楕円暗号を高速化する為に沢山の座標系が提案されているが, 提案座標系はそれら従来の座標系の自然な拡張であり, 楕円曲線が OEF 上で定義されている時は新しい座標系は従来の座標系よりもずっと高速である. 本論文では q = 2^61-1, m = 5 として, 楕円曲線が GF(q^m),上で定義されている時,トータルの計算コストが28%削減される事を示した.そして2.82-GHz Athlon 64 FX PC上で楕円スカラ倍演算の速度が41.9μ秒となった事を報告する.

本人担当部分：理論、システム全体の設計、実装、実験、論文執筆、責任著者
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆した。
共著者：Fumitaka Hoshino, Tetsutaro Kobayashi, and Kazumaro Aoki.

34.	Compressed Jacobian Coordinates.
(圧縮ヤコビ座標)	共著
	平成19年1月
	SCIS 2007 Proceedings 2E3-3, pp.844-847
	VietCrypt2006 で発表された OEF 上の楕円曲線の座標、Compressed Jacobian coordinates
の一般化を行う. Compressed Jacobian coordinates は, 拡大体上で定義された楕円曲線上の点の加算・二倍算を高速に行える座標であり、特に OEF(拡大次数 5)においては従来の Jacobian coordinates よりも 28% 程度高速となり、ベースポイントの位数が 244bit の楕円曲線のスカラー倍が 41.9 µsec per operation on a 2.82-GHz Athlon 64 FX PC という速度が示されている。本稿では、 OEF 以外の楕円曲線暗号への Compressed Jacobian coordinates の適用を考察する。

共著者：Tetsutaro Kobayashi, Fumitaka Hoshino, and Kazumaro Aoki.

35.	On the Invalid Point Attack of Pairing Based Cryptography.
(ペアリングに基づく暗号の Invalid Point 攻撃に関して)	共著
	平成19年1月
	SCIS 2007 Proceedings 4A1-1, pp.1715-1719
	暗号系に不正な入力が行われた時に , 暗号系がどのような挙動を示すかは実装に強く依存する. そのため実装の詳細を抽象した暗号プロトコルに於いては , 入力は何らかの集合に収まっていると仮定し , 入力が集合に含まれなかった場合の系の挙動は捨象しがちである. Lim らは不正な入力を用いて離散対数に基づく暗号系攻撃する Small Subgroup 攻撃を提案した. また Antipa らは不正な楕円曲線上の点を用いて楕円曲線暗号系を攻撃する Invalid Curve 攻撃を提案した. 本論文ではAntipa らの Invalid Curve 攻撃を pairing に基づく暗号系 (PBC) へ拡張した Invalid Point 攻撃を考察し, pairing の型による, 対策コストの軽減を検討する.

共著者：Fumitaka Hoshino, Gen Takahashi, and Tetsutaro Kobayashi.

36.	Revocable Ring Signature using Revocable DDH Assumption.
(Revocable DDH仮定を用いたRevocableリング署名)	共著
	平成19年1月
	SCIS 2007 Proceedings 2B4-2, pp.516-521
	本論文では revocable DDH群の応用として署名者が署名生成能力から匿名性を取り消す能力を分離して委譲可能なRevocable リング署名を提案する.

共著者：Koutarou Suzuki, Fumitaka Hoshino, and Tetsutaro Kobayashi.

37.	Security consideration on the signature scheme 3IC-.
(多変数非線形方程式に基づく署名方式 3IC- の安全性解析)	共著
	平成20年1月
	SCIS 2008 Proceedings 3B1 403_b, pp.1149-1153
	2007 年に Dubois らは NESSIE で採択されたデジタル署名方式 SFLASH (C^∗−) の公開鍵
の差分をとることにより C^∗ の公開鍵を復元する方式を示し，これによって C^∗− の公開鍵が与えられれば署名を偽造できることを示した． C^∗− のほかにも，多変数非線型方程式に基づくデジタル署名方式に対して， Dubois らの用いた差分による攻撃の有効性を評価することは重要である．本稿では， 2007 年に Ding らによって提案されたデジタル署名方式 3IC- (Delta Invertible cycle) に対して，差分を用いた攻撃の有効性を評価した． 3IC- は，多変数 2 次多項式暗号 3IC の公開鍵から (C^∗− と同様に ) 幾つかの 2 次式を削除することによって構成されるデジタル署名方式であるが，本稿では， 3IC- の公開鍵の差分を取ることによって， 3IC の公開鍵を復元できることを示す．

共著者：Toshiyuki Miyazawa, Fumitaka Hoshino, and Tetutaro Kobayashi.

38.	Efficient GF(3m) Multiplication Algorithm for ηT Pairing.
(ηTペアリングの為の効率的なGF(3m)乗算アルゴリズム)	共著
	平成20年1月
	SCIS 2008 Proceedings 3D1 416_b, pp.1384-1389
	共著者：Gen Takahashi, Fumitaka Hoshino, and Tetutaro Kobayashi.

39.	A Point Compression Method for Subfield Curves.
(部分体曲線の点圧縮の方法)	共著
	平成20年1月
	SCIS 2008 Proceedings 2D3 178_b, pp.745-750
	大きな平文空間を持つ再暗号化可能な ElGamal 暗号は, 巡回群の元に直接平文を埋め込んだり, 巡回群の元から平文が容易に復元出来るような特別な性質を巡回群に要求する . 巡回群として楕円曲線を用いる場合, 曲線の位数が素数であるときは, 平文を x 座標の部分情報に埋め込み, x の残りの部分情報を適当に選んで, 楕円曲線の定義式を満たす y を見つければ十分である. しかし, 楕円曲線の位数が合成数で, コファクター c を持つような場合は上記のようにして見つけた (x,y) が目的の巡回群に載る確率はおよそ 1/c である. c が小さい場合はこの埋め込みアルゴリズムは機能するが, OEF で部分体曲線を使う場合のように曲線に大きなコファクターがあると機能しない. コファクターが大きい時は必要としている部分群のサイズに比べて点を定義するデータ (x 座標 ) のサイズが冗長なため, 部分群の点を効率的に見つけられない事が問題の本質である. 従って部分群の点を小さい情報量で表現する事 ( 即ち点圧縮 ) が可能であればこの問題は解決する . 以上の工学的動機に基づき、本稿では比較的大きい部分体で定義された楕円曲線の点圧縮の方法を提案する.

共著者：Fumitaka Hoshino and Tetsutaro Kobayashi.

40.	A Flexible Ring Signature.
(フレキシブルリング署名)	共著
	平成21年1月
	SCIS 2009 Proceedings 3B4-1, pp.1250-1255
	署名者の匿名性を守るための署名技術には大別して 2 つの方法がある. 一つは 1991年に Chaum らが提案したグループ署名の概念で, この方法にはグループ管理者と呼ばれる信頼できる第三者 (TTP) が登場する. もう一つは 2001 年に Rivest らが提案したリング署名の概念で, この方法にはグループ管理者が存在しない. 著者らは, このグループ署名とリング署名の間の中間に位置するような署名を提案している. 本論文では, この中間的な署名方式を改造して署名者がリング署名を生成した後にグループ管理者がリング署名の参加メンバーを変更したりリング署名を普通の署名に変換したりできる事を実現する.

共著者：Fumitaka Hoshino, Koutarou Suzuki, and Tetsutaro Kobayashi.

41.	Relinkable Ring Signature.
(再リンク可能リング署名) 
(査読付)	共著
	平成21年12月
	CANS 2009, Proceedings, LNCS 5888, pp.518-536.
	リングを再構成できるリング署名である再リンク可能リング署名の概念を提案する。再リンク可能リング署名を用いると、署名者はリングを再構成する能力を、署名能力から分離して代理人に付与する事ができる。定義および証明可能安全な具体的な方式を提案する。

本人担当部分：暗号プリミティブの専門家として本研究の理論の一部を担当し、リングを再構成する能力を、署名能力から分離するメカニズムの基本アイディアを提案した。
共著者：Koutarou Suzuki, Fumitaka Hoshino, and Tetsutaro Kobayashi.

42.	Message Dependently Relinkable Ring Signature.
(文書依存再リンク可能リング署名)	共著
	平成22年1月
	SCIS 2010 Proceedings 3A1-1, pp.982-987
	再リンク可能リング署名とは, 署名生成能力からリング生成能力を分離できる特殊なリング署名である. この署名を用いると, 署名者から特別な秘密(再リンク鍵)を得た第三者(代理人)が, 再リンクと呼ばれる手続きにより, 既存のリング署名からメンバーを変更したリング署名を生成する事が出来る. 本論文ではこの署名系が持つ様々な制約を緩和するため, 文書依存再リンク可能リング署名の概念を提案し, その汎用的構成の方法論を与え, 2 つの具体的方式を得た.

共著者：Fumitaka Hoshino, Koutarou Suzuki, and Tetsutaro Kobayashi.

43.	Anonymizable Signature and Its Construction from Pairings.
(匿名化可能署名とペアリングを用いたその構成) 
(査読付)	共著
	平成22年12月
	Pairing 2010 Proceedings,　LNCS 6487 pp.62-77.
	リング署名の拡張である匿名化可能署名の概念を提案する。匿名化署名を使うと、署名されたメッセージを持つ者は誰でもその署名を匿名署名に変換する事ができる。つまり署名されたメッセージを、あとで匿名化してくれる適当なエージェントに預けることが出来る。定義および簡易な構成の方法論および証明可能安全な具体的な方式を提案する。

本人担当部分：理論、論文執筆、責任著者
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆し、責任著者を務めた。
共著者： Fumitaka Hoshino, Tetsutaro Kobayashi, and Koutarou Suzuki.
44.	An Application of Functional Encryption: Verifiable Timed-Release Encryption.
(関数型暗号の応用 : 検証可能時限式暗号)	共著
	平成23年1月
	SCIS 2011 Proceedings 2A4-1, pp.474-481


	時限式暗号とは , 暗号文の正規の受信者であっても送信者が指定した開封時刻になるまで暗
号文が復号できないような特殊な暗号のことである. 本論文では開封時刻以降に時報局より放送される指数的多数の如何なる時報トークンを使用しても暗号文が復号出来る時限式暗号について考察する. そのような時限式暗号は関数型暗号を用いて容易に実現可能である. さらに本論文では上記のような時限式暗号について, 敵対的送信者に関するさまざまな問題点を研究し, 時限式暗号の拡張として検証可能時限式暗号の概念を提案する. そして敵対的送信者に関するさまざまな安全性定義をカバーできる安全性である平文拘束の定義を行う. また強秘匿の概念である IND-TR-CCA をこの設定で定義し, 平文拘束および IND-TR-CCA を実現する汎用構成戦略を考える. 最後に DLIN 仮定および強偽造不可能 One-Time署名の存在の元で, 平文拘束および IND-TR-CCA が証明できる検証可能時限式暗号の効率的実装方法を提案する.

共著者：Fumitaka Hoshino and Atsushi Fujioka.

45.	Symmetric Pairing based on Asymmetric Pairing.
(非対称ペアリングを利用した対称ペアリングの構成)	共著
	平成24年1月
	SCIS 2012 Proceedings 1A1-2, pp.5-8

	楕円曲線のペアリングを応用した ID ベース暗号の提案以来、数多くのペアリングを利用した暗号技術が提案されてきた。楕円曲線のペアリングには大きく分けて非対称ペアリングと対称ペアリングがある。近年、非対称ペアリングの典型的な例である BN 曲線上のペアリング高速実装技術の研究が進んだことと、対称ペアリングの典型的な例である超特異曲線上のペアリング向け曲線への攻撃研究が進んだことから、非対称ペアリングが主流となりつつある。一方、ペアリング利用技術の中には対称ペアリングを前提とした方式もある。このようなアルゴリズムのために、非対称ペアリングを用いて対称ペアリングを実現する研究が行われているが、従来はハッシュ値を楕円曲線上の点に変換する関数 (MapToPoint) を行うことができなかった。本稿は、非対称ペアリングを用いて対称ペアリングを実現する際に MapToPoint を行う方法を提案し、性能の評価を行う。

共著者：Tetsutaro Kobayashi, Fumitaka Hoshino, and Koutarou Suzuki.

46.	A study on id-eCK security of ID-based authenticated key exchange using asymmetric pairing.
(非対称ペアリングを用いた ID ベース認証鍵交換方式における
id-eCK 安全性の考察)	共著
	平成24年1月	SCIS 2012 Proceedings 1D2-3, pp.337-341
	ID を用いて相互認証し鍵交換を行う ID ベース認証鍵交換（ ID-based authenticated key
exchange ）に関して、非対称ペアリングを用いて ID ベース eCK （ ID-based extended Canetti-Krawczyk ）安全性を実現する方法について考察する。従来の ID ベース eCK 安全性を実現する ID ベース認証鍵交換方式は、対称ペアリングを必要としており、より効率のよい非対称ペアリングを用いて eCK 安全性を実現する方式は知られていなかった。本研究では、非対称ペアリングを用いて ID ベース eCK 安全性な ID ベース認証鍵交換方式を実現する際に問題となる点について考察し、 ID ベース eCK 安全性な ID ベース認証鍵交換方式を提案する。

共著者：Koutarou Suzuki, Atsushi Fujioka, Kazuki Yoneyama, Tetsutaro Kobayashi, and Fumitaka Hoshino.

47.	Functional Encryption: Current State of Implementation and Prospects for Practical Applications.
(関数型暗号 : 実装の現在と実用化への展望)	共著
	平成24年1月
	SCIS 2012 Proceedings 1B1-3, pp.105-112
	関数型暗号は属性ベース暗号や述語暗号を含む ID ベース暗号の一般化概念として近年活発に研究されている．本論文の前半では，関数型暗号の概念および構成について概説し，典型的な使用方法とネットワークで必要となる機構を説明する．さらに岡本らの関数型暗号を， x86 プロセッサ上で実装した結果とその評価について報告する．後半では，関数型暗号の応用に関して，どのような応用が可能か具体的に考え，加えて普及に向けて解決すべき課題について考察する．

共著者：Katsumi Takahashi, Fumitaka Hoshino, Tetsutaro Kobayashi, Go Yamamoto, Tomohide Yamamoto, Toshiyuki Miyazawa, Reo Yoshida, Hitoshi Fuji, Masatoshi Yokomori, and Akira Nagai.

48.	Application of Functional Encryption: Key-Insulated Encryption.
(関数型暗号の応用 : 鍵隔離暗号の構成)	共著
	平成24年1月
	SCIS 2012 Proceedings 1A1-5, pp.22-29

	本稿では関数型暗号を用いた鍵隔離暗号の構成について考察する. 関数型暗号とは属性ベース暗号や述語暗号を含む ID ベース暗号の一般化概念で近年活発に研究されているものである . Crypto 2010 において , 岡本らが標準的な暗号学的仮定の下, 任意の述語に関して適応的 payload-hiding な関数型暗号を提案した事により, 属性ベース暗号などの関数型暗号を他の暗号の部品として用いる事に実装上の問題はほとんど無くなった. 本稿では岡本らの関数型暗号を用いた 2 つの鍵隔離暗号の構成方法を提案する. これらの構成では鍵更新の間隔を公開鍵とは独立に設定出来るため柔軟な運用が可能となる.

共著者：Fumitaka Hoshino and Atsushi Fujioka.

49.	Cryptographic Techniques that Combine Data Protection and Ease of Utilization in the Cloud Computing Era.
(データ保護とクラウドコンピューティング時代の利用の容易さを併せ持つ暗号技術)	共著
	平成24年10月
	NTT Technical Review, 10(10), 2012. pp.26-31	共著者：Hitoshi Fuji, Atsushi Fujioka, Tetsutaro Kobayashi, Koji Chida, Fumitaka Hoshino, Toshiyuki Miyazawa, and Koutarou Suzuki.

50.	Fast Implementation of Pairing-based Cryptosystems on Android with NEON.
(NEON を利用した Android 上でのペアリング暗号の高速実装)	共著	平成25年1月
	SCIS 2013 Proceedings 3E1-2, pp.1586-1592	本稿では，高速なペアリング暗号の構成である BN 曲線上の Optimal Ate ペアリングに対して， NEON と呼ばれる ARM アーキテクチャでの SIMD 命令を利用した Android 端末上の高速実装の結果を示す．我々は， NEON を用いることで素体 Fp 上の高速な乗算アルゴリズムを構成し，ペアリングの高速化を図った．実験結果として， Android 端末上での 126-bitセキュリティ相当のペアリングの計算は約 6.77 ミリ秒となり， C による実装と比較し約 4.5 倍高速であった．また暗号システムへの応用として，本実装を関数型暗号へ適応し， Setup, Keygen, Encrypt, Decryptの計算時間を評価した．

共著者：Yuto Kawahara, Reo Yoshida, Fumitaka Hoshino, and Tetsutaro Kobayashi.

51.	Fully Secure Ciphertext-Policy Functional Encryption with O(1) Pairings.
(O(1)ペアリングのフル安全な暗号文ポリシー関数型暗号)	共著
	平成25年1月
	SCIS 2013 Proceedings 4F1-3, pp.2090-2097
	共著者：Reo Yoshida, Fumitaka Hoshino, and Tetsutaro Kobayashi.

52.	On Decentralized Multi-Authority Functional Encryption.
(分権複数局関数型暗号について)	単著	平成25年1月
	SCIS 2013 Proceedings 4F1-1, pp.2074-2081
	結託攻撃を防ぐ為 , 安全な分権複数局関数型暗号(DMA-FE)では大域検証可能識別子(GID) と呼ばれる受信者毎に固有の識別子が用いられ, 秘密鍵は必ず GID と結びつけられて発行される. 同じ GID を持つ秘密鍵は組み合わせて復号に使用する事が可能だが, 異なる GID を持つ秘密鍵は組み合わせて使用出来ないよう暗号文が構成される. ところで, 一般にある鍵生成局が単一の受信者に対して異なる属性を持つ複数の秘密鍵を発行する事がある .このような状況で, 一つの鍵生成局が 2 つ以上の属性を管理している場合を考えると単一の受信者が同じ GID の 2 つ以上の秘密鍵を持っているので結託攻撃と全く同じ攻撃が可能となる. このような鍵再発行攻撃を防ぐ為, 更新の度に異なる GID を用いると, 新たな秘密鍵は元々の GID を持つ他の鍵と組み合わせて使用する事が出来なくなってしまう. 本論文ではこの問題に対し簡易なアプローチを考察する.
53.	id-eCK Secure ID-Based Authenticated Key Exchange on Symmetric and Asymmetric Pairing.
(対称および非対称ペアリング上のid-eCK安全なIDに基づく認証鍵交換)
(査読付)	共著
	平成25年6月
	IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E96.A(6):1139–1155,	対称および非対称ペアリング上のIDに基づく認証鍵交換プロトコルを提案する。提案プロトコルは双線形Diffie-Hellman仮定の下、ランダムオラクルモデルにおけるIDに基づくCanetti-Krawczyk (id-eCK)モデルで安全である。

本人担当部分：ペアリングの専門家として論文執筆に参加し、非対称ペアリングの構造をどのように認証鍵交換に適用すべきかのアイディアを与え、研究指導を行った。
特筆すべき貢献：非対称ペアリングに関するアイディアを与え、研究指導を行った。
共著者： Atsushi Fujioka, Fumitaka Hoshino, Tetsutaro Kobayashi, Koutarou Suzuki, Berkant Ustaoglu, and Kazuki Yoneyama.

54.	A Variant of Diffie-Hellman Problem and How to Prove Independency.
(ある Diffie-Hellman 問題の変種と独立の証明法)	単著	平成26年1月
	SCIS 2014 Proceedings 2B3-4, pp.645-652
	本論文では , 楕円曲線の暗号学的な模型およびある Diffie-Hellman 問題の変種を考察し, 対称ペアリング群を使用して , 非対称ペアリング群に似た暗号プリミティブの設計を行った . 対称ペアリング群上のDLIN 仮定の下で新しい暗号プリミティブは trapdoor DDH 群の性質と XDH 群のような性質を両方満たす .
55.	Attribute based authenticate key exchange scheme.
(属性に基づく認証鍵交換方式)	共著
	平成27年1月
	SCIS 2015 Proceedings 3F2-2, pp.1766-1767
	インターネットで通信を行う際に、認証と鍵交換を行う SSL/TLS などのプロトコルが多く使われている。 従来の認証鍵交換プロトコルは、通信相手を指定してその相手とのみ鍵共
有を行うものであった。 これを拡張し、通信相手の条件を指定して条件を満たす相手と鍵共有
を行う方式を提案する。従来の ID ベース認証鍵交換方式と同様の eCK 安全性に加え、鍵共有相手の ID に関する情報を得ることがないという匿名性についての議論を行う。

共著者：Tetsutaro Kobayashi, Fumitaka Hoshino, and Koutarou Suzuki.

56.	On Barreto-Naehrig Curves.
(Barreto-Naehrig 曲線に関して)	単著	平成27年1月
	SCIS 2015 Proceedings 1F2-4, pp.345-349
	本論文では, 最も代表的な pairing-friendly 楕円曲線の一つである Barreto-Naehrig 曲線における hash to point に関して考察し、高速化の検討を行なった.

57.	Optimal Conversion from Symmetric Pairing-based Scheme to Asymmetric One.
(対称ペアリングに基づく方式から非対称ペアリングに基づく方式への最適変換)	共著
	平成28年1月
	SCIS 2016 Proceedings 2D1-1, pp.833-840
	2014年阿部らは方式の安全性を維持したままペアリングの型変換を自動実行するフレームワークを発表した. 2015 年に整数計画法を直接用いるアルゴリズムが提案されたことにより, かなり大規模な暗号方式の自動変換が可能となった (未発表). 一方 Groth-Sahai 証明などを用いて設計された大規模な方式を対称ペアリングを使って具体的に記述すると, 方式自体が証明する述語の数に対して指数的多数の変種を持ってしまう事がある. 本発表ではそのような場合でも最適な変換を見つけるアルゴリズムを提案する.

本人担当部分：理論、システム全体の設計、実装、実験、論文執筆、責任著者
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆した。
共著者： Fumitaka Hoshino, Masayuki Abe, and Miyako Ohkubo.
58.	Design in Type-I, Run in Type-III: Fast and Scalable Bilinear-Type Conversion Using Integer Programming.
(Type-Iで設計し, Type-IIIで駆動せよ: 整数計画法を用いた高速でスケーラブルな双線形型変換)
(査読付)	共著
	平成28年8月
	CRYPTO 2016 Proceedings Part III, LNCS 9816 pp 387–415.	対称ペアリング群上設計された暗号方式を，非対称ペアリング群上のなるべく効率的な方式に，安全性を損なわずに変換するアルゴリズムをペアリング型変換と呼ぶ。本論文ではIPConv と呼ばれる 0-1整数計画法を用いた新しいペアリング型変換を導入する。広く使われている IPソルバを使うと、IPConv は既存の複雑な方式を即座にペアリング型変換することができる。そうした高速で大規模化可能なペアリング型変換が使えると、対称ペアリング上の暗号方式の設計に関する新たなアプローチが可能となる。

本人担当部分：理論、システム全体の設計、実装、実験、論文執筆
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆した。その為、分野の慣例により著者順は Alphabetical Orderであるが、共著者全員から本人が筆頭であると認められている。（別紙 業績確認書 参照）
共著者： Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,

59.	Faster Bilinear-Type Conversion.
(より高速な双線型型変換)	単著
	平成29年1月
	SCIS 2017 Proceedings 1B1-4, pp.102-109
	非対称ペアリングは対称ペアリングと比較して代数的構造は複雑だが実装の効率はずっと良い. 従って, ペアリングに基づく暗号方式を構成する際， 一旦は対称ペアリング上で設計を行い，しかる後に非対称ペアリングの代数的構造に合わせ再設計し実装を得る事が多くなっている. 2016年, 阿部らは方式の安全性を維持したまま, このタスクを自動実行する効率的なアルゴリズムを発表した. 本研究ではこのアルゴリズムを簡素化して, 幾分高速化する.

60.	Dynamic Multi-Cast Key Distribution with KEM.
(KEM を用いた動的多者鍵配布プロトコル)	共著
	平成30年1月
	SCIS 2018 Proceedings 3A2-1, pp.1376-1383
	Yoneyama らは, 多人数での通信における ユーザエンドでの End-to-End 暗号化 (E2EE) を実現するために, 通信効率の良い動的多者鍵配布 (DMKD) プロトコルの具体的な方式を提案している. しかし, この DMKD プロトコルは量子コンピュータの解読に耐性のない Diffie-Hellman(DH) 鍵交換を利用している. 本研究では量子コンピュータの実用化に備え, Yoneyama らの DMKD プロトコルをモデルとした, これに耐性のあるプロトコルの構築を目的とした.本稿では二者間鍵交換を KEM で記述し, 格子暗号をはじめとしたポスト量子暗号が適用可能な DMKD プロトコルの一般的な構成を提案する.

本人担当部分：本研究の研究動機を提案し、理論の一部を担当し、筆頭著者の直接指導者として研究指導を行った。
共著者： Koha Kinjo, Yuki Okano, Tsunekazu Saito, Keita Xagawa, Tetsutaro Kobayashi, and Fumitaka Hoshino.

61.	Pseudo-Code Performance Estimation for Pairing-Based Cryptographic Schemes.
(ペアリングを用いた暗号方式の擬似コードレベルでのパフォーマンス評価)	共著
	平成30年1月
	SCIS 2018 Proceedings 3A3-4, pp.1448-1454
	高速なペアリングライブラリの実装は特定の曲線やパラメータ限られることが多く、個別の暗号方式の効率を様々な曲線やパラメータに対して実装評価することは多大な労力・コストを要する。本稿では，ペアリング群上の暗号方式の様々な曲線およびパラメータ設定におけるパフォーマンスを簡易的に評価するフレームワーク 'Opcount' を提案する。擬似コードによる暗号方式の記述と、評価対象の曲線における基本演算のパフォーマンスを記録した実装情報データベースから、その暗号方式のパフォーマンスを見積もることで、適切な曲線やパラメータの選択を可能とした。

本人担当部分：理論、システム全体の設計、実装
特筆すべき貢献：論文の核心となるアイディアを与え、研究指導を行い、論文執筆に関わった。この論文は SCIS 2018 イノベーション論文賞を受賞し、電子情報通信学会 情報セキュリティ研究会から表彰された。
共著者： Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo, 

62.	Pairing Type Optimization Problem and Its Hardness
(ペアリング型最適化問題とその困難性)	共著
	平成30年1月
	SCIS 2018 Proceedings 1B1-3, pp.100-107
	非対称ペアリングは非対称の入力ペアを必要とする。即ち、非対称ペアリングには入力に二つの入力データ型が存在する。このことは、暗号方式設計者が各変数に対して矛盾なくデータ型を選択する必要があることを意味する。場合によってはそうしたデータ型の割り当てが実際には不可能な事もある。たとえ割り当てが可能だったとしても、割り当て方の選択が方式の効率に大きな影響を与える。従ってこの割り当ての充足方法および最適化方法に研究的関心がある。この論文ではそういた割り当ておよび最適化の包括的理論を与える。

本人担当部分：理論、システム全体の設計、実装、実験、論文執筆、責任著者
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆した。
共著者： Fumitaka Hoshino, Masayuki Abe, and Miyako Ohkubo.

63.	Designated Agent Anonymizable Signature
(エージェント指定匿名化可能署名)	共著
	平成31年1月
	SCIS 2019 Proceedings 4A2-2, pp.2070-2074
	匿名化可能署名 (Anonymizable Signature) とは リング署名 (Ring Signature) の拡張である. 匿名化可能署名を用いることで, 任意のエンティティが通常の署名から匿名署名に変換することができる. 言い換えると, 署名を代理人に託し, 匿名化を依頼することが可能である. 匿名化可能署名に残存する課題として, 匿名化する前の署名が通常の署名であるため, 誰でも検証可能という点がある.本発表では,匿名化可能署名を匿名化する前の時点で検証できる者を限定化する, という拡張を行った. この拡張により, 匿名化前の署名が流出した場合のリスクを軽減することが可能となる.

本人担当部分：理論
特筆すべき貢献：論文の核心となるアイディアを与え、研究指導を行い、論文執筆に関わった。
共著者： Tetsutaro Kobayashi and Fumitaka Hoshino.

64.	Optimization of Batch Verification for Pairing Product Equations.
(ペアリング積等式の一括検証の最適化)	単著
	平成31年1月
	SCIS 2019 Proceedings 1B2-1, pp.106-113

	高機能暗号方式では, 大量のペアリング積等式の検証がしばしば必要となる. それらの等式は各個に検証するより一括して検証する方が効率的である. しかし, ペアリング積等式の一括検証には沢山の計算方法が存在し, その数は一般にペアリングの数に対して指数関数的に増大する. そして計算方法により計算の効率が大きく変わる事が知られている. 本研究の目的は, 上記のように大量にある各々の検証式の型が全て既知である場合, 指数的多数の計算方法の候補から最も良い, あるいはそれに匹敵するくらい良い計算方法を見つけ出すアルゴリズムを与える事である.

65.	Fast and Scalable Bilinear-Type Conversion Method for Large Scale Crypto Schemes.
(大規模な暗号方式に対する高速でスケーラブルな双線形-型変換の方法)
(査読付)	共著
	平成31年1月
	IEICE Transactions on Fundamentals of
Electronics, Communications and Computer Sciences, E102.A(1):251–269,
	対称ペアリング群上設計された暗号方式を，非対称ペアリング群上のなるべく効率的な方式に，安全性を損なわずに変換するアルゴリズムをペアリング型変換と呼ぶ。本論文ではペアリング型変換に関して考察し，次の3つの結果を得た。 (1) 標準的な計算量仮定の下，最悪の入力でも多項式時間で最適解を見つけるアルゴリズムは存在しない事を証明した。 (2) 整数計画法を用いた実用的なアルゴリズムを提案した。 (3) 暗号学的に興味深い変換例を示した。これらの結果により、2014年に提案されたペアリング型変換に関するオープン問題を解決した。

本人担当部分：理論、システム全体の設計、実装、実験、論文執筆、責任著者
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆し、責任著者を務めた。その為、分野の慣例により著者順はAlphabetical Orderであるが、共著者全員から本人が筆頭であると認められている。（別紙 業績確認書 参照）
共著者： Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,
66.	Opcount: A pseudo-code performance estimation system for pairing-based cryptography.
(Opcount: ペアリングを用いた暗号方式の擬似コードレベルでのパフォーマンス評価システム)
(査読付)	共著
	令和1年
9月
	IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences, E102.A(9):1285–1292,	高速なペアリングライブラリの実装は特定の曲線やパラメータ限られることが多く、個別の暗号方式の効率を様々な曲線やパラメータに対して実装評価することは多大な労力・コストを要する。本稿では，ペアリング群上の暗号方式の様々な曲線およびパラメータ設定におけるパフォーマンスを簡易的に評価するフレームワーク 'Opcount' を提案する。擬似コードによる暗号方式の記述と、評価対象の曲線における基本演算のパフォーマンスを記録した実装情報データベースから、その暗号方式のパフォーマンスを見積もることで、適切な曲線やパラメータの選択を可能とした。

本人担当部分：理論、システム全体の設計、実装
特筆すべき貢献：論文の核心となるアイディアを与え、研究指導を行い、論文執筆に関わった。その為、著者順は分野の慣例により Alphabetical Orderであるが、共著者全員から本人が筆頭であると認められている。（別紙 業績確認書 参照）
共著者： Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,
67.	On an Application of a Variant of Trapdoor DDH Group.
(Trapdoor DDH 群のある変種の応用について)	共著	令和1年
10月
	CSS 2019 Proceedings,
pp.1535-1542	対称ペアリングを用いて非対称ペアリングに似た性質を持つ暗号プリミティブを構成できる事が知られている . そのように構成した暗号プリミティブは対称ペアリングと非対称ペアリングを折衷したような性質を持ち , 高機能な暗号方式への適用が期待できる . 本論文ではそのような暗号プリミティブの応用について考察する
共著者：Fumitaka Hoshino and Tetsutaro Kobayashi.

68.	Asymmetric Pairing based on Symmetric Pairing.
(対称ペアリングに基づく非対称ペアリング)	共著
	令和2年
月
	SCIS 2020 Proceedings, 3B1-2, pp.1385-1392
	対称ペアリングを用いて非対称ペアリングに似た性質を持つ暗号プリミティブを構成できる事が知られている . そのように構成した暗号プリミティブは対称ペアリングと非対称ペアリングを折衷したような性質を持ち , 高機能な暗号方式への適用が期待できる . 本発表ではそのような暗号プリミティブの構成について解説し , 教科書的な各種の離散対数ベースの応用プロトコルに対して、本プリミティブの適用性を評価し , 様々な問題点を議論する.

共著者：Fumitaka Hoshino and Tetsutaro Kobayashi.
（その他）
「論文賞」
1.	SCIS 2018 イノベーション論文賞: Pseudo-Code Performance Estimation for Pairing-Based Cryptographic Schemes. 
(ペアリングを用いた暗号方式の擬似コードレベルでのパフォーマンス評価)
(査読付)












「招待講演」
2.	Pseudo-Code Performance Estimation for Pairing-Based Cryptographic Schemes
(ペアリングを用いた暗号方式の擬似コードレベルでのパフォーマンス評価)

3.	Design in Type-I, Run in Type-III: Fast and Scalable Bilinear-Type Conversion Using Integer Programming.

















4.	Design in Type-I, Run in Type-III: Fast and Scalable Bilinear-Type Conversion Using Integer Programming.


「報告書」
5.	CRYPTREC Report 2009 暗号方式委員会報告












6.	CRYPTREC Report 2008 暗号技術監視委員会報告
	

共著






















－








－





















－







共著













共著
	

平成31年
1月(受賞)





















平成30年9月







平成29年2月




















平成28年12月






平成22年5月












平成21年5月
	

SCIS 2018 Proceedings 3A3-4, pp.1448-1454
 




















ICICE & IPSJ
IWSEC 2018
 (仙台)






第10回 公開鍵暗号の安全な構成とその応用ワークショップ
 (東京)


















ICICE ISEC研究会
(広島)






CRYPTREC Report 2009 暗号方式委員会報告, pp.19-30 および pp.45-157










CRYPTREC Report 2008 暗号技術監視委員会報告, pp.23-32 および pp.77-154	

高速なペアリングライブラリの実装は特定の曲線やパラメータ限られることが多く、個別の暗号方式の効率を様々な曲線やパラメータに対して実装評価することは多大な労力・コストを要する。本稿では，ペアリング群上の暗号方式の様々な曲線およびパラメータ設定におけるパフォーマンスを簡易的に評価するフレームワーク 'Opcount' を提案する。擬似コードによる暗号方式の記述と、評価対象の曲線における基本演算のパフォーマンスを記録した実装情報データベースから、その暗号方式のパフォーマンスを見積もることで、適切な曲線やパラメータの選択を可能とした。

本人担当部分：理論、システム全体の設計、実装
特筆すべき貢献：論文の核心となるアイディアを与え、研究指導を行い、論文執筆に関わった。この論文は SCIS 2018 イノベーション論文賞を受賞し、電子情報通信学会 情報セキュリティ研究会から表彰された。
共著者： Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo,


内容は上記 No.1 と同様. (本人が発表者)
 







対称ペアリング群上設計された暗号方式を，非対称ペアリング群上のなるべく効率的な方式に，安全性を損なわずに変換するアルゴリズムをペアリング型変換と呼ぶ。本論文ではIPConv と呼ばれる 0-1整数計画法を用いた新しいペアリング型変換を導入する。広く使われている IPソルバを使うと、IPConv は既存の複雑な方式を即座にペアリング型変換することができる。そうした高速で大規模化可能なペアリング型変換が使えると、対称ペアリング上の暗号方式の設計に関する新たなアプローチが可能となる。

本人担当部分：理論、システム全体の設計、実装、実験、論文執筆
特筆すべき貢献：論文の核心となるアイディアを与え、実際に論文全体を執筆した。その為、分野の慣例により著者順は Alphabetical Orderであるが、共著者全員から本人が筆頭であると認められている。（別紙 業績確認書 参照）
共著者： Masayuki Abe, Fumitaka Hoshino, and Miyako Ohkubo, (本人が発表者)

内容は上記 No.3 と同様. (本人が発表者)







本報告書は、総務省及び経済産業省が主催している暗号技術検討会の下に設置されている暗号方式委員会の 2009 年度活動報告である。

本人担当部分：暗号技術の専門家として執筆に参加し, 暗号解析技術に関する情報収集監視業務に従事し、世界中で行われる暗号と情報セキュリティ技術の研究会やワークショップに参加し情報収集を行い、報告書(全157頁中)の以下の部分を執筆し、全章の執筆とりまとめを行った。
第３章 監視活動 (pp.19-30)
付録３学会等での主要論文発表等一覧(pp.45-157)

本報告書は、総務省及び経済産業省が主催している暗号技術検討会の下に設置されている暗号技術監視委員会の 2008 年度活動報告である。

本人担当部分：暗号技術の専門家として執筆に参加し, 暗号解析技術に関する情報収集監視業務に従事し、世界中で行われる暗号と情報セキュリティ技術の研究会やワークショップに参加し情報収集を行い、報告書(全154頁中)の以下の部分を執筆し、全章の執筆とりまとめを行った。
第３章 監視活動(p.23-32)
付録４学会等での主要論文発表等一覧(p.77-154)
