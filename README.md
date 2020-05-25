# Frequently asked questions

## Why not add another blocker?

I'm trying to keep the list short and to the point, to avoid introducing choice paralysis. That means making it as obvious as possible why you would choose one over the other.

The list should probably be limited to about 5 options, and each option should have clearly stated trade-offs compared to the others. Merely being an alternative is not a good enough reason to list it. I am willing to admit that the chosen items in the list can be somewhat arbitrary: if two add-ons offer approximately the same functionality, I'd rather just *pick one* than list both.

### How about NoScript?

Ha, ha, ha, no. I'm trying to stick with fire-and-forget stuff.

### How about HTTPS Everywhere or Privacy Badger?

Most browsers are building their functionality in now. HTTPS everywhere is obsoleted by HSTS Preloading, and Privacy Badger is obsoleted by the built-in tracker blocking in Firefox and Safari.

## So, why did you write this thing anyway?

Because it is an attempt to generalize my own lived experiences playing tech-support for family members. I installed ad blockers on most of my family's computers after they became infected with malware (or, in one case, just wound up subscribed to a spam Web Push feed, which isn't quite malware since it didn't actually install anything on the device, but is about the same effect as you would expect from being infected with adware).

## Why are you using news sites as a source?

I get that many of the sites I chose are ad driven, but it's necessary to bootstrap the trustworthiness of these claims.

CNN might do a lot of unfortunate things, but I can’t think of anyone who’s *more likely* to be trusted. If they said that Google ran a month-long ad campaign that pretended to sell fishing licenses, then it probably happened. What other site could I possibly link to, and actually expect my target audience to give me the time of day? Academic papers are probably pretty good, but they use the English language in a way that lots of people find impenetrable. Wikipedia isn’t even worth considering, though in a few cases, I actually discovered the article through Wikipedia. Neither are independent blogs, or people like SwiftOnSecurity that my audience never heard of.

Who could I link to instead that I would expect a technically illiterate reader to both understand and trust?

## Why don't you put more emphasis on privacy?

I know a total of one person IRL who installed an ad blocker to protect their privacy. The rest all did it after they got infected, and I recommended an ad blocker as a way to help avoid it in the future.

## Why don't you put more emphasis on attention scarcity and the role of advertisements?

I know a total of zero people IRL who installed ad blockers because they thought ads were immoral. And most of the alternative business models that aim to fund content on the larger internet have downsides.

And I'm not nearly smart enough to talk about *capitalism in general* anyway, which is where an argument like this inevitably leads.

## Doesn't this end with all of the internet paywalled?

Probably. But I'm not sure what to *do about it*, because the situation is still completely unworkable as it is right now. If your business model has "[critical alert from Microsoft](https://blog.malwarebytes.com/threat-analysis/2017/09/tech-support-scammers-abuse-native-ad-content-provider-taboola-serve-malvertising/)" as an extenality, then I can argue against it without having to propose an alternative. If preventing tech support scams kills your business, then so be it.

It seems like we're kind of stuck anyway. From the advertisers’ standpoint: if users don’t have ad blockers, then they’re better off if they act badly (you save the money that would be needed to vet ads), but if the users do have ad blockers, they’re still better off acting badly (milk whoever remains for all they’re worth). As for the end users, it hardly matters what the ad company does, because blocking ads is always better than not doing so.

I still blame the ads industry for being greedy. Setting up ad blocking takes time, and while it’s hard to give it up once you have it, few would go through the time investment unless things were really bad.

## How about SponsorBlock?

I won't be recommending anything that tries to strip referral links or ads that are truly embedded in the content (the ones I listed as "not blockable", even if you can technically block them if you're willing to manually intervene for each video or article).

The main reason is that most of the arguments I made against ad blocking don’t apply here. Sponsored video clips are unlikely to exploit vulnerabilities (the video creator, and likely the video host, have reencoded the clip they were provided, so any malformed video is probably gone by now). They can’t track you, since they cannot make any outgoing web requests, and they cannot change after the video has been produced. And because they’re unable to change after the video is put out, they’re also unlikely to link to fly-by-night malware operations; starting from scratch as a direct video sponsor is too much work.

They’re still annoying, but it's not clear that it's worth the many trade-offs inherent in installing an add-on:

* Ad lists aren’t 100% reliable. There’s the risk of someone inserting a “sponsor segment” that messes up the video, either because they disagree on what constitutes a sponsor segment (does product placement count?) or because they’re just trolling.

* If you switch browser, you need to re-install the add-on.

* If the browser upgrades, the add-on might break.

* If the video website upgrades, the add-on might break it.

* The add-on might be compromised. Ask [about the Stylish incident](https://arstechnica.com/information-technology/2018/07/stylish-extension-with-2m-downloads-banished-for-tracking-every-site-visit/).

If you want to install it, go ahead. I don't think you're morally obligated to watch sponsored segments. But I'm not recommending it on the front page.
