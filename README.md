# 基于Springboot+Vue的企业OA员工人事管理系统(源码+数据库+论文+讲解视频)

**博客地址：
[https://blog.csdn.net/m0_46479461?type=blog](https://blog.csdn.net/m0_46479461/article/details/160123217?ops_request_misc=elastic_search_misc&request_id=37a68a04dce2ac61ac29d8b3dd1b2cf7&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~ElasticSearch~search_v2-4-160123217-null-null.nonecase&utm_term=人事管理&spm=1018.2226.3001.4450)**

**视频演示：
[https://www.bilibili.com/video/BV1zQ4y137M8/?spm_id_from=333.1387.upload.video_card.click&vd_source=a07d4d9e08429da15979e93a7f680a47](https://www.bilibili.com/video/BV1zQ4y137M8/?spm_id_from=333.1387.upload.video_card.click&vd_source=a07d4d9e08429da15979e93a7f680a47)**

**毕业设计所有选题地址：
[https://blog.csdn.net/m0_46479461?type=blog](https://blog.csdn.net/m0_46479461?type=blog)**



## 接毕业设计和论文

### 作者微信：TELLER-STORY QQ：480644915 (支持部署调试、支持代做毕设)

### 接javaweb、python、小程序、H5、APP、各种管理系统等开发

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt



# 基于Springboot+Vue的企业OA员工人事管理系统(源码+数据库+论文+讲解视频)

## 1，需求分析

本项目旨在实现微型人事管理信息系统。

功能主要由员工资料，人事信息管理，薪资调整分配，统计分析管理和系统设置管理系统构成。实现员工信息编辑，人事信息入库展示分析，工资套帐处理及系统的设置等功能。



##### 项目功能：

注：此系统含有部门管理、职位管理、职称管理、权限角色管理等，用户可自由配置系统角色和角色权限页面，从而实现多角色进入不同页面的登录效果。



注：系统内可自由配置角色权限，每个角色所属的功能可自由配置，所以下文只列举系统的全部功能：

全部功能：员工档案；员工打卡；员工奖惩；员工培训；员工调薪；调动职务；考勤管理；工资套账管理；员工套账管理；工资表管理；综合信息统计；员工积分统计；人事信息分析；人事分析记录；部门管理；职位管理；职称管理；权限角色管理；奖惩规则管理；公告管理；操作日志管理；操作员管理；个人中心

## 二、技术栈
### 后端技术

| 技术           | 说明                | 官网                                           |
| -------------- | ------------------- | ---------------------------------------------- |
| SpringBoot     | Web应用开发框架     | https://spring.io/projects/spring-boot         |
| SpringSecurity | 认证和授权框架      | https://spring.io/projects/spring-security     |
| MyBatis        | ORM框架             | http://www.mybatis.org/mybatis-3/zh/index.html |
| Druid          | 数据库连接池        | https://github.com/alibaba/druid               |
| JWT            | JWT登录支持         | https://github.com/jwtk/jjwt                   |
| Lombok         | Java语言增强库      | https://github.com/rzwitserloot/lombok         |
| PageHelper     | MyBatis物理分页插件 | http://git.oschina.net/free/Mybatis_PageHelper |

### 前端技术

| 技术       | 说明             | 官网                                                    |
| ---------- | ---------------- | ------------------------------------------------------- |
| Vue        | 前端框架         | https://vuejs.org/                                      |
| Vue-router | 路由框架         | https://router.vuejs.org/                               |
| Vuex       | 全局状态管理框架 | https://vuex.vuejs.org/                                 |
| Element    | 前端UI框架       | https://element.eleme.io                                |
| Axios      | 前端HTTP框架     | 📣 有源码 [获取源码](https://note.youdao.com/s/czjbp31B) |

## 三、环境介绍
基础环境 :IDEA/eclipse, JDK 1.8, Mysql8.0, Node.js(14.21), Maven3.6, Vscode

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图


![contents](./picture/01.png)

![contents](./picture/02.png)

![contents](./picture/03.png)

![contents](./picture/04.png)

![contents](./picture/05.png)

![contents](./picture/06.png)

![contents](./picture/07.png)

![contents](./picture/08.png)

![contents](./picture/09.png)

![contents](./picture/10.png)

![contents](./picture/11.png)

![contents](./picture/12.png)

![contents](./picture/13.png)

![contents](./picture/14.png)

![contents](./picture/15.png)

![contents](./picture/16.png)

![contents](./picture/17.png)

![contents](./picture/18.png)

![contents](./picture/19.png)

![contents](./picture/20.png)

![contents](./picture/21.png)

![contents](./picture/22.png)

![contents](./picture/23.png)

![contents](./picture/24.png)

![contents](./picture/25.png)

## 五、浏览地址
- 前台访问路径：http://localhost:8080/
  story/123456 
- 后台访问路径：http://localhost:8888/
  admin/123456

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql
2. 使用IDEA/Eclipse导入ruoyi-master项目，导入时，若为maven项目请选择maven; 等待依赖下载完成
3. 修改resources目录下面application.yml里面的数据库配置, 文件路径配置
4. Application.java启动后端项目
5. vscode或idea打开ruoyi-ui项目
6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示前台访问地址



