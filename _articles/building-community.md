---
title: Building Welcoming Communities
description: Cupcake ipsum dolor sit amet. Muffin chocolate topping. Biscuit toffee jelly beans cheesecake lollipop. Sweet roll oat cake candy canes pudding oat cake I love macaroon. Gummi bears sugar plum caramels soufflé danish cake. Cake tiramisu jelly-o. Chupa chups cupcake bonbon.
more:
- title: Growing a contributor base in modern open source
  href: https://opensource.com/life/16/5/growing-contributor-base-modern-open-source
  by: "@mikeal"
- title: Sustainable Open Source
  href: http://writing.jan.io/2015/11/20/sustainable-open-source.html
  by: "@janl"
- title: How the Moya org handles contributions
  href: https://github.com/Moya/contributors
- title: How to use Github issues to attract new contributors
  href: http://radek.io/2015/08/24/github-issues/
  by: "@pazdera"
- title: Growing the community around your open-source project
  href: http://radek.io/2015/10/12/marketing-for-open-source-projects-5/
  by: "@pazdera"
- title: Welcoming Communities
  href: http://hood.ie/blog/welcoming-communities.html
  by: "@gr2m"
- title: Building Popular Projects
  href: https://ashfurrow.com/blog/building-popular-projects/
  by: "@ashfurrow"
- title: What makes a good community?
  href: http://sarah.thesharps.us/2015/10/06/what-makes-a-good-community/
  by: "@sarahsharp"
- title: Lowering the barriers
  href: https://the-pastry-box-project.net/charlotte-spencer/2015-september-16
  by: "@charlotteis"
- title: First Timers Only
  href: https://medium.com/@kentcdodds/first-timers-only-78281ea47455#.f0i87x7us
  by: "@kentcdodds"
- title: Difficult People
  href: http://producingoss.com/en/producingoss.html#difficult-people
  from: Producing Open Source Software
  by: "@kfogel"
- title: Avoiding Common Pitfalls
  href: http://producingoss.com/en/producingoss.html#common-pitfalls)
  from: Producing Open Source Software
  by: "@kfogel"
- title: "Wikipedia: Consensus-seeking decision-making"
  href: https://en.wikipedia.org/wiki/Consensus-seeking_decision-making
- title: Why Atom doesn't have a voting system
  href: https://discuss.atom.io/t/prioritize-issues-feature-requests-based-on-voting-system/27642/2?u=leedohm
  by: "@lee-dohm"
---

You've launched your project, you're spreading the word, and people are checking out your project. Awesome! Now, how do you get them to stick around? Building a welcoming community will encourage people to use, contribute to, and evangelize your project.

## Setting your project up for success

If your project is just starting to see its first contributions, start by giving early contributors a positive experience and make it easy for them to keep coming back.

### Make people feel welcome

A welcoming community is an investment into your project's future and reputation. When someone new lands on your project, make sure to thank them for their interest! Show them around and help them get started. Point them to resources, like onboarding materials or past mailing list threads, that you think might be helpful. It only takes one negative experience to make someone not want to come back.

![django new contributors page](/assets/images/marketing/django_new_contributors.png)

### Be responsive

As you promote your project, people will probably have feedback and ideas for you. They may request support or functionality, have questions about how things work, or need help getting started.

Try to be responsive when someone files an issue, submits a pull request, or asks a question about your project. When you respond quickly, people will feel they are part of a dialogue, and they'll be more enthusiastic about participating.

Even if you can't review the request immediately, acknowledging it early helps increase engagement. Here's how @tdreyno responded to a pull request on [Middleman](https://github.com/middleman/middleman/pull/1466):

![middleman pull request](/assets/images/marketing/middleman_pr.png)

When Mozilla studied its community and engagement in 2014, [they found that](https://docs.google.com/presentation/d/1hsJLv1ieSqtXBzd5YZusY-mB8e1VJzaeOmh8Q4VeMio/edit#slide=id.g43d857af8_0177) contributors who received code reviews within 48 hours had a much higher rate of return and repeat contribution.

Conversations about your project could also be happening in other places around the internet, such as Stack Overflow, Twitter, or Reddit. You can set up notifications in some of these places so you are alerted when someone mentions your project.

### Make it easy for people to use and contribute

One way to think about your project's community is what @MikeMcQuaid calls the [contributor funnel](https://speakerdeck.com/mikemcquaid/the-open-source-contributor-funnel):

![contributor funnel](/assets/images/marketing/contributor_funnel_mikemcquaid.png)

As you build your community, consider how someone at the top of the funnel (a potential user) might theoretically make their way to the bottom (an active maintainer). Your goal is to reduce friction at each stage of the contributor experience. When people have easy wins, they will feel incentivized to do more.

Start by making it easy for someone to use your project. Tutorials, clear code examples, good documentation, and a friendly README will make it easier for anyone who lands on your project to grasp its value and get started. Don't forget to document processes for non-code contributions as well, such as triaging, community management, or design.

For casual or first-time contributors, be open-minded about the types of contributions you'll accept. Your pool of contributors includes much more than just developers. Many contributors start with a bug report or small fix. A new contributor might write a tutorial or improve your project's documentation, because newer users notice things that more experienced users might not. Let people help how they want to help.

If there's a contribution you disagree with, thank them for their idea and [explain why](../../troubleshooting/contributions/) it doesn't fit into the scope of the project. Link to existing documentation on the types of contributions you are looking for and encourage them to stay involved.

### Document everything

When you start an open source project, it may feel natural to keep your ideas and workflows private. But open source projects thrive when you [document your process](http://www.writethedocs.org/) in public. That way, more people can participate at every step of the way. Not only will they know _what_ to contribute, but they'll also know _how_. You might get help on something you didn't even know you needed.

Documenting your open source project means more than just technical documentation. Be transparent about your project's roadmap, your timeline for completing new features, the types of contributions you're looking for, how contributions are reviewed and accepted, or why you made certain decisions. If there are certain types of contributions that you won't accept, explain so in your CONTRIBUTING.md file. If you get frequent questions or notice users running into the same problem, document the answers in the README. Any time you feel the urge to write something down or privately discuss your project, ask yourself whether you can make it public. For meetings, consider publishing your notes or takeaways in a relevant issue. The feedback you'll get from this level of transparency may surprise you.

Writing things down isn't just for meetings and technical documentation, either. If you're working on a substantial update to your project, put it into a pull request and mark it as a work in progress (WIP). That way, other people can feel involved in the process early on.

## Give your community a place to congregate

There are two reasons to give your community a place to congregate.

The first reason is for them. People with common interests will inevitably want a place to talk about it. And when communication is public and accessible, anybody can read past archives to get up to speed and new people will feel more comfortable participating. Helping people forge connections with each other builds a stronger and more resilient community.

The second reason is for you. If you don't give people a public place to talk about your project, they will likely contact you directly. In the beginning, it may seem easy enough to respond to private messages "just this once". But over time, especially if your project becomes popular, you will feel exhausted. Resist the temptation to communicate with people about your project in private. Instead, direct them to a designated public channel.

If your project is on GitHub, public communication can be as simple as directing people to use [GitHub Issues](https://guides.github.com/features/issues/) instead of emailing you directly. You could also set up a mailing list (such as [Google Groups](https://groups.google.com/forum/#!overview)) or create a Twitter account, Slack, or IRC channel for people to talk about your project. Or try all of the above!

Notable exceptions to public communication are: 1) security issues and 2) sensitive code of conduct violations. You should always have a way for people to report these issues privately. If you don't want to use your personal communication channels, set up a separate email address for this purpose.

## Growing your community

Communities are extremely powerful. That power can be a blessing or a curse, depending on how you wield it. But as your project’s community grows, there are ways to help it become a force of construction, not destruction.

The majority of open source contributors are "casual contributors": people who contribute to a project only occasionally. Sometimes these are also called ["drive-through contributors"](https://lwn.net/Articles/688560/).

A casual contributor may not have time to get fully up to speed with your project. Nearly half of contributors on popular GitHub projects, for example, [only made one contribution](http://gustavopinto.org/lost+found/saner2016.pdf). This level of noise can be overwhelming at first. But [the more people feel ownership](https://medium.com/node-js-javascript/building-a-better-node-community-3f8f45b45cb5) of your project, the more work can be distributed. When you empower your biggest fans to run with the work they're excited about, there's less pressure to do everything yourself.

### Don't tolerate bad actors

Any popular project will inevitably attract people who harm, rather than help, your community. They may start unnecessary debates, quibble over trivial features, or bully others.

Do your best to adopt a zero-tolerance policy towards these types of people. If left unchecked, negative people will make other people in your community uncomfortable. They may even leave.

Regular debates over trivial aspects of your project distracts others, including you, from focusing on important tasks. New people who arrive to your project may see these conversations and not want to participate.

When you see negative behavior happening on your project, call it out publicly. Explain, in a kind but firm tone, why their behavior is not acceptable. If the problem persists, you may need to [ask them to leave](../../troubleshooting/conduct/). Your [code of conduct](../../getting-started/preparing/#establishing-a-code-of-conduct) can be a constructive guide for these conversations.

### Meet contributors where they're at

You started documenting your project’s needs and workflow in the early stages. Clear, comprehensive documentation only becomes more important as your community grows. Casual contributors, who may not otherwise be familiar with your project, use documentation to quickly get the context they need.

In your CONTRIBUTING file, explicitly tell new contributors how to get started. You may even want to make a dedicated section for this purpose. For example, [Read the Docs](http://docs.readthedocs.io/en/latest/contribute.html#contributing-to-development) tells its readers:

> If you want to deep dive and help out with development on Read the Docs, then first get the project installed locally according to the Installation Guide. After that is done we suggest you have a look at tickets in our issue tracker that are labelled Good First Bug. These are meant to be a great way to get a smooth start and won't put you in front of the most complex parts of the system.

In Issues, label bugs that are suitable for beginners: for example, _"good first bug"_, or _"first timers only"_. [These labels](https://github.com/librariesio/libraries.io/blob/6afea1a3354aef4672d9b3a9fc4cc308d60020c8/app/models/github_issue.rb#L8-L14) make it easy for someone new to your project to quickly scan your issues and get started.

Finally, use your documentation to make people feel welcome at every step of the way. Remember that you will never interact with most people who land on your project. There may be contributions you didn't receive because somebody felt intimidated or didn't know where to get started. Do your best to reduce your chances of someone leaving your project in frustration. Even a few kind words can help. For example, here's how [Rubinius](https://github.com/rubinius/rubinius/blob/master/.github/contributing.md) starts its contributing guide:

> We want to start off by saying thank you for using Rubinius. This project is a labor of love, and we appreciate all of the users that catch bugs, make performance improvements, and help with documentation. Every contribution is meaningful, so thank you for participating. That being said, here are a few guidelines that we ask you to follow so we can successfully address your issue.

### Share ownership of your project

People are excited to contribute to projects when they feel as sense of ownership. That doesn't mean you need to turn over your project's vision or accept contributions you don't want. But the more you can give credit to others, the more likely they are to stick around.

@orta found this approach to ownership [helped him succeed](http://artsy.github.io/blog/2016/07/03/handling-big-projects/) with his open source projects, including [Danger](https://github.com/danger/danger/):

> Understanding motivations, encouraging ownership and accommodating multiple viewpoints are vital parts of anyone who wants to make a project bigger than themselves. There [are lots of times](https://github.com/danger/danger/graphs/contributors) when I'm not the lead developer on Danger.

See if you can find ways to share ownership with your community as much as possible. Here are some ideas:

* **Resist fixing easy (non-critical) bugs.** Instead, use them as opportunities to recruit new contributors, or mentor someone who'd like to contribute. It may seem unnatural at first, but your investment will pay off over time. For example, @michaeljoseph asked a contributor to submit a pull request on a [Cookiecutter](https://github.com/audreyr/cookiecutter) issue below, rather than fix it himself.

![cookiecutter issue](/assets/images/sustaining/cookiecutter_submit_pr.png)

* Start a CONTRIBUTORS or AUTHORS file in your project that lists everyone who's contributed to your project. Here's an example that @shazow made for his project, [urllib3](https://github.com/shazow/urllib3/blob/master/CONTRIBUTORS.txt).

* If you've got a sizeable community, consider **sending out a newsletter or writing a blog post** that thanks contributors. Rust's [This Week in Rust](https://this-week-in-rust.org/) and Hoodie's [Shoutouts](http://hood.ie/blog/shoutouts-week-24.html) are two good examples.

* **Consider giving every contributor commit access.** @felixge found that this made people [more excited to polish their patches](http://felixge.de/2013/03/11/the-pull-request-hack.html), and he even found new maintainers for projects that he hadn't worked on in awhile.

The bigger your project, and the bigger your community, the easier it is to find help. [Django](https://github.com/django/django)'s original BDFLs ([benevolent dictators for life](../../sustaining/leadership/#what-are-some-of-the-common-governance-structures-for-open-source-projects)), @adrianholovaty and @jacobian, [both](http://www.holovaty.com/writing/bdfls-retiring/) [retired](https://jacobian.org/writing/retiring-as-bdfls/) after 9 years when they felt the community had outgrown them.

The reality is that [most projects only have](https://peerj.com/preprints/1233.pdf) one or two maintainers who do most of the work. While you may not always find someone to answer the call, putting a Batsignal out there increases the chances that other people will pitch in. And the earlier you start, the sooner people can help.

## Resolving conflicts

In the early stages of your project, making major decisions is easy. When you want to do something, you just do it.

As your project becomes more popular, more people will take interest in the decisions you make. Even if you don't have a big community of contributors, if your project has a lot of users, you'll find people weighing in on decisions or raising issues of their own.

For the most part, if you've cultivated a friendly, respectful community and documented your processes openly, your community should be able to find a resolution. But sometimes you run into an issue that's a bit harder to address.

### Set the bar for kindness

When your community is grappling with a difficult issue, tempers may rise. People may become angry or frustrated and take it out on one another, or on you.

Your job as a maintainer is to keep these situations from escalating. Even if you have a strong opinion on the topic, try to take the position of a moderator or facilitator, rather than jumping into the fight and pushing your views. If someone is being unkind or monopolizing the conversation, [act immediately](../../sustaining/healthy-communities/#dont-tolerate-bad-actors) to keep discussions civil and productive.

Other people are looking to you for guidance. Set a good example. You can still express disappointment, unhappiness, or concern, but do so calmly. Keeping your cool isn't easy, but demonstrating leadership improves the health of your community. The internet thanks you. 🙏

### Treat your README as a constitution

Your README is [more than just a set of instructions](../../getting-started/preparing/#writing-a-readme). It's also a place to talk about your goals, product vision, and roadmap. If people become overly focused on debating the merit of a particular feature, it may help to revisit your README and talk about the higher goals and vision of your project. Focusing on the README can also help depersonalize the conversation around a specific idea, so you can have a constructive discussion.

### Focus on the journey, not the destination

Some projects use a voting process to make major decisions. While sensible at first glance, voting emphasizes getting to an "answer," rather than listening to and addressing each other's concerns.

Voting can become political, where community members feel pressured to do each other favors or vote a certain way. Not everybody votes, either, whether it's the [silent majority](http://ben.balter.com/2016/03/08/optimizing-for-power-users-and-edge-cases/#the-silent-majority-of-users) in your community, or current users who didn't know a vote was taking place.

Sometimes, voting is a necessary tiebreaker. As much as you are able, however, emphasize "consensus seeking" rather than consensus. Under a consensus seeking process, community members discuss major concerns until they feel they have been adequately heard. When only minor concerns remain, the community moves forward. "Consensus seeking" acknowledges that a community may not be able to reach a perfect answer. Instead, it prioritizes listening and discussion.

Even if you don't actually adopt a consensus seeking process, as the maintainer of your project, it's important to make sure that people know you are listening. Making other people feel heard, and committing to resolving their concerns, can go a long way in diffusing a sensitive situation. Then, follow up on your words with actions.

Don't rush into a decision for the sake of having a resolution. Make sure that everybody feels heard and that all information has been made public before moving toward a resolution.

### Keep the conversation focused on action

Discussion is important, but there is a difference between productive and unproductive conversations. Encourage discussion so long as it is actively moving towards resolution. If it's clear that conversation is languishing or going off-topic, jabs are getting personal, or people are quibbling about minor details, it's time to shut this thing down.

Allowing these conversations to continue is not only bad for the issue at hand, but bad for the health of your community. It sends a message that these types of conversations are permitted or even encouraged, and it can discourage people from raising or resolving future issues.

With every point made by you or by others, ask yourself, _"How does this bring us closer to a resolution?"_ If the conversation is starting to unravel, ask the group, _"Which steps should we take next?"_ to refocus the conversation.

If a conversation clearly isn't going anywhere, there are no clear actions to be taken, or the appropriate action has already been taken, close the issue and explain why it has been closed.

### Pick your battles wisely

Context is important. Consider who is involved in the discussion and how they represent the rest of the community. Is everybody in the community upset about, or even engaged with, this issue? Or is a lone troublemaker? Remember to consider your community members who are silent, not just the active voices.

A notable exception to this framing is when the issue concerns community behavior or governance. In this case, your community's health is at stake: not just current members, but people you may never hear from because they don't feel comfortable joining or participating. Healthy and welcoming communities help ensure a future for your project by encouraging active contribution. Unhealthy communities threaten the life of your project and will leave you feeling stressed and unhappy.

If the issue does not represent the broader needs of your community, you may just need to acknowledge the concerns of a few people. If this is a recurring issue without a clear resolution, point them to previous discussions on the topic and close the thread.

### Identify a community tiebreaker

With a good attitude and clear communication, most difficult situations are resolvable. However, even in a productive conversation, there can simply be a difference in opinion on how to proceed. In these cases, you should identify an individual or group of people that can serve as a tiebreaker. A tiebreaker could be the primary maintainer of the project, or it could be a small group of people who make a decision based on voting. Ideally, you've identified a tiebreaker and the associated process in your GOVERNANCE file before you ever have to use it.

Your tiebreaker should be a last resort. Divisive issues are an opportunity for your community to grow and learn. Embrace these opportunities and use a collaborative process to move to a resolution wherever possible.