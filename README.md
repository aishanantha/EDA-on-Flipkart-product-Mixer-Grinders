# EDA-on-Flipkart-product-Mixer-Grinders

Mixer grinders are one of the most essential kitchen appliances, with a vast range of brands and models available on Flipkart. 

With increasing online purchases, understanding pricing, brand popularity, customer ratings, and wattage can help buyers and businesses make informed decisions.

Data Source:
The data has been web scraped from Flipkart using Python library BeautifulSoup.
<img width="3179" height="537" alt="image" src="https://github.com/user-attachments/assets/a12696a6-4872-4609-8189-faec91c1a309" />
<img width="1671" height="1260" alt="image" src="https://github.com/user-attachments/assets/e8731283-8106-457d-827c-46a51efdaff1" />

We extracted essential details such as:
✅ Product Name – Brand name✅ Price – Current selling price in ₹ and original selling price in ₹✅ Ratings & Reviews – Customer ratings and feedbacks✅ Power (Wattage) – Determines performance efficiency

 Web Scraping Approach:

1️⃣ Sent HTTP request to Flipkart’s Mixer Grinder listings using requests.2️⃣ Parsed the webpage using BeautifulSoup to extract relevant HTML tags.
3️⃣ Extracted product details from <div> and <span> elements.
4️⃣ Stored the data in a structured Pandas DataFrame for analysis.
<img width="1170" height="790" alt="image" src="https://github.com/user-attachments/assets/87f87dc7-ce39-4370-bed2-9aea28f86401" />
<img width="1807" height="1132" alt="image" src="https://github.com/user-attachments/assets/27e108f7-354f-48cb-b19c-970f7dc2c50e" />
<img width="1999" height="966" alt="image" src="https://github.com/user-attachments/assets/bc2ea18f-f3bb-47d3-87d2-722d9bd0eb62" />

Graph shows the top 5 most available brands in market to be Butterfly, Longway, Flipkart, Prestige, Growsmart, accordingly.
<img width="1902" height="81" alt="image" src="https://github.com/user-attachments/assets/79b7ba19-3ae0-42a8-8643-16abddbb026f" />
<img width="1080" height="676" alt="image" src="https://github.com/user-attachments/assets/1374defd-7e28-4043-8d33-fec1a164dec5" />
<img width="1811" height="1044" alt="image" src="https://github.com/user-attachments/assets/674a307c-ff16-483c-a53d-7336b917dfb1" />
<img width="1836" height="1057" alt="image" src="https://github.com/user-attachments/assets/575314de-77e9-44eb-aecd-85e69f378c90" />
<img width="1773" height="923" alt="image" src="https://github.com/user-attachments/assets/82baf7a7-7cc3-4805-94f2-d51eb853fb8f" />

## Conclusion:
Don’t fall for brand that gives greater discount than others, like Ghoda, check out the ratings and wattage respective to the brand, then it doesn’t fit the requirement.

 Brands with good rating are : Preethi , Butterfly, Digismart.

Buy mixers in the price range of 800 to 2200, according to the ratings.

Brands with wattage 800W id Growsmart, 750 W are Moonstruck, Prestige, 500W are Pegion, Sansui, etc.

The maximum count of mixers present in dataset are in the ascending order of Butterfly, Longway, Flipkart, Prestige, Growsmart.
