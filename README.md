# jsb-for-ts
- 下载文件
- 复制并覆盖旧的bindings-generator文件夹
- python generator.py ./tools/tojs/test_jsb_ts.ini -s test_jsb_ts -t spidermonkey-ts -o ./tools/tojs/js_bindings/auto -n jsb_test_jsb_ts

### 配合tojs工具使用
- 打开genbindings.py文件
- 将变量target = 'spidermonkey' 修改为target = 'spidermonkey-ts'
- python genbindings.py
