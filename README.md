# 幻世錄 Remake 程式 MOD

《幻世錄 Remake》（Steam 版）的 BepInEx 程式 MOD。
裝好之後，遊戲主選單「創意工坊」會多一張「程式模組」卡片，可以直接在遊戲裡下載、更新、移除下面這些 MOD。

## 第一次安裝

1. 到 [Releases](https://github.com/qqfat/hslr-mods/releases) 下載最新的全套安裝包 `HSLR_Mods_BepInEx_<日期>.zip`。
2. 在 Steam 對「幻世錄 Remake」按右鍵 → 管理 → 瀏覽本機檔案，把 zip 解壓縮到打開的資料夾（跟 `HSLR.exe` 同一層）。
3. 啟動遊戲。第一次啟動 BepInEx 要準備檔案，會多等約 30 秒。

## 之後的更新

主選單「創意工坊」→「程式模組」：每個 MOD 都可以安裝、更新、移除，**重開遊戲後生效**。
有新版本時主選單會提示一次。設定檔（`BepInEx\config`）與存檔裡的 MOD 資料都不會被動到。

## MOD 清單

| MOD | 版本 | 更新日期 | 說明 |
|---|---|---|---|
| 讀檔加速 | [0.5.1](https://github.com/qqfat/hslr-mods/releases/download/FastLoad-v0.5.1/HSLR_FastLoad_plugin_20260925.zip) | 2026-09-25 | 讀檔寫死的等待歸零、淡入淡出縮短 |
| 一鍵快速存讀 | [0.3.0](https://github.com/qqfat/hslr-mods/releases/download/QuickSave-v0.3.0/HSLR_QuickSave_plugin_20260925.zip) | 2026-09-25 | 快速存讀跳過確認，讀檔選單多一格 Quick Save |
| 跳過版本選擇 | [1.1.0](https://github.com/qqfat/hslr-mods/releases/download/SkipLauncher-v1.1.0/HSLR_SkipLauncher_plugin_20260925.zip) | 2026-09-25 | 跳過啟動時的版本選擇視窗與公司 logo（在設定裡選直接進重製版或經典版，預設照樣詢問） |
| 排組牌圖 | [1.0.0](https://github.com/qqfat/hslr-mods/releases/download/DeckHover-v1.0.0/HSLR_DeckHover_plugin_20260925.zip) | 2026-09-25 | 排組畫面滑鼠移到清單上時顯示牌圖與敘述 |
| 道具組合 | [1.7.0](https://github.com/qqfat/hslr-mods/releases/download/ItemPreset-v1.7.0/HSLR_ItemPreset_plugin_20260925.zip) | 2026-09-25 | 每個角色各自的道具組合，F7 全隊套用、F8 組合頁 |
| 一鍵收納（鎖定排除版） | [2.2.0](https://github.com/qqfat/hslr-mods/releases/download/StashLock-v2.2.0/HSLR_StashLock_plugin_20260925.zip) | 2026-09-25 | 背包列上鎖的道具不收，其他全收進倉庫 |
| 一鍵收納（勾選收納版） | [1.4.0](https://github.com/qqfat/hslr-mods/releases/download/StashSelect-v1.4.0/HSLR_StashSelect_plugin_20260925.zip) | 2026-09-25 | 只把勾選的道具收進倉庫 |
| 批量買賣 | [1.3.0](https://github.com/qqfat/hslr-mods/releases/download/BulkTrade-v1.3.0/HSLR_BulkTrade_plugin_20260925.zip) | 2026-09-25 | 倉庫畫面直接販賣，商店買賣可選數量 |
| 設定視窗修復 | [0.3.0](https://github.com/qqfat/hslr-mods/releases/download/ImguiFix-v0.3.0/HSLR_ImguiFix_plugin_20260925.zip) | 2026-09-25 | 修好 F10 設定視窗（ConfigurationManager）在這款遊戲一片灰的問題；設定視窗本身在全套包裡 |
| 切出去不斷聲音 | [1.0.0](https://github.com/qqfat/hslr-mods/releases/download/KeepAudio-v1.0.0/HSLR_KeepAudio_plugin_20260925.zip) | 2026-09-25 | 視窗失去焦點時音樂音效照放 |
| 程式模組管理 | [1.0.0](https://github.com/qqfat/hslr-mods/releases/download/ModManager-v1.0.0/HSLR_ModManager_plugin_20260925.zip) | 2026-09-25 | 主選單「創意工坊」→「程式模組」：直接在遊戲裡下載、更新、移除這些 mod（也會更新自己） |

注意：

- 「道具組合」＋「一鍵收納（鎖定排除版）」或「一鍵收納（勾選收納版）」：兩個預設都用 F7／F8，一起裝要先在設定裡改掉其中一邊的按鍵
- 「一鍵收納（鎖定排除版）」跟「一鍵收納（勾選收納版）」只能裝一個。

## 手動安裝單一 MOD

每個 MOD 的 zip 都在 [Releases](https://github.com/qqfat/hslr-mods/releases)。已經裝過 BepInEx 的話，
把 zip 解壓縮到遊戲資料夾即可（zip 裡是 `BepInEx\plugins\<MOD>\`）。移除就是刪掉那個資料夾。

---

這個 repo 只放發佈的檔案；`manifest.json` 是遊戲裡的程式模組管理器讀的清單，請不要手動改。
