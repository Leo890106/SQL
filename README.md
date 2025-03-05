#Record what i learned

資料庫可以是各式各樣的, 儲存的地方也是。 
    
    1.可以是電話簿，他儲存在書裏面
    2.可以是todo-list 寫在紙上
    3.可以是facebook的用戶資料儲存在伺服器上

DBMS (Data Base Management System)是一種軟體，旨在有效地管理、組織和檢索數據，確保數據的完整性、安全性，並支持多應用程式的並發訪問。 

主要功能：

    1.數據存儲與檢索：提供創建、更新和檢索數據的功能，並以有組織的方式管理數據。 
    2.數據安全性：確保數據的安全性，防止未經授權的訪問和修改。 
    3.數據完整性：通過約束和規則，維護數據的一致性和準確性。
    4.並發控制：支持多用戶同時訪問數據，並確保數據的一致性。

常見的 DBMS 類型：

關聯式資料庫管理系統（RDBMS）：使用表格來存儲數據，並通過結構化查詢語言（SQL）進行操作。 
SPLUNK

NoSQL 資料庫管理系統：適用於存儲非結構化或半結構化數據，提供靈活的數據模型。 
GEEKSFORGEEKS

常見的 DBMS 示例：

關聯式：MySQL、Oracle、Microsoft SQL Server、PostgreSQL。

NoSQL：MongoDB、Cassandra、DynamoDB、Redis。
    

primary key : colum的內容必須是唯一存在 滿足此條件稱之
foregin key : 連結到另一個資料表的colum 並且這個colum的值是另一個資料表的primary key
compond key : 當你與其他表格有關連的key並非唯一時 並需要與另一個colum組合成compond key使唯一性存在
              (即使兩個欄位都並非唯一的key 他們組合有可能形成唯一)
將兩個foregin key組合成primary key是很常見的作法