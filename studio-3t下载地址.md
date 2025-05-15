https://download.studio3t.com/studio-3t/windows/2023.9.0/studio-3t-x64.zip

注册的时候输入的邮箱地址

111@gmail.com
其他都是1111
加入
127.0.0.1 license-portal-eb.studio3t.com
127.0.0.1 update.studio3t.com

1.执行install-all-users.vbs

2.Studio 3T.vmoptions加入

--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED

-javaagent:E:\Develop\Studio3T\jetbra\ja-netfilter.jar=jetbrains

3.jetbra\vmoptions\studio.vmoptions

修改

-javaagent:E:\Develop\Studio3T\jetbra\ja-netfilter.jar=jetbrains
