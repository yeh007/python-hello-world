# python-hello-world

Codespace實作，python hello world

好的，我來示範如何在 GitHub Codespaces 裡實作一個最簡單的 Python Hello World 專案。
步驟流程
1. 建立倉庫

    在 GitHub 建立一個新的 Repository，例如：python-hello-world。

    選擇 Add a README，方便初始化。

2. 啟動 Codespace

    進入你的 Repository 頁面，點擊 Code → Open with Codespaces → New codespace。

    GitHub 會自動建立一個雲端開發環境，打開 VS Code Web 介面。

3. 建立 Python 檔案

在 Codespace 的編輯器中建立一個檔案 hello.py，內容如下：
python

# hello.py
print("Hello, World!")

4. 執行程式

在 Codespace 的 Terminal 輸入：
bash

python hello.py

輸出結果會是：
程式碼

Hello, World!

延伸：互動式版本

你也可以讓程式接收使用者輸入：
python

# hello_input.py
name = input("請輸入你的名字: ")
print(f"Hello, {name}!")

執行後會互動式顯示：
程式碼

請輸入你的名字: Yiefeng
Hello, Yiefeng!

小結

在 Codespaces 中，因為環境已經預先安裝好 Python，你不需要額外設定，只要建立檔案並執行即可。這就是 Codespaces 的便利之處：快速啟動、一致環境、免安裝依賴。

