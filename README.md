# nas-tools-hhan
配合nas-tools工具，适配数据统计页面获取憨憨站点的信息

docker用户的使用方法
`docker exec -it nas-tools sh -c 'cd /nas-tools/app/sites/siteuserinfo && mv nexus_php.py nexus_php.py.bak && wget -O nexus_php.py https://github.com/GTian28/nas-tools-hhan/raw/main/nexus_php.py' && docker restart nas-tools`
