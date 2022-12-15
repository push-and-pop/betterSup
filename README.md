# betterSup

old repo
https://github.com/pressly/sup



增加了ssh密码登录

增加了选择端口

# Supfile

---

`version: 0.4`

`env:`

`  NAME: api`

`  IMAGE: example/api`

`networks:`

`  local:`

`    hosts:`

`      - root@test:12220  123456`

`commands:`

`  echo:`

`    desc: Print some env vars`

`    run: echo nihao`

其中123456是密码

12220是服务器ssh端口