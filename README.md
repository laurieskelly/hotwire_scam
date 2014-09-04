
### The Double Dagger: how Hotwire scammed me with ingeniously evil typography

This is a story about how [hotwire](http://www.glassdoor.com/Reviews/Hotwire-Reviews-E14912.htm?sort.sortType=OR&sort.ascending=true) uses  [Dark Patterns UX](http://darkpatterns.org/) to scam their customers into unloading the site's lowest-quality inventory: using tricks of visual language, typography, and UX, hotwire implies the customer is getting an amazing deal on a higher-priced hotel, when they are just getting a room in a hotel that is not as nice as the other hotels in its neighborhood. 

It's like saying you're getting a great deal on a yacht because you're actually buying a surprise rowboat. 

Hotwire did this to me, and I want my money back. At the very least, I don't want any of my friends to fall for this scam themselves. But ideally, I'd like to not stay at the Holiday Inn Express Brooklyn when my boyfriend comes to visit me later this month.

If you are a lawyer and believe that hotwire.com is crossing legal lines as well as those of poor taste, please contact me. 

### The ol' Cloak and Double Dagger
Look at the image below, specifically at the two places where the $489 figure is crossed out. You might think this is saying "The price is usually $489+" ($489 or more!? this must be a pretty swanky mystery hotel), and the strikethrough indicates that this Hotel has a Hot Rate that is much lower than it usually is. We're familiar with this visual language. It indicates a sale. 

![](advertised_price.jpg)

If you look at the right side, (under the stars) you can notice a small separation between the crossed-out number and the plus sign, but in the center under "standard price" the line is completely continuous through all of the symbols. The eagle-eyed consumer might have noticed the gap and gone to the foot of the page for a disclaimer, but I did not. The woman at the call center called it an asterisk (*), but it's a [double dagger](http://en.wikipedia.org/wiki/Dagger_(typography)) (‡). The double dagger is less common than the asterisk, but it is also a symbol that is used to direct a reader to a footnote. In this case, though, you can't deny that it conveniently and drastically reduces the chance that the visitor will notice the superscript mark and go read the fine print. 

### The footnote

Ok, so if you do go down to the footnote, you get this: 

![](footnote.jpg)

(You can download a pdf of the full hotwire page that I saw from [the root of this repo](https://github.com/laurieskelly/hotwire_scam).)

This footnote explains that the "Standard Price" of $489 is not the price that one would normally pay for the room that I was about to book blind. The standard price, which they list right above your "savings", is just an interesting factoid about hotel rooms in that neighborhood in general. And the amount "you save" is some strange theoretical subtraction of unlike quantities. 

You're not getting a great deal at the Ritz, you're getting a couple bucks off a room, next door to the Ritz, at the Holiday Inn Express. The "discount" is that they've chosen a hotel for you that is **already cheaper** than the Ritz, because **it's a different hotel**. (In this framework, I guess the Ritz itself, would be a Cold Rate Hotel because its rates are higher than the median of the area). 

If you were sneaky enough to find the footnote, thinking in the terms of a sale price / discounted price, it would be pretty confusing, regardless. I am pretty sure that I would have understood it if I had found the camouflaged double dagger and read the footnote. But hindsight is 20/20. In truth, the concept was explained to me by the customer service agent when I called to ask why they had implied that the Holiday Inn Express Brooklyn had a standard rate of $489. I, of course, could find no rooms there at that rate. She showed me the "asterisk" (double dagger) that explains the "discount" (difference in cost between a shitty hotel in a nice neighborhood and the nice hotels that are around it). 

### So what is a "Hot Rate Hotel"? 

Now I know that a "Hot Rate Hotel" is a hotel whose prices are drastically below other hotels in the same neighborhood at the same star rating. In other words, a Hot Rate Hotel is the crappiest hotel in the neighborhood. Because, I'm sure, no one wants to stay in a shitty hotel in a nice area, hotwire had to get creative and scam us into thinking we were getting a great rate at a fancy hotel. Instead, you're a chump with a regular rate at the Holiday Inn Express Brooklyn. That's what happened to me. 

Using the ol' Hotwire, glass-half-full spirit, you can now rebrand all kinds of crappy things in your life as smart discounts, instead of just things that are crappier than other things. For instance, you might say you got a great discount price on that take-out cheeseburger you're eating in front of the TV tonight, when you compare what you paid for it to the price other people are paying for steaks as they are out wearing fancy clothes on dates with each other in your neighborhood. You're not lonely, it's Hot Deal Dining! Remember when you didn't get into that Ivy and found yourself shipping out to state school 25 minutes from your parents' house instead of joining the Skulls and taking classes with celebrities like Natalie Portman? That's Hot Deal University!

I hope that unloading these "Hot Deal Hotel" rooms is extremely high priority to hotwire, because I can't imagine anyone using their site again after suffering the insult of falling for this scam. 

### The last little thing... 

On the phone, the customer service agent also explained to me what a median is. She told me that a median is the middle number in a set that's been ranked in order. (Educational!) The median rate they claimed to have calculated for a three-star hotel in Brooklyn, based on "published" rates from "leading retail travel sites" in the 24-48 hours preceding 5:00pm Eastern time on 8/31/14, is thus $489. Looking at Kayak, I say, "Shenanigans." 

### Ohhhh, how about just a smidge of data before I go?

Right now on kayak, there are 32 listings for three star hotels in Brooklyn, and using the same dates and number of guests that I used on hotwire, I do not get a median of $489. One hotel, Hotel Le Bleu, is exactly $489. So if it is the median, half of the other hotels should be more expensive and the rest should be cheaper. There is only one priced higher than that, the Pointe Plaza at $656. Then there are seventeen that are lower than $489, and thirteen listings that do not have published prices. [Here's a table of the current kayak data](https://github.com/laurieskelly/hotwire_scam/blob/master/kayak_data.md).

Even if hotwire gets to use some funky definition of "published", and even if every single unpublished listing is over $489, (this is the fun part about medians), the median of these 32 listings is $285, not $489. That would make the "Hot Rate Hotel" "discount" 45%, not 68%. 

And remember that we're being kind to hotwire, and pretending that all of the unpublished rates are above $489. The unpublished rates won't all be above $489. The median would be even lower than $285, and the "discount" would be even slimmer than 45%. 

I mean, the consumer protection act has to come into play somewhere here. It's one thing to make up a dumb concept to lure dopes into buying something they don't mean to buy... even though I think it's deceptive and it should be illegal, I think that's tougher to prove. However, once someone is just making up numbers, as I understand it, there are laws that make it much harder to get away with that. 

Hotwire will probably act like it's impossible or proprietary to disclose what rates they used to calculate the median to make up a fake discount-sounding nonsense comparison, but it's not. The published room rates for those rooms over the time window in question are somewhere. If I can get those historical rates, we can see whether it was possible or likely for them to find that suspiciously high figure using the method they claim to use in their fine print. 


Anyway, don't use hotwire. And if I get my hands on that data, I'll be back! 
