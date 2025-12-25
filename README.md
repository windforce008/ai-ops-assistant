# ai-ops-assistant
首先这是个初学着学习的课件代码，没有任何参考价值，只是作业而已，不要浪费您的时间
AI运维助手 - 公司专属ChatGPT

**运维老兵按照AI指导搭建的的企业级AI系统**

### 核心功能
- 实时监控CPU/日志 + 自动企业微信告警
- 支持PDF/Word/Excel私有知识库问答
- Tool Agent自动执行ping/查询命令
- Streamlit美观Web界面

### 演示
![Web界面](screenshots/web_chat.png)
![告警示例](screenshots/wechat_alert.png)

### 快速运行
```bash
pip install -r requirements.txt
streamlit run rag_web/app.py
