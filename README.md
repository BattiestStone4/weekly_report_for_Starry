# Starry-on-ArceOS完善

基础测例未实现syscall列表：

| syscall_id | syscall_name |
| ---------- | ------------ |
| 40         | mount        |
| 80         | fstat        |
| 153        | times        |
| 214        | brk          |

2025/1/10: 同步进度：getdents64，unlinkat，linkat，uname实现。

2025/1/9: 同步进度：openat实现。

2025/1/8: 同步进度：execve，chdir，mkdirat实现。