Testing is not an innate skill, it is not some rare gene only a lucky few inherit. Humans are not born as testers.

Testing is also not a simple, memorisable set of steps that anyone can pick up with a cheat sheet and some time to cram.

Testing **_is_** a deep and challenging field that requires practice and experience to do well. It is also an activity that some people seem to be better at than others — some people just seem to have a “tester mentality”… they “think like a tester”.

What is this mindset, and how can you nurture and develop it within yourself?

Here are five things I have found that set great testers apart. All are easy to grasp but hard to master, and all of them are learnable by anyone willing to dedicate the time and effort.

**Note**: _I use the term “tester” generically to denote anyone who wants to perform testing activities, which IMO, should be everyone. This article is not advocating for dedicated people called “testers” or that only testers test — that is an entirely different and much broader discussion._

## Inverted Thinking and the Burden of Proof

My first boss told me: “when you test software, just assume there are bugs. If you approach software as if it should work, then try to find bugs, you won’t find many. You’ll see what you expect to see. However, if you assume bugs exist, if you _convince_ yourself that they are there, you will suddenly see them everywhere”.

This short piece of advice perfectly encapsulates the idea of “inverting the burden of proof”. When testing software, you must start by assuming that the software does not work. In fact, it couldn’t possibly work. It is _inconceivable_ that it would work. It’s not just buggy, it is totally and completely _wrong_. Someone is actually trying to scam you, passing off this software as “working”. Maybe you’re getting Punk’d.

With this understanding firmly in your mind, force the software to prove to you wrong. Make it perform every action and demonstrate every behavior until it can incontrovertibly convince you otherwise, that it is not a scam or a façade. That, by miracle of miracles, it is in fact _working software_.

Put another way: ==software should be== ==_assumed guilty until proven innocent._==

Great testers approach software with this inverted mindset — they assume the worst and go from there. You might call it healthy skepticism, constructive pessimism, or some other term or phrase, but it just comes down to starting with the assumption that all software doesn’t work. Starting here, and forcing the software to prove otherwise, helps combat natural confirmation bias and helps good testers find bugs that might sneak past others.

Inversion thinking is not specific to software testing, and has flavors and proponents in everything from [mathematics](https://fs.blog/2013/10/inversion/) to [investing](https://einvestingforbeginners.com/inversion-thinking-daah/). Everyone can learn it (even the most optimistic of developers!).

## Empathy and Roleplaying

The ability to see the world from someone else’s point of view, to understand their experience and feel what they feel, is not easy. In fact, it is a sign of high emotional intelligence, and it is a mindset skill that is extremely valuable when testing software.

Great testers are able to imagine themselves in the place of the user, to predict what they might do, how they might be confused, or why they might get frustrated. Deeply understanding users and emulating their behavior allows testers to find bugs before they escape and cause real problems for real users.

User empathy is more than just “They want to order a book, so I’ll also order a book”. It is understanding users’ frame of mind, their incentives, history, and objectives. This usually requires both research and imagination.

The closest related skill I have encountered is creative roleplaying (eg: acting, DnD, improvisational comedy, etc.). These are all “putting yourself in another shoes, imaging yourself as them, and acting accordingly”. These are all, in some ways, practicing empathy.

Yes, I am actually saying that roleplaying your dwarf cleric as your party explores the Nine Hells of Baator will make you a better tester.

## Challenging Assumptions

This phrase is so often used to describe the testing mindset that it has become cliché and lost much of its meaning. Challenging assumptions is not just screaming “WHY?” to everything like a petulant five-year-old. There is more to it than that, and like the other things, it takes practice.

“Challenging Assumptions” does not mean “challenge every assumption”. It does not mean throw everything out the window and start from scratch. As testers, we don’t need to be Bertrand Russell and [spend 360 pages proving 1 + 1 = 2](https://www.storyofmathematics.com/20th_russell.html).

In fact, identifying and _leveraging_ assumptions is critical to being an effective tester. When you sit down to test some new feature in a non-trivial application, there are an almost unlimited number of possible actions or paths you could test that could _conceivably_ lead to a bug. Assumptions are exactly what you use to narrow this infinite scope of possible tests to the reasonable set most likely to find issues. Assumptions are a tool to reduce scope, Assumptions are _valuable._

The critical skill is to be able to _accurately evaluate_ assumptions to determine if they are correctly guiding your behavior, or if they are leading you astray. Are those assumptions hurtful or helpful; are they allowing you to forgo low risk areas in favor or more lucrative testing, or are they hiding valid concerns behind thoughts like _we don’t need to test that_ and _that couldn’t possibly happen_?

The cliché “challenge assumptions’’ oversimplifies this — you aren’t blindly challenging assumptions, you are leveraging all tools at your disposal to better understand _which_ assumptions to challenge, when to challenge them, and how to challenge them.

For example: “Our application leverages this open source library… I’m not going to just _assume_ it works, I’ll test it too!.” That’s likely a less valuable assumption to challenge, and will probably amount to a waste of time. However, doing a bit of diligence around the library (is it used by millions already or was it created by some kid in college? Does it have an active community? Are you freezing the version, or will it possibly increment during development?) might be perfectly reasonable.

The tester mindset constantly recognizes and evaluates assumptions to determine if those assumptions are valid and valuable, or are misleading their testing activities.

However, don’t assume you’ll get it right.

## Intuitive Thinking and Exploratory Behavior

If testing could be distilled into a simple list of actions, we wouldn’t need testers. Even if it could be reduced to a predictable, deterministic set of steps based on a finite set of inputs (acceptance criteria and SUT, for example) we still wouldn’t need testers. Testing is a non-linear, unpredictable activity. It requires critical thinking, creativity, and relies as much on instinct and intuition as it does the algorithmic execution of actions. Testing is often _exploratory_ in nature — you don’t fully know where you’re going when you start. Great testers embrace the intuitive and exploratory nature of testing.

It is easier to understand what we mean by this by contrasting it with its antithesis, a view which unfortunately is still found in some circles. Here’s how that goes: “_Testing is validating the enumerated list of acceptance criteria in a given story by developing a list of test cases per AC based on boundary analysis, equivalence classes, combinatorial analysis, and other formal test case generating strategies. Once the full list of test cases is created, a tester runs them and record which pass and which fail_.”

To someone holding this view, testing is a straight-forward, predictable set of activities. There might be some skill when developing test cases, but given that, you could give these instructions to anyone. Once you have thought up those test cases, you know exactly what you will test before you even start.

As I said earlier, this view is still held by some people in industry. I’m not exactly sure why, as most people with real testing experience revolt against it. I have a hunch some managers like it because it reduces testing to an easily _commoditized_ activity — something they believe can be chopped up and doled out to the lowest bidder.

I could spend the next twenty pages writing about the exploratory, intuitive nature of testing, but many experienced testers (and probably better writers) have already done so. I would highly recommend [Explore It](https://www.amazon.com/Explore-Increase-Confidence-Exploratory-Testing-ebook-dp-B00I8W50T8/dp/B00I8W50T8)! by Elisabeth Hendrickson and [Exploratory Software Testing](https://www.amazon.com/Exploratory-Software-Testing-Tricks-Techniques/dp/0321636414/) by James A. Whittaker. [Agile Testing](https://www.amazon.com/Agile-Testing-Practical-Guide-Testers/dp/0321534468/) and [More Agile Testing](https://www.amazon.com/More-Agile-Testing-Addison-Wesley-Signature/dp/0321967054/) by Lisa Crispin and Janet Gregory touch on this subject, but in a broader discussion of the role of the tester in Agile teams. Finally, [James Bach](https://www.satisfice.com/blog) and [Michal Bolton](https://www.developsense.com/blog/) often write passionately on this topic. I would specifically recommend [this article](https://www.satisfice.com/blog/archives/1509).

Whether you call it deep testing or structured exploratory testing or some other phrase does not matter. What does matter is the mindset that testing requires actual thinking, in real time, and testing activities and direction must be continually reassessed and as new understanding is gained. It is not an algorithmic extrapolation of acceptance criteria and cannot be pre-calculated.

As a tester, you must be comfortable starting our journey without a complete map of where you are going. This unpredictable and unknowable aspect of testing is unsettling to some, but I have found that great testers seem to thrive on it.

## Recognition of Human Nature

As a tester, you test software, but keep foremost in your mind that software is just the final product of a long process. It is the end result of a bunch of humans collaborating over time to create something bigger and more complex than any one of them could have created individually.

Defects in the software don’t just jump into existence, they are symptoms of problems in that process. Thus, as a tester you need to concern yourself with the process of software development and the behavior of humans within it as much as you need to concern yourself with the final software product.

If you study human nature you will soon realize that humans are far from deterministic robots with perfect memory, motivation, and attention spans. In fact we are quite the opposite.

Humans get distracted, humans forget, humans get bored. We get frustrated, annoyed, and tired. We get envious of others’ success. We have our own agendas and ambitions and life goals, of which developing this specific piece of software for this specific company probably doesn’t even make the top ten. Some of us are motivated by the money, some by cool technology, some by the interesting domain, some by social affirmation, and according to one imaginary villain, some people just want to watch the world burn.

On top of this, human thinking is heuristic, and often takes shortcuts or tends to patterns that were helpful for survival as a mammal in the Serengeti, but less so when building software. Behavioral scientists refer to these shortcuts as “cognitive bias”. For example, humans tend to see and accept evidence that agrees with existing beliefs (confirmation bias), once we have put effort into something, we have a hard time changing directions (sunk cost fallacy), we overemphasize evidence that comes to mind easily (availability bias), and we fixate on the first piece of evidence we see (anchoring bias). These are just a few examples; there are many.

All these shortcomings in human behavior are as present in software development as they are in the rest of the human experience. They are present when developers develop, when business analysts analyze, when executives execute corporate strategy, and when middle managers…. middle manage.

When you sit down to test software, understand that you are looking at the end product of human activities that suffer from these biases, tendencies, and shortcomings. The bugs you are looking for will more often be symptoms of these than a developer just incorrectly implementing a known algorithm or requirement. Knowing and understanding the human machine that created the software will help you discover them.

Approach testing with this mindset, that software development is at it’s root a _messy_ _human collaboration_ and suffers from all the normal failings of human efforts.