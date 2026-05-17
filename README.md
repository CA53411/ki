# Corolas AI 技术百科

aiwiki.corolas.top | Corolas子项目

## 简介
AI技术知识百科平台，汇聚AI领域技术文档、教程与最佳实践。

## 技术栈
- Frontend: React 19 + TypeScript + Vite
- Styling: Tailwind CSS + shadcn/ui
- Backend: Supabase (Auth + PostgreSQL + Edge Functions)
- Deploy: Vercel (GitHub Push → Auto Deploy)
- CI/CD: GitHub Actions

## 环境变量
| 变量 | 说明 |
|------|------|
| VITE_SUPABASE_URL | Supabase项目URL |
| VITE_SUPABASE_ANON_KEY | Supabase Anon Key |

## 数据库
Supabase项目: https://supabase.com/dashboard/project/corolas-ki

## 本地开发
```bash
git clone https://github.com/CA53411/ki.git
cd ki
npm install
npm run dev
```

## 部署
Push到main分支自动触发Vercel部署
