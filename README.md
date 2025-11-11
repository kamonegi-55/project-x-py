依存からuvloopを削除してWindowsでもインストールできるようにしました。

このプロジェクトでは、環境変数を管理するために .env ファイルを使用しています。  
.env.example をコピーして.env にリネームしてください。  
.env ファイルを開き、必要に応じて値を編集してください。  

補足: examples/00_trading_suite_demo.py および examples/01_basic_client_connection.py にはすでに以下のコードが含まれています。  
```
from dotenv import load_dotenv
load_dotenv()
```
そのため、.env ファイルに定義した環境変数は自動的に読み込まれます。
