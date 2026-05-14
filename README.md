# sangiin2025

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

福井県における2025年参議院議員通常選挙の市町別開票結果を、SVGスタックバーチャートで可視化するプロジェクトです。

## Demo

**https://github.com/code4fukui/sangiin2025

The application displays four stacked bar charts visualizing election results by municipality:
1.  **市町別得票割合（選挙区）**: Vote share by candidate for each municipality.
2.  **福井市基準得票割合（選挙区）**: Relative vote share by candidate, benchmarked against a standard.
3.  **市町別得票割合（比例）**: Vote share by party for each municipality.
4.  **福井市基準得票割合（比例）**: Relative vote share by party, benchmarked against a standard.

## Features

-   **選挙区・比例代表の可視化**: 市町ごとの選挙区（候補者別）と比例代表（政党別）の得票率を個別に表示します。
-   **相対比較チャート**: 通常の得票率に加え、福井市の結果を基準とした相対的な得票割合も表示し、地域ごとの支持傾向の違いを分析できます。
-   **SVGによる動的描画**: 軽量なSVGチャートライブラリ [svg-chart](https://github.com/code4fukui/svg-chart) を利用して、ブラウザ上で直接グラフを生成します。
-   **CSVデータソース**: 福井県の公開データを基にしたCSVファイルを直接読み込んで表示します。

## Usage

This is a static web page. No build step or server is required.

1.  Clone the repository:
    ```bash
    git clone https://github.com/code4fukui/sangiin2025.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd sangiin2025
    ```
3.  Open `index.html` in a modern web browser.

## Dependencies