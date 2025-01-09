# **Paper Helper - 你閱讀論文的好幫手**

Paper Helper 是一個幫助學生輕鬆理解與報告學術論文的工具，具備以下功能：

1. **快速整理論文摘要**：讓你高效掌握重點內容。
2. **裁切並標註圖片**：從論文中提取圖片並生成說明。
3. **自動生成簡報**：一鍵生成包含摘要與圖片的 PPT。
4. **模擬問答卡片**：模擬教授提問，助你更自信地報告論文！

## **線上 Demo**

👉 [Demo Link](https://g11.papperhelper.xyz/)  

**登入頁面：**  
可以使用以下帳號登錄：  
- 帳號：`yumyuu`  
- 密碼：`Yumyuu123@`


---

## **ER Model**
![image error](https://github.com/yumyuu/2024_nccu_dbms/blob/main/img/ER.png)

---

## **Relational Schema**
![image error](https://github.com/yumyuu/2024_nccu_dbms/blob/main/img/Relation.png)

---

## **系統架構**
![image error](https://github.com/yumyuu/2024_nccu_dbms/blob/main/img/system_arc.png)

---

## **Report**
**[Report Link](https://github.com/yumyuu/2024_nccu_dbms/tree/main/report/Project_Report.pdf)**

---

# **Paper Helper 本地 Demo 使用說明**

## **1. 環境準備**

#### **在目錄 `\code\papper_helper` 中執行以下命令：**

1. 安裝 Python 依賴：
   ```bash
   pip install -r requirements.txt
   ```

2. 安裝 Node.js 依賴：
   ```bash
   npm install
   ```

---

## **2. 啟動本地服務**

需要啟動兩個本地服務：

1. **啟動圖片處理工具服務器：**
   - 進入目錄：`code\papper_helper\cropped_image_tool\src`
   - 執行以下命令：
     ```bash
     node server.js
     ```

2. **啟動主應用程序：**
   - 返回目錄：`code\papper_helper`
   - 執行以下命令：
     ```bash
     python app.py
     ```

---

## **3. 訪問首頁**

啟動服務後，在瀏覽器中打開以下地址即可訪問首頁：
```
http://localhost:8080
```

---

## **4. 注意事項**
- **API Key** 尚未加入 **`.gitignore`**，未來將移除至 **yaml 文件** 進行管理。

---