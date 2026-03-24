# Building a Financial Model

This topic will give you a rough overview of basic financial models. All following topics in this lesson will focus on elaborating on the concepts discussed here. 

There are two main reasons why you want to build a financial model. First, you want to understand the validity of your business. Will you be able to generate profits in the long run? Secondly, receiving funding from investors highly depends on the validity of your financial model, the soundness of the assumptions you have made and the elegance of your calculations. If you want to raise funds, it is critical for you to freshen up your financial vocabulary and learn to build a decent financial model. The good news is: If you know the steps, this is one of the easiest parts of your entrepreneurial journey. 

Before we jump into financial models, have a look at the screenshots from our financial model template. This is a standard profit and loss statement, which builds the core of every financial model. This is what investors will be looking for, usually with three main questions in mind:

- Potential: How big will the turnovers be in 5+ years from now?
- Profitability: How profitable will the business be once it has achieved scale?
- Funds: How much money does the startup need, and what will my funds be used for?

Can you answer those questions by looking at the financial model below?

![Source: Own representation](/api/media/file/ef-bfm.png)

A typical venture capitalist will likely look at the above table and evaluate the company as follows:

- **Potential**
The investor will look for revenue potential of €20-50M within the first 5 years. This is approximately given in this case. 
- **Profitability**
The EBITDA margin of 50% is fantastic. [This graph](https://www.statista.com/statistics/1136227/ebit-ebitda-margin-software-companies/#:~:text=EBIT%20and%20EBITDA%20margin%20of%20major%20software%20companies%20worldwide%202019&text=Microsoft%20led%20major%20software%20company,EBITDA%20margin%20of%2045.6%20percent.) shows the EBITDA margins of major tech companies out there. Comparably, this venture has a very high EBITDA margin. The investors will likely dig deeper and ask a lot of follow-up questions to find out whether such a high margin is indeed achievable. 
- **Funds**
One can see that the EBITDA (i.e. profit) in the first three years is negative. This is likely why the company needs funds. The investor will now be interested in understanding whether these funds will actually lead to the company growing as forecasted. The investor can see that in the first year half of operating expenses are used for distributing the product (marketing & sales) while 50% seem to be invested into building a better product and general [overhead](https://www.investopedia.com/terms/o/overhead.asp). This is atypical for a software business, but in this specific case, the software might have been already built and money is sought for marketing and growth. In such cases, the above cost distribution is valid.

Next, we will have a look at all building blocks of a financial model individually. 

## Your Entrepreneurial Profit and Loss Statement

In order to develop a basic understanding of how to build a financial model, we recommend you watch this video:

[YouTube](https://www.youtube.com/watch?v=Wws6T9uPVfA)

If you are interested in digging even deeper, the below video is a more detailed alternative:

[YouTube](https://youtube.com/watch?v=xlXDZyZ9azk)

When building a profit and loss statement, there are two overarching points that are relevant. For revenues, there is usually an easy calculation, multiplying the following two figures:

- # of customers OR # of sales
- Price

Your assumptions about the price and the # of customers that you can achieve should be valid. Moreover, one should see the link between your costs and your sales. Some costs should scale with sales 1:1 (e.g. customer acquisition costs), others scale slightly (e.g. customer support staff costs) and others should be mostly detached from your # of customers (e.g. basic development costs).

For costs, you always begin with the costs that are the best attributable (i.e. directly linkable) to the product and work yourself to the costs least attributable to the product. For example, a software business would have their customer acquisition costs, hosting costs per user, costs for payment providers such as Stripe, etc. listed first. Further down in the sheet, general administrative costs, staff costs, etc. will follow. You may check out [Investopedia](https://www.investopedia.com/terms/p/plstatement.asp) and [Amazon’s P&L statement](https://corporatefinanceinstitute.com/resources/knowledge/accounting/profit-and-loss-statement-pl/) to get a feeling for how this order is applied in practice. 

## Determining the Amount of Funding Needed: Your Cash Flow Statement 

If you are unfamiliar with cash flow statements, make sure to check out the earlier section in this course on cash flows. As an entrepreneur, your cash flow statement presented to an investor is usually very simple. Beware, though, that in some specific businesses it makes sense to provide an in-depth statement of cash flows to investors, such as when setting up a fund-like business that requires specific liquidity management.

![Source: Own representation](/api/media/file/ewor-assets-financial-model-034x.png)

In the example above, you see the cash flow statement corresponding to the profit and loss statement you have seen in the upper section of this topic. In this case, all that has been done (which is usually sufficient for an early-stage investor) is to take the EBITDA from the profit and loss statement and add the investment amount sought. Row 11 of this sheet lists the accumulated cash flows and applies the ‘MAX-Function’ to determine in which year the negative cash flows peak. As the cash flows will never fall below ~ € -1.8 M, the investment amount is set to €2 M to account for a tiny buffer. It is often recommendable to account for an even higher buffer of up to 20% of the max losses occurring. 

As an entrepreneur, you want to consider two things: Firstly, do you need to raise all the money now? It might be advisable to raise a smaller sum of money first and plan for an additional funding round later. This is beneficial because your valuation will be higher later on, and raising the same amount of money two years later will result in you giving less equity away. On the other hand, you might find it difficult to raise funds in the future and a considerable amount of your time will be invested into fundraising which would be better invested into you focussing on the product. In this case, it is not recommendable that you raise funds earlier. 

## Determining Your Valuation

In the same sheet, you will have everything necessary to determine your company valuation, should you go with a DCF method. There are only two important things to know:

- Do not use a DCF method if your assumptions have little ground. For deep tech ventures or those ventures requiring money to build their product first, a DCF method is not advisable.
- Use a DCF between 40% (if you are already making revenues and have achieved clear product market fit) and 70% (if you are still working on your product market fit).
- Account for 5-7 additional years when working with your DCF. Anything beyond 7 years is heavily assumption-driven.

If you want to do a more sophisticated valuation, check out the third lesson, talking about the relative valuation method and the VC-method.

## Cap Table

The cap table lists the shareholders, the amount of shares they hold and the amount of value attributed to their shares. Usually, investors ask you to provide them with an updated cap table at the beginning of every year. The below cap table explains the fundamentals of how equity is redistributed during funding rounds. 

Firstly, when raising, you are issuing new shares (capital increase). A typical German GmbH has 25,000 shares. Once you have valued your company (pre-money), it will be worth X, which is in this case €8.5 M. The valuation was derived from the DCF method described above. The post-money valuation is nothing more but your current valuation + the amount of investment raised. Then, there will be a pro-rata calculation on how many more shares need to be issued and how much each investor holds given their investment ticket sizes. This means that the founder’s relative equity share will be reduced, but not the absolute amount of equity, measured in €'s or any other currency.

In later rounds, the founder might be further diluted, but also gain in equity value based on the hopefully higher valuations the company achieved. In this case, it is assumed that the company value increases five-fold within 2 years. This is not unrealistic for a promising startup. As you can also see, the founder and current investors will be further diluted as part of the future capital increases.

![Source: Own representation](/api/media/file/ewor-assets-financial-model-024x.png)

## Final Notes

The financial model used in this case study was used to receive an actual investment offer (but has been slightly modified for educational purposes). Therefore, you can assume that the granularity of this sheet will be enough for a pre-seed or seed stage company to raise money. A Series A company will likely have to come up with a more sophisticated model, but will have access to enough resources and financial consultants to update their model without this course. 
