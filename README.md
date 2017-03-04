# print-maven-plugin
this repository include my demo projects

这是一个最简单的maven插件demo,定义了一个目标(touch),默认将touch绑定到PROCESS_SOURCES阶段

touch目标中提供了一个输入参数word,使用时通过-D命令为word指定值

运行该插件不需要依赖任何maven项目,可以直接在命令行中执行,执行的结果就是在命令行输出通过word
传入的值

如mvn com.zhqh.plugin:print-maven-plugin:touch -Dword=haha,执行完就可以在命令行中看到haha被输出
