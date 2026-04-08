# 基于FPGA的大模型加速器发展态势分析
## 项目简介
本项目以Web of Science核心合集为数据源，通过文献计量学方法，系统分析**基于FPGA的大模型（LLM）加速器**领域的发展态势：
- 研究方向：FPGA大模型加速器、AI硬件加速、边缘大模型部署
- 技术栈：Python + pandas + networkx + CiteSpace + VOSviewer
- 核心目标：梳理领域发文趋势、挖掘技术热点、分析作者/机构合作网络、预测未来发展方向

## 目录结构
.├── data/│ ├── raw/ # WOS/CNKI 原始文献数据│ └── processed/ # 清洗后标准化数据├── src/ # 数据清洗、计量分析 Python 脚本├── docs/ # 检索方案、开题报告、分析报告├── results/ # 可视化图谱、分析结果├── requirements.txt # 项目依赖库└── README.md
