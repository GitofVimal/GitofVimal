# GitofVimal

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=VIMALATHITHAN%20N&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Data%20Analyst%20%7C%20Data%20Engineer%20%7C%20UI%2FUX%20Designer&descAlignY=62&descSize=16" width="100%"/>

<div align="center">
</div>

---

## 🧑‍💻 About Me

<img align="right" width="380" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

```python
class Vimalathithan:
    name        = "Vimalathithan N"
    degree      = "Computer Science & Engineering"

    stack = [
        "Python", "SQL", "Power BI",
        "Pandas", "NumPy", "scikit-learn",
        "Power BI", "Google Looker Studio", "Figma", "n8n"
    ]

    currently_learning = [
        " Art of Data "
    ]

    fun_fact = "World generate ocean of data daily. Process tiny puddle."

    def motto(self):
        return "Data is the new oil — I'm the refinery."
```

<br clear="right"/>

---

## 🛠️ Tech Stack

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### 📦 Frameworks & Libraries
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

### 📊 BI & Visualization
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Google Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=google&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

### 🧰 Dev Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=flat-square&logo=pycharm&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Google Opal](https://img.shields.io/badge/Google%20Opal-4285F4?style=flat-square&logo=google&logoColor=white)

---

## 🔥 Streak Stats

<div align="center">
  <img src="https://streak-stats.demolab.com?user=VIMALATHITHAN&theme=tokyonight-duo&hide_border=true&background=0D1117&ring=70A5FD&fire=BF91F3&currStreakLabel=70A5FD&sideLabels=38BDAE&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0D1117&border_radius=10"/>
</div>

---
## 📊 Contribution Graph
"use client";

import {
  ContributionGraph,
  ContributionGraphBlock,
  ContributionGraphCalendar,
  ContributionGraphFooter,
} from "@/components/kibo-ui/contribution-graph";
import { eachDayOfInterval, endOfYear, formatISO, startOfYear } from "date-fns";
import { cn } from "@/lib/utils";

const maxCount = 20;
const maxLevel = 4;
const now = new Date();
const days = eachDayOfInterval({
  start: startOfYear(now),
  end: endOfYear(now),
});

const data = days.map((date) => {
  const c = Math.round(
    Math.random() * maxCount - Math.random() * (0.8 * maxCount)
  );
  const count = Math.max(0, c);
  const level = Math.ceil((count / maxCount) * maxLevel);

  return {
    date: formatISO(date, { representation: "date" }),
    count,
    level,
  };
});

const Example = () => (
  <ContributionGraph data={data}>
    <ContributionGraphCalendar>
      {({ activity, dayIndex, weekIndex }) => (
        <ContributionGraphBlock
          activity={activity}
          className={cn(
            'data-[level="0"]:fill-[#ebedf0] dark:data-[level="0"]:fill-[#161b22]',
            'data-[level="1"]:fill-[#9be9a8] dark:data-[level="1"]:fill-[#0e4429]',
            'data-[level="2"]:fill-[#40c463] dark:data-[level="2"]:fill-[#006d32]',
            'data-[level="3"]:fill-[#30a14e] dark:data-[level="3"]:fill-[#26a641]',
            'data-[level="4"]:fill-[#216e39] dark:data-[level="4"]:fill-[#39d353]'
          )}
          dayIndex={dayIndex}
          weekIndex={weekIndex}
        />
      )}
    </ContributionGraphCalendar>
    <ContributionGraphFooter />
  </ContributionGraph>
);

export default Example;

---

## 🚀 Featured Projects

<div align="center">

| Project | Stack | Highlights |
|:--------|:------|:-----------|
| [**Uber BI Dashboard**](https://github.com/VIMALATHITHAN) | Power BI · Excel · MySQL | Analyzed ride patterns & peak demand hours; interactive dashboards tracking total trips, revenue trends & ride frequency |
| [**Customer Segmentation — K-Means**](https://github.com/VIMALATHITHAN) | Python · Pandas · NumPy · scikit-learn | Segmented **800 customers** into **5 behavioral groups**; **9 visualizations** (PCA, radar, heatmaps); automated marketing strategy generator |
| [**Data Cleaner Pro**](https://github.com/VIMALATHITHAN) | Python · Pandas · NumPy · HTML · CSS · JS | Automated CSV/Excel preprocessing; reduced manual cleaning time by **60–80%**; auto date dimensions + data quality scoring with Excel audit reports |

</div>

---

## 🎓 Education

<div align="center">

| Degree | Institution | Year | Score |
|:-------|:------------|:----:|:-----:|
| B.E. Computer Science & Engineering | Bannari Amman Institute of Technology | 2026 | 7.12 CGPA |
| Diploma | N L Polytechnic | 2023 | 85% |
| SSLC | S R T Universal | 2020 | 84% |

</div>

---

## 🏅 Achievements & Certifications

<div align="center">

| | Achievement | Details |
|:-:|:-----------|:--------|
| 📜 | Essential SQL Skills For Data | Analytics Vidhya — Aug 2025 |
| 📜 | Data Analytics Certification | NXTSYNC PVT LTD — Oct 2025 |
| 💡 | Area of Interest — Analytics | Data · Business Intelligence |
| 🤖 | Area of Interest — Automation | n8n · Google Opal workflows |
| 🎨 | Area of Interest — UI/UX | Wireframe & Design Systems |

</div>

---

## 🌱 Currently Learning

```
📊 Business Intelligence → Google Looker Studio · DAX · Advanced Power BI
🤖 AI Automation         → n8n Workflows · Google Opal · Agentic Pipelines
🎨 UI/UX Design          → Figma Systems · Wireframing · Prototyping
🗄️  Databases             → Advanced SQL · Query Optimization · MySQL
```

---

## 📬 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vimalathithan-n)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vimalthithan.n@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=VIMALATHITHAN&color=70a5fd&style=flat-square&label=Profile+Views)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling" width="100%"/>
