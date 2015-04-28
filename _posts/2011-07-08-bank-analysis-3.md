---
title: 'How to Analyze a Bank Part 3: Stressing Out'
author: Palmer Truelson
layout: post
permalink: /banking/bank-analysis-3/
image:
  - 
seo_follow:
  - 'false'
seo_noindex:
  - 'false'
categories:
  - Banking
tags:
  - bank stress test
---
[<img class="size-full wp-image-254 alignright" title="bank-stress" src="http://www.valuablebehavior.com/wp-content/uploads/2011/07/bank-stress.jpg" alt="Bricks stressed out" width="384" height="256" />][1]After running our <a href="http://www.valuablebehavior.com/banking/bank-analysis-2/"  target="_blank">bank solvency test</a> on our target bank, we have a rough idea of just how good a bank it is.  Now, we get to stress test it.  It&#8217;s time to make the clouds thunder and the winds blow with the stress test from <a title="Morningst Bank Credit Methodology" href="http://corporate.morningstar.com/us/documents/MethodologyDocuments/MethodologyPapers/BankCreditMethodology.pdf" onclick="javascript:_gaq.push(['_trackEvent','download','http://corporate.morningstar.com/us/documents/MethodologyDocuments/MethodologyPapers/BankCreditMethodology.pdf']);" target="_blank">Morningstar&#8217;s Bank Credit Methodology</a> acting as our Prospero.  Fortunately, this section of their methodology doesn&#8217;t require a lot of editing to be useful for small banks, but you do have to make a few extra assumptions.  It&#8217;s a pretty good model for a severe banking downturn AND has the added benefit of helping get a better understanding of a bank&#8217;s asset portfolio as the different types of loans have different write-off rates.  So let&#8217;s get started.

## Are You Ready to Rumble?

You&#8217;ll need a snapshot of the current bank&#8217;s loan portfolio by type.  Once again, get this from a call report at the <a title="FFIEC" href="https://cdr.ffiec.gov/public/" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://cdr.ffiec.gov']);" target="_blank">FFIEC</a> or via <a href="http://www.bankregdata.com" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://www.bankregdata.com']);" target="_blank">BankRegData.com</a>, then fire up Excel or Google Spreadsheet and start inputing values.  Once again using our lovely little example of a bank, Westamerica, we&#8217;ll see how well a good bank does during a harsh financial downturn.

First off, Westamerica is a good underwriter, so thankfully we can use the first column write-off percentages for stress tests, the low column.  If your bank has a history of good underwriting for at least ten years, we can go ahead and use the low column.  If there&#8217;s any doubt, stick to the middle, and if your bank has faced serious problems previously, go ahead and use high.  **Most banks that are worth being interested in are in the low write-off category as the others are likely too unpredictable and determining a margin of safety is likely too difficult.**

For Westamerica, I&#8217;m using their latest 2011 Q1 data.  Westamerica&#8217;s first lien mortgage loans are nearly all prime rated, so we&#8217;ll be using the 3.0% write off here, the same amount Wells Fargo experienced in the early 90s.

Westamerica has a number of FDIC loss share agreements (LSAs) on the books.  You can read more about loss share agreements <a href="http://www.fdic.gov/bank/individual/failed/lossshare/" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://www.fdic.gov']);" target="_blank">here</a> on the FDIC&#8217;s website.  Westamerica has FDIC LSAs of about $330 million in commercial real estate loans, $115 million in commercial and industrial loans, $63 million in individual other consumer loans, $38 million in miscellaneous loans, and some smaller ones from there.  All total about $660 million in loss shared loans and $21 million in real estate owned (REO).  The FDIC generally takes about 80% of the loss on these for the life of the agreement.  I generally add back 80% of the expected loss from each of these loans during the stress test.

Some banks have loans completely guaranteed by the government.  Obviously, be sure to subtract those from your loan amounts.  Westamerica has very few of these type of guaranteed loans, so I didn&#8217;t alter their loans because of loan guarantees.

Another large assumption I make is that interest income remains proportional to asset value, and as asset value shrinks, interest income shrinks proportionally.  I also assume interest expense, non-interest expense, and non-interest income remain constant, so no new business coming in.  Obviously, interest income should drop a little more as the interest of loans that are souring are often higher than the bank&#8217;s average interest income rate, but I make up for this by assuming that the assets sour immediately at the beginning of the year and no new business is added.

A final assumption I make is I include initial loan loss provisions with tangible common equity in the final computation of the ratios.  If you want to be even more conservative, you can exclude the provisions.

As always, **since we&#8217;re ultimately looking for large margins of safety, perfect models are not necessary.**

## Now It&#8217;s Time for the Show

Let&#8217;s see how the numbers play out. Here are our estimates of loan loss assumptions:

<p style="text-align: center;">
  <a href="http://www.valuablebehavior.com/wp-content/uploads/2011/07/WABC-Stress-Loans.png" ><img class="size-full wp-image-258 aligncenter" title="WABC-Stress-Loans" src="http://www.valuablebehavior.com/wp-content/uploads/2011/07/WABC-Stress-Loans.png" alt="" width="583" height="279" /></a>
</p>

Ultimately, Westamerica is about to take a $325 million hit in write-offs before figuring in pre-tax pre-provision earnings.  Here are what final ratios would look like:

[<img class="aligncenter size-full wp-image-265" title="WABC-Stress-Loss-2" src="http://www.valuablebehavior.com/wp-content/uploads/2011/07/WABC-Stress-Loss-2.png" alt="WABC Loss under Stress" width="524" height="289" />][2]

So, it&#8217;s clear Westamerica can take two brutal years in a row.  What was surprising (or not so surprising if you knew what line of banking they were in) was that they don&#8217;t do it perfectly.  They have a lot of commercial real estate, which even for good underwriters can sour quickly in a bad environment.  Fortunately, they don&#8217;t have many construction loans on the books.  High exposure to commercial real estate can hurt.  **Contstruction loans kill.  Large exposure to construction loans is reason to not buy a bank no matter how good they are**.  Don&#8217;t make my previous mistakes.

If we look at the final scores of Westamerica of 6.46% TCE + LL  / Assets and 11.88% TCE + LL / Risk Assets,** they are actually below Morningstar&#8217;s high end scores and are right in the middle.** In other words, Westamerica would only get a slightly above average grade of 6.2 on a scale of 10.  Passable, but they might actually have to raise some equity at the wrong time if more than two years of ruin occurred.  Obviously this is a worst case scenario, but that is **EXACTLY** the sort of scenario you run as a value investor.

One might claim that the annual write-off percentages may be too severe for a good underwriter like Westamerica, but **good underwriting depends on good management, and that can unfortunately change before it shows up in the numbers**, so it&#8217;s better to keep the stress test pretty harsh, even for good underwriters.

This stress test is helpful in analyzing a bank&#8217;s portfolio of loans and getting a better read on a bank&#8217;s asset quality.  Westamerica is definitely an amazing bank, one I would likely still buy at a good price, but they could use some extra tangible common equity because of their exposure to commercial loans.

Next post, we&#8217;ll take a closer look at some of the more qualitative aspects of banks.

***Photo Credit:*** photocase.com / <a title="User profile of Nordreisender ." href="http://www.photocase.com/user.asp?u=342584" onclick="javascript:_gaq.push(['_trackEvent','outbound-article','http://www.photocase.com']);">Nordreisender</a>

***Full Disclosure:*** I have no position in WABC

&nbsp;

 [1]: http://www.valuablebehavior.com/wp-content/uploads/2011/07/bank-stress.jpg
 [2]: http://www.valuablebehavior.com/wp-content/uploads/2011/07/WABC-Stress-Loss-2.png