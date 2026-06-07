# LineageOS 21 GSI for Pixel 7a (and other arm64 devices)

これは自分でビルドしたLineageOS 21のGSI（Generic System Image）です。
主にPixel 7aでの検証用としてビルドしましたが、arm64かつTreble対応端末であれば動作する可能性があります。

## ⚠️ 免責事項 (Disclaimer)
- このイメージを使用して生じた、端末の故障やデータ損失について、私は一切の責任を負いません。
- すべて自己責任（Use at your own risk）で行ってください。

## 🛠 ビルド情報
- **OS:** LineageOS 21 (Android 14)
- **ビルド日時:** 2026-06-06
- **ターゲット:** arm64_gN (GApps included)
- **署名:** Test-keys

## 📱 動作確認済み端末
- Pixel 7a (lynx)

## 🚀 インストール方法 (DSU Sideloader推奨)
DSU Sideloaderを使用してインストールすることを推奨します。

1. ブートローダーをアンロックしてください。
2. DSU Sideloaderを起動し、この `system.img` を選択します。
3. インストールオプションで **"Disable AVB"** を有効にしてください。
4. インストール後、再起動してください。


## 📝 既知の問題 (Known Issues)
- （ここに今確認できている不具合があれば書く。例：指紋認証が遅い、カメラがたまに落ちる など）

## 🤝 謝辞 (Credits)
- AndyCGYan (for GSI scripts)
- LineageOS Team
