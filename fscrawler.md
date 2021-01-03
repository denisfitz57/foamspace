# Fscrawler
Inital state:
 -  2.7-SNAPSHOT downloaded from github;
 -  install of elasticsearch via MSI produces startup issue (java compatibility)
 -  installed Docker version running in WSL2 does notshow connection to fscrawler.
     - wget from powershell does show connection to fscrawler
 -   Error from fscrawler log:
     -   00:57:06,274 FATAL [f.p.e.c.f.c.FsCrawlerCli] Fatal error received while running the crawler: [Cannot invoke "fr.pilato.elasticsearch.crawler.fs.FsParser.isClosed()" because the return value of "fr.pilato.elasticsearch.crawler.fs.FsCrawlerImpl.getFsParser()" is null
        -   How to parse message?

Tried [a docker compose](https://github.com/shadiakiki1986/docker-fscrawler)

Got reading of the target directory to work but didn't figure out how to check into elasticsearch


