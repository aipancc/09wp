# 09WP Python 版全栈项目

本目录为09WP网盘支持多网盘聚合转存、全网搜索、后台管理的Python+Next.js重构版。

## 主要技术栈
- 后端：FastAPI + SQLAlchemy + Meilisearch + MySQL + Redis
- 前端：Next.js 14 + TypeScript + Zustand + TailwindCSS

## 快速启动
1. cp .env.example .env
2. docker-compose up --build
3. 前端访问：http://localhost:3000
4. API文档：http://localhost:8000/docs

## 目录说明
- backend/    FastAPI后端
- frontend/   Next.js前端
- scripts/    辅助脚本
- docs/       系统文档
