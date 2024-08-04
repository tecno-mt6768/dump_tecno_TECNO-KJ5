This file config will cpoy to system/etc/cloudengine
放置规则：
1 以申请的ID创建文件夹,例如1001000002
2 默认配置文件需要以ID命名的文本文件，并去除相应的文件后缀，例如1001000002
3 同样将默认资源文件放入该文件夹，其中json文件为可选项，根据项目要求选择是否放置json文件
.
├── 1001000002
│   ├── 1001000002
│   └── tran_cloud_pq_config.json(可选)
└── ReadMe.txt

1 directory, 3 files