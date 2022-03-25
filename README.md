# pysel-map-scraper-PoC
<div> 
 <p>
 
  # pysel-map-scraper   ✨ ![PoC](https://img.shields.io/badge/PoC-Proof--of--Concept-green)

 </p> 
 <p><small>
  

  </small></p> 

</div>


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)
#### This project is more of a Proof-of-Concept than something for production use.  (´ｰ｀ )ﾉ 🔫

# Table of contents
- [Markdown Badges](#markdown-badges)
- [Table of contents](#table-of-contents)
- [Usage](#usage)
- [Tips](#tips)
- [Contribution](#contribution)
- [License](#license)
- [Badges](#badges)


## Open to any Contributions

<small>_may the source be with you!_<small>
contribution file [file](./CONTRIBUTING.md)


## Contact

You can reach me on [Telegram @forthetim6being](https://t.me/forthetim6being)

## License

[![Licence](https://img.shields.io/github/license/mmshooreshi/pysel-map-scraper-POC?style=for-the-badge)](./LICENSE)
<hr>
<hr>


# Features
Cute: choo choo!
 https://cultofthepartyparrot.com/parrots/hd/parrot.gif
* [Mahdi Shooreshi](https://t.me/forthetim6being) ([Web](http://fabian-beiner.de)) *(GooglePlus-Scraper)*
* ?
```
,<br/>
|'.<br/> 
|_ r<br/>
  ⁮\\<br/>
   `
```

 

 
 
# two

<details>
 <summary>
  <p> 
 
   
   
  </p>
 </summary>
<p>

 
</p>
</details>





```{r df-drop-ok, class.source="bg-success"}
mtcars[1:5, "mpg", drop = FALSE]
```



```{css, echo=FALSE}
.scroll-100 {
  max-height: 100px;
  overflow-y: auto;
  background-color: inherit;
}
```

```{r, class.output="scroll-100"}
print(mtcars)
```
                        
   ⚡                      
┌┬────────────────┐
││General features│
└┴────────────────┘
 ▼🚶



::: {#hello .greeting .message style="color: red;"}
Hello **world**!
:::


```{css, echo=FALSE}
.watch-out {
  background-color: lightpink;
  border: 3px solid red;
  font-weight: bold;
}
```

Then we assign a class `watch-out` to the code chunk via the
chunk option `class.source`.

```{r class.source="watch-out"}
mtcars[1:5, "mpg"]
```


---
title: Change the chunk style
output: html_document
---

When you subset a data frame, it does not necessarily return
a data frame. For example, if you subset two columns, you get
a data frame, but when you try to subset one column, you get
a vector:

```{r class.source="bg-danger", class.output="bg-warning"}
mtcars[1:5, "mpg"]
```

To make sure that we always get a data frame, we have to use
the argument `drop = FALSE`. Now we use the chunk option
`class.source = "bg-success"`.

```{r df-drop-ok, class.source="bg-success"}
mtcars[1:5, "mpg", drop = FALSE]
```


---


 🜚 Scraping google places using Selenium Python in a simple approach.
 🜚 No need to google maps API
 🜚 No need of any scrolling on the google maps sidebar or handling the pagination
 🜚 In case of URL redirecting triggered by google maps, It continue the scraping process from the last place it has been scraped, after it reloaded the page.
 🜚 Predefined scraping track as a GEOJSON file, define the movement route of the scraper on the map.
 🜚 Each time the app start to move in the ❮☡ GEOJSON file❯, it reads the customized search queries and map zooms from the CSV input file. as there may be more than a single query, It may repeat the track for any query and map zoom once it finished the track.

---

⧆ Why?
When your money value become close to zero in the real world outside your country, google APIs may not be in your options as a hobbyist data enthusiast.
this project may be beneficial for small projects, looking to a fast and easy way to look around the local places data. 💸🔰⊞ ⊟ ⊠ ⊡ ⚿ ⛝ ❎ ⟎ ⟏ ⧄ ⧅ ⧆ ⧇ ⧈ ⸬☻ 

---

⚅ What's new?
Previous open-source selenium tools have been mostly based on scrolling on the google maps paginated sidebar of places and scrape the data. However, in this project, google places information are extracted from the local storage of the browser directly with using the content scripts of the GPlaces-get extension, as another open-source project on JavaScript. So without the use of any google APIs, map viewport gets moving and moving on the predefined route and extracts the places data as CSV files for every <n> scraped places (default: 100).

---

 ＊ Get started:
pysel-map-scraper get's moving on the map based on the GEOJSON file defining the route (INPUT-ROUTE.geojson). It run the procedure of scraping for each of search queries in the CSV input file (INPUT-queries.csv), And restart the route once each query finished. The app triggers "search this area" button every time gets to a new viewport. GPlaces-get is writing all the data on CSV files and exporting them automatically, whenever it stores 100 new places (and also you may customize this).
anytime you run the app, it uses the stored logs and gets able to continue the process from the last location&query it has been scraped.  

---

 Scraped fields for each place:
❨UUID❩
❬Created_at❭
❲  

Query
Name
Full address
Local name
Local full address
Phone number(s)
Latitude & Longitude
Categories
Reviews
Rating
URL
Domain
Thumbnail
Addr1 | Addr2 | Addr3 | Addr4
District
Timezone
🗒 📓 📔 📝 📒 📋📎 🖇

---
 ⚙
Get started
1. Clone this repository.
2. 📎 ❮GPlaces-get.crx❯ ❳❪ ❫ ❴ ❵ ❬ ❭ ❮ ❯ ❰ ❱  ➜  . / pysel-map-scraper-SOC / [move to here]
Either download the GPlaces-get.crx or clone it's repository and export it to CRX using google chrome extensions developer tools (or other applicable tools).
3. donwload the latest chromedriver (which is also open-source) for your operating system from the link below:
https://browsers.chromedriver.chromium.org
It is an open source tool for automated testing of webapps across many browsers. It provides capabilities for navigating to web pages, user input, JavaScript execution, and more.  ChromeDriver is a standalone server that implements the W3C WebDriver standard, and is available for Chrome on Android and Chrome on Desktop (Mac, Linux, Windows and ChromeOS).
