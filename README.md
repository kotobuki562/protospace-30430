# users テーブル

email...string 型 (NOT NULL)
password...string 型 (NOT NULL)
name...string 型 (NOT NULL)

---

profilr...text 型 (NOT NULL)
occupation...text 型 (NOT NULL)
position...text 型 (NOT NULL)

#　 comments テーブル

text...text 型 (NOT NULL)
user...references 型
prototype...references 型

# prototype テーブル

title...string 型 (NOT NULL)
catch_copy...text 型 (NOT NULL)
concept...text 型 (NOT NULL)

---

image...ActiveStorage で実装
user...references 型
