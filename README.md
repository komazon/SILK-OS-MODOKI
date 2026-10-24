# SILK OS
Scratchで動くOSもどき！  
https://scratch.mit.edu/projects/1395218024/
## **開発理由**  
久しぶりに何か作りたかったから。  

## **コンセプト**  
限界ブロック数節約  

## **特徴** 
引数間などの空白にとても厳格(手抜k
## **注意**
* defaultユーザーのパスワードは0000です。
* パス指定はルートは`/`、それ以外は`user/default/`のように
## **使用できるコマンド**  

### ls  
##### 使用例:  
`ls /`  

### kuminote  
##### 使用例:  
`kuminote cheat_sheet.txt`  
※フルパス指定です。
※保存は↑+S  

### cd  
##### 使用例:  
`cd user/`  


### mkdir  
##### 使用例:  
`mkdir test_folder`  
※これはCurrentに作成されます  


### touch  
##### 使用例:  
`touch test.txt`  
※これはCurrentに作成されます  

### echo  
##### 使用例:  
`echo sieg_zeon`  
### newuser
引数なし。(対話型です)  


### rm
##### 使用例:  
`rm test_folder/`  

### about
##### 引数なし。ディストリビューションの詳細が出ます。

### clear
##### 引数なし。画面がリセットされます

### shutdown
##### 引数なし。停止します。それだけやで
