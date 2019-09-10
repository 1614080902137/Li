## windows下
### 配置环境变量
    运行 bin/startup.bat 前需配置环境变量 JAVA_HOME
    步骤：
        在系统变量新建 JAVA_HOME ，配置路径为 jdk 的安装路径（注意不是 bin ）
### 修改启动端口（修改配置文件 conf/server.xml）
    <Connector port="8088" protocol="HTTP/1.1"
               connectionTimeout="20000"
               redirectPort="8443" URIEncoding="UTF-8"/>
               
    "port"是启动端口，"URIEncoding"是设定编码
