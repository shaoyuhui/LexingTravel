    乐行旅游网
开发环境：IDEA2020、Tomcat9、Maven3.6.1、JDK1.8、MySql 8.0、Redis2.8
使用技术: JQuery,Servlet,Filter,Jackson,Ajax,Redis,MySQL,Druid,JDBCTemplate,三层架构,Tomcat,Maven
项目描述：实现了旅游网的基本功能：如用户的注册，用户的登录、用户的搜索、用户的注销、旅游项目列表展示、旅游信息的分页，翻页显示、用户的收藏。
项目总结：
1、使用 JavaScript 对用户注册信息进行动态验证。
2、使用 JavaMail工具类发送邮件激活用户状态，为后期对用户进行旅游信息推送。
3、使用 redis 对旅游列表数据缓存，提高查询速度，提升用户体验。