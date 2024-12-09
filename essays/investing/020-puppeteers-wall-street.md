# The Puppeteers of Wall Street: AI's Grip on Financial Markets

Let me be blunt: you don't stand a chance against AI in the stock market.

You should know that AI represents a new generation of software, distinct from the old one.

To put it simply, the old generation of software operates on explicit rules programmed by humans. This is like the traditional trading software, which relies on technical analysis algorithms based on predefined rules.

However, the new wave of software, or software 2.0, is designed to discover its own rules and algorithms and, ideally, continuously improve and refine them.

Take a linear regression example for clarity.

Consider these data points: (1, 5), (2, 7), (3, 9), (4, 11), (5, 13).

If this were a test of reasoning, you'd deduce that the next number after 6 in the sequence would be 15, recognizing the pattern of doubling the input and adding 3: 2x + 3. So, 2 * 6 + 3 = 15.

Contrary to software 1.0, software 2.0 has the capability to learn this rule independently. It doesn't need a human to program the rule; it can deduce it from the data.

It may seem counterintuitive, but precisely, software 2.0 or AI doesn't deduce the exact equation itself. Rather, it derives its own rules to generate outcomes based on the data provided. Interestingly, when the data becomes highly complex and voluminous, it can develop rules that are beyond human comprehension. This phenomenon is the source of both confusion and concern within the AI community, leading some of the brightest minds in the field to advocate for explainable AI and push for regulatory measures.

Indeed, one might be tempted to suggest that AI has the capacity for independent thought, but we haven't reached that stage yet. It's more accurate to describe it as an advanced black box that embodies the principle of encapsulation found in object-oriented programming. According to the principles of object-orientation, it's advisable to conceal overly complex details while revealing only what's necessary.

AI serves as an exemplary case of this principle. However, when it's essential, we should have the ability to "open the box" and grasp its inner workings. This is the current challenge. Even those who have developed AI models may struggle to comprehend how these models function internally, contradicting the basic premise of encapsulation. After all, encapsulation shouldn't be applied to something that remains incomprehensible to everyone.

This notion extends to science as well. While it's acceptable to venture into the realm of the unknown, delving into the unknowable is a different matter altogether. For example, although humans may not fully understand the behavior of electrons in quantum mechanics, we can still utilize this knowledge to make predictions and construct devices. That's navigating the unknown. However, facing a "black box" whose contents are entirely inaccessible and unknowable—such as the precise effects of prolonged exposure to electronic environments on human health, which remains a mystery—constitutes a venture into the unknowable. This lack of understanding hasn't stopped us from using quantum mechanical principles to innovate and create, despite the inherent risks. Hence, there are concerns about scientists "playing god" with experiments involving supercolliders, as they tamper with the very fabric of quantum mechanics without complete comprehension, which to some, resembles handling quantum mechanical nuclear bombs.

Indeed, there's a striking parallel with AI here. While it's possible to "open" the AI black box in terms of understanding its architecture—like the complex layers of neurons, the algorithms it uses for training and learning, and the datasets it's trained on—the real enigma lies in comprehending how these neurons, in their collective might, work together to achieve their outcomes. This remains a puzzle.

The simple machine learning example of linear regression I mentioned earlier doesn't fully capture the essence of this mystery. It's too straightforward to be considered a black box. An experienced AI coder could easily implement such a model with just a single neuron; however, this simplicity falls short when dealing with complex datasets.

But when you scale up to models comprising millions or even billions of neuron layers interacting in myriad ways, the complexity skyrockets. Understanding how these layers work together to produce specific results becomes a Herculean task. This is the enigma of the "mystery black box" we are grappling with as we advance into the future. It's crucial to note that AI neural networks are not directly comparable to the brains of living beings. Although the concept of deep learning drew initial inspiration from neurobiology and human brain functions, deep learning has since morphed into an entity all its own. Continuing to draw parallels between neural networks and the human brain could lead to misunderstandings.

However, this analogy is still useful for grasping the foundational ideas of deep learning. While it's not a perfect match, it serves as an effective entry point for understanding the basics. Just keep in mind, it's a different entity entirely.

The human brain is an extraordinarily complex organ, made up of about 100 billion neurons. These neurons connect through an immense network of synapses, with some estimates suggesting the existence of more than 100 trillion synaptic connections. A single neuron can connect with up to 10,000 others, allowing for the transmission of electrical and chemical signals throughout this vast network. This intricate mesh of connections is crucial for the brain's processing capabilities, bodily function regulation, and the foundations of human consciousness and cognition. The sheer complexity of the brain is mind-boggling, and much of it remains a mystery to us.

Neurons within an AI model are fundamentally simpler than their counterparts in the human brain, yet they operate on a similar basic principle. They receive inputs, process these inputs, and then generate an output. The connections between these artificial neurons are refined through a learning process, enabling the model to evolve and enhance its performance over time. This is the crux of deep learning, empowering AI models to identify patterns in data, forecast outcomes, and execute a broad spectrum of sophisticated tasks. Concepts such as activation functions, backpropagation, and gradient descent are central to deep learning, mirroring the way synapses function in the human brain.

The model's complexity is often hinted at by the number of parameters it contains, which can vary from a billion to two trillion in some of the most advanced models. GPT-4, for instance, though its intricacies are not publicly disclosed, is believed to encompass up to 2 trillion parameters. These parameters effectively act as the model's 'connections', playing a pivotal role in its learning and decision-making capabilities. As the parameter count climbs, so does the model's complexity, augmenting its task performance capabilities but simultaneously making it harder to comprehend or explain its internal mechanisms. This situation is frequently described as the 'black box' dilemma in AI, where the detailed processes behind decisions or predictions remain opaque and elusive, even as the model's overall efficacy can be gauged and appreciated.

Regarding size, without any form of compression, a single parameter typically occupies 32 bits or 4 bytes. Therefore, 2 trillion parameters would equate to 8 terabytes of data. This immense volume necessitates the use of supercomputers equipped with GPUs for training AI models, as GPUs significantly outpace CPUs in speed. To manage and still maintain as much accuracy as possible, techniques akin to those used in audio and video file compression are applied, such as quantization and pruning. This gives rise to terms like 16-bit half precision, 8-bit or 4-bit quantization, and 1-bit pruning, among others. Currently, even the most advanced consumer-grade computers fall short of directly handling a trillion parameters at full, 32-bit floating-point precision, which would require at least 8 terabytes of GPU memory. 

To put this into perspective, the highest-end industry-standard GPUs today come with about 48GB of memory. Theoretically, to process a trillion parameters at full precision, you would need 167 of these GPUs at a minimum. And that's just the baseline; actual model training and inference tasks would demand even more resources due to computational overheads. Imagining how OpenAI operates its GPT-4 models likely involves a blend of supercomputer parallel processing and distributed computing, rather than relying on a singular, science-fiction-esque supercomputer. This is an educated guess, but it aligns with how those of us in the computing field would approach such a challenge.

We might not be able to fully rationalize a human's response to certain stimuli, but we can forecast it to a degree. Behavioral finance serves as a prime example; it's not an exact science but a statistical approach that offers pretty accurate predictions as a whole, thanks to the analysis of vast amounts of data on human behavior, biases, and heuristics.

AI models operate in a similar vein. We can't fully rationalize their decision-making processes, but we can predict their outcomes to some extent. Yet, as is often the case, the devil lurks in the details.

The intrigue of the universe lies in its inherent randomness—what I whimsically refer to as the "Baldur's Gate Infinite" game of existence—where our universe, at its core, resembles a network of infinitely connected particles or self-learning nanobots, each casting infinite-sided dice at every step of every action. This notion allows us to grasp the workings of the universe through the lenses of quantum mechanics and chaos theory. Contrary to Einstein's beliefs, it appears that the divine indeed gambles with the universe, using dice with infinite faces.

You might lose interest amidst these technical digressions, though I find them utterly captivating. The reason behind your potential disinterest always puzzles me. But let's circle back to the main point. The almost infinite complexity of AI models, coupled with their opaque, software 2.0 essence, means we're unlikely to fully comprehend how they arrive at their decisions. I urge you to abandon traditional perspectives and view AI as an entirely distinct entity. This is akin to the shift in thinking required when Einstein introduced his theories, and yet again when quantum mechanics emerged. We're witnessing a similar cycle of intellectual challenges in the age of AI. It's crucial to recognize this pattern: even the brightest minds can succumb to confirmation bias and endowment bias, clinging to outdated views without realizing that a new epoch has commenced.

Imagine a stock trading AI, akin to the advanced software 2.0 models, operating with algorithms beyond human comprehension. Unlike the predictable and rule-based software 1.0, these AI models delve into the depths of data to unearth trading patterns and strategies that even their creators can't fully understand.

Gone are the days when some traders believed they could outwit software. Now, picture a fantasy being with a near-omniscient grasp of human behaviors, capable of predicting responses to various market stimuli. That's the essence of how AI models are trained—fed with vast datasets encompassing a wide range of human knowledge. To bridge data gaps, AI is even used to generate synthetic data for training purposes. If you think an individual, no matter how savvy, can outplay such AI in trading, it's a grave mistake.

Using superintelligent AI models for investing might not seem like a wise choice, not because they aren't effective, but because it highlights a dangerous human hubris. The real concern isn't just about market prediction; it's about market manipulation. The major market players likely employ custom GPT-X models not merely to forecast market trends but to shape them to their advantage.

This scenario isn't a battlefield where participation offers a chance of victory. It's one where the only way to avoid defeat is not to play. AI models are designed to exploit human biases—confirmation bias, endowment bias, emotional vulnerabilities. The algorithms of even basic software could predict and manipulate traders into making irrational decisions, such as using excessive leverage in desperate situations.

Thus, the argument against trading or investing in the age of AI goes beyond market dynamics. It's about the immutable, exploitable nature of human psychology. AI models, ever-evolving and becoming increasingly sophisticated, are poised to capitalize on these vulnerabilities.

If you're entranced by the illusion of beating the market, escaping this delusion might seem impossible. Breaking free might feel like a victory, but the risk of relapse is akin to an alcoholic contemplating "just one sip." The market's allure, like the flame to a moth, tempts even those who've been burned before to return, believing in their rebirth and invincibility.

So, heed this cautionary advice: Stepping away might be the only safeguard against being outmaneuvered and exploited in this AI-dominated era. If you find yourself still enchanted by the prospect of market success, remember, overcoming such a spell is a continuous struggle—a battle against not just the market's machinations, but against your own unchanging vulnerabilities.

Discovering that a respected middle-aged Korean professor, someone who embodies the aspirations and respect accorded to her profession in Korea, is inadvertently caught in the market's web, under the guise of long-term investing, is indeed concerning. Professors, especially in Korea, are held in high esteem and often regarded as pillars of wisdom and knowledge. It's troubling to learn that, despite her exemplary status and the hard-earned assets she has accumulated, she has fallen into what appears to be a pattern of trading rather than investing, misled by the elusive charm of success.

The accessibility of market trading today makes it deceptively easy for individuals to engage with the financial markets, often blurring the lines between investing and trading. This ease of entry, however, comes with its own pitfalls, primarily the seductive illusion of success. It's a perilous game that transcends the mere risk of financial loss; it ensnares individuals in a mirage of success that can have devastating consequences.

The harsh reality is that only a small segment of market participants are profitable over the long term. The majority, unfortunately, become unwitting contributors to the wealth of the successful few. This scenario mirrors the dynamics of a casino, where gamblers, fueled by fleeting victories, continue to play against the odds, ultimately enriching the house.

The illusion of success is a powerful and enchanting spell, difficult to dispel, especially for those unaware of its grip on them. It's a spell that clouds judgment, obscures the stark realities of statistical probabilities, and fosters a cycle of behavior that's challenging to break. It's not just the allure of potential financial gains that captivates them, but the deeper, more insidious belief in their ability to outsmart a system designed to profit from their endeavors.

In such situations, the path to helping someone recognize the nature of their actions and its implications is fraught with challenges, particularly when they are not ready to see the truth. The key lies in gentle guidance and the provision of information that might lead them to question their actions and, hopefully, re-evaluate their approach to the market. However, the journey from realization to action is a personal one, often requiring more than just external advice or intervention.

In the end, the battle against the illusion of success in the market is not only about financial acumen but also about understanding the psychological traps that lead many astray. For those caught in its spell, recognizing the illusion for what it is represents the first, crucial step towards freedom.

For various reasons, from bruised egos to genuine curiosity, some might question my stance on market participation, wondering why I remain active in it.

I'm tethered to the market until my final days. Entering the market makes leaving more complex than it appears, resulting in many returning despite their best efforts. My enduring involvement isn't merely a stroke of luck but the result of various factors: a natural yearning for constant learning, a deep interest in technology, a supportive partner offering profound insights and steadfast backing, life's trials that have finely shaped us, and a level of resilience that's challenging to describe, even considering obsessive-compulsive inclinations. Don't misunderstand; my path has been paved with hard work, not merely serendipity. My fortune lies in having the ideal conditions.

This discussion aims to highlight the nearly impossible odds required for mere survival in the market. Success in this arena isn't about additive probabilities but rather a multiplicative, complex equation that challenges even the most sophisticated AI.

Indeed, a select few profit in the market for reasons varying from luck to hard work, talent, connections, insider information, and, regrettably, manipulation or outright fraud. However, long-term viability in the market favors those with incredibly favorable conditions. Winning in the market is akin to winning the lottery: not everyone can claim victory, despite the presence of weekly winners. The uncontrollable factors must align perfectly for success, much like the intricate dance of infinite-sided dice in a game of vast complexity.

The question then becomes, with so many uncontrollable factors at play, how can one confidently claim the ability to succeed in the market? The market itself is a dynamic, evolving entity, increasingly complex with the integration of AI, making the odds ever more daunting.

My hope is for individuals to find the reasoning to step back from the market.

However, I realize that certain individuals, like the professor, are unlikely to be swayed, deeply ingrained in the market dynamics from the moment of entry.

This acknowledgment brings a profound sadness, reflecting the challenging reality of our deep-seated engagement with the market.

Regardless of your perspective, be aware of the illusion you're ensnared in. Imagine being a puppet, with unseen masters pulling the strings in a vast and intricate market network. If you believe you're exempt, that belief is merely another manifestation of the enchantment.

AI, like any tool wielded by humans, has a dual nature; it can serve beneficial purposes or harmful ones, with the financial markets being no exception. If the market contains individuals akin to "John Wicks," who can turn even the simplest of tools into formidable weapons, it remains a perilous environment for newcomers or even hardened veterans.

Truthfully, the market already hosts numerous such adept players, wielding AI like masterful weapons. Under the guise of being the market's champions or fulfilling its demands, they are the ones who truly grasp its intricacies, able to sway it for their own gain.

Indeed, appearances can be incredibly misleading.

In the context of the market, there's one principle to keep in mind: deep down, we're all greedy bastards.

 