# issues

## 1.上传失败，未知错误

```
Techless+Function+Job
Start:+2019-03-05+00:01:50
Job+ID:+5c7d4beca49b7cc1701e25af
Log:+https://tfapi.alipay.com/logs/5c7d4beca49b7cc1701e25b0
Function+Name:+tf-tiny-builder
Function+Image:+reg.docker.alibaba-inc.com/tf/tf-tiny-builder:3cd21f20190304215217322
Runtime+Version:+@alipay/techless-function@3.12.6
Runtime+Image+Version:+reg.docker.alibaba-inc.com/images/techless-function:1.6.0-centos7-node
Environment:+prod
Memory:+1GB
CPU:+1
Hostname/IP:+i32d01249.sqa.eu95/11.166.207.42
[INFO]+开始执行+下载构建包
[ERROR]+构建失败:+
==============================
Run+"sh+-c+find+./+-type+l"+error,+exit+code+1
Error:+Run+"sh+-c+find+./+-type+l"+error,+exit+code+1
++++at+ChildProcess.proc.on.code+(/home/admin/.function/node_modules/_runscript@1.3.0@runscript/index.js:74:21)
++++at+ChildProcess.emit+(events.js:189:13)
++++at+maybeClose+(internal/child_process.js:970:16)
++++at+Process.ChildProcess._handle.onexit+(internal/child_process.js:259:5)
stdio:+{+stdout:+null,+stderr:+<Buffer+66+69+6e+64+3a+20+27+2e+2f+70+61+67+65+73+2f+63+6e+6f+64+65+27+3a+20+50+65+72+6d+69+73+73+69+6f+6e+20+64+65+6e+69+65+64+0a+66+69+6e+64+3a+20+27+2e+2f+...+>+}

```

>之后再上传就好了，可能是底层的问题