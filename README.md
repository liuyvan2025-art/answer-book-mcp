# 答案之书 MCP 服务

一个基于Model Context Protocol的智慧答案生成服务，为你的问题提供随机而富有哲理的答案。

## 功能特点

- 🎯 随机生成智慧答案
- 📊 查询历史记录和统计
- 🎨 支持自定义答案
- 💾 持久化存储配置

## 安装和使用

1. 安装依赖：`pip install -r requirements.txt`
2. 运行服务：`python answer_book_mcp.py`
3. 通过MCP客户端连接使用

## API说明

- `ask_question(question: str)` - 提问获取答案
- `get_recent_history(limit: int)` - 获取历史记录
- `get_statistics()` - 获取使用统计
- `add_custom_answer(answer_text: str)` - 添加自定义答案
