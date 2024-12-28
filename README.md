# cpu_usage
[![test](https://github.com/keigouozu/cpu_usage/actions/workflows/cpu_usage_test.yml/badge.svg)](https://github.com/keigouozu/cpu_usage/actions/workflows/cpu_usage_test.yml)

## 概要
- 端末のcpu使用率を出力できます

## 使用方法
ros2のワークスペースにリポジトリをクローン
```bash
git clone git@github.com:keigouozu/cpu_usage.git
```
実行
```bash
ros2 run mypkg cpu_usage 
```
出力例
```bash
[INFO] [1735398403.693482049] [cpu_usage]: Current cpu usage: 6.2%
[INFO] [1735398404.683038153] [cpu_usage]: Current cpu usage: 6.3%
[INFO] [1735398405.683000150] [cpu_usage]: Current cpu usage: 6.3%
[INFO] [1735398406.682730751] [cpu_usage]: Current cpu usage: 6.3%
[INFO] [1735398407.682607246] [cpu_usage]: Current cpu usage: 6.3%
```

## 実行環境
- **python**: バージョン3.10以降
- **os**: Ubuntu 22.04 LTS以降
- **Shell** Bashバージョン5.0以降

## ライセンス
BSD-3-Clause

## 著作権
© 2024 Keigo Uozu
