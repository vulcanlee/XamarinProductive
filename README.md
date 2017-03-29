# 說明
這裡提供進行 Xamarin.Forms 跨平台行動應用專案開發的時候，會用到的程式碼片段

# 安裝方式

* 點選 Visual Studio 2017 功能表，`工具` > `程式碼片段管理員`

* 修正 `語言` 欄位的下拉選單為 `CSharp`

* 點選底下 `加入` 按鈕 

* 選擇這個程式碼片段的本機目錄

* 點選底下 `確定` 按鈕 

# 使用方式

當您在編輯 C# 程式碼的時候，輸入

`vl`

就會看到相關的程式碼片段清單

# 可用的 Xamarin.Forms 程式碼片段

## 可綁定/附加屬性/原生注入宣告

* vlAttachedProperty

  附加屬性的程式碼片段

* vlBindableProperty

  可綁定屬性的程式碼片段

* vlOSDependency

  原生專案中相依性服務類別宣告

* vlRenderer

  客製控制項的 Renderer

## ViewModel 內的資料與命令

* vlMVVMObservableCollection

  用於產生 MVVM 內的集合類型 Property，且可以呼叫 OnPropertyChanged

* vlMVVMProperty

  用於產生 MVVM 內的 Property，且可以呼叫 OnPropertyChanged

* vlPrismCmd

  Prism 的 DelegateCommand 宣告

* vlPrismCmdPara

  Prism 有參數的 DelegateCommand 宣告

## 事件聚合器

* vlPrismIEventAggregator

  事件聚合器 建構式注入程式碼片段

* vlPrismIEventAggregatorDeclaration

  事件聚合器 保有注入物件的欄位程式碼片段

* vlPrismIEventAggregatorInitialization

  事件聚合器 將注入物件設定到欄位程式碼片段

* vlEventClass

  定義關注事件類別與Payload類別

## 導航服務

* vlPrismINavigationService

  導航服務 建構式注入程式碼片段

* vlINavigationServiceDeclaration

  導航服務 保有注入物件的欄位程式碼片段

* vlPrismINavigationServiceInitialization

  導航服務 將注入物件設定到欄位程式碼片段

## 對話窗服務

* vlPrismIPageDialogService

  對話窗服務 建構式注入程式碼片段

* vlPrismIPageDialogServiceDeclaration

  對話窗服務 保有注入物件的欄位程式碼片段

* vlPrismIPageDialogServiceDInitialization

  對話窗服務 將注入物件設定到欄位程式碼片段

## ViewModel Region

* vlViewModelRegionForModel

  ViewModel 內可資料繫結子類別的 Region

* vlViewModelRegionFullClass

  整個ViewModel 含類別名稱的完整 Region

* vlViewModelRegionSimpleClass

  整個ViewModel 含類別名稱的簡易 Region

## 其他

* vlXAMLCompilation

  XAML 編譯的宣告

* vlUWPTitleStatusBarInitialization

  UWP平台的狀態列配色

* vlUnityContainer

  取得 Prism 的 Unity 容器物件
  
  手動 註冊/解析 相依性物件


2017.03.29 Vulcan Lee
