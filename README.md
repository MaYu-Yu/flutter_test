# Flutter First Program

* # 架設環境

  ## 測試環境 
      Windows 11 22H2  
  ## Flutter環境架設
  ### [flutter SDK](https://docs.flutter.dev/get-started/install/windows) 安裝
   <img width="570" alt="Screenshot 2023-08-24 142503" src="https://github.com/MaYu-Yu/flutter_test/assets/59922656/1347abbe-6684-4c84-a630-23e5c1622124">

  ### 將 Your Path\flutter\bin加入環境變數
 <img width="112" alt="1" src="https://github.com/MaYu-Yu/flutter_test/assets/59922656/7deacb6e-ac01-4a96-ae53-15061eda7851">

  ### cmd輸入 flutter doctor 確認安裝成功，且上面會顯示尚需安裝那些軟體  
<img width="770" alt="2" src="https://github.com/MaYu-Yu/flutter_test/assets/59922656/aeeace47-4a78-432b-9ad3-fc22f00c7f50">

  ### GPT詢問需安裝軟體如下
  根據您提供的信息，您遇到了Flutter Doctor的一些問題，主要是與Android開發環境、Chrome和Visual Studio相關的問題。以下是解決這些問題的步驟：

  1. **Android toolchain - develop for Android devices**：
     這個問題表示Flutter無法找到Android SDK。您需要安裝Android SDK。您可以按照下面的步驟安裝：
  
     - 下載並安裝Android Studio：訪問 [https://developer.android.com/studio/index.html](https://developer.android.com/studio/index.html) 下載並安裝Android Studio。
     - 安裝Android SDK組件：首次運行Android Studio時，它將引導您安裝所需的Android SDK組件。確保按照指示完成此過程。
  
  2. **Chrome - develop for the web**：
     這個問題表示Flutter找不到Chrome瀏覽器。您可以通過設置CHROME_EXECUTABLE環境變量來解決這個問題，讓Flutter知道Chrome瀏覽器的位置。假設您的Chrome瀏覽器位於默認位置，請執行以下步驟：
  
     - 打開命令提示符。
     - 運行以下命令來設置CHROME_EXECUTABLE環境變量，將路徑替換為您的Chrome瀏覽器安裝路徑：
       ```
       setx CHROME_EXECUTABLE "C:\Program Files\Google\Chrome\Application\chrome.exe"
       ```
     - 重啟計算機或重新打開命令提示符以使更改生效。
  
  3. **Visual Studio - develop Windows apps**：
     這個問題表示Flutter需要Visual Studio來開發Windows應用程序。您可以按照以下步驟安裝Visual Studio：
  
     - 訪問 [https://visualstudio.microsoft.com/downloads/](https://visualstudio.microsoft.com/downloads/) 下載並安裝Visual Studio。
     - 在安裝期間，請確保選擇 "Desktop development with C++" 工作負載以及它的默認組件。
  
  4. 最後，您可以嘗試運行以下命令來更新Flutter配置中的Android SDK位置。確保提供正確的Android SDK路徑：
  
     ```
     flutter config --android-sdk /path/to/android/sdk
     ```
  
     將 "/path/to/android/sdk" 替換為您的Android SDK的實際路徑。
  
  完成這些步驟後，再次運行 `flutter doctor` 命令，應該會顯示更多√標記，表明您的環境已經配置好了。如有需要，請確保按照錯誤消息中提供的鏈接查看詳細說明。
  
  ### [Android Studio](https://developer.android.com/studio) 安裝
  <img width="544" alt="Screenshot 2023-08-24 143338" src="https://github.com/MaYu-Yu/flutter_test/assets/59922656/3a2c0694-966d-43f3-9b96-cd7cccb3220d">

  ### 將更新Flutter配置中的Android SDK位置:
<img width="518" alt="4" src="https://github.com/MaYu-Yu/flutter_test/assets/59922656/26484dda-12cb-4761-8b7c-3243f06952e5">

  ### 安裝Chrome
* # 參考網站
- Flutter - https://docs.flutter.dev/get-started/install
- 
