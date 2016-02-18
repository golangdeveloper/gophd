# gophd 初学者web框架
   我是崇尚自由编程的程序员，不喜欢学习多余的东西，因此我花了3个月时间努力学习了golangweb开发，用我3个月的经验，总结一套适用于大部分golang初学者的web框架。
## gophd特色   
   1.gophd，是microservice式的MVC网站系统。
   
   gophd崇尚的是，web系统是由多个微型程序组合而成，每个微程序职责专一，这是与其他goweb框架非常不同的一点。也是因为这一点，gophd是架构师最喜欢的网站设计风格，适合网站长期扩展功能。
   
   2.gophd为网页及数据库访问，集成了优秀的微服务，并且展现了网页及数据库的原生风格，如html组合，mongo访问，并且尽量删减自身的存在。在这里，我想提一下beego所说的搭积木，beego确实能够搭成房子，事实上gophd是在搭建microservice森林，又不破坏每个颗草与树。
   
   不像php、asp.net等后端几乎蹂躏了网页前端。
   
   也不像各种数据库的驱动和orm，让你又得多学一遍数据库增删改查的函数。
## gophd当前核心组成部分
  1.[goproxy](https://github.com/golangdeveloper/goproxy)：为80端口提供路由注册及反向代理的范例程序。第一解决80端口不够用问题，第二可以控制路由。
  
  2.[golangframework/htmlparts](https://github.com/golangframework/htmlparts)组合引擎，一个原理及其简单的网页组合引擎。仅提供页面的组合，并不提供数据渲染。
  3.[httpdb](https://github.com/golangframework/httpmongo)，数据库访问程序。
## 开发成员
[timeloveboy](https://github.com/timeloveboy)

  
  
