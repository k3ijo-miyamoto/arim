# フォルダ構成
1. ルートフォルダ  
   前処理プロセス notebook  
   ARIMA分析プロセス notebook    
   頂いた技術課題パワポファイルを格納
2. dataフォルダ  
   data/originalフォルダ :  ダウンロードした気象庁データを格納   
   data/original-modifiedフォルダ：上記データのヘッダ部分調整、文字コード変換を施したデータを格納
   data/analyzeフォルダ：前処理プロセスによって生成された分析に利用するデータ

# 分析環境
OS : WIndows11 Home
Python : Python 3.9.18  
分析にあたって利用したLibrary(バージョン省略) :  numpy/pandas/sklearn/seabon/matplotlib/tkinter/statsmodels/statistics/pmdarima  
詳細はfreezeした結果としてrequirements.txtに記載

# 分析の流れ
以下、JupyterNotebookによる分析
1. 前処理  
   PreProcess Notebookにより実施  
   温暖化が観察できるか？の所見も含む
2. ARIMAによる分析  
   ARIMA-model Notebookにより実施