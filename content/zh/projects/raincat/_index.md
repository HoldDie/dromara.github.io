---
title: "Raincat"
description: "Raincat是基于二阶段提交+本地事务补偿机制来实现的强一致性分布式事务解决方案。无缝支持dubbo,motan,springcloud等Rpc框架的微服务。"
subDesc: "强一致性分布式事务解决方案"
feature1Img: "/img/feature/feature_transpart.png"
feature1Title: "支持多种Rpc"
feature1Desc: "raincat为dubbo,springcloud,motan提供了单独的jar包提供支持"
feature2Img: "/img/feature/feature_loadbalances.png"
feature2Title: "支持Spring-boot-start"
feature2Desc: "提供支持spring-boot-start方式启动的jar包"
feature3Img: "/img/feature/feature_service.png"
feature3Title: "高可用的协调者"
feature3Desc: "采用eureka作为注册中心，可集群部署，达到服务的高可用，采用redis集群来分布式存储事务数据"
feature4Img: "/img/feature/feature_hogh.png"
feature4Title: "协调者采用netty通信"
feature4Desc: "采用netty与参与者，发起者进行长连接通信"
feature5Img: "/img/feature/feature_runtime.png"
feature5Title: "解决极端情况下事务不一致的情况"
feature5Desc: "raincat采用保存日志的方式，在极端donw机情况下，通过日志来恢复"
feature6Img: "/img/feature/feature_maintenance.png"
feature6Title: "支持内嵌事务"
feature6Desc: "支持rpc的且套调用"
architectureImg: "/img/architecture/raincat-framework.png"
startUp: "开始"
github: "https://github.com/dromara/raincat"
gitee: "https://gitee.com/shuaiqiyu/Raincat"
level: "main"
weight: 3
icon: "/img/logo/raincat.png"
showIntroduce: true
showFeature: true
sidebar:
  - title: '介绍文档'  	
    link: 'overview'
  - title: '启动raincat-manager'  	
    link: 'raincat-manager-starter'
  - title: '配置详解'  	
    link: 'config'
  - title: '启动admin'  	
    link: 'admin-starter'
  - title: '用户文档'  	
    sub:
      - title: 'dubbo用户'  	
        link: 'dubbo-user'
      - title: 'motan用户'  	
        link: 'motan-user'
      - title: 'springcloud用户'  	
        link: 'springcloud-user'
  - title: '快速体验'  	
    sub:
      - title: 'quick-start-dubbo'  	
        link: 'quick-start-dubbo'
      - title: 'quick-start-springcloud'  	
        link: 'quick-start-springcloud'
# draft: true
---

