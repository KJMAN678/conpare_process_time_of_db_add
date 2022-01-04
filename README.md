### DataFrame型のデータをAzure SQL へ登録する場合、to_sqlで処理する場合とfor文で1行ずつ処理する場合の処理速度を比較

|項目|処理時間|
|--|--|
|for文で1行ずつ登録:|14.4秒|
|to_sql で登録:|4.2秒|

### 参考サイト
1. [【Python】Pandasのデータフレームをテーブルに高速INSERTする](https://tkstock.site/2019/09/07/pandas-sql-table-insert/)  
2. [PandasのSql Upsertを試してみた](https://qiita.com/s2hap/items/b329ce4f9d6c229382ff)  
3. [pandas.DataFrame.to_sql 公式ドキュ](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_sql.html)  
4. [Azure 公式ドキュ 手順 3:pymssql を使用した SQL への接続を概念実証する](https://docs.microsoft.com/ja-jp/sql/connect/python/pymssql/step-3-proof-of-concept-connecting-to-sql-using-pymssql?view=sql-server-ver15)  
5. [Azure SQL Database（pyodbc）でSQLAlchemyを使う](https://rnakamine.hatenablog.com/entry/2020/12/01/000000)  
6. [Python SQLAlchemy：データソース名が見つからず、デフォルトのドライバーが指定されていません](https://www.webdevqa.jp.net/ja/python/python-sqlalchemy%EF%BC%9A%E3%83%87%E3%83%BC%E3%82%BF%E3%82%BD%E3%83%BC%E3%82%B9%E5%90%8D%E3%81%8C%E8%A6%8B%E3%81%A4%E3%81%8B%E3%82%89%E3%81%9A%E3%80%81%E3%83%87%E3%83%95%E3%82%A9%E3%83%AB%E3%83%88%E3%81%AE%E3%83%89%E3%83%A9%E3%82%A4%E3%83%90%E3%83%BC%E3%81%8C%E6%8C%87%E5%AE%9A%E3%81%95%E3%82%8C%E3%81%A6%E3%81%84%E3%81%BE%E3%81%9B%E3%82%93/828542518/)  
7. [SQLAlchemy ORMの基本的な使い方](https://qiita.com/TamaiHideaki/items/346bf843ee6ee1aa6e93)  
8. [SQLAlchemy で Delete するには？](https://qiita.com/nskydiving/items/eedd5cea88b5afdbfc49)  