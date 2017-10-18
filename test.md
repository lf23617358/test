## BankWiz 2.0  

#### bankwiz-commons
放置BankWiz中可以共用的lib
- **bankwiz-ha**  
  實作high availability lib
- **bankwiz-setting**  
  共用設定檔讀寫lib
- bankwiz-security  
  密碼加解密API,Payload編碼解碼API,Data Masking
- bankwiz-data-exchange  
  共用資料交換lib 
- bankwiz-ems-starter  
  共用設定EMS存取相關Spring Bean設定
- bankwiz-db-starter  
  共用設定DB存取相關Spring Bean設定
- bankwiz-dependencies  
  POM 共用Dependencies lib設定
***
#### bankwiz-framework
放置Framework各模組
- bankwiz-framework-mediation  
  Service Mediation
- bankwiz-framework-pattern  
  Framework Pattern
- bankwiz-framework-adapter  
  Framework Adapter
- bankwiz-framework-core  
  Framework所會使用到的java程式碼
***
#### bankwiz-manager
放置Manager各模組
- bankwiz-manager-auth  
  Authorization and Authentication Management  
  **Component:**
  * Account Management
  * Role Management
- bankwiz-manager-framework-mgr  
  Framework Management  
  **Component:**
  * Mapping Table Management
  * Error Code Management
  * Service Provider Management
  * Data Mask Management
- bankwiz-manager-notification  
  **Component:**
  * Notification Management
- bankwiz-manager-basic-setting  
  **Component:**
  * Basic Setting Management
- bankwiz-manager-governance  
  Governance Tool
  **Component:**
  * Design Time Tool
  * Run Time Tool
- bankwiz-manager-monitoring  
  Monitoring
- bankwiz-manager-logging  
  Logging  
  **Component:**
  * Message Routing Log
  * Error Statistics
- bankwiz-manager-parent  
  manager共用parent pom設定,包含模糊化設定,dependency jar,etc...
- bankwiz-manager-basic  
  模組共用jar,layout,js,css,i18n,etc...
- bankwiz-manager-security  
  安全相關處理模組
- bankwiz-manager-starter  
  manager啟動jar,可設定需要包含哪些jar
***
#### bankwiz-daemons
放置啟動後會持續監聽的服務
- bankwiz-logging-daemon  
  Logging服務
- bankwiz-monitor-daemon  
  監控服務
- bankwiz-notification-daemon  
  通知服務
***
#### bankwiz-tools
放置可以用Command Line執行的utility
- bankwiz-deployment  
  Deployment Tool
- bankwiz-logging-cmd  
  Logging Command Line Tool,整合Logging Redo Utility,Logging Redo Stat Utility,etc...
