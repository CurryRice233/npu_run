一键安装命令

```shell
curl -fsSLk https://raw.githubusercontent.com/CurryRice233/npu_run/main/npu_run -o /usr/local/bin/npu_run && chmod +x /usr/local/bin/npu_run
```

如果你的环境中 curl 依然问题，可以尝试使用 wget 
```shell
wget --no-check-certificate -qO /usr/local/bin/npu_run https://raw.githubusercontent.com/CurryRice233/npu_run/main/npu_run && chmod +x /usr/local/bin/npu_run
```
