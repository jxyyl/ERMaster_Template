ERMaster模板。使用ERMaster导出excel时，用自带的英文模板或自定义的中文模板，会报错，修复后格式会丢失。
现在提供修改后的英文及中文模板。

如果你自己要修改模板，用excel修改后，再用wps打开后另存就可以解决这个问题，或直接用wps修改保存。

如何使用自定义模板，请看帮助文档：https://ermaster.sourceforge.net/    -  22.3. Register template

另外，如果要从mysql数据库导入结构，经测试，使用mysql8及jdbc5的驱动可以实现导入，经测试过的版本是mysql-8.0.34-winx64与mysql-connector-java-5.0.8-bin.jar，
如何修改mysql的jdbc驱动，同样看https://ermaster.sourceforge.net/的说明。

对于导入后的中文乱码，需要在连接中，加入编码参数，具体如：jdbc:mysql://127.0.0.1:3306/wms?characterEncoding=utf-8
