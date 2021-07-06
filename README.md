# mht_com_task1

QueensTechLabの課題１を載せています

## 課題1

出力のさせかた(print?、log?、console.log?)

CUIで出力される場合はprintを使う。

以下はproject作成時のサンプルアプリの生成順番を知るためのprint。

main_void=>"main Start"

main_voidの次に来るステートレスウィジェット=>"initMyapp_StatelessWidget"

MyAppに返されたステートフルウィジェット=>"initMyHomePage_StatefulWidget"

※debugPrintも使える。ロギングするためにはパッケージが必要っぽい。

参考：https://rizumita.medium.com/logging-in-dart-dd9c01eb459a

※Webではconsole.logで出力することができる。

画面とログの両方に出力する

ステートフルウィジェットに定数buildDebugを入れてログと画面に出力。