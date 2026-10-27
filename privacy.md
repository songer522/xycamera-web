# Privacy Policy — XY Camera (祥云相机 / 祥雲相機)

**Effective Date:** October 26, 2026<br>
**Last Updated:** October 26, 2026<br>
**Developer:** Yang Song ([rewind.feedback@gmail.com](mailto:rewind.feedback@gmail.com))

---

## 1. Summary (English)

**XY Camera** (**祥云相机** / **祥雲相機**) is built with a strict **on-device privacy architecture**:
- **Zero Data Collection:** We do not collect, transmit, store, or sell any personal data, photos, videos, audio recordings, location coordinates, or usage analytics.
- **No Servers or Third-Party SDKs:** The app contains no third-party analytics SDKs, advertising frameworks, crash-reporting trackers, or cloud accounts. The app makes no network requests of its own. It uses only Apple's StoreKit 2 framework, for the optional Tip Jar in Settings and, at launch, to check whether the app was installed from the App Store or TestFlight; no personal data is sent to the developer.
- **100% On-Device Storage:** Everything you shoot and import stays exclusively on your iPhone, in your personal iOS Photos library (when you choose to save or export there), or on an external USB-C storage drive that you connect.

## 2. Permissions & How Your Device Uses Them

XY Camera requests iOS system permissions only when needed to operate the camera:

1. **Camera (`NSCameraUsageDescription`):** Used solely to render the live camera viewfinder and capture photos and videos on your device.
2. **Microphone (`NSMicrophoneUsageDescription`):** Used solely to record audio alongside your videos and display the live stereo audio level meter on screen.
3. **Photo Library (`NSPhotoLibraryUsageDescription` & `NSPhotoLibraryAddUsageDescription`):** Used only when you choose to save takes directly to the iOS Photos app or export graded videos/photos from the in-app Media library to Photos.
4. **Location When In Use (`NSLocationWhenInUseUsageDescription` — Optional):** Requested **only** if you explicitly turn on **Record location** in the app's Settings. When enabled, your iPhone writes GPS coordinates directly into the EXIF / QuickTime metadata header of the photo or video file saved on your device. Location coordinates are never logged, transmitted, or shared outside the recorded file itself, and location access is never active in the background.

## 3. Custom LUT Imports & App Preferences

- **Imported `.cube` LUTs:** When you import a `.cube` file via the system file picker, the file is parsed and stored locally inside the app's container on your device.
- **On-Device Preferences:** Camera preferences (such as your selected format, lens, grid, histogram mode, LUT selection, and tip supporter heart counter) are stored locally on your device using standard iOS storage (`UserDefaults` and the app sandbox).

## 4. In-App Purchases (Optional Tip Jar)

XY Camera includes an optional "Buy Me a Coffee" tip jar in Settings powered entirely by Apple's **StoreKit 2** framework. All payment processing is handled directly by Apple. The developer never receives or has access to your Apple ID, name, billing address, or payment card details.

## 5. Children's Privacy

XY Camera does not collect personal information from anyone, including children under the age of 13 (or the applicable minimum age in your jurisdiction).

## 6. Contact Us

If you have any questions about this Privacy Policy, please contact:<br>
**Yang Song** — [rewind.feedback@gmail.com](mailto:rewind.feedback@gmail.com)

---

## 隐私政策（简体中文）

**生效日期：** 2026年10月26日<br>
**开发者：** Yang Song ([rewind.feedback@gmail.com](mailto:rewind.feedback@gmail.com))

**祥云相机**（海外版名称：**XY Camera**）严格遵循**纯本地隐私保护原则**：

1. **零数据收集与零第三方追踪：** 本应用不收集、不上传、不存储也不出售您的任何个人身份信息、照片、视频、录音、地理位置或使用行为数据。应用内不包含任何第三方统计 SDK、广告插件或云服务器请求。
2. **设备端权限说明：**
   - **相机与麦克风：** 仅用于实时取景、拍摄照片与录制视频声音，及显示实时音频电平表。
   - **照片图库：** 仅在您选择将拍摄内容保存或导出至系统“照片”应用时使用。
   - **使用期间的位置信息（可选）：** 仅当您在应用“设置”中主动开启“记录位置信息”开关时才会请求授权。开启后，位置坐标仅写入您设备本地生成的照片（EXIF）或视频（QuickTime）文件元数据中，绝不会上传或写入任何日志，也不会在后台获取位置。
3. **应用内购买（自愿打赏）：** “设置 › 买杯咖啡”中的一次性打赏由 Apple 官方 **StoreKit 2** 框架处理，开发者无法获取您的 Apple ID 或任何支付信息。应用启动时也会通过 StoreKit 确认安装来源（App Store 或 TestFlight），不会向开发者发送任何个人信息。

如有任何疑问，请联系：[rewind.feedback@gmail.com](mailto:rewind.feedback@gmail.com)。

---

## 隱私權政策（繁體中文）

**生效日期：** 2026年10月26日<br>
**開發者：** Yang Song ([rewind.feedback@gmail.com](mailto:rewind.feedback@gmail.com))

**祥雲相機**（國際版名稱：**XY Camera**）嚴格遵循**純本機隱私保護原則**：

1. **零資料收集與零第三方追蹤：** 本應用不收集、不傳送、不儲存亦不出售您的任何個人資料、照片、影片、錄音、地理位置或使用分析資料。應用內不包含任何第三方分析 SDK、廣告框架或雲端帳號系統。
2. **裝置權限說明：**
   - **相機與麥克風：** 僅用於即時取景、拍攝照片與錄製影片聲音，以及顯示即時立體聲電平表。
   - **照片圖庫：** 僅在您選擇將拍攝內容儲存或匯出至系統「照片」App 時使用。
   - **使用期間的位置資訊（選用）：** 僅當您在應用「設定」中主動開啟「記錄位置資訊」時才會請求授權。開啟後，GPS 座標僅寫入儲存在您裝置上的照片或影片檔案中繼資料，絕不會上傳或記錄於任何日誌。
3. **App 內購買（自願打賞）：** 「設定 › 買杯咖啡」中的一次性打賞完全由 Apple 官方 **StoreKit 2** 處理，開發者不會取得您的 Apple ID 或付款資訊。App 啟動時也會透過 StoreKit 確認安裝來源（App Store 或 TestFlight），不會向開發者傳送任何個人資料。

如有任何問題，請聯絡：[rewind.feedback@gmail.com](mailto:rewind.feedback@gmail.com)。

---

© 2026 Yang Song. All rights reserved.
