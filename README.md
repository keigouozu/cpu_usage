# cpu_usage
[![test](https://github.com/keigouozu/cpu_usage/actions/workflows/cpu_usage_test.yml/badge.svg)](https://github.com/keigouozu/cpu_usage/actions/workflows/cpu_usage_test.yml)

## 概要
- ROS 2のパッケージです
- 端末のCPU使用率を出力できます

## 実行方法
```bash
ros2 run mypkg cpu_usage 
```
別の端末を立ち上げサブスクライブする
```bash
ros2 topic echo /cpu_usage
```
出力例
```bash
data: 6.400000095367432
---
data: 6.199999809265137
---
data: 6.300000190734863
---
data: 6.199999809265137
---
```

## トピック一覧
**cpu_usage**
- CPU使用率のデータをパブリッシュします。値はFloat32型で送られます。

## ノード一覧
**cpu_usage**
- CPU使用率を1秒ごとに取得し、cpu_usageトピックにパブリッシュします。

## 実行環境
- **Python**: バージョン3.10以降
- **OS**: Ubuntu 22.04 LTS以降
- **shell**: Bashバージョン5.0以降

## ライセンス
BSD-3-Clause

## 著作権
© 2024 Keigo Uozu
