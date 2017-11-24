#简介
	swagger-server-api是一个GUI的WEB接口管理工具，基于 [swagger-ui](https://github.com/swagger-api/swagger-ui) 的后台API开源项目，采用SpringMvc+Maven3+Jdk1.7+Tomcat7。
	该项目的初衷是为了更好的去发展Swagger-ui与SpringMvc的结合，希望能够更加灵活，轻量化的根据后台不同的数据源展示出不同接口文档，满足日益增长的接口文档需求。
	这里包括（接口文档的格式，权限，视图，Mock数据，Api监控,自动化测试,接口文档分享，版本管理等）。
	swagger-server-api 可以帮助后台开发人员解放双手，直接用注解生成文档，省去与前端、测试的沟通，以及项目上线后问题的监控和排查。
	完美融合Spring MVC,采用注解编写文档

#配置-前端 
	swagger支持注解文档和配置文档两种方式，注解直接在源码中使用可能显得内容比较繁琐但直接明了，完全与代码同步；配置方式可以另起一个项目，不涉及源码，可能更新不如注解及时；
	swaggerUI通过修改index.html 中的url指向"http://localhost:8080/server-api/api-docs"和'swagger.json'分别是
	读取通过注解配置和通过swagger editor生成的内容；
#配置-后端

#配置-参考
http://blog.csdn.net/fansunion/article/details/51923720
小雷FansUnion-一个有创业和投资经验的资深程序员-全球最大中文IT社区CSDN知名博主-排名第119
博客：http://blog.csdn.net/fansunion 







