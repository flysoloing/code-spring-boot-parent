# code-spring-boot-parent

[![GitHub release](https://img.shields.io/github/release/flysoloing/code-spring-boot-parent.svg)](https://github.com/flysoloing/code-spring-boot-parent/releases)

通用parent模块（Spring Boot版本），统一管理各Project的依赖项和配置项，定期升级优化，减少各应用的依赖包维护成本。

当前最新正式版本：[1.1](https://github.com/flysoloing/repo/blob/gh-pages/libs/com/flysoloing/code-spring-boot-parent/1.1/code-spring-boot-parent-1.1.pom)

当前最新快照版本：1.1-SNAPSHOT

**Release Notes:**

- 1.1
  
  [升级]
  
    - code-parent（原版本：1.0，升级后版本：1.1）
    
    - spring-boot（原版本：1.5.22.RELEASE，升级后版本：2.1.8.RELEASE）
    
    - 核心Maven插件：maven-clean-plugin（原版本：3.0.0，升级后版本：3.1.0）；maven-compiler-plugin（原版本：3.7.0，升级后版本：3.8.1）；maven-deploy-plugin（原版本：2.8.2，升级后版本：3.0.0-M1）；maven-install-plugin（原版本：2.5.2，升级后版本：3.0.0-M1）；maven-resources-plugin（原版本：3.0.2，升级后版本：3.1.0）；maven-site-plugin（原版本：3.6，升级后版本：3.8.2）
          
    - packaging types/tools：maven-jar-plugin（原版本：2.6，升级后版本：3.1.2）；maven-source-plugin（原版本：2.4，升级后版本：3.1.0）；maven-plugin-plugin（原版本：3.4，升级后版本：3.6.1）
          
    - 增强型Maven插件：versions-maven-plugin（原版本：2.5，升级后版本：2.7）

- 1.0
  
  [初始化]
  
    - 引入通用parent模块依赖，code-parent-1.0.pom
  
    - 引入Spring Boot依赖，当前版本：1.5.22.RELEASE
  
    - Maven插件，如：maven-source-plugin、jetty-maven-plugin等