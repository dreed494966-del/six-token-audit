# six-token-audit
Audit and compliance repository for Six Token (6T) — includes verified signer tree, permission updates, metadata, and bilingual documentation for TRON ecosystem and Chinese listing.
# 1. Create local folder
mkdir TAMA && cd TAMA

# 2. Initialize Git
git init

# 3. Create base files and folders
mkdir audits contracts docs logs
touch README.md LICENSE \
      audits/tama-audit-report.md audits/signer-tree.md audits/compliance-tags.md \
      contracts/tama-mainnet.sol contracts/metadata.json \
      docs/workflow-notes.md docs/bilingual/tama-audit-cn.md docs/bilingual/tama-audit-en.md \
      logs/tx-history.md logs/forensic-trail.md

# 4. Add everything
git add .

# 5. Commit initial structure
git commit -m "Initial commit: TAMA repository structure"

# 6. Link to GitHub (replace with your actual repo URL)
git remote add origin https://github.com/YOUR-USERNAME/TAMA.git

# 7. Push to GitHub
git branch -M main
git push -u origin main
 bilingual docs 
 # TAMA 审计报告 (中文)

## 概述
本文档提供 TAMA 项目的审计结果、合规说明以及已验证的签名树。

## 主要部分
- **合约元数据**：TRON 主网部署详情、参数和版本信息
- **签名树**：已验证的权限结构和阈值
- **合规标签**：CoinSpot、SafePal 和 Yk 钱包操作的审计记录
- **交易日志**：交易哈希、时间戳和取证说明

## 合规目标
- 为 TRON 生态系统提供透明的审计记录
- 验证签名和权限更新
- 为中国审核人员提供双语文档
- 模块化工作流程，适应 TRON/EVM 集成
 
