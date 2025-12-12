# hidencloud-new
游戏机hidencloud自动续期
📌 补充：GitHub Actions yaml 里要这样写

如果你是在 Actions 用这个脚本，记得在 yaml 里把 Secrets 传进去：

env:
  HIDENCLOUD_COOKIE: ${{ secrets.HIDENCLOUD_COOKIE }}
  HIDENCLOUD_EMAIL: ${{ secrets.HIDENCLOUD_EMAIL }}
  HIDENCLOUD_PASSWORD: ${{ secrets.HIDENCLOUD_PASSWORD }}


如果你不用账号密码，那就删掉后两个。
