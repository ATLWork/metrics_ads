# 任务列表

## 项目：atour-dashboard

| ID | Age | Priority | Tags | 描述 | Urg |
|----|-----|----------|------|------|-----|
| 14 | 2d | H | data,wave1 | EDA：探索三个 CSV（数据质量/空值/分布/异常值） | 7.91 |
| 15 | 2d | H | data,wave1 | 实现 backend/data_loader.py（单例加载，启动预热） | 7.91 |
| 16 | 2d | H | data,wave1 | 实现 backend/analysis/aggregations.py（6个纯聚合函数） | 7.91 |
| 17 | 2d | H | data,wave1 | 输出 backend/api_schema.md（字段/类型/样例契约文档） | 7.91 |
| 18 | 2d | H | frontend,wave1 | 执行 create-next-app（TypeScript + Tailwind + App Router） | 7.91 |
| 19 | 2d | H | frontend,wave1 | 安装 shadcn/ui 并添加 card/tabs/table/badge/select 组件 | 7.91 |
| 20 | 2d | H | frontend,wave1 | 安装 recharts | 7.91 |
| 21 | 2d | H | frontend,wave1 | 配置 next.config.ts API 代理（/api/* → localhost:8000） | 7.91 |
| 22 | 2d | H | frontend,wave1 | 编写 app/layout.tsx + app/globals.css（商务风格基础布局） | 7.91 |
| 23 | 2d | M | backend,wave2 | 编写 backend/requirements.txt | 5.81 |
| 24 | 2d | M | backend,wave2 | 编写 backend/main.py（FastAPI + CORS + 路由注册 + startup 预热） | 5.81 |
| 25 | 2d | M | backend,wave2 | 编写 backend/routers/kpi.py（调用 aggregations 函数） | 5.81 |
| 26 | 2d | M | backend,wave2 | 编写 backend/routers/hotels.py（含 /filters 端点） | 5.81 |
| 27 | 2d | M | backend,wave2 | 编写 backend/routers/channels.py | 5.81 |
| 28 | 2d | M | frontend,wave2 | 实现 KpiOverview.tsx（8个 KPI 卡片 + 双轴折线图） | 5.81 |
| 29 | 2d | M | frontend,wave2 | 实现 HotelRanking.tsx（可排序 DataTable + 多维筛选） | 5.81 |
| 30 | 2d | M | frontend,wave2 | 实现 ChannelAnalysis.tsx（占比饼图 + 月度堆叠柱状图） | 5.81 |
| 31 | 2d | M | frontend,wave2 | 实现 ProblemHotels.tsx（预警列表 + 彩色 Badge） | 5.81 |
| 32 | 2d | M | frontend,wave2 | 实现 app/page.tsx（Tabs 切换 + 全局筛选器） | 5.81 |
| 33 | 2d | L | test,wave3 | 编写 backend/tests/conftest.py（httpx AsyncClient fixture） | 3.71 |
| 34 | 2d | L | test,wave3 | 编写 backend/tests/test_kpi.py | 3.71 |
| 35 | 2d | L | test,wave3 | 编写 backend/tests/test_hotels.py | 3.71 |
| 36 | 2d | L | test,wave3 | 编写 backend/tests/test_channels.py | 3.71 |
| 37 | 2d | L | test,wave3 | 执行后端测试套件并验证全部通过 | 3.71 |
| 38 | 2d | L | test,wave3 | 编写 frontend/e2e/dashboard.spec.ts（Tab/卡片/图表/Badge 验证） | 3.71 |
| 39 | 2d | L | test,wave3 | 执行 Playwright E2E 测试并验证通过 | 3.71 |

**总计：26 tasks**
