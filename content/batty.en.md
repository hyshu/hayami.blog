+++
date = "2023-02-01T00:00:00+09:00"
title = "Released Batty"
pagetitle = "Released Batty, a Location Sharing SNS"
description = ""
ogimage = "batty/ogp.png"
+++

{{< figure src="/images/batty/eyecatch.png" title="" >}}

Today, zoome LLC released Batty.

{{< link title="https://batty.life/" url="https://batty.life/" >}}

It's a location-sharing SNS app where you can communicate with acquaintances while sharing your location.

# The Market Leader That Suddenly Ended Service

The "location-sharing SNS" field had long been dominated by Zenly, an app operated by the American company Snap Inc., but it was decided to end service on February 3rd.

The reason for ending the service was stated as "{{< link title="to reduce team size across the company" url="https://newsroom.snap.com/ja-JP/restructuring-and-refocusing-our-business" >}}", but if it had been profitable, they would naturally have continued it, so it's reasonable to assume it was unprofitable.

Also, despite having {{< link title="40 million users" url="https://www.businessinsider.jp/post-259096" >}}, the fact that they chose not to sell the business or continue the service by reducing costs suggests this was a field with particularly poor profit prospects.

This makes sense if you think about it for even a moment.

Since the app sends location information when you move even when it's not in the foreground—meaning when the app is closed or the phone is turned off—the data traffic is enormous.

Many people probably send location data all day but only open the app for a few minutes, so I think it was difficult to make it profitable (though this is normal app usage).

Therefore, if you're going to create a location-sharing SNS as a successor, it's important to think about how to keep maintenance costs down while getting people to open the app.

# Difficulties in Creating a Location-Sharing SNS

Actually, when the news broke that Zenly was ending service, I had absolutely no intention of creating Batty.

There were two reasons. One was the aforementioned difficulty in profitability, and the other was the emphasis on "imitating Zenly."

Needless to say, the 40 million former Zenly users are looking for an app that looks exactly like Zenly, with equivalent features and the same operability.
It's not hard to imagine that if you could create an app that was identical down to the details, almost everyone would use it.

However, imitation is dangerous from copyright and trademark perspectives, and in the first place, it's nearly impossible to create the same thing as Zenly, which probably had billions invested in development.

Additionally, there's a non-zero possibility that Zenly could return.
It's quite conceivable that you could spend a year developing something only to have it all be for nothing when Zenly resumes service.

In fact, I only learned this after starting Batty's development, but {{< link title="the former Zenly map development team is creating a location-sharing SNS" url="https://peerclub.com/about" >}}.

# Why I Decided to Create It

The reason I decided to create it despite all this was that when reading the reviews on Zenly's app store page, many said "It was useful for keeping in touch with family, so it's unfortunate."
I was surprised that there was demand for family use, as I thought most people would use monitoring apps for family sharing.

But it makes sense when you think about it...
There's a psychological difference in ease of starting between using an app you're already using with friends for family purposes versus using an app exclusively for family.

So I thought that proceeding in the direction of "an SNS you also use with family" could create a unique appeal not found elsewhere.

For example, privacy-related features are hard to prioritize at the initial stage.
Also, arrival and departure notifications for home, school, or work, which are difficult to implement and put a heavy load on servers, aren't difficult if designed early on.

From experience, in competitive situations like this, apps that focus on appearance and atmosphere initially become popular, but as time passes, people tend to switch based on differences in desired features.
(Incidentally, these migrations often happen suddenly, so preparation is very important)

Even being fourth or fifth in the location-sharing SNS space, you could expect tens of thousands of users, which would be sufficient scale as a business.

So, assuming slower growth than others, I started developing Batty on December 11th last year.

I made it look as different from Zenly as possible and made it personally easy to use.
I also incorporated many innovations from the design stage to reduce data traffic and server-side calculation time.

If there's demand as intended and people use it, I'll of course be happy, and even if my pessimistic prediction comes true and a foreign latecomer dominates the market, the service can continue because maintenance costs are kept low.
Additionally, since it has highly reusable features like chat and maps, the code assets created through service development won't go to waste.

# Origin of the Name

Batty is a pun on "battery."

The English word "batty" literally means "bat-like."

As slang, it means "weird" or "unsteady," and in extreme cases, "crazy."
However, since Batty is also a surname, I don't think it will be misunderstood in the extreme sense if the first letter is capitalized.

Also, the URL "batty life" means "dissolute life," playing on "battery life."
Battery life refers to either "until the battery is worn out and needs replacement" or "from full charge to empty"—here it means the latter.

Since it's an app that also shares battery level and is aimed at young people, I named it thinking that having slightly bad slang meaning would be more appealing.

# Icon

I created it in about an hour.

First, I did a Google image search for "bat illustration" and found that many drew the wing membranes with curves.

So I tried making them straight lines and it looked surprisingly good, so I adopted it. I thought it would be boring if both eyes were open, so I tried closing one eye and it looked somehow good, so I adopted that too.

Batty is planned to launch overseas, and recent overseas SNS apps seem to often be black or purple (I haven't researched in detail), so I chose purple as the base color, associating it with bats.

Finally, I decided to use the design trick of "layering gradients makes things look good somehow."
I applied a gradient to the background and the same colored gradient to the bat.
At this time, if you shift the bat's gradient in the direction of the open eye, for some reason I don't understand, it creates a meaningful atmosphere and looks good.

When considering only the domestic market, I thought it might be too dark, but when I showed it to a few acquaintances as a test, it was quite well-received, so I adopted it without changes.

My icon creation is haphazard.

{{< figure src="/images/batty/compare.png" title="" >}}

The left one looks like a sea angel.

# Redesigning the Icon

{{< figure src="/images/batty/new_icon.png" title="" >}}

Originally, the icon was designed for overseas markets, but I thought about creating a separate icon for Japan and changed to a new icon on May 16, 2023.

After that, though not particularly intended, BeReal. became popular, Meta's Threads appeared, and Twitter changed its name to X, with black backgrounds and white text designs suddenly increasing, so I decided to unify with this design.

{{< figure src="/images/batty/new_logo.png" title="" >}}

I created the logo on August 22 of the same year.