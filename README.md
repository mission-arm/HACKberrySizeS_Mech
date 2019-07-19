# HACKberrySizeS_Mech

小児向けサイズの HACKberry の、機構部品の3Dプリント用STLファイルです。
ディレクトリ構成は以下のようになっています。

This repository contains stl files of small sized HACKberry to make it with 3D printer.
The directory structure is below.

```
HbSizeSMech/
│  HbSizeS_BOM.xlsx : 小児用 HACKberryの部品一覧エクセルファイルです。/ Parts list for small sized HACKberry 
│  README.md        : この説明書です。/ This description file.
│
├─UnitHand/ : 手部分の部品のフォルダです。/ Directory for hand unit.
│  ├─JointForWrist/ : 手首との接続部分のフォルダです。/ Directory for joint parts between hand and wrist.
│  │      HbWristMountForChild_aiwa.stl
│  │      HbWristMountForChild_HACKberry.stl
│  │
│  └─Unit_SR-H/ : 手のメインの部品類のフォルダです。/ Directory containing hand parts
│      ├─Parts_SR-H/ : 手のひら, 手の甲の部品のフォルダです。/ Directory containing palm parts
│      │      SR-H-02.stl
│      │      SR-H-03.stl
│      │      SR-H-04.stl
│      │      SR-H-05.stl
│      │      SR-H-06.stl
│      │      SR-H-07.stl
│      │      SR-H-08.stl
│      │      SR-H-09.stl
│      │      SR-H-10.stl
│      │      SR-H-11.stl
│      │      SR-H-12.stl
│      │      SR-H-13.stl
│      │      SR-H-14.stl
│      │      SR-H-15.stl
│      │
│      ├─Unit_SR-I/ : 人差し指の部品のフォルダです。/ Directory containing index finger parts
│      │      SR-I-01.stl
│      │      SR-I-02.stl
│      │      SR-I-03.stl
│      │      SR-I-04.stl
│      │      SR-I-05.stl
│      │      SR-I-06.stl
│      │      SR-I-07.stl
│      │
│      ├─Unit_SR-O/ : 三指 ( 中指, 薬指, 小指 ) の部品のフォルダです。/ Directory containing other fingers parts ( middle, ring and little finger )
│      │      SR-O-01.stl
│      │      SR-O-02.stl
│      │      SR-O-03.stl
│      │      SR-O-04.stl
│      │      SR-O-05.stl
│      │
│      └─Unit_SR-T/ : 親指の部品のフォルダです。/ Directory containing thumb parts
│              SR-T-01.stl
│              SR-T-02.stl
│              SR-T-03.stl
│              SR-T-04.stl
│              SR-T-05.stl
│              SR-T-06.stl
│
├─UnitSocket/ : 短断端用ソケットの部品のフォルダです。( 試作中 ) / Directory contaning socket parts for short stump ( in develop )
│  └─UnitSocket/ : ソケットの部品のフォルダです。/ Directory containing socket parts
│          BatteryCaseBase.stl
│          BatteryCaseButton.stl
│          ForeArm.stl
│          ForeArmCover.stl
│          SocketMount.stl  ( 実際のソケット部分をマウントする部品 )
│
└─UnitWrist/ : 手首の部品のフォルダです。/ Directory contatning wrist parts
    └─Parts_SR-W
            SR-W-01.stl
            SR-W-02.stl
            SR-W-03.stl
            SR-W-04.stl
            SR-W-05.stl
            SR-W-06.stl
            SR-W-07.stl
            SR-W-08.stl
```
