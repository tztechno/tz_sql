# tz_sql

SELECT: データを取得するために使用されます。
SELECT column1, column2 FROM table WHERE condition;

INSERT: データを挿入します。
INSERT INTO table (column1, column2) VALUES (value1, value2);

UPDATE: データを更新します。
UPDATE table SET column1 = value1 WHERE condition;

DELETE: データを削除します。
DELETE FROM table WHERE condition;

CREATE TABLE: テーブルを作成します。
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    ...
);

ALTER TABLE: テーブルの構造を変更します。
ALTER TABLE table_name ADD column_name datatype;

DROP TABLE: テーブルを削除します。
DROP TABLE table_name;

CREATE INDEX: インデックスを作成します。
CREATE INDEX index_name ON table_name (column1, column2, ...);

ALTER INDEX: インデックスを変更します。
ALTER INDEX index_name RENAME TO new_index_name;

DROP INDEX: インデックスを削除します。
DROP INDEX index_name;

JOIN: テーブルを結合します。
SELECT column1, column2 FROM table1 JOIN table2 ON table1.column = table2.column;

GROUP BY: グループごとに結果をまとめます。
SELECT column1, COUNT(*) FROM table GROUP BY column1;

ORDER BY: 結果を指定した列で並び替えます。
SELECT column1, column2 FROM table ORDER BY column1 ASC, column2 DESC;

