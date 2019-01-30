CardViewTest
============

If I use [Material Card](http://material.io/develop/android/components/material-card-view),
it works well in API 17+

![API 17](https://raw.githubusercontent.com/dscoppelletti/CardViewTest/master/docs/images/Nexus_4_API_17.png)

... but in API 16 the background of the card is set to black.

![API 16](https://raw.githubusercontent.com/dscoppelletti/CardViewTest/master/docs/images/Nexus_4_API_16.png)

I have found in StackOverflow similar problems concerning the `CardView` from
Support Library:

* http://stackoverflow.com/questions/35923377 - March 10, 2016
* http://stackoverflow.com/questions/38185880 - Apr 7, 2016

... and I have tried the proposed solutions, but they do not work with Material
Card.

[CardView](http://developer.android.com/reference/androidx/cardview/widget/CardView)
from Android X seems to work well in API 16+, so I think that I have to fallback
to it. :disappointed_relieved:
