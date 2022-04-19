
```uml
@startuml

  ユーザー -> Webサーバー : コース選択
  Webサーバー -> DBサーバー : ユーザー登録
  DBサーバー -> DBサーバー : 登録処理
  DBサーバー -> Webサーバー : 登録結果
  alt 登録成功
    Webサーバー -> ユーザー : 登録成功
  else 登録失敗
    Webサーバー -> ユーザー : 登録失敗
  end
end

@enduml
```
