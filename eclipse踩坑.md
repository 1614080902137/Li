# 关于 Maven
#### 创建 maven 项目
* 步骤：
  * 新建 Maven Project，填写项目信息
# 关于 Tomcat
#### 配置 tomcat
* 步骤：  
  * Window -> Preferences -> Server ->Runtime Environments，  
  * 点击 Add... 添加，  
  * 然后在 Window -> Show View 中找到 Servers 模块进行配置
#### 新建 Maven 项目后需要添加tomcat依赖
* 步骤：
  * 点开项目的 Build Path，
  * 选择 Libraries，
  * 点击 Add Libray...，
  * 选择 Server Runtime，
  * 添加 tomcat（前提是eclipse已经配置了tomcat），
  * finish
#### 启动报错
* 可能是 Servers 里的配置文件出错（出现多个<Context />）
