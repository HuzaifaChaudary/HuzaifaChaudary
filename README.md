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
- ⚡ &nbsp;**Fun fact** — I have upstream code merged at **Google** (Gson), **Microsoft** (Playwright, GitHub spec-kit, EF Core, ML.NET, ONNX Runtime), the **Apache Software Foundation** (Maven), **Red Hat** (Quarkus), the **OpenJS Foundation** (Jest), **SciPy**, the **Python** org (mypy), **radare2** and **LangChain** — and my Jest fix shipped in **v30.5.1**, credited by name in the release notes.

---

## 🌍 Open Source

> Upstream contributions to projects I actually use in production.

<div align="center">

<img src="https://img.shields.io/badge/Merged%20upstream-32-8957e5?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1b27" alt="32 merged" />
<img src="https://img.shields.io/badge/Merged%20into-1.04M%20stars-0f2027?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1b27" alt="Merged into 1.04M stars" />
<img src="https://img.shields.io/badge/Open%20upstream-27-1f6feb?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1b27" alt="27 open upstream" />
<img src="https://img.shields.io/badge/Shipped%20in%20a%20release-jest%20v30.5.1-36BCF7?style=for-the-badge&logo=jest&logoColor=white&labelColor=1a1b27" alt="Shipped in jest v30.5.1" />

</div>

### ✅ Merged

| # | Project | Stars | Contribution |
| :-- | :--- | :-- | :--- |
| **1** | <img src="https://img.shields.io/badge/Google-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google" /> **Gson** | `24.2k` | [#3112](https://github.com/google/gson/pull/3112) — a `? extends Base` element type was serialised from the declared type, so subclass fields vanished, and a `List<? extends CharSequence>` came out as `[{},{}]` with the strings gone entirely. **Merged by a Gson maintainer after it passed Google's internal tests** |
| **2** | **OpenClaw** | `390.2k` | [`1bf5fb6`](https://github.com/openclaw/openclaw/commit/1bf5fb68d3896a76740d64bd0d3096d656b15b23) — the macOS Talk overlay was hidden by a dismissal that had already been interrupted. My [#132565](https://github.com/openclaw/openclaw/pull/132565) was superseded, and the fix shipped carrying my `Co-authored-by`. **Released in [v2026.9.1](https://github.com/openclaw/openclaw/releases/tag/v2026.9.1)** |
| **3** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **GitHub** · spec-kit | `138.2k` | [#4356](https://github.com/github/spec-kit/pull/4356) — command-ref tokens could not hold a hyphen, so a bundled command was unreachable. *Chosen as the canonical fix for [#4198](https://github.com/github/spec-kit/issues/4198) over two competing PRs* |
| **4** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **GitHub** · spec-kit | `138.2k` | [#4367](https://github.com/github/spec-kit/pull/4367) — `check-prerequisites` exported the spec path but never checked the file existed, so later phases failed with no guidance |
| **5** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **Playwright** | `96.5k` | [#42449](https://github.com/microsoft/playwright/pull/42449) — the UI-mode filter summary was a plain `div`, so it could not be reached or opened from the keyboard |
| **6** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **.NET** · EF Core | `14.8k` | [#38880](https://github.com/dotnet/efcore/pull/38880) — pruning a pooled SQLite connection could kill the process from a native callback, because the rollback hook was cleared through a handle that was already closing |
| **7** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **.NET** · EF Core | `14.8k` | [#38971](https://github.com/dotnet/efcore/pull/38971) — `ExecuteNonQuery` and `ExecuteScalar` reported success when a later statement failed, and a busy commit after `RETURNING` was retried with a second `sqlite3_reset`, which answers OK once the first has reported the busy, so the write was rolled back with no error at all. **Merged into 12.0-preview1** |
| **8** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **.NET** · EF Core | `14.8k` | [#38976](https://github.com/dotnet/efcore/pull/38976) — reading a stream from a SQL expression handed three nulls to `sqlite3_table_column_metadata`, which answers `SQLITE_MISUSE`, so `GetStream` threw as soon as another expression column shared the query. Open since April 2022. **Merged into 12.0-preview1** |
| **9** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **.NET** · EF Core | `14.8k` | [#38875](https://github.com/dotnet/efcore/pull/38875) — a named default constraint was carried onto the temporal history table. Approved by a second EF Core team member after the `AlterColumnOperation` case the original tests did not reach. **Merged into 12.0.0** |
| **10** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **.NET** · BenchmarkDotNet | `11.5k` | [#3242](https://github.com/dotnet/BenchmarkDotNet/pull/3242) — `--affinity` could not address a CPU above the 32nd, and the 64th threw an unhandled `OverflowException` on a 32-bit host instead of a normal option error |
| **11** | <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" /> **LangChain** | `146.8k` | [#39978](https://github.com/langchain-ai/langchain/pull/39978) — removed a contradictory duplicate block from the Groq `with_structured_output` docstring |
| **12** | <img src="https://img.shields.io/badge/OpenJS-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="OpenJS Foundation" /> **Jest** | `45.5k` | [#16413](https://github.com/jestjs/jest/pull/16413) — a leading `#` was read as a URL fragment, so every package `imports` subpath broke under ESM. **Shipped in [v30.5.1](https://github.com/jestjs/jest/releases/tag/v30.5.1)** |
| **13** | <img src="https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white" alt="Apache" /> **Maven** | `5.4k` | [#13055](https://github.com/apache/maven/pull/13055) — the concurrent builder caught `Exception`, so a step throwing an `Error` printed BUILD SUCCESS while nothing had been built. A reviewer reproduced it and found a second failure wrapped the error in a checked exception, so the halt decision now reads the failures themselves |
| **14** | **Scrapy** · parsel | `1.4k` | [#367](https://github.com/scrapy/parsel/pull/367) — pinned how C1-range numeric character references extract, gated on the libxml2 version that implements the mapping rather than branching the expectations |
| **15** | <img src="https://img.shields.io/badge/Red%20Hat-EE0000?style=flat-square&logo=redhat&logoColor=white" alt="Red Hat" /> **Quarkus** | `15.9k` | [#56360](https://github.com/quarkusio/quarkus/pull/56360) — `@WithFormRead` request filters were moved after the body handler in reverse order, so their priorities were applied backwards. **Merged by a Quarkus maintainer** |
| **16** | <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy" /> **SciPy** | `15.1k` | [#26100](https://github.com/scipy/scipy/pull/26100) — `fcluster` with `maxclust` and `t=0` read one slot past the end of its criterion array, so the answer came from whatever was in that memory. **Merged by a SciPy maintainer for 2.0.0** |
| **17** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **.NET** · ML.NET | `9.4k` | [#7692](https://github.com/dotnet/machinelearning/pull/7692) — `DataFrame.Join` and `Merge` never returned when both suffixes were the same string. Open since 2022 |
| **18** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> **mypy** | `20.7k` | [#21941](https://github.com/python/mypy/pull/21941) — stubtest aborted the entire run when a `classmethod`'s first parameter wasn't named `cls`, taking out stub checking for a whole distribution. **Merged by a mypy core developer** |
| **19** | **radare2** | `25.1k` | [#27118](https://github.com/radareorg/radare2/pull/27118) — the reverse-engineering framework aborted `rabin2` on a valid 11-byte WebAssembly module whose export section was empty, because an empty section vector was sorted while still NULL. Fixed with a regression test built from raw bytes, no fixture file. **Merged by radare2's creator** |
| **20** | **radare2** | `25.1k` | [#27132](https://github.com/radareorg/radare2/pull/27132) — the arm64 assembler turned every `ldp` and `stp` into a different instruction, so `stp x29, x30, [sp, -0x20]!`, the usual function prologue, was written as an `ldp`. All 68 `ldp` and `stp` forms tested now give the same bytes as `llvm-mc`, and SIMD register pairs were added after a reviewer asked about them. **Merged by radare2's creator** |
| **21** | **radare2** | `25.1k` | [#27137](https://github.com/radareorg/radare2/pull/27137) — negative offsets in arm32 `ldr` and `str` were encoded as positive ones, so `ldr r0, [r1, #-4]` became `ldr r0, [r1, #4092]` with no error, and a negative register offset came out as an `add`. Six tests that had been marked broken pass now. **Merged by radare2's creator** |
| **22** | **radare2** | `25.1k` | [#27139](https://github.com/radareorg/radare2/pull/27139) — the `dis` and `pyc` disassemblers crashed on a null pointer when no file was loaded, as with `rasm2 -d`. Found with an ASan build by disassembling random bytes with every plugin, 8,500 runs, where these were the only two crashes. **Merged by radare2's creator** |
| **23** | **radare2** | `25.1k` | [#27141](https://github.com/radareorg/radare2/pull/27141) — arm32 `cmp`, `cmn`, `tst` and `teq` with an immediate overwrote the condition, so `cmpeq` assembled as an unconditional `cmp`, and above 255 the register was lost too. **Merged by radare2's creator** |
| **24** | **radare2** | `25.2k` | [#27133](https://github.com/radareorg/radare2/pull/27133) — the RISC-V assembler sent stores through the I-type encoder, so `sw a1, 8(sp)` came out as `sw s0, 11(sp)`, `srai` lost its arithmetic bit, and `jalr` broke. Checked against `llvm-mc` on random instruction words, matching encodings went from 880 to 1,934 of 3,482 and wrong ones from 315 to 5. **Merged by radare2's creator** |
| **25** | **radare2** | `25.2k` | [#27135](https://github.com/radareorg/radare2/pull/27135) — the AVR assembler wrote every I/O address other than `SPL`, `SPH` and `SREG` as 0 in `out`, `sbi` and `cbi`, and assembled the `-X`, `-Y` and `-Z` pre-decrement pointers as post-increment. After review it also rejects addresses that do not fit or carry trailing junk, and `in` takes the same I/O operand. **Merged by radare2's creator** |
| **26** | **radare2** | `25.2k` | [#27140](https://github.com/radareorg/radare2/pull/27140) — arm32 data-processing immediates above 255 kept only their low 8 bits unless they were a power of two, so `adc r11, r0, 61341696` was assembled with `#0`. radare2's creator checked all 4,096 immediate and rotation combinations across 19 mnemonics, then **landed it on master under my name** |
| **27** | **Markdig** | `5.3k` | [#966](https://github.com/xoofx/markdig/pull/966) — paragraphs, headings and code info strings were trimmed of every kind of Unicode space instead of only spaces and tabs, so a trailing no-break space or CJK ideographic space disappeared. Found by rendering 19,200 random documents with Markdig and cmark-gfm: 608 differences fixed, none new. **Merged by Markdig's author** |
| **28** | **Markdig** | `5.3k` | [#967](https://github.com/xoofx/markdig/pull/967) — an escaped backslash was read again as the start of a second escape, so a code fence info string like `\\*` lost its backslash. **Merged by Markdig's author** |
| **29** | **pyelftools** | `2.3k` | [#683](https://github.com/eliben/pyelftools/pull/683) — reading DWARF from any RISC-V object file failed with `Unsupported relocation type`, because there were no RISC-V relocations at all. Adds the 15 relocation types found in RISC-V debug sections, checked against `llvm-dwarfdump` on 16 GCC and clang objects. **Merged by pyelftools' creator** |
| **30** | **jadx** | `51.3k` | [#3028](https://github.com/skylot/jadx/pull/3028) — a method first reached through a dependency cycle was marked as visited before its code was loaded, so it never got its `throws` declaration and the decompiled Java did not compile. Found in a real APK, where 10 methods in 3 classes were missing it. **Merged by jadx's creator** |
| **31** | <img src="https://img.shields.io/badge/Microsoft-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> **ONNX Runtime** | `22.2k` | [#33543](https://github.com/microsoft/onnxruntime/pull/33543) — the CPU `TopK` comparators stopped being a strict ordering once a NaN was present, so `[1, NaN, 3, 2]` with k = 2 returned `[1, NaN]`. NaN now ranks largest, as the CUDA kernel already did, and the k = 1 fast path keeps its vectorised compare, since a naive NaN check made it 6x slower. **Merged by an ONNX Runtime maintainer** |
| **32** | **pefile** | `2.1k` | [#635](https://github.com/erocarrera/pefile/pull/635) — `write()` put back the zero padding of PE headers cut short by the end of the file, so an unmodified file came out longer: the 97-byte tiny PE files came back as 124 bytes, and `generate_checksum()` was off for them. Found by checksumming 3,419 PE files from the .NET 10 SDK and the radare2 test binaries with an independent implementation. **Merged by a pefile maintainer** |

### 🔄 In review

| Project | Contribution |
| :--- | :--- |
| <img src="https://img.shields.io/badge/Apple-000000?style=flat-square&logo=apple&logoColor=white" alt="Apple" /> **Core ML Tools** | [#2899](https://github.com/apple/coremltools/pull/2899) · [#2907](https://github.com/apple/coremltools/pull/2907) — `nn.MultiheadAttention` in inference mode runs through `_native_multi_head_attention`, which had no converter, so every model built on it failed to convert to Core ML, open since 2024; and antialiased resizes (torchvision `Resize`'s default) silently dropped the filter, off by 0.116 on average, which also uncovered a Core ML runtime bug in `reduce_sum` past 65,536 elements ([#2906](https://github.com/apple/coremltools/issues/2906)) |
| <img src="https://img.shields.io/badge/Prettier-1A2B34?style=flat-square&logo=prettier&logoColor=F7B93E" alt="Prettier" /> **Prettier** | [#20128](https://github.com/prettier/prettier/pull/20128) — nested emphasis around a bare URL turned into strong emphasis, open since 2020 |
| <img src="https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" /> **AWS** · CLI, CDK CLI | [aws-cli#10677](https://github.com/aws/aws-cli/pull/10677) · [aws-cdk-cli#1988](https://github.com/aws/aws-cdk-cli/pull/1988) — `--generate-cli-skeleton output` failed validation on its own sample data for 4,638 of 17,737 operations, open since 2017; and `cdk import` submitted the template CloudFormation mangles, so the import failed naming a resource nobody touched |
| <img src="https://img.shields.io/badge/Elastic-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elastic" /> **Elasticsearch** | [#158437](https://github.com/elastic/elasticsearch/pull/158437) — a malformed SQL cursor came back as a raw JVM error |
| <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" /> **pandas** | [#68035](https://github.com/pandas-dev/pandas/pull/68035) · [#68036](https://github.com/pandas-dev/pandas/pull/68036) — an `Enum` subclass is iterable but `is_list_like` said otherwise so it could not be used as `columns`, and `MultiIndex.factorize` rebuilt its uniques from tuples, silently dropping extension dtypes and level names |
| **Tailwind CSS** | [#20436](https://github.com/tailwindlabs/tailwindcss/pull/20436) — the v4 upgrade codemod rewrote a React `variant` prop as a utility class |
| **Chart.js** | [#12292](https://github.com/chartjs/Chart.js/pull/12292) · [#12293](https://github.com/chartjs/Chart.js/pull/12293) — a legend key that did not match the line it stood for, and a fractional-canvas resize regression |
| **Netty** | [#17389](https://github.com/netty/netty/pull/17389) — a form field still being decoded was in neither list `destroy()` clears, so a client that goes away mid-upload leaked the field and its slice of the inbound buffer. Vert.x installs the exact factory configuration this fires in |
| **jadx** | [#3026](https://github.com/skylot/jadx/pull/3026) — the Android decompiler silently produced wrong code for a loop exit shared with code before the loop |
| **ONNX** | [#8654](https://github.com/onnx/onnx/pull/8654) — the reference `ConvTranspose` crashed when an explicit `output_shape` needed padding; found by running the reference evaluator against onnxruntime |

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

## 🐍 Watch the snake eat my daily contributions

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
