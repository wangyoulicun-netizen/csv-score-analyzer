# csv-score-analyzer

2/3 CSVを読み込んで価格計算を自動化するPythonスクリプトを作成

  　# CSV商品データ変換ツール

## 概要
商品データ（CSV）を読み込み、加工・整形するPythonスクリプトです。

## 使用技術
- Python
- CSVファイル操作

## ファイル構成
- products.csv：商品データ
- convert.py：CSVを読み込んで処理するスクリプト

## 使い方
1. products.csv を用意
2. convert.py を実行

## 課題
- output.2.csvのTシャツ・2200となってしまう

## Example Use
This script is useful for:
- EC product registration
- Price calculation (tax included)
- CSV data cleanup and formatting

## Output
- Reads product data from CSV
- Converts prices automatically
- Outputs clean, structured data

2/4
## Use Case
- Product listing for EC platforms (Amazon / eBay)
- CSV-based product data management

## Price Adjustment Tool
This script updates product prices in a CSV file by a fixed percentage.
Useful for bulk price changes in EC product listings.
I was able to accomplish yesterday's task.

2/5
- Prevents invalid price changes by validating percentage ranges.
## Features
- Adjust prices by specified percentage
- Preserve original CSV file
- Output Excel-safe UTF-8 CSV
- Validate input range to prevent mistakes

- - Checks mismatches between product CSV and image files to prevent upload errors.

