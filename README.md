# RequirementTraceAgent - 跨系统需求追踪与合规检查 Agent

## 运行方式
1. 确保 Python 3.8+
2. 无需安装额外依赖（标准库即可运行）
3. 执行 `python main.py`
4. 查看生成的 `trace_report.md` 报告

## 核心特性
- 多 Agent 协作：解析、扫描、比对、报告
- 长链推理：语义匹配 + 合规规则级联检查
- 输出需求覆盖率矩阵 + 合规违犯清单
- 支持模拟创建 Jira 修复任务

## 自定义
- 修改 `sample_requirements.md` 和 `sample_code_repo/` 下的代码文件
- 调整 `config.json` 中的合规规则关键词
