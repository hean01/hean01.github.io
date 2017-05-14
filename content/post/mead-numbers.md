+++
date = "2017-05-14"
title = "Mead numbers and math examples"
subtitle = "A few words and examples on calculation of receipts"
tags = ["brew", "mead"]
categories = ["Brewing"]
lastmod = "2017-05-14"
#draft = true
+++

In this post I will talk about how to calculate sugar volumes for
targeting a specific sweetness and or alcohol of a mead. In a recipe
the final gravity is your target and you will choose a yeast to
control the ABV and on top of that the amount of honey. Here follows a
table of ranges of final gravity for a mead for different sweetness.

Sweetness| Oechele Gravity
--------|----------------
Dry|0.990 – 1.006
Medium|1.006 – 1.015
Sweet|1.012 – 1.020
Dessert|1.020+


Now to the numbers. First I found that...

> 17g sugar in one liter liquid gives 1% alcohol

...and I also calculated that gotmead.com mead calculator uses:

> 2.6462g sugar for 1° Oe in one liter liquid

# Numbers of the PGW receipe

Lets continue using the [PGW mead](../pgw-mead-startkit) as an
example. The receipt is for a target volume of 4 liter mead with
1.25Kg honey. Now there are many figures out there how much % of honey
weight is actual sugar, lets settle on the number of 79.6% sugar in
honey, which is used in the calculator from gotmead.com.

> sugar per liter = 248.75g  = (1250g * 0.796) / 4l

With the sugar per liter number, we can calculate how much of ABV the
mead will have when the sugar is fully fermented, eg. final gravity of
1.000.

> ABV = 14.63 % = 248.75 / 17g

We can also calculate the starting gravity of the mead knowing the
amount of sugar in a liter of must.

> OG = 1.094 = 94.22 = 248.75g / 2.6462g

Lets analyses the PGW receipt further. The recipe uses D47 yeast which
hash an tolerance of 14% ABV, this means when this ABV is reached in
the fermentation process, the yeast will get exhausted and stop
fermentation.

With that knowledge we could calculate the final gravity of this
recipe. Theoretically there is 0.63% of sugar left in the mead.

> sugar left per litre = 1,567125g = (248.75g * 0.0063)

And with that number we can calculate the final gravity.

> FG = 1.005922 = 0.5922 = 1.567125g / 2.6462g

As you can see, this mead recipe creates a mead in the upper dry
sweetness range.


## Examples of changes

Now with the above knowledge, lets see if we can make changes to the
PGW mead recipe. Lets settle for sweet mead with a final gravity of
1.020. We start to calculate how much sugar we need per liter to reach
14% ABV.

> sugar per liter = 238g = 14% * 17g

and the amount of honey in 4l must with final gravity 1.000 is
calculated like following.

> total amount honey = 1195.96g = (238g / 0.796) * 4l

Now we want to calculate how much more honey to add to the recipe for
additional sweetens targeting a final gravity of 1.020. We known that
2.6462g sugar is needed for 1 degree and we can calculate the
additional amount of honey to the recipe.

> additional honey = 265.94g  = ((20 * 2.6462) / 0.796) * 4l

This will give us a recipe of 1.462 Kg honey in 4 liter must.


# Numbers of Blueberry and Raspberry mead

Now lets dig into the [recipe](../blueberry-raspberry-mead) I came up
with and calculate some numbers. First off we need to find the sugar
contents of blueberry and raspberry. I found that blueberries have
9.8% sugar content and Raspberries 5.11%.

The recipe uses 250g blueberries, 250g raspberries and 1.5kg honey in
4 liter must. Lets start calculate the amount of sugar that is.

> blueberry sugar per liter = 6.125g = (250g * 0.098) / 4l
>
> raspberry sugar per liter = 3.187g = (250g * 0.051) / 4l
>
> honey sugar per liter = 298.5g = (1500g * 0.796) / 4l
>
> total sugar per liter = 307.81g = (6.125 + 3.187 + 298.5)
>

With the total sugar per liter volume we can calculate the starting
gravity of the must and the ABV, if all sugar gets fermented into
alcohol.

> ABV = 18.10% = 307.81g / 17g
>
> OG = 1.116 = 116.4 = 307.81g / 2.6462g
>

With the knowledge that D47 yeast have a tolerance of 14% ABV we now
know there is 4.1% sugar left in the mead.

> sugar left per liter = 12.62g = 307.81g * 0.041

And from that we calculate the final gravity just like this.

> FG = 1.0047 = 4.769 = 12.62g / 2.6462g
