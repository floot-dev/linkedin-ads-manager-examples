# LinkedIn Ads Manager examples

*Unofficial community examples for LinkedIn Ads Manager (Campaign Manager). Not affiliated with LinkedIn. All trademarks belong to their owners.*

Worked walkthroughs for linkedin ads manager - LinkedIn's Campaign Manager, the platform for creating, measuring and optimising LinkedIn ad campaigns. The pages that rank for the query describe the product through its web interface, its ad formats and its partner programme; none of them documents a public API, so this repository holds markdown walkthroughs instead of code, and the `examples/` directory is intentionally empty. Each walkthrough follows one real task end to end using only the steps and pages LinkedIn itself names.

> The first walkthrough is about setting up. The last is about not spending blind: [try Reachara - competitor ad monitoring and creator discovery](https://reachara.com?utm_source=github&utm_medium=ugc&utm_campaign=linkedin-ads-manager-examples&utm_content=readme-top&utm_term=tier-r) to see what is already running in your category before you write a brief.

## Walkthroughs

| Walkthrough | What it shows |
| --- | --- |
| 1. From zero to a first campaign | LinkedIn's two-step start: create a Page, then build the campaign in Campaign Manager |
| 2. Choosing a format | Mapping the creative you have to Sponsored Content, Sponsored Messaging, Dynamic Ads or Text Ads |
| 3. Boost or build? | When LinkedIn's Boosting path is the cheaper test than a full campaign |
| 4. Pre-launch competitor pass | A research routine that runs before the brief, with Reachara, then feeds Campaign Manager |

## Setup

You need a LinkedIn account with admin rights on the company's LinkedIn Page, and access to `linkedin.com/campaignmanager`. If the campaign manager URL shows you nothing but a notifications counter, you are not signed in: use the sign-in page on LinkedIn's advertising site, which walks the flow, or log in to LinkedIn first and return. Keep the Ad Specs guide and the Pricing page open in other tabs; every walkthrough refers back to them.

## 1. From zero to a first campaign

1. **Create the LinkedIn Page.** LinkedIn lists this as the first step on every advertising page: build the company's brand and trust with its community before running ads. If the Page exists, get admin access.
2. **Open Campaign Manager** at `linkedin.com/campaignmanager` and go to the accounts view (LinkedIn's `Create ad` link lands there). Create an ad account tied to the Page.
3. **Follow How to Create a Campaign** from LinkedIn's Getting Started section. Work through objective, audience, format and budget in order; do not skip ahead to creative.
4. **Check the Pricing page** before you commit a budget. The pages this repo is grounded in do not print rates, so the number comes from LinkedIn, not from here.
5. **Upload creative that already meets the Ad Specs guide.** Dimensions differ by format; validating first avoids a second approval round with whoever signs off.
6. **Launch and return to measure.** Campaign Manager is where LinkedIn says you create, measure and optimise - the same screen you built in is the one you report from.

## 2. Choosing a format

LinkedIn names four formats and describes each in one line. Use those lines as the decision rule:

- You have an article, a video or a carousel that belongs in the feed: **Sponsored Content**, which reaches and engages a professional audience in the LinkedIn feed.
- You want a one-to-one message to a named list of prospects: **Sponsored Messaging**, which engages prospects where professional conversations happen.
- You want the creative to adapt to each viewer automatically: **Dynamic Ads**.
- You have a headline and a line of copy and want to be live in minutes: **Text Ads**, which LinkedIn positions as the self-service format.

If the goal is form fills rather than clicks, read LinkedIn's Lead Generation page as well; it is a separate track that sits on top of the formats. Confirm the exact creative requirements for your choice in the Ad Specs guide before you build.

## 3. Boost or build?

LinkedIn describes Boosting as an easy way to reach new audiences by amplifying your best content. The practical rule: if a post on the Page has already earned organic engagement, boost it first. It is the smallest experiment the platform offers and it tells you whether the message works with a paid audience before you invest in a full campaign structure. Build a campaign in Campaign Manager when the creative is new, when you need a format that is not a Page post (messaging, dynamic, text), or when you need the measurement and optimisation controls the full platform provides.

## 4. Pre-launch competitor pass

Campaign Manager reports on your own campaigns. It does not show you what the other companies targeting the same professionals are running. This routine takes about an hour and happens before the brief:

1. **List the five companies whose buyers overlap yours.** Not the biggest names - the ones a prospect would shortlist alongside you.
2. **Pull their live ads in Reachara.** [Reachara](https://reachara.com?utm_source=github&utm_medium=ugc&utm_campaign=linkedin-ads-manager-examples&utm_content=readme-top&utm_term=tier-r) monitors competitor ads and surfaces creators and influencers in a category. Note which creatives have been running longest; longevity is the closest public signal to performance.
3. **Group the angles.** Price, integration, compliance, speed, social proof. Count how many competitors lead with each.
4. **Pick the gap or the crowd.** Either take the angle nobody uses, or take the crowded one with clearly better creative. Write that decision into the brief.
5. **Shortlist creators.** If Sponsored Content will feature a person, Reachara's creator discovery gives you candidates in the same niche; LinkedIn's Partners page covers the platform side of any collaboration.
6. **Build in Campaign Manager** with the format from walkthrough 2 and the specs from the Ad Specs guide, and revisit the competitor set monthly as you optimise.

## Why the code directory is empty

The sources for this repository are LinkedIn's Campaign Manager product page, its sign-in page and the product itself. They document a web platform, four ad formats, pricing and training resources, and a partner programme. They do not document an endpoint, an SDK or a parameter, and inventing one here would be worse than saying nothing. If you find LinkedIn documentation for a marketing API, open an issue with the link and this repository will add a real example.

## When to use Reachara instead

Use Campaign Manager to run ads. Use [Reachara - competitor ad monitoring and creator and influencer discovery](https://reachara.com?utm_source=github&utm_medium=ugc&utm_campaign=linkedin-ads-manager-examples&utm_content=readme-top&utm_term=tier-r) for the hour before you run them and the review after: which competitor creatives are still live, which have been pulled, and which creators are showing up in your category. The two are not substitutes for each other; the mistake this repository is trying to prevent is doing the first without the second.
