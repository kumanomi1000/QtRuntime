# QtRuntime

本アーカイブは、Windows 11上のQt 6.9.1 + MSVC2022 64bitでビルドされた実行ファイルで必要なQtランタイムライブラリを、Qtの推奨手順（windeployqtを使用する）で収集し、QtのオープンソースライセンスおよびLGPLv3により再配布するものです。<br>
This archive contains the Qt runtime libraries required for an executable built on Windows 11 using Qt 6.9.1 and MSVC2022 (64-bit). These libraries have been collected following Qt’s recommended procedure (using `windeployqt`) and are redistributed in accordance with the Qt open-source license and the LGPLv3.

- 使用方法：ZIPファイルを適当なフォルダで展開し、Qtアプリの実行ファイルを同じフォルダに配置して実行してください。<br>
Instructions: Extract the ZIP file into a folder of your choice, place a Qt application executable in the same folder, and then run it.
- 補足：MSVCのランタイムライブラリは含まれません。必要な場合は別途入手してください。<br>
Note: The MSVC runtime library is not included. Please obtain it separately if needed.<br>
入手方法の一例：[サポートされている最新の Visual C++ 再頒布可能パッケージのダウンロード](https://learn.microsoft.com/ja-jp/cpp/windows/latest-supported-vc-redist)から「サポートされている最新の再頒布可能パッケージ バージョン」をダウンロードしてインストールする。
