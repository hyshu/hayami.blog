+++
date = "2024-02-14T00:00:00+09:00"
title = "Started the AITuber Project"
description = ""
ogimage = "aituber/ogp.png"
keywords = ["AITuber"]
+++

{{< figure src="/images/aituber/eyecatch.png" title="" >}}

Today, we launched the AITuber Project at zoome LLC.

{{< link title="https://aituber.net/" url="https://aituber.net/" >}}

This is a suite of services aimed at realizing VTubers powered by AI (artificial intelligence).

# The Journey to Creating AITuber

The first idea that led to AITuber came to me in 2017 when iOS 11 was released with ARKit support for the first time.

At that time, VTubers were rapidly gaining attention.

Video streaming with 3D avatars and tracking was, for me as a programmer, an extremely interesting combination of technologies.  
I was intrigued that this was also being valued commercially, and I was thinking about what I could do in this space.

However, I quickly realized that VTuber success depends more on talent management and public relations than technical capability, making it a field where people with sales and PR backgrounds have the advantage.  
It became clear that it would be tough for a programmer to enter this field.

So I came up with the idea of an app that would let "anyone become a VTuber."  
Unlike video, if you could send just the 3D model to smartphones, you'd only need to send voice, coordinates, expressions, and body joint information, enabling lightweight streaming.

With ARKit's decent accuracy in detecting forward/backward and left/right movement, users could approach or view from different angles.

While I was developing this concept in my head, it seems many others had their eyes on the same opportunity. Several services appeared with almost identical selling points to what I had envisioned - letting anyone become a VTuber with less bandwidth than video.
Eventually, major companies began acquiring or entering this space, and my idea died in its embryonic stage.

Next, I thought about AITuber. This was around 2019, I think.

With the advancement of deep learning, the idea that we were entering the AI era had become established.  
VTubers were popular, AI was popular, so what about AI VTubers? I think this was a very natural progression.

Our company also started studying deep learning belatedly in 2020, and created {{< link title="Keigo Translation" url="https://honorific.app/" >}} as an app that could leverage this knowledge. Since then, I had been saying internally that "after Keigo Translation comes AITuber."

By 2021, my resolve had solidified, so I acquired the domain aituber.net and reserved the app name on the App Store.

Now, searching for AITuber returns many results, but at that time there were only a handful.  
I believe this was due to the many technical challenges involved.

I also tried to create an AI VTuber, but there were two major challenges:

1. What should the AI learn?
2. How to handle conversation?

The first goal was of course to create an AI that moves and speaks as if there's a person inside, while being entertaining. But I needed to consider what training data to accumulate as a company asset.

As time passes, AI-related technologies advance and barriers to entry lower, making it harder to create unique strengths for our company.  
In this field where something you worked hard on can become meaningless in a day, this required even more careful consideration.

This hasn't changed much from when I first thought about it in 2021 to now, but it's dangerous to disclose before implementation, so I won't write about it here.

The second challenge of realizing "conversation" was a heavy burden and difficult to solve.

AI conversation could be created with predictive natural language models like BERT, but it's closer to selecting responses from pre-prepared sentences.  
While it's one approach, it alone wasn't sufficient.

Also, GPT-3, a generative large language model, was attracting attention, and the efforts of small companies like ours were likely to become futile.

In addition to these challenges, being entertainment meant people would easily migrate when something better appeared, making it difficult to enjoy first-mover advantages.

So while developing ideas, I was taking a wait-and-see approach, but then ChatGPT appeared - an AI service that far exceeded expectations - and the situation completely changed.

I started creating AITuber on March 31st last year.

# How to Draw AITuber

Naturally, the question arose of what to do about AITuber illustrations.

Even if I commissioned someone, I knew nothing about character design so I could only request "something that looks good," and since I have at least minimal aesthetic sense to judge good from bad, I'd want to request revisions until I was satisfied (definitely the worst kind of client).

While I can't draw, I do create vector format images for app icons and such (so-called vector art).  
The advantage of vectors is that once you draw a line, you can bend it repeatedly, so with time and trial and error, you can create something that looks decent.

Thinking I might manage somehow with the same approach, I spent about 4 months creating everything from illustrations to Live2D models, occasionally getting advice from friends who could draw.  
Live2D was my first time using it, but I thought it was interesting software that could do various things depending on how you use the parameters.

The most helpful series of articles was this:

{{< link title="https://note.com/himono_vtuber" url="https://note.com/himono_vtuber" >}}

Front-facing drawings can be made symmetrical, and by finding the rules of human anatomy and common elements in these types of drawings, I somehow managed to create them.

# Reason for the Name

The reason for choosing the straightforward name "AITuber Project" is that the meaning of AITuber isn't unified.

While the term AITuber itself saw a surge in usage with the advent of ChatGPT, what specifically it entails hasn't been established.

This is because there's still limited capability.  
For example, VTubers can easily do game streaming if they have the streaming setup, but AITubers need to develop AI to play games.

Even for simple conversation, it's difficult to make statements based on past conversations, and getting consistent content requires considerable effort.

So while some people are trying to move 3D models with AI computational processing and have them speak with machine-generated voices, others are manually posting ChatGPT-generated dialogue on social media, and some just continuously publish AI-generated images of the same character - activities under the AITuber label vary greatly.

This means you need to go through three stages: "AITuber agency or group name → what activities they do → AITuber character name."  
The order people learn about these varies, but either way it's long and confusing.

With the name "AITuber Project" and describing it as "a project where everyone creates AITubers together," it's immediately clear that this is a user-participatory service.  
I think this is the best approach for now.

Of course, we won't trademark it (I don't think it would pass anyway), and it might not stay this name forever.

# Ye Ling (Ierin)

I came up with the name "Ie Rin" when I was trying to write a novel from 2017-2019, thinking it would be interesting if the name and nickname matched, and decided to use it now that the time was right.

While creating the Live2D model, I learned that the onomatopoeia for bell sounds is written as "ting-a-ling," so I made the English spelling of the given name "Ling" and changed the kanji to "鈴" (bell).

In English-speaking countries, writing Ie as "Ie" makes the pronunciation unclear, so I referenced DeepL and Google search's reading function and made it "Ye."

The English word 'ye' is archaic and apparently rarely seen outside of the Bible nowadays.  
Also, both 'Ye' and 'Ling' are apparently used when writing Chinese names in alphabets.

So it ended up becoming a mysterious name that works as a Japanese, English, and Chinese name.  
However, using "yeling" for Japanese SNS account IDs would be confusing, so I'll probably use "ierin" alongside it.

# Toiro

Originally, we planned to start the service with two AITubers - Ye Ling and a male AITuber - but I judged that a male character was premature with current AI and stopped.  
I considered starting with just Ye Ling, but having two would expand the service's possibilities, so despite the tight schedule, I decided to create another.

I was anxious due to time constraints, but once I started creating, after about a week I thought "Hey, this is looking pretty good?" and it was well-received when I showed it to acquaintances.  
Since it took over a month for Ye Ling to reach that stage, this was a pleasant surprise.

However, the back hair, eyes when moving the face left and right, and shoulder curves were difficult to make natural, so it still took about two months to complete.

# Logo

{{< figure src="/images/aituber/logo.png" title="" >}}

Since "AITuber Project" is a long name, I used the vertically elongated font {{< link title="FONTOPO" url="https://fontopo.com/?p=70" >}}.

I think it's a wonderful font with high visibility, playful yet not too pop.

However, two lines would be too vertically long, so I shortened "Project" by making the elliptical parts circular.

For colors, I made "AI" similar colors while trying various combinations for the others that were spread out but not too random.