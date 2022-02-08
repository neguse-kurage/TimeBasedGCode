# TimeBasedGcode
TimeBasedGcodeは3Dプリンタに使用するGcodeの記述において、従来の位置本位ではなく移動時間本位とするものである。<br>
これによって3Dプリンタの動作と外部機器の連携等を実現する。<br>
本ツールはTimeBasedGcodeを任意の曲線の連続から生成する。<br>

## Requirement
- Rhinoceros - 3DCAD
  - Grasshopper - Plug-in for Rhinoceros

## Usage
![0](https://user-images.githubusercontent.com/19545173/153058066-8c043c1b-8583-4183-98db-ddbab7c5207c.png)
### ①CurveのListを入力する - Input a list of Curves.
<img width="473" alt="1" src="https://user-images.githubusercontent.com/19545173/153059527-fd3abd32-2d57-42d4-bebd-fb01c92ed457.png">

### ②ヘッドの移動速度を設定する - Set the head travel speed.
<img width="522" alt="2" src="https://user-images.githubusercontent.com/19545173/153059640-7185cf9a-4a06-4431-b21e-fb5d01773119.png">

### ③吐出速度を設定する - Set the extrusion speed.
<img width="436" alt="3" src="https://user-images.githubusercontent.com/19545173/153060021-9148bc21-fe19-46f6-8bcd-0c14dd8f811a.png">

### ④StartGcode,EndGcode,Filenameを設定する - Set StartGcode, EndGcode and Filename.
![5_1](https://user-images.githubusercontent.com/19545173/153060638-9d709ec9-ee7a-450e-9459-4cc25802a4fb.png)

### ⑤書き出し場所を設定する - Set the file path to export
<img width="669" alt="4" src="https://user-images.githubusercontent.com/19545173/153060102-5d674143-2907-485a-b910-3d4eabdcbd32.png">

### ⑥書き出しボタンを押す - Press export button.
![5_2](https://user-images.githubusercontent.com/19545173/153060694-31d34483-e1c4-48ce-81f5-3a5e3c396a9d.png)
