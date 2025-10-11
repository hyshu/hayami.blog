+++
date = "2017-06-25T00:00:00+09:00"
title = "Attended VR Tech Tokyo #7"
pagetitle = "【Participation Report】Attended VR Tech Tokyo #7"
description = "Participation report of VR Tech Tokyo. An event where you can feel the heat of Japan's VR industry. Two-part structure with sessions by speakers and hands-on experience."
ogimage = "vr-tech-tokyo-7/ogp.jpg"
keywords = ["xR Tech Tokyo", "STYLY Suite"]
+++

{{< figure src="/images/vr-tech-tokyo-7/eyecatch.jpg" title="VR Tech Tokyo #7 Title Slide" >}}

It's been a little over a year since the HTC VIVE and Oculus Rift went on general sale.

I too ordered both devices at launch to get into VR early, but due to being busy, I haven't had time to develop anything, and now they've become toys I occasionally play with...

Thinking this wouldn't do, I decided to attend VR Tech Tokyo #7 to learn about the current state of the VR industry.

(The name changed to xR Tech Tokyo from #8)

# VR Experience Exhibition
On the day, 12 VR software titles were exhibited.

I was able to hear detailed explanations about three of them, which I'll introduce here.

## Open World VR Game Where You Become the Wind and Travel the World - "WINDIAN"
{{< figure src="/images/vr-tech-tokyo-7/exp-vr.jpg" title="EXPVR in action" >}}

Developer: EXPVR ({{< link title="http://expvr.jp" url="http://expvr.jp" >}})

HTC VIVE is what's called room-scale VR, allowing free movement in a limited space of about 2-5 meters.

Since that's too narrow for moving through large virtual spaces, the current mainstream method is the "warp method," where you point the controller where you want to go and press a button to instantly move within the virtual space.

In contrast, "WINDIAN" is a game featuring a new movement method where you "move forward by swinging your arms."

{{< figure src="/images/vr-tech-tokyo-7/exp-vr-explain-1.jpg" title="EXPVR explanation image 1" >}}

You move forward by pulling your arm back while holding the trigger button on the HTC VIVE controller.

Since there are two controllers, you can move forward continuously by alternately swinging your hands as if running.

From my hands-on experience, it felt closer to rowing a boat than running.

However, compared to the "warp method" which can feel bland despite instant movement, I strongly felt the sensation of moving through the virtual world by my own will.

Additionally, you can jump by swinging the controller downward while holding the button.

Similar to the image of flapping wings, it was refreshingly fun, as if flying through VR space.

{{< youtube-2x1 Cu1gxVWNkto >}}

EXPVR, who created this content, wants to make this movement method mainstream in the VR industry as a replacement for the warp method.

## Narikiri VR Comedy
{{< figure src="/images/vr-tech-tokyo-7/comte.jpg" title="Narikiri VR Comedy in action" >}}

Developer: Natsu-san ({{< link title="@yashinut" url="https://twitter.com/yashinut" >}})

Narikiri VR Comedy is an app where one person performs comedy in VR while the audience can freely watch via the internet.

Since Oculus Rift and HTC VIVE cost around 100,000 yen, there's a problem that only some gaming enthusiasts buy them, preventing widespread distribution.

Narikiri VR Comedy solves this problem by dividing the audience side to Android smartphones and the performer side to Oculus Rift.

Viewers can watch on widely available Android devices, while performers can do comedy in VR with the immersive feeling of having an audience right in front of them.

Since the comedy function was still under development, the demo featured communication between a person (performer side, right in video) and dragon (audience, left in video).

## VR File Manager
{{< figure src="/images/vr-tech-tokyo-7/file-manager.jpg" title="VR File Manager in action" >}}

Developer: Yuto-san ({{< link title="@yutoVR" url="https://twitter.com/yutoVR" >}})

Currently, {{< link title="Virtual Desktop" url="http://store.steampowered.com/app/382110/Virtual_Desktop/?l=japanese" >}} exists as an app that floats PC desktop screens in VR space.

While it's a popular app, since Oculus Rift and HTC VIVE don't have particularly high resolution, text becomes crushed and unreadable for actual work, so it's mainly used for video viewing.

Unlike Virtual Desktop which displays the desktop as-is in VR, VR File Manager aims for practical functionality by displaying content in units of text files, images, and videos in VR.

While normal desktop screens arrange windows on a two-dimensional plane, this extends it to three dimensions.

You can move windows you're using close to you, move unused ones far away, and place windows above your head or directly below.

The demo showed display and operation of images, videos, and text files, but once completed, it could become an extremely convenient app that overturns conventional concepts of PC work.

# Talk Sessions
## The Production of VR Attraction GoldRush VR Was Indeed Too Much of a Rush
{{< youtube-2x1 OpN07PfAbfU >}}

{{< link title="Presentation Slides" url="https://chiepom.me/technical/2017-06-25-vr-tech-tokyo/" >}}

GoldRush VR is a VR game developed by {{< link title="Hashilus" url="https://hashilus.com/" >}} for exhibition at {{< link title="SXSW Conference" url="https://www.sxsw.com" >}}.

Its main features are an immersive play experience using a trolley device and the ability for up to 4 people to play simultaneously while sharing the same VR space.

In this session, they talked about the behind-the-scenes of development.

The most surprising point was the development period. An ultra-short development of just 1.5 months.

Given that it was developed solely for a 3-day exhibition with no need for detailed polishing, that was apparently a major factor, but it's still extremely short.

According to the session speaker {{< link title="chiepomme" url="https://twitter.com/chiepomme" >}}, there were several success factors.

I'll omit details for brevity, but the most important was that "the director was well-versed in network games."

This is because network synchronization was essential. When you hear that 4 people play in the same space, it might seem like network communication wouldn't be necessary.

However, since one PC was required per HTC VIVE, sharing the space required real-time synchronization like an online game across 4 PCs.

Games using network communication have synchronization lag due to communication delays, so if you plan with the mindset of making a regular game, you'll be late to notice this synchronization problem.

This time, they were able to avoid it because the director was well aware of this point.

Beyond the main session theme, what I personally found valuable was that "people enjoy just throwing balls at each other in the same VR space."

GoldRush VR is a game where 4 people work together to clear missions, but everyone enjoys just throwing balls at each other, so they struggled with UX design to get players to progress.

## The World of Gunner of Dragoon ~ Creating Beautiful Skies That Run Even on Non-VR Ready with Unity
{{< link title="Gunner of Dragoon" url="https://www.circle-hydrangea.net/the-gunner-of-dragoon/" >}} is a famous game in Japan's VR industry for its extremely high quality despite being individually developed by {{< link title="Yasei no Otoko" url="https://twitter.com/yasei_no_otoko" >}}.

{{< youtube-2x1 Z1rcdm7fDTI >}}

Beyond the graphics, with a rodeo machine that moves with the game and fans that provide wind, you can experience the immersive feeling of actually riding a dragon.

In this session, we heard technical talks about the graphics aspect of development.

While you can see the beauty in the video above, it apparently runs on non-VR Ready PCs (performance levels that normally wouldn't run VR).

Basically, reducing draw calls is key:

* Expressing the ground with shaders ({{< link title="Horizon[ON]" url="https://www.assetstore.unity3d.com/en/#!/content/31861" >}}) instead of modeling
* Utilizing standard shaders (physically based rendering)
* Utilizing Post Processing Stack
* Expressing the sky by applying textures to a celestial sphere ({{< link title="++skies." url="https://aokcub.net/cg/incskies/" >}})

These were the techniques used.

That said, overall it seemed to be the result of fine-tuning rather than utilizing individual features.

The latter half of the session explained specific uses of effects through Post Processing, showcasing Unity's capabilities.

The glow processing that brightens the entire field of view when looking toward the sun to express glare, and effects that can generate fog or rivers on the ground with one click were amazing.

## Research and Development Case Study of Disaster Simulator for Architecture Field
{{< link title="Pocket Queries" url="http://www.pocket-queries.co.jp" >}} and {{< link title="Takenaka Corporation" url="http://www.takenaka.co.jp" >}} presented their joint VR research and development.

Pocket Queries conducts development in various fields using {{< link title="VR and Real-time CG Rendering" url="http://www.pocket-queries.co.jp/vr_cg.html" >}}, and the main focus of this presentation was the disaster simulation system jointly developed with Takenaka Corporation.

The two companies had previously been simulating tsunami flood damage to buildings and smoke movement with real-time CG rendering, and researching evacuation behavior of people during such events.

The comprehensive VR system "{{< link title="maXim" url="http://www.takenaka.co.jp/news/2017/03/04/index.html" >}}" allows you to experience this more realistically in VR.

Rather than viewing tsunamis and smoke movement from a bird's-eye view, being able to see from the actual evacuee's perspective in VR provides more immersion and lets you feel the harshness of actual disasters more viscerally.

While only video was shown this time, the scientifically simulated flood and fire damage, with limited visibility due to smoke and people evacuating, had great realism, and I definitely wanted to experience it in VR.

## STYLY Suite
STYLY Suite is a VR showcase app for designers currently being developed by {{< link title="Psychic VR Lab" url="http://psychic-vr-lab.com" >}}.

Designers can view their own creations in VR space like an actual showcase.

When interviewing designers about creating a VR showcase app, they received the following requests:

* Want to handle Maya and CAD data
* Want to apply effects
* Want to use animations
* Want to distribute
* Want Instagram integration
* Want interactive elements
* Want to use on Mac

They realized all these numerous requests by "creating in a browser and viewing what's made directly as WebVR."

Without complex coding, you can build an interactive showcase VR just by uploading and arranging work data (Maya, CAD, Tilt Brush).

{{< youtube 0emnFoiBxfs >}}

Currently in closed beta ({{< link title="http://suite.styly.cc" url="http://suite.styly.cc" >}}), so if you're interested, why not participate?

## Re: Starting Life in Another World from VR
{{< link title="Halne-nezumi" url="https://twitter.com/halne369" >}}, active as {{< link title="VR IMAGINATORS" url="http://vr-imaginators.jp" >}}, talked about development methods for avatar control in VR space.

Halne-nezumi, who dreams of VRMMO in virtual worlds due to Sword Art Online, is developing a system to enter VR space as an avatar.

HTC VIVE only comes with two controllers by default, and can't track leg movement for free movement in VR space.

However, using an asset called {{< link title="FINAL-1K" url="https://www.assetstore.unity3d.com/en/#!/content/14290" >}}, you can estimate leg position from arm and head positions to some extent and reflect it in VR (though setup is apparently very difficult).

{{< youtube-2x1 Fy-WRFXsW6Y >}}

Also, by attaching additional tracking devices called VR trackers to your feet, quite detailed tracking becomes possible.

I couldn't experience it due to crowds at the VR exhibition, but a demo of the currently developing {{< link title="Chuunibyou VR Online" url="https://www.youtube.com/watch?v=rcqlL1W8xeM&feature=youtu.be" >}} was also exhibited.

I hope the era of VRMMO comes soon.

## Differences in Domestic and International User Reactions Learned from Releasing a VR Game
{{< link title="Presentation Slides (SlideShare)" url="https://www.slideshare.net/YuukiOgino/vr-tech-tokyo-7-presented-by-codeiq" >}}

{{< link title="Yuuki Ogino" url="https://twitter.com/yuukiogino" >}} talked about domestic and international reactions when releasing {{< link title="Zombie Hazard" url="http://vrzproject.wp.xdomain.jp/?page_id=238" >}}, developed by the doujin circle "VRZ_Project," on the Oculus Store.

VRZ_Project set a goal of "just making some VR game and releasing it to the store," and successfully released Zombie Hazard on the Oculus Store.

Since they released with only minimal implementation, reactions from international users weren't very good, but he entertainingly introduced those witty reviews.

While the overall presentation was jokingly presented as a "healing segment," the information about actually releasing to the store, how many downloads and plays it got, is very valuable.

Also educational was that international users actively try to modify things as MODs.

Details are in the slides linked above. As I've said repeatedly, since business is often involved, getting direct information from developers about actual store reactions is very valuable.

## NVIDIA VRWorks Audio
In the final session, NVIDIA explained about {{< link title="VRWorks Audio" url="https://developer.nvidia.com/vrworks/vrworks-audio" >}}.

VRWorks Audio is a library that realizes 3D audio using ray-traced audio.

Based on 3D space model information, it calculates how sound reflects from the source and reaches the user's ears.

This can achieve very realistic acoustic effects.

Since this can't be conveyed in words, please listen to the following demo (preferably with headphones).

{{< youtube-2x1 jVp88IjDX24 >}}

Currently provided as a plugin for Unreal Engine 4 and as a library for direct C++ development.

# Conclusion
Let me summarize what I felt through all the sessions and hands-on experiences.

## Unity's Overwhelming Share
Generally, Unity and Unreal Engine 4 (UE4) are commonly used game engines for 3DCG game development.

I thought it would be the same for VR development, but all developers I spoke with at this event were using Unity.

Why is that? UE4 is also a game engine that can easily create content at the same level as Unity.

As a potential hint, many people I spoke with were involved in or had been involved in the social game industry.

Since Unity is mainstream in smartphone social game development, did Japan's VR development naturally become Unity-centered as well?

While the only reference data is from this event, I strongly felt that being able to use Unity is essential for involvement in development in Japan's VR industry.

## Ideas Are Rapidly Taking Shape
Haven't people who have experienced VR and thought about content come up with ideas like these at least once:

* Floating PC content in VR space
* A Twitter client where tweets float in VR space
* VR space movement method where swinging arms moves you forward
* Communication using avatars in VR

At this event, all of these had taken shape to a level where you could actually experience them.

In another six months to a year, I think they'll be available to anyone with VR devices through stores.

Ideas are rapidly being realized. While I'm excited about the VR industry in the coming months and years, it was an event that made me feel a sense of crisis about not yet being able to participate.

## Links
* {{< link title="VR Tech Tokyo #7 Presented by CodeIQ (connpass)" url="https://vrtokyo.connpass.com/event/53581/" >}}
* {{< link title="Exhibited at VR Tech Tokyo #7 (VR Twitter Client Progress Record ⑧)" url="http://blog.toofu.net/entry/2017/06/26/222645" >}}
* {{< link title="Exhibited at VR Tech Tokyo #7 (VR File Manager)" url="http://yutokun.com/blog/2017/VRTechTokyo7/" >}}