<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Huzaifa%20Iftikhar&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=Full-Stack%20Engineer%20%C2%B7%20AI%20Systems%20%C2%B7%20Open%20Source&descAlignY=58&descSize=18" width="100%" alt="Huzaifa Iftikhar" />

<a href="https://github.com/HuzaifaChaudary">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=36BCF7&center=true&vCenter=true&width=680&lines=Building+full-stack+products+end+to+end;Shipping+AI%2FLLM+features+to+production;Contributing+upstream+to+the+tools+I+use" alt="Typing SVG" />
</a>

<br/>

<a href="https://github.com/HuzaifaChaudary?tab=followers"><img src="https://img.shields.io/github/followers/HuzaifaChaudary?label=Followers&style=for-the-badge&color=0f2027&labelColor=1a1b27" alt="Followers" /></a>
<img src="https://komarev.com/ghpvc/?username=HuzaifaChaudary&label=Profile+Views&style=for-the-badge&color=0f2027" alt="Profile views" />
<a href="mailto:chhuzaifaiftikhar@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20out-0f2027?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1b27" alt="Email" /></a>

</div>

---

## 👨‍💻 About Me

- 🔭 &nbsp;**Currently working on** — full-stack applications, AI-powered products, and developer tools.
- 🤝 &nbsp;**Looking to collaborate on** — open-source projects, AI/ML tooling, developer infrastructure, and interesting full-stack products.
- 🆘 &nbsp;**Looking for help with** — building reliable, scalable AI systems and improving production-grade software architecture.
- 🌱 &nbsp;**Currently learning** — advanced AI/LLM engineering, distributed systems, cloud infrastructure, and scalable backend architecture.
- 💬 &nbsp;**Ask me about** — TypeScript, Python, Next.js, React, Node.js, AWS, AI/LLM applications, APIs, and full-stack development.
- ⚡ &nbsp;**Fun fact** — I have upstream code merged at **Microsoft** (Playwright, GitHub spec-kit), the **OpenJS Foundation** (Jest) and **LangChain** — and my Jest fix shipped in **v30.5.1**, credited by name in the release notes.

---

## 🌍 Open Source

> Upstream contributions to projects I actually use in production.

<div align="center">

<img src="https://img.shields.io/badge/Merged%20upstream-5-8957e5?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1b27" alt="5 merged" />
<img src="https://img.shields.io/badge/Combined%20stars-552k%2B-0f2027?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1b27" alt="Combined stars" />
<img src="https://img.shields.io/badge/Shipped%20in%20a%20release-jest%20v30.5.1-36BCF7?style=for-the-badge&logo=jest&logoColor=white&labelColor=1a1b27" alt="Shipped in jest v30.5.1" />

</div>

### ✅ Merged

| # | Project | Stars | Contribution |
| :-- | :--- | :-- | :--- |
| **1** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **Playwright** | `95.5k` | [#42449](https://github.com/microsoft/playwright/pull/42449) — the UI-mode filter summary was a plain `div`, so it could not be reached or opened from the keyboard |
| **2** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **.NET** · BenchmarkDotNet | `11.1k` | [#3242](https://github.com/dotnet/BenchmarkDotNet/pull/3242) — `--affinity` could not address a CPU above the 32nd, and the 64th threw an unhandled `OverflowException` on a 32-bit host instead of a normal option error |
| **3** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **GitHub** · spec-kit | `132.8k` | [#4367](https://github.com/github/spec-kit/pull/4367) — `check-prerequisites` exported the spec path but never checked the file existed, so later phases failed with no guidance |
| **4** | <img src="https://img.shields.io/badge/OpenJS-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="OpenJS Foundation" /> **Jest** | `45.5k` | [#16413](https://github.com/jestjs/jest/pull/16413) — a leading `#` was read as a URL fragment, so every package `imports` subpath broke under ESM. **Shipped in [v30.5.1](https://github.com/jestjs/jest/releases/tag/v30.5.1)** |
| **5** | <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" /> **LangChain** | `145.4k` | [#39978](https://github.com/langchain-ai/langchain/pull/39978) — removed a contradictory duplicate block from the Groq `with_structured_output` docstring |
| **6** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **GitHub** · spec-kit | `132.8k` | [#4356](https://github.com/github/spec-kit/pull/4356) — command-ref tokens could not hold a hyphen, so a bundled command was unreachable. *Chosen as the canonical fix for [#4198](https://github.com/github/spec-kit/issues/4198) over two competing PRs* |

### 🔄 In review

| Project | Contribution |
| :--- | :--- |
| <img src="https://img.shields.io/badge/Elastic-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elastic" /> **Elasticsearch** | [#158437](https://github.com/elastic/elasticsearch/pull/158437) · [#158503](https://github.com/elastic/elasticsearch/pull/158503) — a malformed SQL cursor came back as a raw JVM error, and setting `similarity` on an nvidia embedding endpoint always threw a 500 |
| <img src="https://img.shields.io/badge/Red%20Hat-EE0000?style=flat-square&logo=redhat&logoColor=white" alt="Red Hat" /> **Quarkus** | [#56360](https://github.com/quarkusio/quarkus/pull/56360) — `@WithFormRead` request filters were moved after the body handler in reverse order, so their priorities were applied backwards |
| <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **.NET** · EF Core | [#38875](https://github.com/dotnet/efcore/pull/38875) · [#38880](https://github.com/dotnet/efcore/pull/38880) — a named default constraint carried onto the temporal history table, and a pooled SQLite connection that killed the process from a native callback |
| <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" /> **pandas** | [#68035](https://github.com/pandas-dev/pandas/pull/68035) · [#68036](https://github.com/pandas-dev/pandas/pull/68036) — an `Enum` subclass is iterable but `is_list_like` said otherwise so it could not be used as `columns`, and `MultiIndex.factorize` rebuilt its uniques from tuples, silently dropping extension dtypes and level names
| <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy" /> **SciPy** | [#26100](https://github.com/scipy/scipy/pull/26100) — `fcluster` read one slot past the end of its criterion array, so `maxclust` with `t=0` returned whatever was in that memory
| **mypy** | [#21941](https://github.com/python/mypy/pull/21941) — stubtest aborted the entire run when a `classmethod`'s first parameter wasn't named `cls`, taking out stub checking for a whole distribution
| **Tailwind CSS** | [#20436](https://github.com/tailwindlabs/tailwindcss/pull/20436) — the v4 upgrade codemod rewrote a React `variant` prop as a utility class |
| **Chart.js** | [#12292](https://github.com/chartjs/Chart.js/pull/12292) · [#12293](https://github.com/chartjs/Chart.js/pull/12293) — a legend key that did not match the line it stood for, and a fractional-canvas resize regression |
| <img src="https://img.shields.io/badge/Apple-000000?style=flat-square&logo=apple&logoColor=white" alt="Apple" /> **Pkl** | [#1840](https://github.com/apple/pkl/pull/1840) — silenced a publish warning for the shaded variant |
| **Scrapy** · parsel | [#367](https://github.com/scrapy/parsel/pull/367) — pinned how C1-range numeric character references extract |

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**AI / LLM**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

**Cloud & Tooling**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=HuzaifaChaudary&hide_border=true&background=0d1117&stroke=0d1117&ring=36BCF7&fire=36BCF7&currStreakLabel=36BCF7&sideLabels=c9d1d9&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" alt="Contribution streak" />

<br/><br/>

<img src="https://ghchart.rshah.org/36BCF7/HuzaifaChaudary" width="90%" alt="Contribution chart" />

<br/><br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=HuzaifaChaudary&theme=github_dark" width="98%" alt="Profile summary" />

<br/><br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=HuzaifaChaudary&theme=github_dark" width="41%" alt="Repos per language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=HuzaifaChaudary&theme=github_dark" width="41%" alt="Most committed language" />

<br/><br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=HuzaifaChaudary&theme=github_dark" width="41%" alt="Stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=HuzaifaChaudary&theme=github_dark&utcOffset=5" width="41%" alt="Productive time" />

<br/><br/>

<img src="https://img.shields.io/github/followers/HuzaifaChaudary?style=for-the-badge&label=Followers&color=0f2027&labelColor=1a1b27&logo=github&logoColor=white" alt="Followers" />
<img src="https://img.shields.io/github/stars/HuzaifaChaudary?style=for-the-badge&label=Total%20Stars&color=0f2027&labelColor=1a1b27&logo=github&logoColor=white" alt="Stars" />

</div>

---

## 🐍 Watch the snake eat my contributions

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HuzaifaChaudary/HuzaifaChaudary/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/HuzaifaChaudary/HuzaifaChaudary/output/snake.svg" />
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/HuzaifaChaudary/HuzaifaChaudary/output/snake.svg" />
</picture>

</div>

---

<div align="center">

### 🤝 Let's build something

<a href="mailto:chhuzaifaiftikhar@gmail.com"><img src="https://img.shields.io/badge/Email-chhuzaifaiftikhar%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/HuzaifaChaudary"><img src="https://img.shields.io/badge/GitHub-HuzaifaChaudary-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

<br/><br/>

<i>Always happy to talk about a hard bug, a messy codebase, or an AI feature that needs to actually work in production.</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" alt="" />

</div>
