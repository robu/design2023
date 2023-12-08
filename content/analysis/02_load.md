# Analyzing web sites' load times

This assignment selects three web sites and analyzes their load times. 

## Selection

I have selected the following web sites:
* [Valmyndigheten](https://www.val.se/)
* [Sveriges Radio](https://sverigesradio.se/nyheter)
* [Försäkringskassan](https://www.forsakringskassan.se/)

This time, I have used the criteria that the web sites should be critical to the society in some way. I have also tried to select web sites that are not too similar to each other.

## Method

I will use the Google Pagespeed tool to measure each site's load times. I have chosen three particular pages on each site to analyze. The measurements will be recorded in a table for each web site in the report below. Additionally, I will measure network load times and number and size of resources using the browser's developer tools.

## Results

### Valmyndigheten

[![Valmyndigheten start page](../image/kmom05/start_valmyndigheten.png?w=400){.website-capture}](../image/kmom05/start_valmyndigheten.png)

Valmyndigheten is the Swedish authority that is responsible for the elections in Sweden. It is centrally responsible for the conduct of elections and nationwide referendums and must otherwise fulfill the tasks that the central electoral authority has according to law or regulation.

<div style="clear:both"></div>
These are the results from the Google Pagespeed tool on three pages from the Valmyndigheten web site:

| Page | Mobile | Desktop | Load time | Num/Size resources |
|-----|:------:|:-------:|:------:|:-------:|
| [Start page](https://www.val.se/) | 98 | 100 | 178 ms | 33/1.4 MB |
| [Election results](https://www.val.se/valresultat.html) | 93 | 99 | 197 ms | 28/1.3 MB |
| [News](https://www.val.se/servicelankar/servicelankar/press/nyheter.html) | 84 | 86 | 186 ms | 27/1.4 MB |

### Sveriges radio

[![Sveriges radio start page](../image/kmom05/start_sr.png?w=400){.website-capture}](../image/kmom05/start_sr.png)

Sveriges Radio's mission is to deliver independent journalism and cultural experiences to audiences wherever they are and can listen.

<div style="clear:both"></div>

These are the results from the Google Pagespeed tool on three pages from the Sveriges radio web site:

| Page | Mobile | Desktop | Load time | Num/Size resources |
|-----|:------:|:-------:|:------:|:-------:|
| [Start page](https://sverigesradio.se/) | 64 | 97 | 320 ms | 39/2.1 MB |
| [News](https://sverigesradio.se/nyheter) | 58 | 77 | 324 ms | 43/2.2 MB |
| [Mission](https://sverigesradio.se/grupp/36951) | 65 | 72 | 255 ms | 31/2.1 MB |

### Försäkringskassan

[![Försäkringskassan start page](../image/kmom05/start_fk.png?w=400){.website-capture}](../image/kmom05/start_fk.png)

Försäkringskassan investigates and decides on the right to compensation from social insurance. It includes benefits such as child support, parental allowance and sickness allowance.

<div style="clear:both"></div>

These are the results from the Google Pagespeed tool on three pages from the Försäkringskassan web site:

| Page | Mobile | Desktop | Load time | Num/Size resources |
|-----|:------:|:-------:|:------:|:-------:|
| [Start page](https://www.forsakringskassan.se/) | 60 | 85 | 457 ms | 84/1.1 MB |
| [About](https://www.forsakringskassan.se/om-forsakringskassan/vart-uppdrag/kort-om-forsakringskassan) | 61 | 76 | 461 ms | 76/2.9 MB |
| [Info on sick with kids](https://www.forsakringskassan.se/privatperson/sjuk/foraldraledig-och-sjuk) | 33 | 52 | 729 ms | 113/6.6 MB |

### Summary of results

By observing the numbers, one can see the following commonalities:
* The mobile versions of the web sites are slower than the desktop versions.
* The start page is generally more optimized than other pages on the same web site.
* The Valmyndigheten web site is significantly faster than the other two web sites.

## Analysis

One reason that the mobile versions of the web sites are slower than the desktop versions could be that it is a sign that these sites were simply not built "mobile first", but designed for and with a desktop in mind, and then adapted to mobile devices. This is a common problem with older web sites. The Valmyndigheten web site could be seen as an exception to this, as it is very fast on both mobile and desktop.

The fact that the start page is generally faster than other pages on the same web site could be explained by the fact that the start page is the most important page on a web site, and therefore the one that is most optimized. It is also the page that is most likely to be cached by the browser.

The fact that the Valmyndigheten web site is significantly faster than the other two web sites could be explained by the fact that it is a very simple web site, with few images and not much JavaScript or other dynamic content. It is also a very important web site, which means that it is likely to be optimized. Finally, we are clearly in a "low season" for the Valmyndigheten web site, which means that it is not under heavy load.

## References

The course material on [web performance](https://dbwebb.se/kurser/design-v3/kmom05#artikel) was used as a reference for this assignment, as well as the [Google Pagespeed tool](https://developers.google.com/speed/pagespeed/insights/) and the developer tools in [my chromium-based browser](https://arc.net/).

# Misc 

This report was written by [Robert Burén](../).

