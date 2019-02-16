# RacingViewer
RacingViewer はドローンレースにフォーカスしたアプリケーションです.
マネジメントから動画配信までレース運営に必要なタスクを一括して管理実行する事が目標です.
本格的なレースに特化するのではなく, 簡易的なレース, 練習会も想定しています.
 
現在以下の機能がサポートされています．
- FPV画像, Webカメラのビューワー機能
- ARマーカーによるラップタイム/区間タイム計測機能


[こちらの動画](https://youtu.be/sj2ZjWYpoUQ)を見ていただければ何ができるのかわかると思います.

# チュートリアル
簡単な使い方を説明します.

1. RacingViewerを立ち上げて下さい.  
このときカメラがPCに接続されていなくても大丈夫です. 

1. Preference タブを開き以下の操作を行って下さい

    + 各種データを保存するフォルダを指定して下さい.  
    指定するのは以下の3つのフォルダです. 取り敢えずは３つ全て同じフォルダを指定しても構いません.  
    
        - Pilots path:  
        パイロット情報を保存しておくフォルダを指定します.  
        - Event path:  
        イベントに必要な情報を保存するフォルダを指定します.  
        具体的にはコースの情報と各パイロットのラップタイムがこのフォルダに記録されます.  
        - Layout path:  
        Viewerのレイアウト情報を置いておくフォルダを指定します.  
        このフォルダにレイアウトファイル(テキストファイル) を置いておくと Viewer の画面レイアウトをカスタマイズする事ができます.
    
    + Auto Lap の Speech laptime のチェックを ON にして下さい  
    1ラップ毎にタイムを読み上げてくれます.  
    
1. Pilot タブを開き, 以下の操作を行って下さい

    + パイロット名を Name 欄に Ken と入力して下さい
    + Image 欄をダブルクリックして適当な画像ファイルを入力して下さい  
    (何でもいいです) 
    + Color 欄をダブルクリックして適当に色を選んで下さい  
    (何でもいいです)
    + Aspect 欄にカメラのアスペクト比を入力して下さい  
    (何でもいいです) 
    
1. Course タブを開き リストの１番上が ID 0, Type Start&Goal となっていることを確認して下さい

1. Screen 1 を開き, 以下の操作を行ってください
    + USBカメラまたはFPV受信機(以下, ビデオソースと称する)をPCに接続して下さい  
    (すでに接続していた場合は飛ばしてください)
    + 使用するビデオソースのみ Activate にチェックを入れ, 使わないものはチェックを外してください.
    
    + Cut In のとなり 01 と書かれている項目に適当な1以上の数字を入力してください.  
    使用するビデオソース全てについてそれぞれに 1, 2, 3と入力してみてください.  
    1, 3, 5 のように飛ばして入れても大丈夫です.  
    Viewer ウインドにビデオソースが表示されます.
    
    + 上で入力した数字を変更してみてください
    Viewer ウインドのレイアウトが変更されるはずです.
    
    + 01 のとなり, 02 の綱目に 01 とは違う数字を入れてください
    + 01 と書かれている場所と 02 と書かれている場所を交互にクリックしてください  
    Viewer ウインドのレイアウトが変更されるはずです.
    
    + どれか1つのVPF映像ビデオソースの Pilot の項目にKenと入力してください  
    
    + 上記のビデオソースのRecognition の項目にチェックを入れてください.
    
1. Lapttime タブを開き, 以下の操作を行って下さい
    
    + 左のリストで Ken を選択します
    + ARマーカーを映したのち, カメラの視点をARマーカー上方にずらして, ARマーカーが画面から外します.  
    するとラップタイム計測が開始されます.
    + 上記操作を繰り返します.  
    上記捜査の度にラップタイムが計測されます.

