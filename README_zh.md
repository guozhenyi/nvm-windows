# 编译打包

## 编译

```sh
cd src

go mod download

go build -o ../nvm.exe nvm.go

```

## 打安装包
```sh
buildtools\iscc.exe "./nvm.iss"
```
