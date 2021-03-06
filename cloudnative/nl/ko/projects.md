---

copyright:
  years: 2016, 2017
lastupdated: "2017-03-17"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# 프로젝트
{: #projects}

{{site.data.keyword.Bluemix}} {{site.data.keyword.dev_console}}은 앱 사용자 인터페이스, 데이터 및 서비스를 하나의 완전한 *프로젝트*로 결합합니다. 프로젝트를 작성하여 앱의 모든 필수 파트와 추가된 기능을 {{site.data.keyword.Bluemix_notm}} 서버에서 유지보수합니다. 사용자는 앱 코드를 다운로드할 수 있으며 서비스가 프로젝트 내에 구성된 경우에는 필수 신임 정보 및 초기자(initializer)도 다운로드할 수 있습니다. **프로젝트**를 선택하여 모든 프로젝트를 볼 수 있습니다.   

**프로젝트** 페이지에서 프로젝트를 선택하여 하나의 프로젝트에 대한 추가 정보를 볼 수 있습니다. 이를 수행하면 **프로젝트 개요** 페이지가 표시되며, 이 페이지는 해당 프로젝트용으로 구성되고 사용 가능한 서비스를 포함합니다. 서비스는 기능을 추가하여 앱을 확장하는 별도의 기능입니다. 서비스는 개별적으로 추가되므로 푸시 서비스, 인증, 데이터 및 스토리지 또는 기타 서비스 등 필요한 서비스를 추가할 수 있습니다. **프로젝트 개요** 페이지에서 프로젝트에 서비스를 추가하고 지시사항에 따라 이를 구성하면 해당 서비스가 자동으로 앱과 연관됩니다. 프로젝트 개요 페이지에 대한 자세한 정보는 [프로젝트 개요 페이지](project_overview_page.html)를 참조하십시오. 

프로젝트를 작성하려면 [패턴](patterns.html) 및 [스타터](starters.html)를 선택해야 합니다. 


## 프로젝트 개요 페이지
{: #project_overview}

**프로젝트** 페이지에서 프로젝트를 선택하여 하나의 {{site.data.keyword.Bluemix}} {{site.data.keyword.dev_console}} 프로젝트를 보고 이에 대한 작업을 수행할 수 있으며, 이렇게 선택하면 프로젝트 개요 페이지가 열립니다.
{: shortdesc}

**프로젝트 개요** 페이지는 선택한 프로젝트에 대해 구성되거나 구성하는 데 사용 가능한 각 기능에 대해 하나의 타일을 표시합니다. 타일은 기능의 유형과 3개의 수직 정렬된 점이 있는 *조치* 단추를 표시합니다. 사용 가능하거나 구성된 서비스의 예에는 {{site.data.keyword.mobilepushshort}}, 분석 또는 데이터 및 스토리지가 포함됩니다. 호환 가능한 기능은 프로젝트 유형 및 해당 지역에서 사용 가능한 기능에 따라 달라지므로, 모든 기능을 모든 프로젝트와 연관시킬 수는 없습니다.  

기능 유형이 아직 프로젝트와 연관되지 않은 경우에는 **작성** 단추가 타일에 표시됩니다. 이 조치 단추 옵션은 기능이 아직 연관되지 않은 경우 서비스의 인스턴스를 작성하거나 기존 서비스 인스턴스를 추가하는 용도로 사용됩니다. **기존 추가**를 선택하면 사용자의 영역에 있는 해당 유형의 서비스 인스턴스 목록이 제공됩니다. 

기능이 이 프로젝트와 이미 연관된 경우에는 기능 유형 뒤에, 연관된 서비스 인스턴스의 이름이 타일에 표시됩니다. 이를 통해 {{site.data.keyword.dev_console}}에서 이 프로젝트와 관련된 서비스 인스턴스를 쉽게 찾을 수 있습니다. 기능이 이미 프로젝트와 연관된 경우, 조치 단추에서 사용 가능한 조치는 **보기** 및 **제거**입니다. 서비스 인스턴스를 제거하면 이 프로젝트에 대한 연관만 제거되며 {{site.data.keyword.dev_console}}에서 서비스 인스턴스가 삭제되지는 않습니다. 서비스 인스턴스를 삭제하려면, 서비스 인스턴스를 보고 삭제할 수 있도록 **웹 및 모바일 > 서비스** 페이지를 클릭하십시오. 

**코드** 타일에서 **코드 가져오기**를 선택하여 프로젝트의 코드를 다운로드하십시오. 코드 다운로드에 대한 자세한 정보는 [코드 가져오기](get_code.html)를 참조하십시오. 


## 새 스타터를 사용하도록 프로젝트 업데이트
{: #update-starter}

1. **프로젝트** 또는 **프로젝트 개요** 페이지에서 **오버플로우 메뉴** 아이콘을 클릭하고 **스타터 업데이트**를 선택하십시오. 

2. 새 스타터를 선택하고 **업데이트**를 클릭하십시오. 

3. **프로젝트 개요** 페이지에서 **코드 가져오기**를 클릭하여 언어를 선택하십시오. 

   또는 **코드** 페이지를 클릭할 수 있습니다.


## 새 언어를 생성하도록 프로젝트 업데이트
{: #update-language}

1. **프로젝트** 또는 **프로젝트 개요** 페이지에서 **오버플로우 메뉴** 아이콘을 클릭하고 **스타터 업데이트**를 선택하십시오. 

2. 새 언어를 선택하고 **업데이트**를 클릭하십시오. 

3. **프로젝트 개요** 페이지에서 **코드 가져오기**를 클릭하여 언어를 선택하십시오. 
