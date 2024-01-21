### This project focuses on the first three years of the factory's activity and provides key metrics and insights to view and predict the growth and improvement of the company.


Mr. Fuzzy is an imaginary stuffed animals' factory that established in March 2012.

The factory produced four products in a few different time periods, as follows: 

Product one "Mr. Fuzzy" launched in March 2012.
Product two "Love Bear" launched in January 2013.
Product three "Sugar Panda" launched in December 2013.
Product four "Mini Bear" launched in February 2014.

I based my project on five main questions:

The first question focused on how the annual and monthly revenue by product looks like? So I can better understand the business.
The second question focused on whether products were often bought together with another product?
The third question focused on the commonly used website traffic marketing source?
The fourth question focused the commonly device type used in the marketing source found in question number three?
The fifth question focused on how can we help the business grow?

To answer these five questions and get some insights, I analyzed Mr. Fuzzy Factory dataset with SQL and Tableau to better understand the data and create the dashboards below.



**My Conclusions:**

•	The four products added a consistent revenue growth since 2012 and attracted clients to buy two or more products.
•	The analysis presents the effectiveness of "gsearch" and "brand search" as marketing sources, and the factory should consider a budget increase for these two sources.
•	The marketing source "bsearch" future investment should be monitored and reconsidered.
•	 Since “Mr. Fuzzy” brand became popular, and more clients are searching for the brand directly in the search engine. This phenomenon can assist the company to decrease marketing expenses in the future.
•	The factory should decide; Either to focus on desktop users’ ads or find a better source to increase mobile device users’ activity.
•	The new page lander-1 showcases effectiveness over homepage and therefore the factory should consider replacing homepage with lander-1 page.


I might consider analyzing further the website funnel to better understand which page loses most sessions and create an AB testing to confirm page improvement.



**This dashboard provides an overview of [the company's annual revenue](https://public.tableau.com/app/profile/serach.mayerfeld/viz/ProductsDashboardbyYear/ProductsByYearDashboard?publish=yes) since 2012 , as a key metric to monitor performance:**


(<div class='tableauPlaceholder' id='viz1705854898250' style='position: relative'><noscript><a href='#'><img alt='Products By Year Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProductsDashboardbyYear&#47;ProductsByYearDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ProductsDashboardbyYear&#47;ProductsByYearDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProductsDashboardbyYear&#47;ProductsByYearDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1705854898250');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>)

- The first product the company published is "Mr. Fuzzy". This product provided a stable revenue growth over the years.
 
- In 2013, the company launched the products "Love Bear" and "Sugar Panda", and in 2014, the latest product "Mini Bear".


**This dashboard displays insights on the products' [cross sale](https://public.tableau.com/app/profile/serach.mayerfeld/viz/ProductsCrossSaleDashboard/ProductsCrossSaleDashboard?publish=yes):**


![Products Cross Sale Dashboard](https://public.tableau.com/app/profile/serach.mayerfeld/viz/ProductsCrossSaleDashboard/ProductsCrossSaleDashboard?publish=yes).


- Product 1 "Mr. Fuzzy" was often bought together with product 3 "Sugar Panda", whereas Product 2 "Love Bear" and Product 4 "Mini Bear" were often bought together with Product 1 "Mr. Fuzzy".

  
**The following dashboard showcases the [website's traffic source and device type](https://public.tableau.com/app/profile/serach.mayerfeld/viz/ChannelSourceandDeviceTypeDashboard/MarketingInvestmentInvestigationDashboard?publish=yes) used by sessions:**


![Marketing Investment Investigation Dashboard](https://public.tableau.com/app/profile/serach.mayerfeld/viz/ChannelSourceandDeviceTypeDashboard/MarketingInvestmentInvestigationDashboard?publish=yes).


The top graph showcases the conversion rate of the website's traffic source by order:

- The marketing sources "gsearch" and "brand search" have a consistent 'session to order' conversion rate's growth since 2012. 
-  The marketing source "bsearch" 'session to order' conversion rate decreased in 2014 as opposed to 2013. 
- The marketing source "organic search" 'session to order' conversion rate, has consistently increased since 2012. This means that “Mr. Fuzzy” brand became popular, and more clients are searching for the brand directly in the search engine. 
 
The bottom graph focuses on the device type used by sessions in the marketing source "gsearch":

- Both sections, "Sessions" and "Orders", showcase a consistent website's activity growth for desktop user’s vs mobile device since 2012. 

  
The following [AB testing](https://public.tableau.com/app/profile/serach.mayerfeld/viz/HomeandLanderPagesABTestingDashboard/ABTestingHomeLanderandShippingPagesDashboard?publish=yes) focuses on whether the new "Lander-1” page attracts more sessions to click through to next page vs "Home" page.


![AB Testing Home Lander and Shipping Pages Dashboard](https://public.tableau.com/app/profile/serach.mayerfeld/viz/HomeandLanderPagesABTestingDashboard/ABTestingHomeLanderandShippingPagesDashboard?publish=yes).


- This Tableau dashboard showcases an increase in sessions' click through "Lander-1” page rate, which ultimately led to a revenue growth.  

 

 Working on this data made me understand the business accurately. Which product has high demand, whether the company is profitable, how can we rationalize the sessions process to increase revenue. Each dashboard presented the insights about the factory and led me to the conclusions above. By following my recommendations, the factory can rationalize the business and therefore see an increase of the monthly revenue.
