## Note

Hey there, I want to commend you on taking up this challenge. These are the few thing I concluded about after checking your code

-- Since optimization is a key when designing, in my opinion, some of the lines in the media query section are not needed. Even without it, the site will still be responsive. I comment out the media query and it worked just fine.
where I think there will be problem is when it reaches the Samsung fold screen size because the width of the card is more than the width of the device, you need to look for a way to restructure it.

-- The media query also has a lot of repitition, though they all work well.

-- Since the site will also be accessed by mobile users, it is necessary to work on the viewport and that was why I set the height of the body to 100% of the viewheight.

-- Making sure the card is centered both in vertical and horizontal axis is crucial. I discovered that there was overflow in x-axis on other screen size when I used the dev tool and since you are using flex box, that will be the easiest way to address that.

-- In case you see "margin-inline/padding inline", it is the same as writing "margin-right and margin-left"; The CSS rule gives you access to place content horizontally.

## Please Note that I did not dive much deeply into the code and I may have done some things wrong, but I must say you have done a great job. Do check the changes I made and let me see how you think you can tackle the responsiveness in a different from your end.

Cheers 🥂
