# Academic Map

Academic Map 是一个学业信息全栈应用，包含 Spring Boot 后端和 Vue 3 前端。

> 课程说明：本目录是课程实验或课程作业的解决方案。

## 目录结构

- `Academic_Map/`：基于 Java 21 的 Spring Boot 服务
- `frontend/`：Vue 3 与 Vite 前端
- `sql/academic_map.sql`：数据库初始化脚本

## 本地运行

启动后端：

```powershell
cd Academic_Map
.\mvnw.cmd spring-boot:run
```

在另一个终端启动前端：

```powershell
cd frontend
npm install
npm run dev
```

请使用 Java 21 JDK 与 Node.js 20.19 或更高版本。使用 MySQL 时，请先配置后端数据库连接。