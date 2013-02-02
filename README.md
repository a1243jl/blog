blog
====

テスト用のアカウントをDBに登録

rails c

User.create!(:account => "admin", :password => "test", :password_confirmation => "test")

exit


テストについて：

rails serverを立ちあがって

ブラウザのURLで”localhost:3000/sessions/”を開いてください。
