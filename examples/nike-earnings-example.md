# NIKE Earnings Example

> 真实调用案例 · 2026-10-02
>
> Earnings 模式

这个案例来自一次真实的 `equity-research` 调用。

用户没有提供季度、指标、来源、比较维度或研究框架，只提出了一个普通问题。

## 用户输入

> 分析一下 NIKE 最新财报，告诉我这次真正值得关注的变化。

## 为什么保留这个案例

这个案例主要用于展示：

> 用户不需要先学习一套复杂 Prompt，研究方法本身已经包含在 Skill 中。

面对上面这一句话，Skill 自行完成了：

- 确认截至调用日最新已经发布的财报；
- 锁定 NIKE 自身财年和季度口径；
- 对比上一季度寻找真正新增的变化；
- 优先核验公司和 SEC 原始披露；
- 区分主动渠道调整与真实需求疲软；
- 区分已经兑现的经营结果与管理层未来预期；
- 检查毛利率、渠道、区域等指标背后的实际驱动；
- 结合外部信息解释财报后的二级市场反应；
- 从大量指标中选择真正改变判断的核心问题。

## Skill 抓到的核心问题

### 1. Performance 的恢复越来越真实，但规模还不足以抵消旧增长引擎的下滑

FY2026，NIKE Performance 业务已经达到约 160 亿美元，并实现中个位数增长；FY2027 Q1 又进一步增长高个位数。

本季度跑步、全球足球、网球和高尔夫均实现两位数增长，北美篮球也实现两位数增长。

这意味着 NIKE 重新聚焦运动性能产品已经开始出现经营数据支持。

但与此同时，NIKE Sportswear 本季度仍下降低双位数，而且仍占接近一半收入；Jordan Brand 约占整个 NIKE 业务的 13%，收入下降中双位数。

Dunk 收入接近减半，单这一项就给 Sportswear 带来约 2 亿美元收入拖累。

更重要的是，管理层明确表示，部分上市时间较长、体量较大的 Sportswear 鞋款实际终端销售低于预期，并已经影响后续批发订单。

因此，这里的问题已经不能简单解释成“NIKE 为了品牌健康主动少卖”。

**Performance 的复苏是真的，但 Sportswear 和 Jordan 同时存在主动缩量与真实产品需求不足。**

### 2. Greater China 不但没有见底，短期压力反而进一步加大

上一季度 FY2026 Q4，大中华区固定汇率收入下降 17%。

FY2027 Q1，这一降幅扩大到 26%。

本季度大中华区：

- 批发固定汇率收入下降 31%；
- NIKE Direct 下降 18%；
- 鞋类下降 26%；
- 服装下降 27%。

管理层表示，中国数字渠道清理需要多个销售季；CFO 进一步明确表示，FY2027 全年指引本身已经假设中国收入在本财年剩余时间继续恶化。

因此，现在需要验证的已经不是：

> 中国什么时候马上恢复增长？

而是：

> NIKE 用短期收入规模换取渠道、折扣和品牌重新受控以后，消费者需求最终会不会真正回来？

这件事目前仍未得到证明。

## 两个容易误读的信号

### 北美批发恢复，不等于“DTC 失败”

本季度北美固定汇率收入增长 2%，其中批发增长 9%，NIKE Direct 下降 6%。

FY2026 全年北美批发收入已经增长 14%。

这说明 NIKE 修复批发伙伴关系已经出现经营数据支持。

但更准确的理解不是“直营失败、批发成功”，而是 NIKE 正从过去过度偏向直营，重新回到直营与批发更平衡的渠道结构。

### 毛利率改善，不等于品牌定价权已经恢复

FY2027 Q1 毛利率提升 60 个基点至 42.8%。

但公司披露，本季度毛利率改善主要受益于仓储、物流和供应链成本下降，电话会同时提到汇率带来的帮助；折扣增加和渠道结构则形成负面影响。

因此目前更合理的结论是：

**运营效率正在改善。**

而不是：

**消费者已经重新愿意为 NIKE 支付更高价格。**

## 为什么市场反应依然负面

NIKE 给出的 FY2027 全年收入预期是下降高个位数，调整后 EPS 为 1.15–1.35 美元。

当时 Reuters 引用 LSEG 汇总的市场预期约为全年收入下降 2%。

财报后 NIKE 股价在盘后交易中一度下跌约 8.5%。

真正改变市场判断的，不只是 Q1 当季数字，而是：

**这轮调整的时间被进一步向后拉长。**

管理层预计 Sportswear、Jordan Brand 和 Greater China 的主动调整会继续压制 FY2027 剩余时间，并可能延续进入 FY2028。

## 最终判断

> **NIKE 的运动产品复苏已经越来越不像故事，但现在的问题变成了：这块正在恢复的业务，增长速度仍赶不上 Sportswear、Jordan 和中国区主动缩量与真实需求疲软造成的拖累。**

这个案例展示的不是一个固定的 NIKE 分析模板。

更重要的是：

> 用户只问了一个普通问题，而 Skill 自行决定应该验证哪些事实、比较哪些季度、在哪里停止推断，以及什么才是真正值得展开的变化。

## 主要来源

- [NIKE FY2027 Q1 官方财报](https://about.nike.com/en/newsroom/releases/nike-inc-reports-fiscal-2027-first-quarter-results)
- [NIKE FY2027 Q1 SEC Exhibit 99.1](https://www.sec.gov/Archives/edgar/data/320187/000032018726000184/q1fy27exhibit991er.htm)
- [NIKE FY2026 Q4 官方财报](https://about.nike.com/en-GB/newsroom/releases/nike-inc-reports-fiscal-2026-fourth-quarter-and-full-year-results)
- [NIKE FY2026 Form 10-K](https://www.sec.gov/Archives/edgar/data/320187/000032018726000088/nke-20260531.htm)
- [NIKE FY2027 Q1 Earnings Call Transcript](https://stockanalysis.com/stocks/nke/transcripts/702283-q1-2027/)
- [Reuters：NIKE FY2027 Q1 市场反应与预期](https://www.reuters.com/business/retail-consumer/nike-quarterly-sales-miss-estimates-china-weakness-competition-weigh-2026-10-01/)

---

这是历史研究案例，数据和判断对应 2026-10-02 当时可获得的信息，不应被视为 NIKE 的当前状态或投资建议。
