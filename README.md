3/24 

昨日、とある方から大きなアドバイスをいただき変更をしました。

3/24に変更したのは、不正解時の条件をまるっと変更です。

SerchCount変数で機械言語から部位開示は0であるので=して0のときの条件式を、

不正解のTest_Constant.NOT_STRIKEをeualsで一致させる手段にしました。

コンソール表示はできてると思いますが…今度は正解時に2回出力されるように。

スコープを再考慮してる最中です…

3/23修正

アドバイスをいただき、不正解判定のif文の前のelseを削除しました。

不正解が連続する場合は出力がでるようになりました。

ただ…アドバイスをいただいた方の懸念どおり、正解した後の不正解は出力されません。

カウンタ変数で正解して次に不正解のとき、値が更新されてないのでは？と仰るとおりです。

まだその部分は修正できていません。

カウンタ変数をもう一つ設定するかな…と思案中です。


3/24解決しました。

ｺﾝｿｰﾙ表示で想定している結果が表示できません… 

作成の趣旨
Java Bronze 資格取得をするために受験勉強用に作成をしました。

CSVから答えと答えの概要を読み取り、答え合わせをｺﾝｿｰﾙ表示する対話型のｺｰﾃﾞｨﾝｸﾞです>

CSVの縦列ﾃﾞｰﾀ分だけ出題をするようにし、答えを縦列分入力した後に、正解数と正解率を出力するようにしました。

ただ…困ったことに不正解のときは「不正解」の表示と、正解だったときの解説の表示出力をする時としない時があります。

正解時は表示ができています。

検索手段は線形探索を選択しています。

最後に出力する正解数と正解率は問題は無いように思えます。

なんとか解決しようと試行錯誤をしています。

csvﾃﾞｰﾀはﾃｽﾄﾊﾞｰｼﾞｮﾝで適宜作成をしました。(本の回答だと著作権に抵触をするので)

csvﾃﾞｰﾀの概要は以下のとおりです。

全て答えは"a"です。 


