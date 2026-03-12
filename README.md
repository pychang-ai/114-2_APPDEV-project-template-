# 114-2 APP 開發

## 目錄
- [課程資訊](#課程資訊)
- [課程說明](#課程說明)
- [作業繳交方式](#作業繳交方式)
- [課程進度表](#課程進度表)
- [小考說明](#小考說明)
- [期末專題](#期末專題)
- [課程工具與教材對應表](#課程工具與教材對應表)
- [評分比例](#評分比例)
- [Git 基本流程](#git-基本流程)

---

## 課程資訊
| 項目 | 說明 |
|------|------|
| 課程名稱 | APP 開發 |
| 學期 | 114 學年度第 2 學期 |
| 課程 GitHub | [114-2_APPDEV 主頁](https://github.com/pychang-ai/114-2_APPDEV/blob/main/README.md) ｜ [期末專題規範](https://github.com/pychang-ai/114-2_APPDEV/blob/main/README.md#%E6%9C%9F%E6%9C%AB%E5%B0%88%E9%A1%8C) |
| 授課對象 | 大三以上 |
| 每週上課 | 3 小時 |
| 教科書/教材 | 1. [GeeksforGeeks: Java Tutorial](https://www.geeksforgeeks.org/java/java/) (W1-W6)<br>2. 依據課程教學大綱 (W7-W18) |
| 實作環境 | 第 1-6 週：VS Code + Java Extension (或線上編譯器)<br>第 7 週起：本機端 Android Studio、AWS EC2 (後端服務) |

## 課程說明
本課程分為兩大階段。由於設備考量與技術打底，**第一階段（第 1-6 週）將專注於 Java 物件導向程式設計 (OOP) 的核心觀念**，涵蓋類別與物件、封裝、繼承、多型與介面，這將為後續的 App 開發打下堅實的邏輯基礎。**第二階段（第 7 週起）將正式進入 Android App 開發**，涵蓋 UI 佈局、生命週期、資料儲存與網路 API 串接。

課程後期將結合 AWS EC2 建立專屬後端服務，並於第 10 週起導入 AI 輔助開發流程。我們將學習 Prompt Engineering 技巧，掌握如何對 ChatGPT、Copilot 等 AI 工具下達有效指令，輔助程式碼撰寫、架構優化與除錯，核心原則為「先理解再使用」。

## 作業繳交方式
本課程採用業界標準的 **Fork + Pull Request** 流程繳交作業：
1. Fork 本 Repo 到你的 GitHub 帳號。
2. 在你的 Fork 中建立每週資料夾（如 `week01/`）並完成作業。
3. 發 Pull Request 回本 Repo 繳交。

## 課程進度表

### 第一階段：Java OOP 核心基礎 (對應 GeeksforGeeks 教材)
| 週次 | 教學內容 | 對應 GfG 網頁主題與連結 | 作業與專題進度 |
|------|---------|------------------------|---------------|
| **W1** | **課程導論與 Java 環境建置**<br>Git 操作。Java 基本語法：資料型態、變數、運算子。 | - [Java Basics](https://www.geeksforgeeks.org/java-basics/)<br>- [Java Operators](https://www.geeksforgeeks.org/operators-in-java/) | 建立 GitHub 帳號、完成首次 Fork+PR。 |
| **W2** | **流程控制與陣列**<br>If-else、Switch、迴圈 (for/while)、陣列、String 處理。 | - [Java Flow Control](https://www.geeksforgeeks.org/flow-control-in-java/)<br>- [Java Arrays](https://www.geeksforgeeks.org/arrays-in-java/)<br>- [Java String](https://www.geeksforgeeks.org/strings-in-java/) | 作業：實作基礎演算法（如九九乘法表、陣列處理）。 |
| **W3** | **類別與物件 (Classes & Objects)**<br>OOP 精神、定義 Class、建立 Object、屬性、方法、建構子。 | - [Java OOPs Concepts](https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/)<br>- [Classes & Objects](https://www.geeksforgeeks.org/classes-objects-java/) | **專題分組、建立 Repo**。<br>作業：設計「海洋生物」類別並實例化。 |
| **W4** | **封裝與繼承 (Encapsulation & Inheritance)** + **小考 1**<br>Access Modifiers、`extends`、`super` 關鍵字。 | - [Java Encapsulation](https://www.geeksforgeeks.org/encapsulation-in-java/)<br>- [Java Inheritance](https://www.geeksforgeeks.org/inheritance-in-java/) | **個人專題題目探索**。<br>作業：實作海洋生物繼承架構。 |
| **W5** | **多型 (Polymorphism)**<br>方法多載 (Overloading)、方法覆寫 (Overriding)、`final`。 | - [Java Polymorphism](https://www.geeksforgeeks.org/polymorphism-in-java/) | **決定題目、繳交專題提案**。<br>作業：利用多型實作生物移動方式。 |
| **W6** | **抽象、介面與例外處理**<br>Abstract class、Interface (`implements`)、Try-catch。 | - [Java Abstraction](https://www.geeksforgeeks.org/abstraction-in-java/)<br>- [Java Interfaces](
