## Stonks
With the events of /r/wallstreetbets hitting the mainstream over short squeezing of GME and AMC there has been increased interest and scrutiny of social media's impact on retail investors and the larger market. There are various subreddits for different types of investors, Tiktok traders, and Twitter feeds are some of the more popular forms of information. The idea is to scrape the information off certain subreddits, feeds, and popular social media trades and identify which individual stocks they are tweeting about. Then using live market data to create a paper trading account and simulate what happens if we trade on that information. The idea is to set up several different strategies on timing, is sentiment similar across platforms, are there any outliers with which correlate stronger with positive trades, and are there particular financial vehicles (crypto, options, pennystocks, stonks) that are more susceptible. 

## Educational Case
Several of the topics within this project will be test driven development to ensure our paper transactions are handle successfully, making frequent calls to a live data API, multithreading process (scrape data off social media (twitter, reddit, tiktok), another to execute trades as keywords are stored in a data structure). Since in the real world large quantities of money are at stake an emphasis would be constant testing and optimizing and mostly approach this from a functional programming mindset. Storage of the information is still up in the air depending on what will be easiest and fastest for people to work with, structured seems like it would work in this situation but if need be we can switch to document based (MongoDB)

Two cases why I think this is important, one is that working with data is baked into every job and will be in the forseeable future. There being able to work with data, make inferences, and take actional steps are skills that you will use in your career. One of the goals is to optimize for speed something that we talk about in concept for our classes but during implementation it is usually an after thought due to the scope of our projects. Secondarily I think basic financial knowledge is something that everyone should learn about and there is far to little of it being taught in our school systems. 

## Requirements
Project is looking to be primarily in Python with some injection of C/C++ to speed up our scripts, some ability to use SQL (can be easily learned). A link to the proposed api and it’s library is [here](https://github.com/alpacahq/alpaca-trade-api-python). 

The project repo would be setup here or can be changed. 
[Repo](https://github.com/venturizhou/Stonks)

