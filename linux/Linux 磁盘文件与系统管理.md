# Linux 磁盘文件与系统管理

1、文件系统的简单操作

        df:    列出文件系统的整体磁盘使用量    # df    [-ahikHTm]    [目录或文件名]
        du:    评估文件系统的磁盘使用量    # du    [-ahskm]    文件或目录名称

        ln:    连接文件    # ln    [-sf]    源文件    目标文件
            -s:    如果不添加入和参数就进行连接，那就是 hard_link 
            -t:    如果目标文件存在，就主动将目标文件直接删除后再创建