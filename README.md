# betterSup

old repo
https://github.com/pressly/sup



增加了ssh密码登录

# Supfile

---

`version: 0.4`

`env:`

`  NAME: api`

`  IMAGE: example/api`

`networks:`

`  local:`

`    hosts:`

`      - root@test:1222  123456`

`commands:`

`  echo:`

`    desc: Print some env vars`

`    run: echo nihao`
