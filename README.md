# プロフィール

## スキル

- Python3
- AWS
    - Lambda
        - LambdaLayers
    - S3
    - APIGateway
    - SAM

## Webアプリ「Melody App」

「Melody App」は動画ファイルを音声ファイルに変換することができます。

### 接続先

https://dev.d2czufkjyn70t8.amplifyapp.com/

### バックエンド

![](https://github.com/michonchy/Melody-API/raw/main/.readme/architecture.png)

### フロントエンド

`TODO: できた後で、Melody Appの画像を貼る`

## 作成物

<!-- 演習問題用のAPIの羅列 -->

### [even-odd-API](https://github.com/michonchy/even-odd-API)

整数値を入力させ、その値が偶数ならばeven、奇数ならばoddと表示するプログラム。

**実行URL**

https://y5suepry5a.execute-api.ap-northeast-1.amazonaws.com/Stage/even-odd?number=8

| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [display-graph-API](https://github.com/michonchy/display-graph-API)

0以上の整数値を5つ入力させ、それぞれの値に対して、次の形式でグラフを描くプログラム
形式：左端に値を表示し、適切に空白を空けて":"を書く。その後ろに値の数だけ"*"を描くが、5個おきに空白を１つ入れる。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [binary-number-API](https://github.com/michonchy/binary-number-API)

0〜65535の整数値を入力させ、2進数に変換して表示するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [max-min-API](https://github.com/michonchy/max-min-API)

複数の数値を入力させ、その中から最大値と最小値を表示するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| numbers | 数値 |

### [dream-flower-API](https://github.com/michonchy/dream-flower-API)

「とんで」を9回「まわって」を3回繰り返した後「まわる」と表示して改行する、をn回繰り返すプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [prime-factorize-API](https://github.com/michonchy/prime-factorize-API)

自然数の入力値を素因数分解して結果を表示するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [leap-year-API](https://github.com/michonchy/leap-year-API)

西暦を入力したらその年が閏（うるう）年かどうかを判定するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [pay-money-API](https://github.com/michonchy/pay-money-API)

入力された金額を、100円玉と10円玉と1円玉だけで、できるだけ少ない枚数で支払うとき、それぞれの枚数を計算して表示するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [admission-fee-API](https://github.com/michonchy/admission-fee-API)

神山美術館の入場料金は、一人600円であるが、5人以上のグループなら一人550円、20人以上の団体なら一人500円である。人数を入力し、入場料の合計を計算するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [repetition-numbers-API](https://github.com/michonchy/repetition-numbers-API)

最初に2以上の整数値を入力し、次の規則で計算し、計算回数と計算結果を表示し、計算結果が1になるまで繰り返すプログラム。
規則：ある値が偶数ならその値を1/2にする。奇数ならその値を3倍して1を足す

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [number-swap-API](https://github.com/michonchy/number-swap-API)

異なる整数値を2つ入力し、それぞれ別の変数に格納する。そして、それらの変数の値を入れ替えた後、それぞれの変数の値を表示するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [taxi-rate-API](https://github.com/michonchy/taxi-rate-API)

初乗り料金が1700mまで610円、それ以降は313mごとに80円のタクシーがある。このタクシーに乗った距離をm単位で入力し、料金を計算するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [currency-conversion-API](https://github.com/michonchy/currency-conversion-API)

換算したい金額（円単位）と1ドル何円かを整数値で入力すると、入力した金額が何ドル何セントか計算して表示するプログラム。（1セント未満の端数切り捨て）

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [quadratic-equation-API](https://github.com/michonchy/quadratic-equation-API)

2次方程式 ax^2 + bx + c = 0 （x^2はxの2乗の意味）の係数a, b, cを入力し、2次方程式の解が2つの実数解か、重解か、2つの虚数解かを判別するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [assending-order-API](https://github.com/michonchy/assending-order-API)

整数値を3つ入力させ、それらの値が小さい順（等しくてもよい）に並んでいるか判定し、小さい順に並んでいる場合はOK、そうでない場合はNGと表示するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |

### [single-figure-API](https://github.com/michonchy/single-figure-API)

整数値を入力させ、その値が一桁の自然数かそうでないか判定するプログラム。

**実行URL**



| パラメーター | フォーマット |
| --- | --- |
| number | 数値 |