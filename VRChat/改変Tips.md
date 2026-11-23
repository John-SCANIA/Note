# 改変の備忘録

## 衣装のメニューの作り方 (MA)
Modular Avaterで衣装MENUを作りたいとき

①Create Emptyで空のObjectを作成

②Add ComponentでInspectorから"MA Menu installer" と "MA Menu Item"を追加 

③MA Menu Itemのトグルを追加

④追加されたObjectを開き"MA Object Toggle"から+をクリックし、切り替えたい衣装をD&D


## 1つのスイッチで2つの衣装のToggleを作りたいとき (MA)
### 1つのスイッチで2つの衣装を切り替えたいとき

| スイッチの状態 | 衣装①の状態 | 衣装②の状態|
|:-:|:-:|:-:| 
|OFF|ON|OFF|  
|ON|OFF|ON|

のような状態にしたいとき  
(スイッチがOFFの状態の時に表示したい衣装を衣装①とするとき)

①Inspecterでの衣装②の☑を外す  
    (非アクティブにする)

②Object Toggleに衣装①,衣装②を追加し、衣装②をONにする。