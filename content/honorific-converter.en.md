+++
date = "2020-11-24T00:00:00+09:00"
title = "Honorific Converter Released"
description = ""
ogimage = "honorific-converter/ogp.png"
+++

{{< figure src="/images/honorific-converter/eyecatch.png" title="" >}}

Today, zoome LLC released the Honorific Converter.

{{< link title="https://honorific.app" url="https://honorific.app" >}}

This is an app that converts casual Japanese text into honorific language.

# The Importance of Honorifics
According to a 2018 {{< link title="report" url="https://www.bunka.go.jp/tokei_hakusho_shuppan/tokeichosa/kokugo_yoronchosa/pdf/92701201_01.pdf" >}} by the Agency for Cultural Affairs, "usage of honorific language" ranks second at 62.1% in terms of interest in the Japanese language.

This stands alongside the first place "daily language use and speaking style" at 73.7%. Since everything after third place is below 30%, it's clear how high the interest is.

Also, from my personal experience, I feel that honorifics are important in business.

There are many cases where you can only judge someone from their writing, such as in emails with people you've never met.
In such situations, whether or not appropriate honorifics are used can determine whether you'll receive a reply.

While this is deeply related not only to honorifics but also to business manners, since business manners vary by industry and company without definitive correct answers, I decided to create a service focused solely on honorifics.

# Compatibility with Deep Learning
Although a service to "convert casual language to honorifics" seems like it would obviously exist, there are actually almost no apps or web services for this.

Currently, there's only one app in smartphone app stores, and from what I've researched, there are only a few undergraduate and graduate theses on the topic.

The reason for this situation is likely because it was technically difficult.

With a manual approach of "replace this word with this honorific," it's impossible to handle double honorifics or the proper use of respectful, humble, and polite forms that change depending on the subject of the action.

Therefore, creating a service that converts casual text to honorifics was only possible for large corporations with strong AI capabilities like machine learning,
and considering the effort required, it was a difficult situation. However, the emergence of deep learning in 2012 greatly reduced this effort.

Using deep learning, appropriate honorific combinations can be derived from training data based on the context, making service operation feasible within realistic bounds.

That said, using deep learning requires a large dataset of "non-honorific sentences and their honorific equivalents," so initially, there's no choice but to steadily create conversion tables.

# An App for Learning Honorific Conversion
Japanese is a language where subjects can be omitted, and such sentences cannot be mechanically converted to correct honorifics.

For example, when converting "As for the matter mentioned before" to honorific form, the correct type of honorific changes depending on whether the person who "mentioned" it was yourself, a third party on your side, the other person, or a third party on their side.
Furthermore, you need to choose honorifics with an appropriate level of respect based on your relationship with the other person.

To make this mechanically determinable, for sentences without subjects, it would require the cumbersome specification of entering who the subject is and what their position is.
So for sentences where the subject is unclear, we have no choice but to let users choose, and I think it's best to let users decide the level of respect they want based on their preferences.

Additionally, since honorifics are fundamentally a matter of feeling, I believe we need to create an app that not only converts but also teaches.

# Icon
To clearly convey that it's for business use, I've designed it with a blue color scheme similar to corporate software.

It's a simple design with just one character on a gradient background,
but the left icon below is the initial draft created in about 5 minutes, while the right is the final version after 3 hours of trial and error.

{{< figure src="/images/honorific-converter/compare.png" title="" >}}

Even though the background color remains the same, just changing the character placement, font, and gradient direction creates a significantly different impression, making me feel the depth and difficulty of design.