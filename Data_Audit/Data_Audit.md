---
Title: Data Audit
Author: Xianlai Yin
Data: 19/11/2022
---

### 1. Who collected the data? √√

> `2 points; 25 words`; *Consider the source of the data and its relation to the underlying data generating process.*

经过比对，本数据与Inside Airbnb提供的数据在结构与内容上有着高相似性，可以认为该项目的研究者收集并整理了本数据。

By comparison, this dataset is highly similar to the dataset provided by Inside Airbnb (IA) and it can be assumed that the researchers of this project collected the data.

***

### 2. Why did they collect it? √√

> `4 points; 50 words`; *Consider the purposes for which the data was collected and how this might shape its structure or content.*

IA的研究目的主要是分析Airbnb对城市社区的影响，以保护社区免受短期租赁负面影响(@)，如包括士绅化、租赁住房资源减少等(@)。因此，本数据集更加注重收集房东信息以判断其是否为商业运营者，及房源可用信息以判断其对住房市场的影响程度。

The purpose of the IA's research is to analyse the impact of Airbnb on urban communities in order to protect them from the negative effects of short-term rentals (@), including gentrification and a reduction in rental housing resources. (@)Therefore, this dataset focuses more on collecting information on hosts to determine whether they are commercial operators, and on the availability of properties to determine the extent of their impact on the housing market.

***

### 3. How was it collected? √√

> `7 points; 75 words`; *What was the method by which the data was collected and how might this shape its structure, content, or completeness.*

IA的研究者们利用python等技术scrape了Airbnb网站的原始数据并进行了清洗与整理，这既使得数据集能够包含大量非常广泛的相关信息（几乎覆盖了Airbnb房源页面的所有信息），且可以在一定程度避免Airbnb官方对数据的美化(@)。但另一方面，这样的获取方式无法获得一些细致的内部信息，如房源的精确位置（因为例如位置信息经过了Airbnb的匿名处理）等。

IA researchers scraped the data from the Airbnb website using techniques such as python and cleaned and collated it, which allows the dataset to contain a wide range of relevant information (almost all the information on the Airbnb listing pages is covered) and avoids the official embellishment of the data (@). On the other hand, this does not allow access to detailed internal information, such as the exact location of the listing, because some of Airbnb's data such as location information is anonymised.

***

### 4. What useful information does it contain? √√

> `12 points; 100 words`; *Discuss how the data might support a range of analyses and note any limitations encountered so far in class or in your own investigations.*

本数据集包含了房源的一系列信息，包括：房屋信息、房东信息、社区与位置信息、房源可用信息、房源评价等。数据集提供的房东信息和房源可用信息，结合社区与位置信息可以反映Airbnb的房源在城市中的整体情况和分布特征，并分析其对城市或社区产生的各类影响。此外，房屋信息、房源可用信息、房源评价等可以帮助人们对房源进行选择，也可以帮助房源运营者调整运营策略。

This dataset contains a range of information about listings, including: properties information, host information, community and location information, listing availability information, and listing reviews. The dataset provides information on hosts and availability of listings, which combined with community and location information can reflect the overall status and distribution of Airbnb's listings in the city and analyse the various impacts they have on the city or community. In addition, the properties information, listing availability information and listing reviews could help people choose properties and help operators adapt their strategies.

***

### 5. To what extent is the data ‘complete’? √√

> `25 points; 200 words`; *Reflecting on your earlier answers, and drawing on what you’ve learned about the data so far in class, to what extent is this data a ‘complete’ picture of Airbnb’s operations in London?*

数据本身来说，数据集中这不可避免地有着许多空缺值，不过这并不影响整体的数据分析；但是，尽管本数据集广泛应用于各类研究，但是有学者对该数据集的有效性和准确性提出了质疑，他们认为scrape数据的python脚本是落后的，且scrape过程中可能受到Airbnb网站的反爬干扰，数据集可能会出现缺失和重复等问题(@)。
对于研究者的研究目的来说，数据收集的类别是基本完整的，数据集几乎覆盖了Airbnb房源页面的所有信息。但是如果仅从这一个角度出发并不能完整描绘出picture of Airbnb’s operations in London，因为这仅仅是从房源角度（供给端）考虑的。然而，Airbnb的运营并不能离开租客的视角，对于租房群体的用户画像分析可以从需求端补齐一个完整的房屋租赁运营图景。

The data itself, which inevitably has many vacant values in the dataset, does not affect the overall data analysis; however, although this dataset is widely used in various studies, some scholars have questioned the validity and accuracy of the dataset, arguing that the python script for scraping data is outdated and that the scrape process may be interfered with by anti-scraping on the Airbnb website, and that the dataset may have problems such as missing and duplicate data (@).
For the researcher's purposes, the data collection are largely complete and the dataset covers almost all the information on Airbnb's listing pages. However if this is the only perspective it does not give a complete picture of Airbnb's operations in London, as it is only considered from the listing perspective (supply side). However, the picture of Airbnb's operations cannot be viewed without the perspective of the renter, and a user profile of the rental groups can provide a relatively complete picture of rental operations from the demand side.

***

### 6. What kinds of analysis would this support? √√

> `15 points; 200 words`; *Given the issues identified above, what kinds of analysis would this data support? You do not need to propose a specific analysis and should instead focus on generic classes of analysis.*

基于研究者收集该数据的目的，可以分析Airbnb对城市社区的影响。第一，将Airbnb的租金收入视为Rent Gap Model中的potential income，可以分析城市或社区的士绅化进程；第二，通过对Airbnb房源在一年中可用天数的分析，判断将房屋作为短期租赁所造成的住房资源的浪费程度；第三，基于房东拥有房屋数量和接受率，分析判断房东是否为商业运营商，而商业运营商则被认为对当地房屋市场有着更加负面的影响(@)。
在数据收集者的研究目的外，该数据集还可以支撑其他的分析。在房屋出租方的视角，可以通过分析该数据集以了解市场情况，从而制定合理的经营战略和定价策略；在租客的视角，可以通过分析该数据集来判断不同房源的优劣及评价，从而选择合适的房源；在政府及其规划部门的视角，可以通过该数据集分析Airbnb房源分布反应的城市空间特征（如旅居者在城市中更青睐的区域），及其房源对城市发展产生的影响（如对住房租赁市场的影响），从而调整政策与规划来应对(@)。

Based on the researcher's purpose of collecting this data, the impact of Airbnb on urban communities can be analysed. Firstly, by considering Airbnb's rental income as the potential income in the Rent Gap Model, the gentrification process of the city or community can be analysed; secondly, by analysing the number of days in a year that Airbnb listings are available, the extent to which housing resources are wasted by using homes as short-term rentals can be determined; thirdly, based on the number of listings owned by the host and the acceptance rate, the analysis determines whether the host is a commercial operator, which is considered to have a more negative impact on the local housing market (@).
The dataset can also support other analyses outside of the research aims of the data collectors. From a renter's perspective, the dataset can be analysed to understand the market situation in order to develop sound business strategies and pricing strategies; from the perspective of tenant, the dataset can be analysed to determine the strengths and weaknesses of different listings and to evaluate them in order to choose the right one; from the perspective of governments and the planning authorities, the dataset can be used to analyse the spatial characteristics of cities as reflected by the distribution of Airbnb listings (e.g. travellers are more likely to live in cities) and the impact of Airbnb listings on urban development (e.g. the impact on the housing rental market), so that policies and plans can be adjusted to respond (@).

***

### 7. Which of the analyses outlined above are ethical? √√

> `35 points; 350 words`; *Discuss the ethics of these classes of analysis with reference to your earlier answers and to the assigned readings.*

首先是数据收集与使用的伦理问题，涉及侵犯隐私权与知情同意权。根据Airbnb的Terms of Service statement，并不允许用户使用任何automated process从站点scrape数据(@)，而利用这个scrape得到数据集进行研究明显违背了这一条款。同时，上传这些信息的是众多Airbnb用户，而使用这些数据进行各类分析并没有得到他们的允许，而利用该数据集的研究很可能对他们的隐私产生侵犯。另一个角度来说，也有观点认为收集与分析公开数据并不需要获得许可(@)，这一ethical边界在不同地区和人群中有着一定争议。

其次是研究影响带来的伦理问题，前文提到的分析多与城市社会相关，分析结果不可避免会对社会中的人们产生直接或间接影响。假设政府对数据集进行分析后，制定政策禁止或限制了Airbnb在该城市的运营以避免其带来的负面影响，这对平台与hosts的利益造成了损害，然而研究使用的数据集甚至是源自他们且并未被许可使用的。但是，该政策制定是基于更广泛的公众利益而考量的，当地的居民因此可以享有更合理的租金和更适宜的社区氛围，这便涉及到公众利益和特定群体利益之间的ethical争议。但若政府更加考量经济利益而不是公民权益呢来利用数据呢？假设政府利用该数据集研究出某一区域深受游客喜爱，因此决定投资在这个片区发展旅游业，导致了当地社区房租和生活成本上升以及社区社会结构的破坏，尽管带来了更高的旅游收入，但这是否是ethical的呢？

总的来说，利用本数据集进行的上述分析，均存在ethical争议。但是数据收集的过程中并未收集私人数据(@)，规避了许多隐私相关的ethical问题。而利用相关研究影响产生的ethical问题则涉及到社会层面的ethical思辨，不仅仅局限于本数据集和分析。

Firstly, the ethical issue of data collection and use, involves the violation of the right to privacy and informed consent. According to Airbnb's Terms of Service statement, users are not allowed to use any automated process to scrape data from the site (@), and using this dataset for research is an obvious violation of this clause. Also, the information was uploaded by a large number of Airbnb users who did not give their permission to use the data for various types of analysis, and the research using the dataset is likely to be an invasion of their privacy. On the other hand, it is also argued that permission is not required to collect and analyse publicly available data (@), the ethical boundaries are controversial in different regions and groups.

Secondly, the ethical issue of the impact of the research. The analyses mentioned earlier are mostly related to urban society and the results will inevitably have a direct or indirect impact on people in the society. Suppose that the government, having analysed the dataset, had made a policy to ban or restrict Airbnb's operations in the city to avoid its negative impact, to the detriment of the platform and the hosts, even though the dataset used in the research originated from them and was not permitted to be used. However, the policy was developed in the wider public interest, so that residents could enjoy more reasonable rents and a better community atmosphere, and this involves an ethical debate between the public interest and the interests of particular groups. But what if the government uses the data more for economic interests than for the rights of citizens? Suppose the government uses the dataset to find that a particular area is popular with tourists and decides to invest in tourism in that area, leading to higher rents and living costs for the local community and the destruction of the social fabric of the community, albeit with higher tourism revenues, is this ethical?

In summary, the above analyses using this dataset are ethically controversial. However, the data collection process did not collect private data (@), circumventing many of the ethical issues related to privacy. The ethical issues arising from the impact of the research involved ethical thinking at a societal level and were not confined to this dataset and analysis.


***

### Data 

`基础信息`：'id', 'listing_url', 'scrape_id', 'last_scraped', 'source', 'name', 'description', 'neighborhood_overview', 'picture_url', 'license',  'calendar_last_scraped',

`房东信息`： 'host_id', 'host_url', 'host_name', 'host_since', 'host_location', 'host_about', 'host_response_time', 'host_response_rate', 'host_acceptance_rate', 'host_is_superhost', 'host_thumbnail_url', 'host_picture_url', 'host_neighbourhood', 'host_listings_count', 'host_total_listings_count', 'host_verifications', 'host_has_profile_pic', 'host_identity_verified', 'calculated_host_listings_count', 'calculated_host_listings_count_entire_homes', 'calculated_host_listings_count_private_rooms', 'calculated_host_listings_count_shared_rooms', 'reviews_per_month', 'instant_bookable'
 
`社区与位置信息`：'neighbourhood', 'neighbourhood_cleansed', 'neighbourhood_group_cleansed', 'latitude', 'longitude', 

`房屋信息`：'property_type', 'room_type', 'accommodates', 'bathrooms', 'bathrooms_text', 'bedrooms', 'beds', 'amenities', 'price', 
 
`房源可用信息`：'minimum_nights', 'maximum_nights', 'minimum_minimum_nights', 'maximum_minimum_nights', 'minimum_maximum_nights', 'maximum_maximum_nights', 'minimum_nights_avg_ntm', 'maximum_nights_avg_ntm', 'calendar_updated',  'has_availability', 'availability_30', 'availability_60', 'availability_90', 'availability_365', 
 
`评价信息`： 'number_of_reviews', 'number_of_reviews_ltm', 'number_of_reviews_l30d', 'first_review', 'last_review', 'review_scores_rating', 'review_scores_accuracy', 'review_scores_cleanliness', 'review_scores_checkin', 'review_scores_communication', 'review_scores_location', 'review_scores_value', 

***