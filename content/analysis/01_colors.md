# Analysis of web sites' choice of colors

In this report, I will analyze the choice of colors on three different web sites. I will use a tool to extract the colors used and compare their usage.

## Selection

I have chosen these three web sites to analyze:
* [Bredband2](https://bredband2.se/) -- a Swedish ISP that offers broadband and telephony services.
* [Qliro](https://www.qliro.com/) -- similar to the more well-known Klarna, Qliro is a Swedish company that offers payment solutions for e-commerce sites.
* [Verkkokauppa.com](https://www.verkkokauppa.com/) -- a Finnish e-commerce site that sells a wide range of products. It's like a Finnish version of Elgiganten and Clas Ohlson combined.

When I started the process of choosing the sites to analyze, I thought it would be helpful and relevant to select sites from companies that I have worked with in the past, either as a CTO or as a member of the board of directors. In those companies, I am deeply familiar with the companies and their business models. I tried to select sites that weren't too similar when it comes to the nature of the businesses, so that we can see a wider range of scenarios.

## Method

My approach on this analysis is to use the [ColorZilla](https://www.colorzilla.com/) browser extension to analyze the colors used on the sites. I will capture the front page as a long screenshot, using the "Capture Full Page" feature of my prefered browser, [Arc](https://arc.net/).

## Results

### Bredband2 overview {.clear}

[![Bredband2 overview](../image/kmom04/bredband2.png){.website-capture}](../image/kmom04/bredband2.png)

These are the colors picked up by the ColorZilla browser extension from the [Bredband2](https://bredband2.se/) site:

<table class="coloruse"><tr>
<td style="background-color: #F93E48" class="white">1</td>
<td style="background-color: #9F2943" class="white">2</td>
<td style="background-color: #FCE9EE">3</td>
<td style="background-color: #D50141">4</td>
<td style="background-color: #590030" class="white">5</td>
<td style="background-color: #D2FBD0">6</td>
<td style="background-color: #0D5F07" class="white">7</td>
<td style="background-color: #F7F7F0">8</td>
<td style="background-color: #000000" class="white">9</td>
<td style="background-color: #444444" class="white">10</td>
<td style="background-color: #AAAAAA">11</td>
<td style="background-color: #E8E8E8">12</td>
<td style="background-color: #FFFFFF">13</td>
</tr></table>

The color schema could be described as a monochromatic schema with different shades of red (colors 1-5), combined with a half dozen shades of grey (8-13). The green colors (6-7) picked up by the tools aren't seen on the site, but are probably used as colors for user notification and messages. 

Bredband2's choice of font family for different elements are the same for all kinds: Manrope, Arial, sans-serif. That means they have chosen a consistent sans serif fonts for all text on the front page of the site.

Bredband2 pushes their brand colors. Selling a fairly generic service such as internet connections and telephony, it's important to build a brand that is recognizable. 

### Qliro overview {.clear}

[![Qliro overview](../image/kmom04/qliro.png){.website-capture}](../image/kmom04/qliro.png)

(Please note that the black area shown in the screenshot to the left shows an image on the actual Qliro site, which isn't being captured by my capture tool.)

These are the colors picked up by the ColorZilla browser extension from the [Qliro](https://www.qliro.com/) site.

<table class="coloruse"><tr>
<td style="background-color: #003437" class="white">1</td>
<td style="background-color: #CFD7D6">2</td>
<td style="background-color: #00FFC2">3</td>
<td style="background-color: #4AAC91" class="white">4</td>
<td style="background-color: #F4F3EB">5</td>
<td style="background-color: #000000" class="white">6</td>
<td style="background-color: #2D2D2D" class="white">7</td>
<td style="background-color: #333333" class="white">8</td>
<td style="background-color: #565656" class="white">9</td>
<td style="background-color: #5F5F5F" class="white">10</td>
<td style="background-color: #666666" class="white">11</td>
<td style="background-color: #696969" class="white">12</td>
<td style="background-color: #999999" class="white">13</td>
<td style="background-color: #CCCCCC">14</td>
<td style="background-color: #D1D1D1">15</td>
<td style="background-color: #D8D8D8">16</td>
<td style="background-color: #F5F5F5">17</td>
<td style="background-color: #FFFFFF">18</td>
</tr></table>

The Qliro color schema is very black/white/grey monochromatic, with the green from the Qliro green logo used as signal color. One could definitely question whether the number of shades of grey really has a purpose, or if it's just a result of a fragmented design process.

Qliro's choice of font family for different elements are:
* h1, h3 and h4: Shentox-Bold, a sans serif, all caps, font used in very bold titles.
* h6: Inter-SemiBold, a sans serif thinner font, used in titles for information boxes.
* p: Inter-Regular, a simple sans serif font.

Qliro is primarily a B2B business in the consumer finance space. The strict black/white schema enhances the feeling of seriousness, trustworthiness and "bankiness", and the clarity of the font choices also reflects this.

### Verkkokauppa.com overview {.clear}

[![Verkkokauppa.com overview](../image/kmom04/verkkokauppa_com.png){.website-capture}](../image/kmom04/verkkokauppa_com.png)

These are the colors picked up by the ColorZilla browser extension from the [Verkkokauppa.com](https://www.verkkokauppa.com/) site.

<table class="coloruse"><tr>
<td style="background-color: #E3101B" class="white">1</td>
<td style="background-color: #037AC4" class="white">2</td>
<td style="background-color: #025589" class="white">3</td>
<td style="background-color: #008751" class="white">4</td>
<td style="background-color: #4DAB85" class="white">5</td>
<td style="background-color: #FFD65D">6</td>
<td style="background-color: #000000" class="white">7</td>
<td style="background-color: #212121" class="white">8</td>
<td style="background-color: #333333" class="white">9</td>
<td style="background-color: #525252" class="white">10</td>
<td style="background-color: #656565" class="white">11</td>
<td style="background-color: #767676" class="white">12</td>
<td style="background-color: #C8C8C8">13</td>
<td style="background-color: #EFEFEF">14</td>
<td style="background-color: #F1F1F1">15</td>
<td style="background-color: #FFFFFF">16</td>
</tr></table>

The Verkkokauppa.com ("VK") color schema is similar to both the earlier ones in that it relies on a black/white monochromatic schema with a signal color. In this case, the signal color is the VK red color (color #1).

Just looking at the colors identified by the tool, one would expect a complementary color schema, but most of colors 2-6 are rarely seen on the site.

The Verkkokauppa.com web site isn't using hx header elements that much. However, the site's choice of font family for all elements are Antarctica, "Helvetica Neue", Helvetica, Arial, sans-serif. Antarctica is a simple no-nonsense sans serif font.

The main purpose of the Verkkokauppa.com site is to sell products. The black/white schema is used to make the products stand out, and the red signal color is used to highlight important elements on the site and build brand recognition. Similarly, the simple font choices are there to make the products stand out and not be distracting.

## Analysis {.clear}

Even though the three companies I chose are quite different in the nature of their businesses, they all have a similar approach to their color schema. They all use a monochromatic schema with a signal color, and they all use a lot of shades of grey. Looking more at the actual sites, the Bredband2 site is clearly redish, where the Qliro site is more black and white. The Verkkokauppa.com site is also black and white, but it's use of product images and the red signal color makes it look more colorful.

The results were somewhat surprising to me - I thought the difference would be bigger. However, I think the similarities may reflect the current trends in business websites, as far as color schemas (monochromatic with a possible signal color) and font choices (simple sans serif fonts) are concerned.

## References

As mentioned above, I used the [ColorZilla](https://www.colorzilla.com/) browser extension to analyze the colors used on the sites. I also used the [Arc](https://arc.net/) browser to capture the screenshots.

The terminology of color schemas are taken from the [dbwebb course material](https://dbwebb.se/guide/design-med-html5-och-css3/farg) on the topic.

## Misc

This report was written by [Robert Burén](../).
