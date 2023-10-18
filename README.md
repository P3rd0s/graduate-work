# graduate-work
Automated collection of information about current security threats based on analysis of open sources.

To start enter in terminal ```docker-compose up```

Then, all statistics can be found at ```localhost:4200```.
It may take some time to collect threats info by scrapy module

Used features:
* [Redis](https://github.com/P3rd0s/RedisScripts);
* [Developed library on Lua to make requests to Redis database](https://github.com/P3rd0s/RedisScripts/blob/main/ioclib.lua);
* [Postgres](https://github.com/P3rd0s/Postgres-db);
* [Python framework Flask on backend](https://github.com/P3rd0s/Flask-back);
* [Python framework Scrapy to scrap information from web-pages](https://github.com/P3rd0s/NewsFinder);
* [Angular on frontend](https://github.com/P3rd0s/IOCs-front);
* [Reaction module - Python with ETW](https://github.com/P3rd0s/ResponseModule);
* [Language model BERT combined with template semantics methods](https://github.com/P3rd0s/NewsFinder/tree/main/NewsFinder/modules/BertNer).
