# 术数解读参考资料索引（Numerologist Skills 合并）

> 以下参考资料来自外部术数技能包合并，属传统解读经验规则，不进入本地引擎 claims 校验。
> 引用时须标明为传统经验参考，与引擎排盘事实分开表述。

## 八字参考资料（bazi-refs/）

| 文件 | 内容 | 何时读取 |
|---|---|---|
| `bazi-refs/tiangan-dizhi.md` | 天干地支基础、五行生克、十神对照表 | 需要查干支五行、十神关系时 |
| `bazi-refs/prompt-template.md` | 八字排盘解读输出模板 | 生成八字解读报告时 |
| `bazi-refs/interpretation-guide.md` | 八字解盘完整规则（格局、喜用神、大运流年分析框架） | 做八字命盘系统解读时 |

## 梅花易数参考资料（meihua-refs/）

| 文件 | 内容 | 何时读取 |
|---|---|---|
| `meihua-refs/interpretation-guide.md` | 梅花易数完整起卦、断卦流程与解读规则 | 梅花易数测事完整流程 |
| `meihua-refs/references/64gua.md` | 六十四卦卦名、卦序、基本卦义 | 查卦名卦义时 |
| `meihua-refs/references/yaoci.md` | 六十四卦爻辞详解 | 查动爻爻辞时 |
| `meihua-refs/references/bagua-wanwu.md` | 八卦万物类象（乾天坤地等取象） | 断卦时取外应、类象参考 |
| `meihua-refs/references/hexagram-relationships.md` | 卦与卦之间的错综关系、变卦逻辑 | 分析本卦变卦关系时 |
| `meihua-refs/references/hexagram-strategy.md` | 断卦策略、体用生克、吉凶判断步骤 | 系统断卦时 |
| `meihua-refs/references/18-divinations.md` | 十八类所占事项分类断法 | 按所问事项类别查断法 |
| `meihua-refs/references/ying-guides.md` | 外应（应期、外应观察）指南 | 取外应、断应期时 |
| `meihua-refs/references/yingqi-calc.md` | 应期计算方法 | 断事情何时发生时 |
| `meihua-refs/references/case-studies-expanded.md` | 梅花易数案例分析 | 参考实际断卦思路时 |
| `meihua-refs/references/zhouyi-zhuan.md` | 周易系辞、说卦等传文 | 需要引用易传原文时 |
| `meihua-refs/scripts/meihua_calc.py` | 梅花易数起卦计算脚本（Python） | 需要自动排卦时 |

## 紫微斗数参考资料（ziwei-refs/）

| 文件 | 内容 | 何时读取 |
|---|---|---|
| `ziwei-refs/stars.md` | 十四主星、辅星、煞星完整释义 | 需要解读具体星曜含义时 |
| `ziwei-refs/sihua.md` | 化禄/化权/化科/化忌四化解读规则 | 分析四化飞星时 |
| `ziwei-refs/patterns.md` | 紫微斗数常见格局（紫府同宫、府相朝垣等） | 判断特殊格局时 |
| `ziwei-refs/calculation.md` | 紫微排盘计算规则、宫位转换口径 | 需要理解排盘逻辑时 |
| `ziwei-refs/interpretation-guide.md` | 紫微解盘完整规则（三合派为主、飞星派补充） | 做紫微命盘系统解读时 |
| `ziwei-refs/ziwei-marriage.md` | 夫妻宫十四主星+辅煞+四化+格局解读；**必须结合三方四正（夫妻宫+迁移+福德+官禄）同看，不可单宫论命** | 看婚姻感情、配偶特质、正缘格局时 |
| `ziwei-refs/scripts/ziwei_verify.py` | 紫微结果校验脚本 | 需要交叉验证排盘结果时 |

## 奇门遁甲参考资料（qimen-refs/）

| 文件 | 内容 | 何时读取 |
|---|---|---|
| `qimen-refs/yongshen.md` | 奇门用神取法（日干、时干、值符、值使等） | 奇门解盘第一步取用神时 |
| `qimen-refs/geju.md` | 奇门常见格局（吉格、凶格） | 判断盘面格局时 |
| `qimen-refs/ruleset-mainline.md` | 时家奇门主线规则集（转盘奇门） | 奇门排盘解盘规则依据 |
| `qimen-refs/examples.md` | 奇门盘例分析 | 参考实际断盘思路时 |
| `qimen-refs/interview.md` | 正式排盘前的结构化访谈流程 | 用户要求奇门测事时，先访谈再排盘 |
| `qimen-refs/interpretation-guide.md` | 奇门完整工作流程（访谈→脚本排盘→解读建议） | 奇门测事完整流程 |
| `qimen-refs/scripts/qimen_cli.py` | 奇门遁甲排盘 CLI（Python） | 需要排奇门盘时，依赖 lunar_python |
| `qimen-refs/scripts/requirements.txt` | Python 依赖（lunar_python, tzdata） | 首次运行奇门脚本前安装 |

## 西方玄学参考资料

### 塔罗牌（tarot/）

| 文件 | 内容 | 何时读取 |
|---|---|---|
| `tarot/interpretation-guide.md` | 塔罗牌完整解读流程（Rider-Waite-Smith 体系） | 用户要求抽牌、每日牌、牌阵解读时 |
| `tarot/references/major-arcana.md` | 22 张大阿尔卡那正逆位释义 | 抽到大牌时查牌义 |
| `tarot/references/minor-arcana.md` | 56 张小阿尔卡那（四花色）正逆位释义 | 抽到小牌时查牌义 |
| `tarot/references/spreads.md` | 常用牌阵（三张牌、凯尔特十字、关系牌阵等） | 用户需要选牌阵时 |
| `tarot/references/interpretation-rules.md` | 塔罗解读通用规则、结合问题整合牌义 | 综合解读多牌时 |

### 西方占星（astrology/）

| 文件 | 内容 | 何时读取 |
|---|---|---|
| `astrology/interpretation-guide.md` | 本命盘解读体系（十二星座、十大行星、十二宫位、相位、合盘、运势） | 用户要求占星、星盘、星座运势、合盘时 |

## 使用规则

1. 排盘事实仍以本地 TypeScript 引擎（`pnpm engine`）为准；上述参考资料仅用于**解读规则和经验**。
2. 奇门 CLI 是 Python 脚本，作为排盘的备用/交叉验证手段，不替代主引擎。
