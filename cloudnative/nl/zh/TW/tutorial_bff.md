---

copyright:
  years: 2016, 2017
lastupdated: "2017-03-17"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# BFF Basic Starter 的完整指導教學
{: #tutorial}

下列完整指導教學逐步執行從 BFF Basic Starter 建立專案的步驟，包括您必須安裝的工具，以及執行專案程式碼的步驟。

## 安裝開發人員工具
{: #dev_tools}

請確定您已安裝[必備開發人員工具 ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](get_code.html#prereq-dev-tools){: new_window}。


## 使用 {{site.data.keyword.dev_console}} 建立專案
{: #create-devex}

1. 在 {{site.data.keyword.Bluemix}} {{site.data.keyword.dev_console}} 中建立專案。

	1. 從 {{site.data.keyword.dev_console}} 的**開始使用**頁面中，按一下**建立專案**。

		您也可以按一下**專案**頁面中的**建立專案**。

	2. 選取 **Backend for Frontend**，然後按**下一步**。

	3. 選取 **Basic Backend**，然後按**下一步**。

	4. 輸入專案名稱。對於此指導教學，使用 `BFFProject`。   

	5. 輸入主機名稱。對於此指導教學，使用 `devhost`。 

	6. 選取語言平台。對於此指導教學，使用 `Node`。
   
	7. 按一下**建立**。

2. 選用項目：新增「資料」功能。

	1. 在**專案概觀**頁面上，針對**資料**按一下**檢視**。

      您也可以選取**功能 > 資料**頁面上的**建立**或**新增現有項目**。

   2. 輸入服務名稱，然後按一下**建立**。


3. 產生專案程式碼。

	1. 按一下**專案概觀**頁面上的**取得程式碼**，以選取您的語言。
   
		您也可以按一下**程式碼**頁面。
      
	2. 按一下**產生程式碼**。
   
	3. 當專案程式碼生成完成時，請按一下**下載程式碼**來下載專案保存檔。

4. 選用項目：[更新專案](project_overview_page.html#update_language)以產生新語言。


## 使用 {{site.data.keyword.dev_cli_notm}} 建立專案
{: #create-cli}

1. 確定您已安裝 [{{site.data.keyword.dev_cli_short}}](dev_cli.html)。

2. 在「終端機」提示字元中，導覽至您選擇的本端目錄，然後執行下列指令。
  
	```
	bx dev create
	```
	{: codeblock}
	
3. 系統提示時，提供下列值：

	* 選取型樣：3（適用於 Backend for Frontend）
	* 選取入門範本：1（適用於 Basic Backend）
	* 選取語言：1（適用於 Node）
	* 輸入專案的名稱：`BFFProjectCLI`
	* 輸入專案的主機名稱：`myhost`

4. 如果您要將服務新增至專案，請在問題提示字元中鍵入 `y`，並回答其餘的問題。

5. 順利儲存 `BFFProjectCLI` 後，請導覽至 `BFFProjectCLI` 資料夾。

6. 此時，您可能會新增自己的程式碼、建置或執行專案。
 
	1. 使用下列指令來建置專案：
   
		```
		bx dev build
		```     
		{: codeblock}
  
	2. 使用下列指令來執行專案：

 		```
		bx dev run
		```
		{: codeblock}


## 執行 BFF 專案
{: #running-bff}

### 本端
{: #bff-local}

1. 編譯伺服器：

  ```
  swift build
  ```
  {: codeblock}

2. 執行應用程式。例如，假設您的應用程式稱為 `MyServer`：

  ```
  .build/debug/MyServer
  ```
  {: codeblock}

3. 您可以使用 `curl http://localhost:8080`，在伺服器上執行 curl。


### 使用 Bluemix 外掛程式
{: #using-blumix}

1. 執行編譯

	```
	bx dev run
	```
	{: codeblock}

2. 您可以使用下列項目在伺服器上執行 curl： 
  
	```
	curl http://localhost:8080
	```
	{: codeblock}
