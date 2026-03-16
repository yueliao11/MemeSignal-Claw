# MemeSignal Claw 🦞

**币安 OpenClaw AI Agent 大赛参赛作品**  
用 AI 建设加密，和币安一起逐浪 Web3！  
一个专注 Meme 币猎取 + 交易信号的智能小龙虾助手，帮助用户在币安生态中安全发现热点、审计风险并获取可靠建议。

## 项目简介

**痛点解决**：  
- Meme 币热度爆炸，但 99% 存在 rug pull、蜜罐或 pump-dump 风险，散户容易追高被割。  
- 交易信号碎片化，难以快速结合 Alpha 数据和实时热度做出决策。

**MemeSignal Claw 核心功能**：  
1. 实时监控 meme-rush 热度榜 + crypto-market-rank  
2. 对热门 Meme 自动调用 query-token-audit 安全审计 + query-token-info 基本面分析  
3. 融合 trading-signal + alpha 数据，给出“买入/观察/跑路”明确建议  
4. 支持一键跳转 Binance spot / 合约页面（只读建议，不自动执行）  
5. 安全围栏设计：优先审计、只读优先、透明步骤、明确风险警告

**已启用核心技能**（仅授予必要权限）：  
- meme-rush  
- crypto-market-rank  
- query-token-audit  
- query-token-info  
- trading-signal  
- alpha  
- （可选扩展）spot、derivatives-trading-usds-futures、square-post

## 系统提示词（System Prompt）

完整提示词已放在仓库文件：  
[system_prompt.md](system_prompt.md)

关键原则：安全第一、数据透明、结构化输出、幽默但专业、只读优先、不自动交易。

## 演示截图

### 配置界面 / Agent 设置示例
![配置截图1](https://github.com/yueliao11/MemeSignal-Claw/raw/main/%E6%88%AA%E5%B1%8F2026-03-16%2010.21.16.png)

### 运行对话 / 输出结果示例
![运行截图2](https://github.com/yueliao11/MemeSignal-Claw/raw/main/%E6%88%AA%E5%B1%8F2026-03-16%2010.22.01.png)

（如果图片未显示，可点击文件名查看原图：  
[截屏2026-03-16 10.21.16.png](https://github.com/yueliao11/MemeSignal-Claw/blob/main/%E6%88%AA%E5%B1%8F2026-03-16%2010.21.16.png)  
[截屏2026-03-16 10.22.01.png](https://github.com/yueliao11/MemeSignal-Claw/blob/main/%E6%88%AA%E5%B1%8F2026-03-16%2010.22.01.png)）

## 如何自己部署 / 测试

1. 安装并登录 OpenClaw（小龙虾）工具  
2. 创建新 Agent，导入以上系统提示词  
3. 启用币安技能包（中心化 + Web3 相关技能）  
4. 配置安全围栏：只授查询类权限，避免交易执行权限  
5. 开始对话测试，例如：  
   - “今天最热的 Meme 有哪些？”  
   - “查这个代币安全吗？合约地址：0x...”  
   - “给我 BTC 当前交易信号”

## 视频演示（推荐观看）

[在这里插入你的 1-3 分钟演示视频链接，例如 YouTube / B站 / 微博公开链接]  
（建议：30 秒展示完整流程：热度 → 审计 → 信号 → 建议）

## 参与信息

- 活动标签：#AIBinance  
- 官方账号：@binancezh  
- 提交表单链接：（填写你的表单提交后可补充）  
- X 账号：@jiaming_wa76520

欢迎测试、反馈、转发！你的下一个 100x Meme 可能就在这里～ 🚀

币安官方提醒：AI 代理使用存在风险，请谨慎配置权限，保护账户和资金安全。
