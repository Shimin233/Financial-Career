Warmup: Finance interview questions and Answers
![](Warmup_FinanceQ1.png)

- __Financial modeling__: the process of creating a summary of a company's expenses and earnings, in the form of a spreadsheet   
that can be used to calculate the impact of a future event or decision\
(Source: [investopedia](https://www.investopedia.com/terms/f/financialmodeling.asp))


- Weighted average cost of capital(__WACC__): a calculation of a firm's cost of capital in which each 
category of capital is proportinately weighted. 

WACC = (E * Re /V) + (D * Rd * (1-Tc)/V)
where
E=Market value of the firm's equity, \
D=Market value of the firm's debt, \
V=E+D, \
Re=cost of equity, \Rd=cost of debt, \
Tc=corporate tax rate. \
Weighted value of equity-linked capital=(E/V) * Re, \
weighted value of debt-linked capital=(D/V) * Rd * (1-Tc). \

WACC inc <-> beta (volatility of a stock, i.e. both risk and return) and rate of retuen on equity inc
<-> valuation dec and risk inc (remember WACC is a 'cost')\
(Source: [invstopedia](https://www.investopedia.com/terms/w/wacc.asp))

- 'Build a cash flow (statement)' from an income statement:
- __Income statement__ (profit and loss statement / statement of revenue and expense): one of the three important financial statements, used for reporting a company's financial performace   over a 
specific accounting period. \
  The other two key statements are the __balance sheet__, and the __statement of cash flows__. 
  - four key items:
    - revenue
      - operating revenue: the revenue realised via primary activities (e.g. sale of product for a wholesaler)
      - non-operting revenue: the revenue realised via secondary, non-core business activities (e.g. interest income earned on business capital lying in the bank)
    - gains (aka other income): net income from sale of long-term assets), incl. net money made from one-time non-business activities, e.g. unused land, a subsidiary company
      - Note: tell revenue from receipt (cash accounted for when money is actually received)
    - expenses
      - primary activity expenses: incl. cost of goods sold (COGS), selling, and general administrative expenses (SG&A), depreciation or amortisation (the systematic repayment of a debt), research and development (R&D) expenses, emplyee wages
      - secondary activity expenses: all expenses linked to non-core business activities, e.g. interests paid on loan money
    - losses (as expenses): all expenses that go to a loss-making sale of long-term assets, one-time or any other un-usual costs, or expenses towards lawsuits 
      - e.g.++++++++++++++\
(Source: [investopedia-Income statement](https://www.investopedia.com/terms/i/incomestatement.asp))
-  __Statement of cash flows__: provides aggregate data regarding all _cash inflows_ that a company reveices from its ongoing operations and external investment sources, and all _cash outflows_ that pay for business activities and investments during a given period. \
  - a bridge between income statement and balance sheet, via showing how money moves in and out
  - most intuitive of all the financial statements: follows the cash made by the business in 3 ways/sections: 
    - operations, investment, and financing
    - sum of these three = _net cash flow_
    - these 3 sections help determine the value of a company's stock, or of the whole company
  - section 1, cash flow from operations(CFO): transactions from all operational business activities. e.g. buying&selling inventory and supplies, paying emplyees salaries; excl. investments, debts, dividends
  - section 2, cash flow from investment(CFI): the result of investment gains and losses, and cash spent on property, plant, equipment
    - look at this section for changes in _capital expenditures (capex)_ (capex inc -> cash flow dec, maybe -> invest for future and firm growing)
  - section 3, cash flow from financing (CFF): overview of cash used from debt and equity, measures cash flow between a company and its owners/creditors
    -  CFF>0 -> more money coming into than out; CFO<0, company is paying off debt/ making devidend payments and/or stock buybacks (a company pays shareholders the market value per share, to re-absorb ownerships of it from investors) 
(Source: [Cash flow statement](https://www.investopedia.com/investing/what-is-a-cash-flow-statement/); 
[Understanding a cash flow statement](https://www.investopedia.com/investing/what-is-a-cash-flow-statement/))

see section of the source web: How to Prepare a Statement of Cash Flows (Source: [CFI](https://corporatefinanceinstitute.com/resources/knowledge/accounting/statement-of-cash-flows/)

- Net present value(__NPV__)(https://www.investopedia.com/terms/n/npv.asp)

- XNPV is a function in Excel (https://www.investopedia.com/articles/investing/102715/calculating-npv-and-xnpv-formulas-using-excel.asp)

- difference? (https://www.wallstreetmojo.com/npv-vs-xnpv/)
The answer is simple. NPV assumes that future cash inflows happen at the end of the year (from today). ... However, when we calculated the present value using XNPV, the cash inflow dates were the actual year-end dates. When we use XNPV, we are discounting the first cash flow for a period that is less than one year.

![](Warmup_FinanceQ2.png)

![](Warmup_FinanceQ3.png)


### Efforts to insert LaTeX into markdown
(the only working way:) <img src="https://render.githubusercontent.com/render/math?math=WACC = (E * Re /V) + (D * Rd * (1-Tc)/V)">

can use Jupyter notebook, [ref1](https://gist.github.com/VictorNS69/1c952045825eac1b5e4d9fc84ad9d384), [ref2](https://stackoverflow.com/questions/35498525/latex-rendering-in-readme-md-on-github)

```markdown
![formula](https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1)
```

```math
SE = \frac{\sigma}{\sqrt{n}}
```

\\[ WACC = (E * Re /V) + (D * Rd * (1-Tc)/V) \\], \


