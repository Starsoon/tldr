# base64

> 将文件或标准输入编码到 Base64 或从 Base64 解码为标准输出。
> 更多信息：<https://manned.org/base64>.

- 编码一个文件：

`base64 {{路径/到/文件}}`

- 按特定宽度包装编码输出（“0”表示禁用包装）：

`base64 {{[-w|--wrap]}} {{0|76|...}} {{路径/到/文件}}`

- 解码一个文件：

`base64 {{[-d|--decode]}} {{路径/到/文件}}`

- 从标准输入编码：

`{{某指令}} | base64`

- 将标准输入解码：

`{{某指令}} | base64 {{[-d|--decode]}}`
