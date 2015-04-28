---
title: 'How to Analyze a Bank Part 2: Riding on the Back of CAMELS'
author: Palmer Truelson
layout: post
permalink: /banking/bank-analysis-2/
image:
  - 
seo_follow:
  - 'false'
seo_noindex:
  - 'false'
categories:
  - Banking
---
## [<img class="alignright size-full wp-image-222" title="Robot camel racing" src="http://www.valuablebehavior.com/wp-content/uploads/2011/06/camel-race.jpg" alt="" width="425" height="282" />][1]

The first section of <a title="Morningstar's Bank Credit Methodology" href="http://corporate.morningstar.com/us/documents/MethodologyDocuments/MethodologyPapers/BankCreditMethodology.pdf" onclick="javascript:_gaq.push(['_trackEvent','download','http://corporate.morningstar.com/us/documents/MethodologyDocuments/MethodologyPapers/BankCreditMethodology.pdf']);" target="_blank">Morningstar&#8217;s Bank Credit Methodology</a> is the bank solvency score, basically a current check of capital adequacy, asset quality, earnings power, and liquidity.  Yes, four of the letters from <a title="CAMELS" href="http://en.wikipedia.org/wiki/CAMELS_ratings" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://en.wikipedia.org']);" target="_blank">CAMELS</a>, the undisclosed rating system that the US government uses to rate banks to determine if they can continue to operate.  We&#8217;ll hit management and sensitivity to market risk later.  For now, this first solvency score will give us a pretty good first approximation of how good a bank is.  However, Morningstar&#8217;s solvency score does suffer from one major flaw.

## No Moral Relativity in Banking

Morningstar&#8217;s solvency score does a great job of weighing earnings power, asset quality, capital, and liquidity.  However, the category scores are based on where banks are ranked relative to each other.  This really surprised me as I think it&#8217;s easier and more accurate to design an absolute scale to rate against within each category.  **Just because you&#8217;re better than 70% of other banks in a category doesn&#8217;t mean you&#8217;re good** as we&#8217;ve seen during many financial crises throughout history.  Although relative scores work most of the time, we should still have a system that can work relatively well even in a bad environment, so we&#8217;re only going to take &#8220;inspiration&#8221; from Morningstar&#8217;s methodology and tack on our own absolute scales.  My methodology rates each category on a 0-10 scale correlated to an underlying metric or metrics, weighs each category score, then finds the average.  The weights for each category are roughly similar to Morningstar&#8217;s but modified so as to be more useful for smaller banks.

## Behold, the Power of Earnings

This is the most important category, and one we&#8217;re giving 25% of the solvency score weighting.  A bank with sustainable earnings power is a bank with great offense.  When trouble comes, the bank can bowl right through it&#8217;s problems.  Westamerica (WABC) with its very low cost deposits and thus high net interest margin and US Bank (USB) with it&#8217;s merchant processing and asset management businesses are examples of banks with fantastic earnings power.  Finding these advantages in smaller banks, however, is rare and difficult, but extremely valuable if found.

We&#8217;re going to use pre-tax, pre-provision income to average assets as our metric for earnings power.  Morningstar rates this metric against other banks, but we&#8217;re going to use a scale of 1% to 3% with anything above 3% a ten, anything below 1% a zero, and with a sliding scale in between.  In my opinion, a great and rare bank is one who&#8217;s pre-tax, pre-provision earnings are at 3%.  My preference for 3% began with the classic line from Warren Buffett&#8217;s <a title="Berkshire 1990 Shareholder letter" href="http://www.berkshirehathaway.com/letters/1990.html" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://www.berkshirehathaway.com']);" target="_blank">1990 shareholder letter</a> on his purchase of Wells Fargo:

> Consider some mathematics: Wells Fargo currently earns well over $1 billion pre-tax annually after expensing more than $300 million for loan losses. If 10% of all $48 billion of the bank&#8217;s loans &#8211; not just its real estate loans &#8211; were hit by problems in 1991, and these produced losses (including foregone interest) averaging 30% of principal, the company would roughly break even.

In other words, roughly pre-tax, pre-provision was 3% of assets.  And Wells Fargo did roughly break even because they had such strong earnings.

I chose the floor to be 1% as opposed to 0% because anything below 1% (or really even 2%) we just don&#8217;t want to consider.  I&#8217;m interested in banks with strong earnings.  Banks deal with leverage.  They live in what can be a commodity business.  **We need some sign that they have something going for them that makes them not an ordinary bank**.  Strong earnings are a good clue, but be careful.

A number of small banks I&#8217;ve studied appeared to have strong earnings, but the quality of those earnings was suspect.  **A good operating history of strong earnings is what we&#8217;re looking for**, not just during boom times.  I have been burned by small banks with lots of commercial and development loans pumping up their earnings that sour in a downturn.  We&#8217;ll handle loan quality in later posts, but for now, just note that earnings power, while incredibly important, needs further investigation to make sure that their earnings are of quality.

One last caveat.  If you notice the annual growth rate of loans to be in the lower midteens or above and the growth is not through acquisition, you may have to give their earnings strength a zero score and forget this bank.  High growth in banks is dangerous and unpredictable.  Some can do it, but it&#8217;s very hard to get a handle on their asset quality.

## Assets Refusing to Perform

Second is a comparison of non-performing assets and past due loans to total assets which we&#8217;ll count as 20% of the total solvency score.  Morningstar uses relative weightings, so we&#8217;re using an inverse scale of 4% &#8211; 1% with 4% and above earning a 0 and 1% and below earning a 10.  We want good underwriters like Valley National which averaged a 0.6% over the past three years when we look at the data from <a title="BanRegData" href="http://www.bankregdata.com/bkAQnpa.asp?met=NPA&inst=HC1048773" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://www.bankregdata.com']);" target="_blank">BankRegData.com</a>. (**Note**: it&#8217;s not the first NPA / Total Assets data on the page.  It&#8217;s the second, just below that has the adjusted data with government guaranteed and FDIC loss shared data taken out.)

Now, some banks are still good banks that run higher NPA ratios, usually because they get paid for the added risk.  But if we want to find lower risk banks, we&#8217;ll want to stick to percentages that are in the  0 &#8211; 2% range and not dabble in the higher ones.  Checking this metric not just in the present but also in the past is especially important. ** It&#8217;s key that we ensure that they have quality assets to back up their strong earnings** and have a history of doing so.  We&#8217;ll analyze more of their asset quality in later tests.

We weight this score at 20%.

## Capitally Adequate

<a title="TCE" href="http://www.investopedia.com/terms/t/tangible-common-equity-ratio.asp#axzz1QiKkmSnU" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://www.investopedia.com']);" target="_blank">Tangible common equity</a> is the in vogue metric amongst regulators for assessing capital adequacy, and I have to agree with them.  It cuts out most of the fluff, and you&#8217;re left with a bank&#8217;s actual cushion against losses.  The ratio we&#8217;ll be using is tangible common equity to tangible common assets; about as conservative a measure of capital adequacy as we can get.  I&#8217;m not a stickler for this as I feel earnings strength and asset quality are way more important.  As long as it&#8217;s 8%, I&#8217;m happy.  If at or above 8%, I give it the full ten points.  If below, I give it zero as regulators will soon be requiring at least 7%.  A little bit of a buffer is necessary.

We weight this score at 15%.

## The Eyes of Texas

The Morningstar document then has two categories devoted to capital adequacy via a tangible common equity to non-performing assets ratio and a loan loss reserve to non-performing assets ratio.  I realized that combining them gives us something pretty close to the infamous <a title="Texas Ratio" href="http://en.wikipedia.org/wiki/Texas_ratio" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://en.wikipedia.org']);" target="_blank">Texas ratio</a>.  A rather abbreviated description of the Texas ratio is that it compares how much bad stuff ( non performing assets, 90 day past due loans, restructured loans, real estate owned ) to good stuff ( loan loss reservers, tangible equity ).  And the creator of the ratio found that as it approached 100%, most banks tended to fail.

Nevertheless, The Texas ratio suffers from some flaws and relying solely on this metric to determine the viability of a bank is foolhardy.  For a fantastic discussion on why comparing loan loss reserves to non-performing assets faces problems, read <a title="Loan Loss Reserves" href="http://www.bankstocks.com/ArticleViewer.aspx?ArticleID=5748&ArticleTypeID=2" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://www.bankstocks.com']);" target="_blank">Everything You Wanted to Know About Loan Loss Reserves</a> at BankStocks.com.   The key flaw he points out is that loss reserves are leading indicators and non-performing assets are lagging indicators.  Ultimately, you can&#8217;t fully rely on the statistic to say whether a bank will fail or not.

However, **the Texas ratio does a great job of identifying strong, conservative banks**, the kind of ones that are our focus.  Low ratios in the 10%-30% range are strong signs of a great bank, so I&#8217;ve placed the range for this score going from 20% &#8211; 70%, where 20% and below gets a 10, 70% and above gets a zero, and a sliding scale in between.

For getting this information, BankRegData&#8217;s Texas ratio section is a great resource for grabbing this metric in a painless fashion.  They calculate it in a very conservative means and handle all of the gooey details like government guaranteed assets, FDIC shared losses, mortgage servicing rights (which should be considered tangible in my opinion as they are a revenue source), and also adding in restructured loans to non performing assets as they have a tendency to default as well.

We then weight this score at 20%.

<span style="font-size: 20px; font-weight: bold;">Just Say No to Brokered Deposits</span>

Finally, we look at liquidity risk.  We want to make sure that <a href="http://www.investopedia.com/terms/c/core-deposits.asp#axzz1QiOaFpy4" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://www.investopedia.com']);" target="_blank">core deposits</a> are a major part of the bank&#8217;s liabilities and that the bank isn&#8217;t over-loaned.  When you get a <a href="https://cdr.ffiec.gov/public/ManageFacsimiles.aspx" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://cdr.ffiec.gov']);" target="_blank">Uniform Bank Performance Report</a> from the FFIEC, the summary ratios page has two major ratios for liquidity, the non-core funding dependence ratio and net loans and leases to assets ratio, so these are the two ratios we&#8217;ll use.

Non-core funding dependence is determined by the formula:

> ( non-core liabilities &#8211; short-term investments ) / long-term assets.

This roughly tells you how much &#8220;hot money&#8221; the bank has, i.e. deposits over the FDIC limit, deposits that are brokered, debt from capital markets, anything that is more likely to disappear more quickly than a vanilla, sticky FDIC deposit.  If this ratio is below 25%, I give the bank five points and zero if it&#8217;s above.

For the other five points, I check to make sure the loans to assets ratio is below 70%.  We want to make sure they aren&#8217;t overextended.  The <a title="Bank Scores" href="http://bank-scores.com/?page_id=63" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://bank-scores.com']);" target="_blank">folks at Bank-Scores.com like 65%</a>, and being even safer isn&#8217;t a bad thing, though I liked having it just a touch higher.

These are two quick, relatively simple checks to make sure your bank suddenly won&#8217;t find itself lacking capital in the event of a crisis.  Morningstar lessens the impact of this metric since they&#8217;re focused on the larger banks and larger banks get a great deal of funding from capital markets.

We weight this score to the total at 20%.

## All Together Now

In summary:

  1. Pre-provision, pre-tax earnings to average assets, 1%-3% scale, 25% overall weighting
  2. Non-performing assets and past due loans to total assets, 4%-1% scale, 20% overall weighting
  3. Tangible common equity to tangible assets, 8% threshold, 15% overall weighting
  4. Texas ratio, 20% &#8211; 70% scale, 20% overall weighting
  5. Non-core deposit dependency ratio and loan to asset ratio, theshold or 25% and 70% respectively, 20% weighting overall.

And a quick example with Westamerica:

  1. PPPT Earnings &#8211; 2.9% &#8212; Score of 9.5
  2. NPA & +90DPD / Total Assets &#8211; 1.67% &#8212; Score of 7.8
  3. TCE / TA &#8211; 9% &#8211; Score of 10
  4. Texas Ratio &#8211; 19.19% &#8211; Score of 10
  5. Non-Core Dependency Ratio &#8211; 6.44%, L / A &#8211; 57.2% &#8212; Score of 10

Overall Score: 9.4

No big surprise here.  Westamerica is an interesting bank, worthy of more consideration. (If only it would ever go on sale!)  **Scores in the 8-10 range are worth taking a look at.** Obviously this solvency test is not foolproof.  We still need to dig deeper into asset quality to make sure earnings are sustainable, and we haven&#8217;t paid any attention to management at all.  We&#8217;ll take a look at these in future posts.

But for now, we have a pretty solid screen for smaller banks that could have an edge.

***Photo Credit: ****iStockPhoto.com / forgiss*

***Full Disclosure: ****I own shares of Wells Fargo (WFC) and US Bank (USB).  I have no positions in Westamerica (WABC) or Valley National (VLY).*

 [1]: http://www.valuablebehavior.com/wp-content/uploads/2011/06/camel-race.jpg