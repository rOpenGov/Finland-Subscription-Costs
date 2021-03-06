## Subscription costs to scientific publishers in Finland 2010-2017

Leo Lahti (Dec 3, 2018) 




This post provides a brief overview of the subscription prices paid by Finnish research institutions to academic publishers in 2010-2017.

Finland is possibly the only country that has systematically released subscription prices that research libraries pay to academic publishers [as open data](https://avointiede.fi/fi/avoimet-julkaisut/kustantajahintatietoja). The data is available for all major research institutions in Finland. Recently, an updated data set for 2010–2017 was made openly available at [avointiede.fi](https://avointiede.fi/fi/avoimet-julkaisut/kustantajahintatietoja). In addition, [full text agreements](https://www.kansalliskirjasto.fi/extra/finelib_julkinen/) with many publishers have been [made available](http://finelib.fi/negotiations/agreements/). The subscription price data was initially provided by Finnish Ministry of Education and Culture, and its Open Science and Research Initiative funded 2014–2017, after a successful Freedom of Information request by the Finnish Open Science community, as summarized [elsewhere](https://www.mostlyphysics.net/blog/2016/6/13/finland-takes-leading-role-in-the-openness-of-academic-journal-pricing). This post updates our [earlier analysis](http://ropengov.github.io/r/2016/06/10/FOI/). For source code, see [main.R](https://github.com/rOpenGov/Finland-Subscription-Costs). 


## Overall subscription costs 2010-2017



Based on the data collected by the Ministry of Education, Finland paid in total
198.7 million EUR subscription and other
fees on scientific publishing in 2010-2017. The average annual costs for in Finland were 25 MEUR.

Data for the top-10 publishers in the UK 2010-2014 is available in [Lawson, Meghreblian & Brook, 2017](https://olh.openlibhums.org/articles/10.16995/olh.72/#B45) ([Table 1](https://olh.openlibhums.org/articles/10.16995/olh.72)). During this period the UK paid altogether 4319 MEUR (rough estimate based on the exchange rate June 12, 2016) for the top-10 publishers. Finland paid 62 MEUR for the same top-10 publishers in 2010-2014. This is  17.1% of the UK expenditure _per capita_. It could be that the data is not directly comparable but this will require further investigation. 


Information for Finland is available by [agreement
type](table/cost_by_type.csv), organization type, and [subscription
category](http://data.okf.fi/ropengov/20160613-FOI/dashboard.html).



### Costs by publisher

Overall, the Finnish data covers 376 unique publishers ([see annual costs by publisher](http://data.okf.fi/ropengov/20160613-FOI/dashboard.html)). The figure indicates the total subscription fees paid to the top publishers 2010-2017. One third of the total costs go to Elsevier, which has been often [criticized](https://gowers.wordpress.com/2014/04/24/elsevier-journals-some-facts/) for its huge [profit margins](http://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0127502). The costs are given per bundle, so we cannot compare average journal prices among individual publishers based on this data.

![plot of chunk foi-totalcosts2b](figure/foi-totalcosts2b-1.png)




The total costs paid to scientific publishers by Finland have increased roughly 10% per year in 2010-2017 (annual increase is indicated in the left figure). The top-10 publishers correspond to 75% of the overall costs (right figure). See a separate table for full [annual costs by publisher](http://data.okf.fi/ropengov/20160613-FOI/dashboard.html). 

<img src="figure/foi-costbytime-1.png" title="plot of chunk foi-costbytime" alt="plot of chunk foi-costbytime" width="860px" />




Let us compare the [relative increase in publisher costs](http://data.okf.fi/ropengov/20160613-FOI/dashboard.html). The costs are normalized to 1 in 2010, and the top 10 publishers with the highest cost increase in 2010-2017 are shown. The 275 publishers that did not have declared costs in 2010 or 2017 (see [here](http://data.okf.fi/ropengov/20160613-FOI/dashboard.html)) are excluded.

![plot of chunk foi-timebypublisher2b](figure/foi-timebypublisher2b-1.png)



### Costs by organization



The Finnish data collection includes 82 organizations ([see annual costs by organization](http://data.okf.fi/ropengov/20160613-FOI/dashboard.html)). The universities ('yliopisto') are responsible of 78.9% of all costs (left figure); University of Helsinki had the highest total costs in 2010-2017 (37.9 MEUR; top institutions shown in the right figure).

<img src="figure/foi-totalcosts2d-1.png" title="plot of chunk foi-totalcosts2d" alt="plot of chunk foi-totalcosts2d" width="420px" /><img src="figure/foi-totalcosts2d-2.png" title="plot of chunk foi-totalcosts2d" alt="plot of chunk foi-totalcosts2d" width="420px" />



Finally, let us compare the relative share of costs per
institution. The top organizations with the highest total costs are
shown.


![plot of chunk foi-timebyorganization2c](figure/foi-timebyorganization2c-1.png)
