# RX62N-WAIT-SSP-HEWSIM
WAIT-SSPを用いたサンプル　HEWのシミュレータで動作確認できます

20150720 リリース情報
1.サンプルプログラム変更
2.遅延ディスパッチの処理の不具合修正
　longjmp時に関数ローカル変数が保証されないので、その対応
3.タスク起動時のCPU状態の設定
　タスク起動時にマスクレベル0 割り込み許可にする

20150717 リリース情報
アセンブリ言語の部分をなくしました。(inlineアセンブラを除く)

