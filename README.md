# Manage-anything-java

# ファイルとフォルダの説明
## scheduleapp_2/app/src/main/java/com/exapmple/y3033010/scheduleapp_2/
* *MainActivity.java*
    * アプリのスタート画面に関するプログラム
* *changeWorkInfo.java*
    * すでに設定済みの仕事情報を編集する画面のプログラム
* *datashift.java*
    * 予定として入っているシフトに関する情報を保存するプログラム
* *dayActivity.java*
    * 特定の日にちに予定を追加する画面のプログラム
* *lessonInTImeTable.java*
    * データベースに授業を追加するプログラム
* *PlanInDayActivity.java*
    * 特定の日にちに追加した予定をデータベースに書き込むプログラム
* *schduleActivity.java*
    * その日に入っている予定を表示するプログラム
* *setWorkInfo.java*
    * 仕事に関する情報をデータベースに追加するプログラム
* *ShiftActivity.java*
    * 仕事に関する情報を管理するプログラム
* *TestOpenHelper.java*
    * データベースを作成するプログラム
* *TimePickerDialogFragment.java*
    * 予定追加画面の時計型ダイアログを表示させるプログラム
* *TimetableActivity.java*
    * 時間割管理画面のプログラム


# 使用方法
scheduleapp_2のプロジェクトをAndroid studio開く

## インポート方法

1. 「TakiVR.unitypackage」はUnityのプロジェクトパッケージです。[このリンク](https://kan-kikuchi.hatenablog.com/entry/Unitypackage)に従ってimportしてください。
2.  実験のシーンは「/Scenes/TakiVR」です。
3.  シュミレーターモードなのでVRでは動きません。シュミレーターの操作方法は[このリンク](https://tech.framesynthesis.co.jp/unity/xr/#:~:text=%E3%81%A6%E3%81%8F%E3%81%A0%E3%81%95%E3%81%84%E3%80%82-,%E3%83%98%E3%83%83%E3%83%89%E3%82%BB%E3%83%83%E3%83%88%E3%81%AA%E3%81%97%E3%81%A7XR%20Origin%E3%82%92%E6%93%8D%E4%BD%9C%E3%81%99%E3%82%8B%E3%81%AB%E3%81%AF,-XR%20Device%20Simulator)に従ってください。
## VRで動かしたい場合
1.  TakiVRシーンのHierarchy上にある「XR Device Simulator」オブジェクトを[このリンク](https://tech.pjin.jp/blog/2021/03/31/unity_gameobject_component_on-off/)のように無効化
