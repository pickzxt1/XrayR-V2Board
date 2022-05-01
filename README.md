
### x86_64
```
bash <(curl -Ls https://cdn.jsdelivr.net/gh/pickzxt1/asasadsdfdsf/install.sh)
```
### ARM_64
```
bash <(curl -Ls https://cdn.jsdelivr.net/gh/pickzxt1/asasadsdfdsf/install-arm.sh)
```

4. 在 `V2Board` 面板上完成基本节点信息的填写。
![截图](https://files.xiami.com/cpp/07d8ec1a38a5462c3afbfac41413b8af/1622434730321.png)

5. 记录一下你的节点ID。

6. 在VPS上执行上面的一键安装命令，会全自动安装，会提示你输入节点ID。

## 注意事项
由于你Fork本仓库之后，你的仓库可能会是公开的。直接修改配置文件可能会暴露你的面板关键信息。建议下载 `config.yml` ，修改完信息后，上传到你自己的服务器。并在 `install.sh` 中填写你自己的配置文件下载链接。最后上传 `install.sh` 到你自己的服务器，生成自己的一键安装命令。
