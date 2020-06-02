# ginで作る簡易予定管理

# version
1.11.4

# go install
```
git clone https://github.com/syndbg/goenv.git ~/.goenv

vim .bash_profile
export GOENV_ROOT=$HOME/.goenv
export PATH=$GOENV_ROOT/bin:$PATH
eval "$(goenv init -)"

source .bash_profile

goenv install 1.11.4
goenv local 1.11.4
```

# gin install 
go get github.com/gin-gonic/gin

# gormをinstall
go get github.com/jinzhu/gorm

# sqlite3をinstall
go get -u github.com/mattn/go-sqlite3

# サーバー起動
go run main.go

http://localhost:8080/にアクセスします