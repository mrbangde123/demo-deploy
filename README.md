 # demo-deploy

  本仓库用于存放 demo 项目的部署配置。

  ## 包含内容（后续会陆续添加）
  - docker-compose.yml
  - nginx 配置
  - 环境变量示例 .env.example

  ## 项目整体架构
   3. browser → nginx → frontend → springboot-main → mysql / redis
                                  ↓
                         springboot-client-service
