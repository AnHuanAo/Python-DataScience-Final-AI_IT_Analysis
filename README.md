# python语言与数据科学期末大作业---AI/IT岗位待遇分析
本项目使用了来自Kaggle、和鲸社区的已有数据集以及Boss直聘手爬数据作为数据源，针对近两年AI/IT岗位的变化进行了数据分析，旨在为本科低年级学生提供一定的方向选择参考。

## 📈 核心洞察

通过分析 Notebook 中的可视化数据，我们得出以下关键结论：

### 1. 地域决定薪资上限 (全球版图)
根据 `2025-2026年AI岗位薪资分析报告 (按国家/地区)` 的统计，全球 AI 薪资呈现明显的梯队化：
*   **北美与全球中心：** 美国 (平均 **164万 RMB**) 和 全球平均 (**161万 RMB**) 处于绝对领先地位。
*   **发达经济体：** 澳大利亚、加拿大、欧洲国家平均在 **130万-140万 RMB** 之间。
*   **中国市场：** 平均年薪 **97.4万 RMB**。虽然在榜单中处于第三梯队，但考虑到生活成本，依然是极具吸引力的高薪赛道。
<img width="1550" height="1142" alt="国外可视化" src="https://github.com/user-attachments/assets/013d019b-71ca-424f-a14f-057396c84f6a" />


### 2. 岗位决定薪资天花板
根据 `热门AI岗位类别薪资对比` 的分析，**架构师 (Architecture)** 以 **182万 RMB** 的平均年薪位居榜首，其次是 **AI工程** 与 **基础设施** 岗位。
*   **高薪逻辑：** 掌握核心算法落地（AI Engineering）或底层算力优化（Infrastructure）的人才，薪资远超普通开发。
<img width="1184" height="784" alt="国外2" src="https://github.com/user-attachments/assets/6c56720a-d42d-4c0f-b225-90a9174af4e1" />

### 3. 经验与学历依然是硬通货
*   数据显示，拥有 **5-10年** 经验的资深专家，其薪资涨幅最为迅猛。
*   **学历溢价：** 硕士学历在 AI 领域的薪资优势依然明显，尤其是在算法和研究岗。

### 4.国内2024年IT行业概览
*    高薪由“城市、学历与AI技能”共同决定。
*    市场呈现“前端需求大，测试稳健”的格局。
*    人才画像高度集中在“本科+3-5年经验”。
<img width="1499" height="784" alt="国内9" src="https://github.com/user-attachments/assets/6e040d02-1999-418a-8169-cc55e3c15ffc" />
<img width="1384" height="684" alt="国内8" src="https://github.com/user-attachments/assets/81d5825b-ca96-45da-bf4f-c45846ae489a" />
<img width="1384" height="684" alt="国内7" src="https://github.com/user-attachments/assets/5f96ce38-7e0e-41a3-ba83-f6d1b86c00eb" />
<img width="1014" height="557" alt="国内6" src="https://github.com/user-attachments/assets/27c6eb38-724a-4bcf-89eb-ccba17c4e102" />
<img width="482" height="508" alt="国内5" src="https://github.com/user-attachments/assets/4bb65173-ebce-4a51-bda5-0ede47f29742" />
<img width="859" height="557" alt="国内4" src="https://github.com/user-attachments/assets/94faba03-b55d-4885-8906-490687c03d7f" />
<img width="1022" height="557" alt="国内3" src="https://github.com/user-attachments/assets/d0650a94-2992-4f19-a362-470b4d0fb4f5" />
<img width="1184" height="554" alt="国内2" src="https://github.com/user-attachments/assets/0de9082e-5ec8-44ef-9cdc-7300c58d647a" />
<img width="1011" height="645" alt="国内1" src="https://github.com/user-attachments/assets/e759a96d-8dfd-4090-9d37-377ef84e8fae" />


### 5.2026年国内腰部企业AI岗位待遇
*    AI与大模型是绝对的薪资天花板。
*    “越老越贵”在高端技术岗得到验证。
*    基础技术与架构管理是第二梯队。
<img width="1749" height="1284" alt="国内10" src="https://github.com/user-attachments/assets/707430c6-0917-4522-a813-d947abdf4d97" />





## 📂 项目结构

本项目包含以下核心文件：

1.  **`AI岗位薪资爬取、收集、清洗及可视化.ipynb`**
    *   **功能：** 数据爬取、缺失值处理、异常值清洗、特征工程（如计算薪资溢价）、数据可视化。
    *   **输出：** 生成了全球薪资对比图、岗位类别薪资分布图等。

## 🛠️ 技术栈

*   **Python Libraries:** Pandas (数据清洗), Matplotlib/Seaborn (可视化)
*   **数据分析:** 数据去重, 缺失值填充, 异常值检测
*   **数据可视化:** 柱状图 (国家对比), 箱线图 (薪资分布)



## 📝 结论

当前 AI 就业市场呈现出 **"技术深、薪资高、地域集中"** 的特点。单纯依靠“堆年限”已无法获得高薪，必须向 **AI工程化**、**架构设计** 或 **底层基础设施** 等高壁垒方向转型。

> **注：** 本数据集仅反映 2024-2026 年市场行情，不构成投资或职业建议。
