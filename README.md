Steps:

1. [Install Node](https://nodejs.org/en)
2. [Install Instant Data Scrapping](https://chromewebstore.google.com/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah)
3. git clone
4. npm i
5. insert google.csv file
6. replace in `website.js` in line 52 name of url column in csv file:
```const website = row['MRe4xd href'] || '';```
7. node website.js
