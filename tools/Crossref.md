# Crossref

## site
[Crossref](https://www.crossref.org/)

## accessing through `getpapers`
`getpapers` allows Crossref to be searched in the same general manner as EPMC (but the API, and therefore the precise query, is different).

### search

A simple climate change example:
```
MacBook-Pro-3:climate pm286$ getpapers -q "climate change" --api crossref -o climate.cross -x -k 200
info: Searching using crossref API
info: Found 689816 results
info: limiting hits
info: Saving result metadata
info: Full CrossRef result metadata written to crossref_results.json
info: Individual CrossRef result metadata records written
info: Got XML URLs for 3 out of 200 results
info: Downloading fulltext XML files
Downloading files [==============================] 100% (3/3) [0.0s elapsed, eta 0.0]
info: All downloads succeeded!

### output

gives the resultant 200 files in the `CProject`

```
MacBook-Pro-3:climate pm286$ tree climate.cross/
climate.cross/
├── 10.1002_9780470958674.ch6
│   └── crossref_result.json
├── 10.1002_9780470960929.ch1
│   └── crossref_result.json
├── 10.1002_9780470960929.ch31
│   └── crossref_result.json
├── 10.1002_9780470960929.ch37
│   └── crossref_result.json
├── 10.1002_9781118279380.ch2
│   └── crossref_result.json
├── 10.1002_9781119974178.ch3
│   └── crossref_result.json
├── 10.1002_wcc.126
│   └── crossref_result.json
...
```

### json files
The `Ctree` names of these files are the DOIs returned by crossref.


```
```

### REST api

[REST api](https://github.com/CrossRef/rest-api-doc)

This is mpre powerful than `getpapers` string and should probably be run with`curl`


