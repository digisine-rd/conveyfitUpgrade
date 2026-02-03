### 🚀 ConveyFit
本工具使用 Squirrel.Windows 框架，支援靜默背景更新與快速安裝。

安裝: 下載最新版本 Setup.exe，系統將自動完成安裝並建立桌面捷徑。

更新: 程式啟動時會自動檢查 GitHub Releases。若有新版本，系統將在背景下載並於下次啟動時自動套用。

### 🛠 技術架構
開發框架: .NET / WPF (MVVM 架構)

通訊協議: BLE (Bluetooth Low Energy), USB HID

資料格式: JSON, Protobuf (CRM 通訊)

部署工具: Squirrel.Windows (v2.0+)

### 📦 版本發布與 Squirrel 更新說明
每次版本發布皆包含以下必要檔案：

RELEASES: Squirrel 用來辨識版本差異的索引檔。

ConveyFit-X.X.X-full.nupkg: 完整的安裝包。

ConveyFit-X.X.X-delta.nupkg: (選填) 增量更新包，用以減少使用者更新時的流量。
