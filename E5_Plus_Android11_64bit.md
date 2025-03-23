# E5 Plus Android11 64bit化の手順

# 謝辞
素晴らしい情報に感謝いたします。  

- redditコミュニティー  
https://www.reddit.com/r/SBCGaming/comments/1hg5w9e/i_just_got_my_gamemt_e5_plus_since_there_is_very/?rdt=41092

- GameMTオフィシャルサイト  
http://gamemt.net/index.php/2024/11/11/e6-e5-plus-%E5%AE%89%E5%8D%93linux%E7%B3%BB%E7%BB%9F%E5%88%B7%E6%9C%BA%E6%95%99%E7%A8%8B/

# はじめに
この作業に失敗すると文鎮化する可能性があるため、自己責任にてお願いいたします。  
また、念の為上記リンク先を参照してこの手順に問題がないことも各自で確認した上で作業をお願いします。  

# 手順
1. ダウンロードURLから下記3つのファイルをダウンロードする  
  [ダウンロードURL](https://drive.google.com/drive/folders/1fhtvCX77iy6DeuCIb02hqX1nA0DNsPEx)  
    - DriverAssitant_v5.1.1(1).rar
    - FactoryTool_v1.81(1).rar
    - rk3566_mt_e5p_gms_wifi_android64_tf_2401021

 2. `DriverAssitant_v5.1.1(1).rar`を解凍したら`DriverInstall.exe`を実行してドライバーをインストールする
 3. E5 plusの電源をOFFにする
 4. 付属のUSBケーブルでPCとE5 plusのOTGポートを接続する
 5. E5 plusの電源ボタンと音量＋ボタンを同時に押し続ける(windowsから「ポロン」という音がしてE5 Plusが認識されるはずで、E5 plusの画面は真っ黒だった気がする)
 6. `rk3566_mt_e5p_gms_wifi_android64_tf_2401021`ファイルを解凍して`rk3566_mt_e5p_gms_wifi_android64_tf_2401021.img`ファイルができていることを確認しておく
 7. `FactoryTool_v1.81(1).rar`を解凍して`FactoryTool.exe`を実行する
 8. 画面左上の`Firmware`をクリックして`rk3566_mt_e5p_gms_wifi_android64_tf_2401021.img`ファイルを指定する
 9. 画面左上の`Run`ボタンを押すとAndroid11 64bitがE5 Plusに書き込まれ始める
 10. 画面右側に緑色のランプで`Success`と表示されたら画面左上の`Stop`ボタンを押して、FactoryToolプログラムを終了させる
 11. E5 PlusからUSBケーブルを抜いて、電源をONにしたら数分そのままでまつ
 12. Android11が起動したら作業完了

以後お好きなようにエミュ環境構築をすればOKですが、USB-HUBとUSBキーボード＆マウスがあると作業が捗ります

以上
