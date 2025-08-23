# Awesome Business, Marketing, and Financial Datasets
A curated list of awesome datasets, repositories, and resources for data professionals working in business, finance, sales, and marketing. This guide is designed to be a comprehensive starting point for discovering high-quality data for analysis, machine learning, and strategic intelligence.

# Table of Contents

- [General-repositories--data-platforms](#general-repositories--data-platforms)
- [Commercial--b2b-intelligence](#commercial--b2b-intelligence)
- [Financial--economic-data](#financial--economic-data)
- [Sales--crm-data](#sales--crm-data)
- [Marketing--advertising-data](#marketing--advertising-data)
- [Web--digital-analytics](#web--digital-analytics)
- [Resources--tutorials](#resources--tutorials)

## General Repositories & Data Platforms
This foundational section lists the major aggregators and platforms that serve as primary gateways to a vast universe of datasets. These are the essential first stops for any data discovery process. The modern data landscape is a sprawling, federated ecosystem, not a monolithic library. The sheer volume and variety of available data have created a significant discovery challenge. In response, the data science community has developed a multi-layered approach to curation, from community-driven lists to centralized platforms. Understanding the landscape of these major data hubs is a prerequisite for efficient and targeted data sourcing, as they not only host data but also provide the communities and tools necessary for analysis.   

### Curated "Awesome" Lists
The open-source community maintains numerous "Awesome" lists that serve as excellent, topic-centric starting points. These lists represent a grassroots effort to impose order on the decentralized world of public data, providing curated pathways into specific domains.

- [/awesomedata/awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) - A high-quality, topic-centric list of public data sources, widely considered a cornerstone resource in the data community. It is collected and tidied from blogs, answers, and user responses, covering a vast range of subjects from agriculture to social sciences.   


- [/bytewax/awesome-public-real-time-datasets](https://github.com/bytewax/awesome-public-real-time-datasets) - A specialized list focusing on streaming data sources accessible via HTTP or WebSockets. This is a crucial resource for real-time analytics applications in areas like finance, transportation, and cybersecurity.   


- [datasets/awesome-data](https://github.com/datasets/awesome-data) - Another well-regarded, curated list of quality open datasets that emphasizes accessibility and high quality across various domains.   


- [/oxnr/awesome-bigdata](https://github.com/oxnr/awesome-bigdata) - A collection of resources related to big data technologies, including distributed programming frameworks, stream processing engines, and databases. While not a list of datasets per se, it is essential for understanding the tools required to handle the scale of many datasets listed in this guide.   

### Major Data Portals
These platforms represent the central hubs of the data science and open government ecosystems. They offer not just data, but also integrated tools, collaborative environments, and extensive documentation.

- [Kaggle Datasets](https://www.kaggle.com/datasets) - An online community platform for data scientists that hosts thousands of public datasets. Many datasets are accompanied by notebooks with starter analysis code, making it an invaluable resource for both learning and competitive data science. Kaggle supports various formats, including CSV, SQLite, and Google BigQuery datasets.   


- [Dataset Search by Google](https://datasetsearch.research.google.com/) - A powerful search engine specifically for datasets. It indexes millions of datasets from thousands of repositories across the web, making it an indispensable tool for broad data discovery.   


- [Data.gov](https://data.gov/) - The home of the U.S. Government's open data, providing access to nearly 300,000 datasets from federal, state, and local government organizations. It is a primary source for official statistics on demographics, economics, public services, and more, reflecting a national policy of data transparency.   


- [Data.World](https://data.world/) - A collaborative data platform that hosts a large catalog of open datasets. It is designed to facilitate community-driven data projects, emphasizing ease of use, data joining, and sharing of analytical findings.   

## Cloud-Based Public Datasets
Major cloud providers host large-scale datasets, making them accessible for analysis with powerful cloud computing resources. This model shifts the burden of data storage from the user to the provider, democratizing access to petabyte-scale data and enabling analysis that would be infeasible on local machines.

- [Public BigQuery Datasets](https://cloud.google.com/bigquery/public-data) - A collection of large-scale public datasets hosted in Google's BigQuery data warehouse. Users pay only for the queries they run, with a generous free monthly tier of 1 TB. This makes it ideal for exploring massive datasets like the complete revision history of Wikipedia, GitHub activity, or SEC filings without incurring storage costs.   


- [Public AWS Data](https://registry.opendata.aws/) - A registry of public datasets available via AWS resources. It exists to help people discover and share datasets hosted on AWS, including data from major scientific and governmental organizations like NASA, the National Oceanic and Atmospheric Administration (NOAA), and the National Institutes of Health (NIH).   

## Commercial & B2B Intelligence
This section focuses on datasets that describe the business world itself. This data is the lifeblood of B2B sales, marketing, and corporate strategy, enabling organizations to understand their target markets, identify potential customers, and analyze competitive landscapes. While some public data exists, this field is dominated by commercial providers who invest heavily in collecting, verifying, and enriching firmographic, technographic, and intent data. The progression from static business directories to dynamic, real-time behavioral signals marks a fundamental shift in B2B strategy—moving from asking "who could we sell to?" to answering "who is ready to buy now?".   

### Firmographic & Technographic Data
Firmographic data describes the attributes of a business (industry, size, revenue, location), while technographic data details the technology stack it uses. Together, they form a detailed profile of a potential customer, allowing for precise market segmentation.   

- [OpenCorporates](https://opencorporates.com/) - The largest open database of companies in the world, providing access to foundational legal entity data. It is an essential starting point for obtaining public information on company registration and structure.   

### Commercial Data Providers: These services offer enriched, verified, and detailed B2B datasets, often via API, for direct integration into CRM and marketing automation platforms. They provide the actionable intelligence required for targeted sales and marketing campaigns.

- [Data Axle](https://www.data-axle.com/)	B2B marketing and sales data, data validation and enrichment services.	90M+ business profiles with 400+ attributes, 183M+ contacts.	
Deep business location data, strong coverage of small- and medium-sized businesses (SMBs), and human-verified data through 25 million annual calls.   
- [Dealfront](https://www.dealfront.com/)	Sales intelligence and engagement platform.	40M+ companies, 180M+ contacts.	
Integrates with popular CRMs (Salesforce, HubSpot) and includes a convenient browser extension for real-time prospecting.   

- [ZoomInfo](https://www.zoominfo.com/)	B2B data provider with a focus on buyer intent.	Company insights, direct dial phone numbers, and buying intent signals.	
Offers buyer intent insights, data enrichment APIs, and website visitor tracking to identify active buyers.   

- Apollo.io	All-in-one sales intelligence and engagement platform.	B2B lead database with lead scoring and filtering.	
Combines a large contact database with engagement tools to manage the entire sales pipeline in one platform.   

- 6sense	AI-powered sales and marketing platform.	Customer behavior, intent data, and interest information.	
Utilizes AI and predictive analytics to uncover anonymous buying signals and prioritize accounts that are ready to buy.   

- LocationsCloud	Location-based B2B data provider.	Industry-specific datasets for restaurants, hotels, cleaning services, etc.	
Specializes in geospatial data for competitive benchmarking, site selection, and location-based lead generation.   

### B2B Intent & Lead Generation Data
Intent data is a crucial layer on top of firmographics, providing signals about a company's active interest in purchasing a product or service. This information is derived from a company's online behavior, such as web searches, content downloads, and event attendance. It allows sales and marketing teams to prioritize outreach to organizations that are already in the market, dramatically increasing efficiency and conversion rates.   

- [Datarade](https://datarade.ai/) - A data marketplace where users can find, compare, and purchase datasets from various B2B data providers. It is an excellent resource for discovering specialized vendors for intent data, lead generation lists, and other niche B2B data categories.   

## Financial & Economic Data
This section provides resources for macroeconomic analysis, investment research, and understanding corporate financial health. These datasets are foundational for financial analysts, economists, and quantitative traders. Financial and economic data is characterized by its time-series nature and its direct impact on market movements and policy decisions. The sources range from governmental bodies providing official statistics to specialized firms offering real-time market feeds. A comprehensive financial analysis requires integrating data from three distinct levels: the macroeconomic context, corporate fundamental performance, and technical market data.

### Stock Market & Corporate Filings
This data provides insight into the performance and financial health of individual public companies and the markets they trade on.

- (https://www.sec.gov/edgar/searchedgar/companysearch) - The U.S. Securities and Exchange Commission's Electronic Data Gathering, Analysis, and Retrieval system is the primary source for corporate filings. It contains 10-K (annual) and 10-Q (quarterly) reports, providing deep, structured financial data on public companies. This raw data is the ground truth for all fundamental analysis. The data is also accessible in more user-friendly formats on platforms like    

- [Data.gov](https://www.data.gov)
- [SEC Public Dataset](https://console.cloud.google.com/marketplace/product/sec-public-data-bq/sec-public-dataset).   
- [yfinance](https://finance.yahoo.com/) - A popular and powerful open-source Python library for downloading historical market data from Yahoo! Finance. It is an essential tool for quantitative analysts for backtesting trading strategies and performing technical analysis.   

- [/JerBouma/FinanceDatabase](https://github.com/JerBouma/FinanceDatabase) - A comprehensive, open-source database of over 300,000 financial symbols, including equities, ETFs, funds, indices, and cryptocurrencies. It is invaluable for building a universe of tradable assets for broad market analysis.   

- [Quandl](https://data.nasdaq.com/publishers/QDL) - A premier platform for financial, economic, and alternative data. While many datasets are premium, it offers a significant amount of free data and is a staple in the quantitative finance community for its clean, well-documented APIs.   

- [Awesome Quant](https://wilsonfreitas.github.io/awesome-quant/projects.html) - A meticulously curated list of libraries, packages, and resources specifically for quantitative finance. It includes a vast collection of data source APIs for Python and R, making it a critical resource for quants.   

### Global Economic Indicators
Macroeconomic data provides the context in which all businesses operate. Understanding trends in GDP, inflation, employment, and trade is crucial for strategic planning and risk assessment.

- [World Bank Open Data	Global](https://data.worldbank.org/) development data for hundreds of countries.	GDP, population, poverty rates, access to electricity, GNI per capita.	Varies by indicator, often annually.
- IMF Data	International financial statistics from 190 member countries.	Government Finance Statistics, World Economic Outlook, Balance of Payments.	Quarterly and annually.
- FRED (St. Louis Fed)	U.S. and international macroeconomic time-series data.	GDP, CPI, unemployment rates, interest rates, exchange rates.	Daily, monthly, quarterly.
- BEA (Bureau of Economic Analysis)	U.S. national economic accounts.	GDP, personal income and outlays, international trade in goods and services.	Monthly, quarterly.
- U.S. Census Bureau	U.S. demographic and economic data.	Retail sales, housing starts, business formation statistics, international trade.	Monthly, quarterly, annually.
- OECD Public Finance Data	Comparable public finance data for OECD member countries.	Government spending, revenues, fiscal balances, debt, and assets.	Annually.

### Cryptocurrency & Alternative Finance
The world of digital assets has its own unique data ecosystem, characterized by high-frequency, real-time data streams.

- (https://docs.cloud.coinbase.com/exchange/docs/websocket-overview) - Provides real-time market data, including level 2 order books, via a WebSocket feed, offering granular insight into market depth.   

- (https://github.com/binance/binance-spot-api-docs) - A WebSocket API that delivers real-time cryptocurrency trading data and order book updates from one of the world's largest crypto exchanges.   

- Awesome AI in Finance - A curated list that includes resources for crypto trading bots, arbitrage strategies, and various alternative data sources relevant to decentralized finance.   

## Sales & CRM Data
This section covers datasets related to the entire customer lifecycle, from the initial transaction to long-term relationship management. These datasets are invaluable for retail analysis, sales forecasting, and understanding customer behavior. A significant challenge in this domain is that real transactional data is highly sensitive and proprietary, making it rarely available to the public. This has led to the creation of high-quality synthetic datasets that mimic the structure, relationships, and statistical properties of real-world data without exposing sensitive information. These "digital twins" have become essential tools for developing and honing analytical skills in areas like customer segmentation, churn prediction, and sales forecasting.   

### Transactional & Retail Sales Data
These datasets provide the raw transaction-level information needed to analyze what was bought, when, and by whom.

- (https://archive.ics.uci.edu/dataset/501/online+retail+ii) - A classic transnational dataset from a UK-based online retailer, containing all transactions occurring between 2009 and 2011. It is widely used in academia and for practice projects on market basket analysis, customer segmentation, and time-series forecasting.   

- (https://www.kaggle.com/datasets/kyanyoga/sample-sales-data) - A well-structured synthetic dataset containing order information, sales figures, customer details, and shipping data. It is specifically designed for practicing customer analytics, segmentation, and clustering techniques.   

- (https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset) - Another synthetic dataset created to simulate a dynamic retail environment. It focuses on sales and customer demographics (age, gender), making it ideal for exploratory data analysis (EDA) and practicing data visualization.   

- (https://gist.github.com/Ironraptor3/34f3938c703111353ee5f28cc9b29d68) - A historical dataset of video game sales, broken down by platform, genre, publisher, and sales in North America, Europe, and Japan. It is an excellent resource for practicing EDA, data visualization, and trend analysis.   

### CRM & Customer Segmentation Data
Customer Relationship Management (CRM) data goes beyond single transactions to build a profile of the customer. Segmentation involves dividing this customer base into groups with similar characteristics to tailor marketing and sales strategies. A common and powerful technique for behavioral segmentation is RFM (Recency, Frequency, Monetary) analysis, which groups customers based on how recently they purchased, how often they purchase, and how much they spend.   

- (https://archive.ics.uci.edu/ml/datasets/bank+marketing) - This dataset contains information from direct marketing campaigns (phone calls) of a Portuguese banking institution. It includes client demographic data, campaign details, and the final outcome. It is a standard dataset for building classification models to predict whether a client will subscribe to a term deposit.   

- (https://help.salesforce.com/s/articleView?language=en_US&id=sf.pardot_b2bma_dataset_reference.htm&type=5) - While this is not a public dataset for download, the documentation provides a real-world reference for how enterprise CRM data is structured within Salesforce's analytics platform. It describes the schema for datasets like pdCampaign (campaign performance) and pdEmail (email statistics), offering a blueprint of professional CRM data architecture.   

## Marketing & Advertising Data
This section provides datasets for measuring and optimizing the entire marketing funnel, from brand awareness to conversion. Marketing has evolved into a deeply data-driven discipline where analyzing campaign performance, understanding customer attribution, and optimizing ad spend are core competencies. The available datasets reflect a clear hierarchy of analysis: high-level campaign data is used for strategic decisions like budget allocation and overall ROI measurement, while granular, channel-specific data is used for tactical optimization, such as changing a webpage title or adjusting an ad bid. A successful marketing analytics function requires both a "forest" view for strategy and a "trees" view for tactics, and different datasets serve these distinct levels of analysis.

### General Campaign Performance
These datasets provide a holistic view of marketing initiatives, often combining data from multiple channels to assess overall effectiveness.

- (https://www.kaggle.com/datasets/manishabhatt22/marketing-campaign-performance-dataset) - A large, synthetic dataset with 200,000 rows spanning two years of data. It covers campaign type, target audience, channels used, acquisition cost, and ROI, making it excellent for comprehensive marketing analytics projects.   

- (https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign) - A real-world dataset focused on predicting customer response to a marketing campaign. It includes detailed customer attributes such as income, education, marital status, and past purchasing behavior, making it ideal for building predictive models.   

### Pay-Per-Click (PPC) / Search Engine Marketing (SEM)
PPC data is used to analyze the performance of paid advertising campaigns on platforms like Google Ads and social media.

- (https://www.kaggle.com/datasets/aashwinkumar/ppc-campaign-performance-data) - A synthetic dataset with 1,000 rows of PPC performance data. It includes essential metrics like budget, clicks, CTR, CPC, conversions, CPA, and ROAS across different platforms (Google, Facebook, etc.) and content types (Video, Image, etc.).   

- (https://www.kaggle.com/datasets/marceaxl82/shopping-mall-paid-search-campaign-dataset) - A real dataset from a 5-month paid search campaign for a U.S. shopping mall. It contains performance data for different ad groups, including impressions, clicks, cost, and revenue, providing a realistic basis for campaign analysis.   

### Search Engine Optimization (SEO)
SEO data helps in understanding and improving a website's visibility in organic search results.

- (https://www.kaggle.com/datasets/eliasdabbas/seocrawldatasets) - A collection of website crawl datasets where each row represents a URL and columns contain on-page SEO attributes like title, H1 tags, and meta description. This type of data is fundamental for technical and on-page SEO analysis.   

- (https://www.kaggle.com/datasets/sakshiandhale62442/seo-performance-data-urbanscape-apparel) - A dashboard-style dataset that tracks daily SEO metrics such as organic traffic, keyword rankings, clicks, impressions, and CTR. It is useful for monitoring performance over time and identifying trends.   

- (https://developers.similarweb.com/docs/search-dataset) - A commercial API that represents a professional-grade tool for competitive SEO analysis. It provides data on website keywords, search volume, CPC, and Search Engine Results Page (SERP) features, allowing for deep dives into the competitive landscape.   

## Web & Digital Analytics
This section focuses on the raw material of digital user behavior: clickstream and web traffic data. This data allows for the granular analysis of how users navigate websites and apps, what content they engage with, and where they drop off. Web analytics is the foundation of digital product improvement and conversion rate optimization (CRO). Clickstream data, the digital breadcrumb trail left by users, provides an unbiased and detailed view of the user journey. Analyzing this data helps businesses identify friction points in their funnels, optimize user flows, and personalize experiences. This data serves as the "ground truth" that validates or invalidates assumptions made in other areas of the business, bridging the gap between marketing attribution and actual user behavior. For instance, a marketing report might show a high number of clicks from an ad campaign, but clickstream analysis can reveal if those users immediately left the site (high bounce rate), indicating that the landing page failed to meet the expectations set by the ad. This demonstrates that analyzing marketing channels in isolation can be misleading; true performance analysis requires joining marketing data with on-site behavioral data.   

### Clickstream & Web Traffic Data
These datasets capture the sequence of interactions a user has with a website or application.

- (https://www.kaggle.com/datasets/bigquery/google-analytics-sample) - This is a cornerstone dataset for anyone learning web analytics. It contains obfuscated but real Google Analytics 360 data from the Google Merchandise Store, a functional e-commerce site. The data is structured at the session and hit level, allowing for deep analysis of traffic sources, user behavior on-site, content interaction, and e-commerce transactions. It is the go-to resource for learning to query and analyze complex, nested web analytics data.   

- (https://ailab.criteo.com/criteo-sponsored-search-conversion-log-dataset/) - A massive, well-known dataset focused on click-through rate (CTR) prediction for display advertising. It contains millions of ad impression records with features describing the user and the ad shown. It has become a benchmark dataset for building recommendation engines and ad-tech machine learning models.   

- (https://www.kaggle.com/datasets/afranur/web-analytics-dataset) - A simpler, aggregated dataset containing key web metrics like users, new users, sessions, bounce rate, and pageviews over time. It is suitable for high-level trend analysis and practicing time-series forecasting of website traffic.   

- (http://cnets.indiana.edu/groups/nan/webtraffic/click-dataset/) - An enormous academic dataset of anonymized clickstream data from 100,000 users. Due to its scale, it is suitable for large-scale academic research into web navigation patterns, network analysis, and user behavior modeling.   

## Resources & Tutorials
Access to data is only the first step; the true value lies in the ability to analyze it effectively. This section provides a curated list of learning resources to help users analyze the datasets listed above, transforming this guide from a simple data repository into an actionable tool for skill development. A common thread across these resources is the universality of the core analytical stack and methodology. Whether analyzing financial statements, marketing campaigns, or sales data, the foundational skills remain the same: proficiency in tools like SQL and Python, and mastery of the analytical process from data cleaning and exploratory data analysis (EDA) to modeling, visualization, and reporting. The underlying principles of data analysis are domain-agnostic, meaning a data professional who masters these core skills can pivot between industries by learning the specific domain context and metrics, making these foundational skills highly transferable and valuable.

### Business & Data Analysis Guides
These resources provide foundational knowledge for data analysis applicable across any business domain.

- (https://www.geeksforgeeks.org/data-analysis/data-analysis-tutorial/) - A comprehensive, text-based tutorial covering the entire data analysis lifecycle. It details everything from understanding data types and scales to data preprocessing, EDA, and visualization using essential Python libraries like Pandas, NumPy, and Matplotlib.   

- (https://online.hbs.edu/blog/post/types-of-data-analysis) - An excellent conceptual guide from Harvard Business School Online that clearly explains descriptive, diagnostic, predictive, and prescriptive analytics. It uses practical business examples to illustrate how each type of analysis answers different questions and contributes to a holistic, data-driven strategy.   

- (https://mode.com/sql-tutorial/introduction-to-sql/) - A practical, hands-on tutorial for learning SQL, the fundamental language for accessing and manipulating data in relational databases. It is designed specifically for analysts who need to answer questions with data.   

- (https://online.hbs.edu/blog/post/business-analytics-examples) - A collection of real-world case studies from major companies like Microsoft, Uber, Blue Apron, and PepsiCo. These examples show how business analytics is applied to solve concrete problems, such as improving productivity, enhancing customer support, and forecasting demand.   

### Financial Analysis Tutorials
These resources are tailored for analyzing financial statements, market data, and economic indicators.

- Financial Analysis Courses (Coursera) - A collection of online courses from top universities and institutions (like University of Illinois Urbana-Champaign and London Business School) covering financial statement analysis, valuation, portfolio management, and risk management.   

- Financial Analysis Fundamentals (CFI) - A practical, in-depth course from the Corporate Finance Institute on how to perform a comprehensive financial evaluation of a company. It covers ratio analysis (profitability, leverage, liquidity), horizontal and vertical analysis, and the DuPont pyramid framework.   

- (https://www.youtube.com/c/365FinancialAnalyst) - A YouTube channel offering a library of short, focused video tutorials on a wide range of topics in finance, accounting, corporate finance, and valuation. The videos are designed to explain complex concepts clearly and concisely.   

### Marketing Analytics Guides
These guides focus on the specific techniques used to measure and optimize marketing and advertising efforts.

- A Complete Guide to Marketing Analytics (Analytic Edge) - A thorough guide that covers modern marketing analytics, including data collection methods (surveys, A/B testing), data quality processes, and the application of AI and machine learning to predict campaign outcomes and measure ROI.   

- (https://www.polymersearch.com/blog/analyze-marketing-data) - A practical, step-by-step guide to analyzing marketing data. It emphasizes starting with clear goals and Key Performance Indicators (KPIs) and then exploring controllable variables (like ad creative, audience, and timing) to find the combinations that yield the highest return on investment.   

- (https://www.factors.ai/blog/the-ultimate-guide-to-advanced-marketing-analytics-techniques) - An overview of more sophisticated techniques that are becoming essential in marketing. It explains complex topics like Customer Lifetime Value (CLV) analysis and multi-channel marketing attribution, which are crucial for understanding long-term profitability and the true impact of each marketing touchpoint.   

Cotributing
Contributions are welcome! Please read CONTRIBUTING.md first to understand the guidelines for adding new datasets or resources to this list.
