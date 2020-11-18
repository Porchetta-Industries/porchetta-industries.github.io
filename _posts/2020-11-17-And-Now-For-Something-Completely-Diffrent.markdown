---
layout: post
title: And now for something completely different...
featured: true
date: 2020-11-17 0:0:0
image: '/images/hand.jpg'
---

Warning: this will be a somewhat lengthy blog post. I do encourage everyone to read everything here before coming to any sort of conclusion, however, below is a TL;DR with the most "impactful" announcements of this blog post.

***

* Porchetta Industries is partnering with [Kali Linux](https://www.kali.org/) to help improve the status quo of the Open Source Infosec/Hacking tool developer community with the end goal of *actually* making it sustainable through a number of experiments.

* Starting from now, all new [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) updates will be made exclusive to Kali Linux for a 30 day period. They *will* be made publicly available after the 30 day window. Individuals who are [directly sponsoring me already on Github](https://github.com/sponsors/byt3bl33d3r/) will have access to the exclusive updates as well. 

* Porchetta Industries will be giving out 1 [Offensive Security training](https://www.offensive-security.com/courses-and-certifications/) voucher per quarter in exchange for *meaningful* contributions (e.g. Pull Requests) to any of the tools in the Porchetta Industries [Discord Server](https://discord.com/invite/sEkn3aa).

* A Porchetta Industries merch shop will be opened soon. All income from it will be donated to the authors of widely used OSS infosec/hacking tools on a bi-monthly basis (TBD).

* [Offensive Security](https://www.offensive-security.com/) has expressed interest in sponsoring other open source Infosec/Hacking tool developers through the [Github Sponsorship](https://github.com/sponsors) program. Check out their [accompanying blog post]() on the Kali Linux website.

***

(Whenever you see "Infosec/Hacking tool" in this article I mean **any** tool/project that falls under the realm of information security or hacking. **Not just Offensive/Red Team tooling.**)

# Some Background

When I first started publishing open source tools on Github (over 10 years ago at this point), I primarily did it for myself: I wanted to learn about computers to eventually get a job in the US and escape the little town in Italy I grew up in.

After attending a number of conferences and speaking to people, I realized the stuff I was creating  was also helping small businesses on a budget, independent contractors, startups and individual pentesters/red teamers. This was absolutely fantastic, felt amazing and gave me an insane drive to continue developing. This quickly became the primary driver and source of motivation for continuing to work on the tools I was making.

As time went on, I started realizing that some of the tools I published were also being used every day by a number of multi-million dollar security companies and **extremely** expensive Infosec training courses. Initially I was somewhat bewildered and humbled. I wasn't expecting this at all given the quality of the code of some of the initial tools I made (I had no idea what I was doing, and arguably still don't).

Nevertheless, I thought this was fantastic. Everything was open source, this means they'll obviously be helping me in the development process! It's in their best interest after all since they're using them constantly and they sure as hell have the resources to dedicate for this.

Oh man, was I naïve. Time passes and... \*crickets\*. Long story short, over the past 10 years, I've received around 15-20 pull requests that I'd consider to be meaningful across all the projects on my [Github profile](https://github.com/byt3bl33d3r). Only one of those contributions was from any of the companies that **I know** use these tools on a daily bases. In terms of donations, I've received around 150 USD.

Initially, I thought this was only limited to things I personally was publishing, as I grew older and a little wiser I learned this is the status quo for open source in general.

<p align="center">
    <img src="https://imgs.xkcd.com/comics/dependency.png">
</p>

# The problem

This problem seems to be cranked up to 200% when it comes to Infosec/Hacking open source software (why exactly, I still don't know) **especially** on the Blue Team/defensive side of Infosec tooling. 95% of other developers in this space that I've talked to have had this same experience. Not a single line of code was contributed and/or not a single donation was given. Some of these developers don't even receive any sort of feedback. Meanwhile, companies continue to use their tools and profit from them in one way or another.

As a developer of one of these tools, you obviously start questioning your life decisions after a while. Especially after putting so much time into these projects. If you've never managed or created an open source project you cannot even start to imagine the amount of time and effort it entails: it's essentially a second job.

The issue really boils down to the following moral question:
> Am I ok with huge companies using the tools I publish for free and them not giving anything back?

This has been debated for a while in the OSS (Open Source Software) community and really comes down to personal preference. Well, after thinking about this for a very long time, here's my personal stance on this: this isn't ok. The fact that this is considered normal still astounds me to this day. 

There is a "leech" culture in this industry (and open-source in general) and it has to stop. It should not be considered "normal" that multi-million dollar companies use these tools for free without giving anything back. One of the fundamental aspects of open source software is collaboration. If the people who have the time and resources don't collaborate, what's even the point?

Now the traditional solution to a problem like this (especially in the security space) is to make a "pro" version of the software, slap an insane price tag on it along with a restrictive license/copyright protection, hire a bunch of sales people and go about your merry way. I considered this for a long time, but it's not really solving the core issue is it? On top of that, it would be screwing over the people who I was trying to make the tools for in the first place.

Additionally, I dearly love the hacker community. Despite all the drama, opposing/cynical views of the world and all of the shade we throw at each other sometimes. I've spent my entire life in it. I want to leave it better off than it was when I started.

> How does one go about solving this issue, specifically in a way where everyone benefits and without screwing over the "little guy"?

# My idea of a solution

There have been numerous attempts of trying to solve this problem in the OSS space but none of them really worked. And they are definitely not geared toward the infosec/hacking community. We need something specifically for our own little "niche" in the IT ecosystem. We're primarily hackers, not developers, and consequently we need a completely different approach.

On top of that, there needs to be a fundamental culture shift as huge multi-million dollar companies won't do anything out of the goodness of their own heart (usually), so there needs to be incentive.

I had "lightbulb" moment after reading [this blog post by Caleb Porzio introducing the concept of SponsorWare](https://calebporzio.com/sponsorware), suddenly it all clicked into place. With the introduction of the [Github Sponsors](https://github.com/sponsors/) program we can create a community that empowers & helps other Infosec/Hacking tool developers to achieve successful sponsorships from companies and individuals alike by offering a tiered "perk" system. These perks can be anything that the developer wants and is comfortable with ("update exclusivity windows", the companies logo in the README's etc...)

Having a specific community for this solves an enormous amount of issues including some that are specific to the hacker community, just to state a couple:

1. Scale. You can't divy out all funds you receive through the Github Sponsorship program to every single contributor to your project/tool. It would be an insane burden. You can, however, with the help of a community empower those contributors to be successful with **their own** Github Sponsorship program and the tools that they make.

2. A lot of people who create these tools have no desire to speak at conferences, do any sort of "marketing" for the tools they make and/or do not have a "voice" on social media platforms (or even have an account on social media for that matter). This is just the nature of the hacking community, we're a paranoid bunch. As much as I'd like to say that if you have some insane 1337 code publicly available you'll automatically get recognized for it, the reality is that you need to make that 1337 code known to the community for it to gain any traction. Speaking at cons, getting a nice little logo for it and getting it "out there" through blog posts and social media makes your chances of getting sponsored increase dramatically.

That last one is a big one, and a community like this can solve that. It can provide your "voice" on social media to get the word out there. It can help you through some of the "marketing" aspects and help you navigate through some of the corporate space. Additionally, it can help you with the infrastructure necessary to set up your sponsorship program and support you along the way.

In summary, at least in my mind, this has the potential of solving most of the issues I've outlined in this post. It'll give companies incentive to actively seek out and sponsor individual developers, does not screw over the "little guys", and the author of the tool/project actually benefits from the insane amount of work they put into their OSS project.

> Everybody wins.

What I outlined above is the goal of Porchetta Industries, I want to make it that community that can provide the voice and support for you to have your own successful Github Sponsorship as an Infosec/Hacking tool developer.

# Porchetta Industries

Porchetta Industries has officially partnered with [Kali Linux]() to see if this model can work. To encourage **actual**  contributions, we're going to be giving out 1 [Offensive Security training](https://www.offensive-security.com/courses-and-certifications/) voucher per quarter in exchange for *meaningful* contributions (e.g. Pull Requests) to any of the tools in the Porchetta Industries [Discord Server](https://discord.com/invite/sEkn3aa). 

The [Discord Server](https://discord.com/invite/sEkn3aa) is going to be the central place where people can get in touch with developers and participate in this crazy experiment if they want to. If you want a channel for your own tool you can join the server (invite [here](https://discord.com/invite/sEkn3aa)) and request one.

The idea around this is that every quarter the participating tool authors get together and review all of the Pull Requests they've gotten. The training voucher will get awarded to the person who gave the most comprehensive code contributions in any of the tools in the Discord Server. If more companies are willing to sponsor Porchetta Industries, we can obviously do this a lot more frequently and give more stuff away.

Porchetta is also going to be opening up an online Merch Shop relatively soon. All income generated from it will be donated to the authors of widely used OSS infosec/hacking tools on a bi-monthly basis (TBD).

[Offensive Security](https://www.offensive-security.com/) has also expressed interest in sponsoring other OSS Infosec/Hacking tool developers through the [Github Sponsorship](https://github.com/sponsors) program. 

Finally, starting from today, all updates for one of the most popular projects I've made [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) will be made exclusive to Kali Linux for a 30 day period. They **will** be made public after that 30 day window. If you [sponsor me on Github](https://github.com/sponsors/byt3bl33d3r/) you'll also have access to the exclusive updates automatically. This is also an experiment, if this model works [Kali](https://www.kali.org/) is willing to do the same with other tool authors.

# Conclusion

Is this the "silver-bullet" that solves every single issue related to this? Probably not. It is a start? Yes. It's also my personal take on a solution.

The end goal here is to make this entire system sustainable. As of writing it is not and there seems to be a very pervasive "leech" culture. The entire multi-billion dollar Infosec industry (especially the pentesting and blue team side of it) seems to be propped up by a bunch of open source software that are largely maintained by single individuals. There's largely zero support or contributions going back to the tools these security/training companies are using.

Meanwhile, the developers of these tools are essentially working two jobs in order to maintain and update them.

Nobody seems to be doing anything about this problem even though it's an issue thats widely known in the Infosec/Hacking tool developer community and has been talked about for years. Because of this, I might as well give it a shot and see what happens. At the end of the day its an experiment, if it doesn't work out? So be it. At least I can say I tried to do something about it.

If you're part of an organization thats willing to help, try to change things for the better, thinks this is a worth while effort and are willing to become a partner in this you can contact Porchetta Industries at [info@porchetta.industries](mailto:info@porchetta.industries)

Thank you for coming to my TED talk.
