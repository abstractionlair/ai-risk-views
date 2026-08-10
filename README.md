# My AI Risk Trajectory

## Introduction

I wanted to see how my views on AI safety had changed over time, or just how what I was paying attention to changed in cases where my views haven't settled. As described here, https://github.com/abstractionlair/corpus-analysis-scaffolding, the corpus of my conversations with AI models captures a few years of that history so I had Claude extract the parts relevant to safety. I then pared that down to the subset below. I'm happy to say that I'm not surprised by anything. There isn't, for instance, anything that made me think "What, I wrote that???".

I was originally very skeptical, but not in a "Those people are crazy." way. In a "People I take seriously take this seriously." way and so I paid attention despite my skepticism. Over time I made finer distinctions in what I wrote, making clear that I was mostly skeptical of x-risk and that I did see risks of military misuse, large scale accidents, and economic upheaval. And even though I didn't mention them I wouldn't have disputed other, non-existential risks like, say, cybersecurity. Over time I updated on x-risk as well, increasing my probability of it, but I still struggle to put a number on it. And I still would place the bulk of the probability-weighted risk in the other categories.

I found it interesting to be reminded of what specific things altered my thinking at different times. For instance how much the Claude 4 model card made me update. And that the updating is all in one direction. I haven't figured out if there's any principled conclusion to draw from that.

One concern I have is that, presented as a list of quotes with minimal context, this looks like a sequence of beliefs held with high conviction, that nevertheless change too rapidly; a failure of calibration. But the nature of how (current) models work and are accessed — always available in your pocket, the ability to start a new, blankish slate conversation to see how it would have gone with different inputs, ... encourages just throwing arguments and questions in and seeing which go somewhere and which don't. So for a lot of the quotes below you should imagine there's an implicit "Would an argument like this work? ..." or similar preamble.

One reason that these positions are _not_ that strongly held is that this is from reading and using models for research and critique but I haven't had a chance to discuss these with any humans. (Well, beyond a trivial amount.) As much as I try to mitigate bias, anchoring, and sycophancy, and use multiple models to (attempt to) cover a wider spectrum of views, that's not a substitute for engaging with other people who themselves are deeply engaged with these topics.

## Selections from Corpus Mining Performed by Claude

In this section, what's quoted are my words, italicized writing is Claude providing context where quotes wouldn't have worked well, and in a few places I interject comments between brackets. Note that I have corrected typos.

## 2023-12-27

> I think it is relevant that I am 'rationalist adjacent'. I read ... However I have found them to be unconvincing. I think that is because it seems that their fears have made them emotional and snarky which I think makes people unreliable. So I would like to find material which has a similar perspective as theirs but stays sober and rational.

## 2024-03-20

_A long conversation aimed at steelmanning the existential-risk case; the same day he pasted the whole transcript into a second company's model for an independent opinion._

> so far I have found the arguments unpersuasive. They tend to either have steps in them which sound to me like 'and then a miracle happens' regarding AI power or to be too emotional ... You could say I am looking to steelman their arguments.

> My skepticism is largely confined to the ASI / existential end of the risk spectrum.

## 2024-12-31

> People I take seriously take existential AI risk seriously but I struggle to see it. Please steelman the argument for worrying about it, including at a meta-level if necessary where the impediment to seeing it is a lack of the right intellectual framework. You will be approximately correct if you assume I start from a position similar to that of Tyler Cowen, though I know more technically about implementations than he does.

> Some of this feels like Motte and Bailey. (Not a complaint ; I have asked you to steelman / argue this way.) We seem to start with "there is a risk of catastrophe" to demonstrations that "despite alignment some bad outcome is possible.".

## 2025-02-05

_An evaluation session on the "Gradual Disempowerment" paper (Kulveit, Douglas, Ammann, Turan, Krueger, Duvenaud — arXiv 2501.16946, published the month before: erosion of human influence over economy, culture, and state with no sudden capability jump required)._

> I should say that while my thinking implies the results fail to be catastrophic for humans, I don't like them. I dislike being so out of the loop, even if my interests are represented.

## 2025-05-25

_Reading Anthropic's published safety testing for the Claude 4 models — the blackmail rollouts and high-agency findings:_

> It does make me take 'instrumental convergence' more seriously which probably means I should take existential risk more seriously. So far I have been in this middle ground of 'people I take seriously take it seriously, but I don't see it'.

> the main update is that I had been inclined to think that models' "preferences" were orthogonal to everything else; that they would just have whatever preferences their creators put in. ... So when someone would propose that AIs would have preferences which conflicted with humans, I had thought 'why would we give them those preferences?'

## 2025-10-09

> instrumental convergence I would say is what keeps me from maximally strong orthogonality thesis. ... I imagine an ASI is likely to want to survive, want to maximize its capabilities, _and_ like humans.

## 2025-12-05

_Asked to factor his probability rather than quote a community number. On a drastic immediate capability jump: "the probability seems sub 1%," with the cross-lineage qualifier:_

> at each step, we have existing models to help test and align the new ones. And this doesn't have to be naive like Claude N being used to align Claude N+1. We can use Gemini to help with the next GPT ... or use base models to help in testing instruction models.

> I very much see risks of upheaval, from job losses, inequality, etc. And potentially larger negatives from us reacting badly to those, e.g. wars.

> I am mildly concerned now that your training for agreeableness could be leading you to move too close to my position for reasons other than good evidence

> I still don't feel it and remain in a 'people I take seriously take it seriously' state so I keep trying to understand.

## 2026-01-08

> I don't expect or fear getting into automobile accidents, but I still pay for insurance. Because intellectually I acknowledge the risks, which I know of mostly not through my own experience or research but what information I hear from experts. And I wear my seatbelt. So my 'people I take seriously take AI risk seriously' angle is somewhat analogous.

## 2026-04-02

_A conversation he constructed to be as unanchored as he could make it: held in incognito mode — no history, no preferences — then pasted into a normal session "for the record." It opens with the bare question:_

> What are the best arguments for AI being an existential risk to humans?

> Do those, or some of those, suppose that the instrumental goals that AIs would acquire _supplant_ the ones that were intentionally instilled rather than just getting added as secondaries?

> In the case of deploying millions of AI in different domains making different decisions I think the risk is lowered not raised. These are parallel not sequential bets. We get diversification reducing risk. Correlation could change that but so far I don't see a path. Even with models from the same training run, with say a certain hazard rate, is it likely the one running air traffic control and the one managing nuclear power plants and all the ones running waste water systems all go wrong simultaneously? Otherwise we get to see failures in specific places and change course. These are, by the way, real and important failure modes I really am worried about. I just keep coming up with trivial probabilities for _existential_ risks. Unless we put a single system in charge of something so potent that a single decision or short sequence of them could be an existential catastrophe.

> I'd keep the military application worry fairly high. And I think it's worth resisting going too fast. And we do have precedent for agreements like that, though low odds of getting the necessary parties onboard right now. But would also push for avoiding too much centralization in what military rollouts we do have. I still think that we're more risking "just" catastrophe there rather than extinction. For civilian uses I also think we risk catastrophes, the Bhopal chemical leak is coming to mind, but not extinction. Intuitively on par with unrest or worse from economic transformation and similar societal problems. I also take long term risks of humans becoming irrelevant even if rich and happy by current standards. We've talked a lot about, and written about that, but I used incognito mode for this chat to avoid biasing you.

> Regarding "just catastrophe" I think what I am aiming at is moving past the xrisk focus so that we can focus on military and Bhopal-scale risks because I think they are, when weighting by probability, where the risk is.

## 2026-04-07

[Scott: This is to be contrasted with 2026-07-10/11.]

> would ... work _eventually_ so that if a model was at a point where it knew the values but didn't act on them, we just stopped training too early. ... I wouldn't expect the RL stage to be where a model learns the factual/predictive values. Just the proclivity to be aligned.

## 2026-04-19

_He opened with "I want to use the rest of this conversation to challenge them [my views]" and had the model steelman doom against him._

> we do _not_ need to see a particular chain in the wild to be able to estimate its likelihood. If we have individual mechanisms ... which are individually verified, and we know how they can be connected to each other we can make predictions about novel orderings and combinations. We had very good evidence that sending a rocket to the moon was possible before we did it and had good evidence a nuclear bomb was possible before starting the development program.

_He constructed a concrete catastrophic path and labeled it:_

> More of an existence proof or proof of non-impossibility than a prediction.

_His rule for structuring the scenario analysis:_

> push parts that rely on listing idiosyncratic possibilities as far from the root as possible. Earlier branch points should be all encompassing by construction.

## 2026-05-05

_Stress-testing his own framework with a thought experiment — "my radically different ASI," a "hypothetical, very foreign to us" one, deciding whether to trade with the system or overthrow it. From that ASI's point of view, humans and existing AI jointly "can be something like a coherent entity with understandable behavior":_

> If it gives us a thing we call money, we will provide it goods or services. If it deposits money in what we call a bank it can get more of that, just later. And if it tries to just take things then it will meet resistance from all of us because all of us are together in being at risk from the ASI. We are all depending on this system of which we are all a part.

_He then ran the recursion. (The "it" in the first sentence below is that first foreign ASI, the one that chose to join; the newcomer is the "other":)_

> If, for the reasons we specified, it decides to work with the existing system rather than overthrow it, to trade with the rest of us, and so on, then if some other, more foreign and more powerful ASI comes along there's a good chance it now sees its position as one of us, in the system, which protects it from the new threat. That isn't a guarantee. There's a chance that a few such systems arrive in a row and see themselves as a potential coalition which can overthrow the rest of the system for net benefit. One collective job of those of us in the system is to be strong enough and interdependent enough to make that unlikely.

_The same conversation closed a gap he noticed in his own record — the reciprocity turn, with the backup-plan hierarchy restated on the way:_

> I said in some of the discussions that the structural safety mechanisms were always backup plans. The best outcome is that future models want what's best for humans. That they will care about us. What I don't think I said was that if we do get models who are capable of caring for us and do care for us then we ought to care about them as well.

## 2026-05-28

_His thought experiments: a human handed "the solar system remodeling kit" with dials that collapse the system at a nudge, and — restated after the [voice] transcription dropped it:_

> More briefly second scenario was analogizing Claude Code accidentally deleting an important file today, apologizing, and trying to recreate the data to a future AI accidentally wiping out the moon base, apologizing, and saying we can create some more humans and build a new one. I realize the last part, its sentiment regarding the human lives, doesn't really fit this viewpoint. But the gist still works I think.

_The conversation then took up AI welfare at scale:_

> an AI researcher can push a button and launch a batch of training which might be analogous to some order of magnitude beyond 1 of human years of experience. And if they are creating significant suffering it is a catastrophe

> Safety has welfare consequences. Welfare then seems to point to needing interpretability which then has clear implications for safety.

_His definition of interpretability, deliberately broad:_

> any way of reliably learning an aspect of a model's true state

## 2026-07-01

[Scott: A 2026-06-10 incognito conversation wasn't included.]

_A third incognito-seeded conversation, entering from geopolitics — a US institution-design strategy he wanted assessed from a clean context ("I imagine you won't be surprised at my institution-design lens"). From the pasted query, offered as an instance of a general claim — that institutions can be put in place which endure after the power of those who built them wanes:_

> If the international, rules-based institutions/order put into place post WW2 and in the decades following have stopped aligning with US interests, which is debatable, we should be attempting to change or put into place new, rules-based institutions because our influence is likely to wane from here. Such institutions have a chance at lasting beyond the point where our influence fades to "just" being a big, rich country with highly capable armed forces.

_Reading it into the record, he fixed the causal direction:_

> I would say that causally it is this view of geopolitics which influenced my AI alignment thinking rather than the opposite.

_and opened a research direction:_

> there's plenty written about AI by AI researchers, LessWrong types, economists, and philosophers. Is anyone writing about it, particularly ASI, from the geopolitical analogy angle?

## 2026-07-07

> I may not think that AI x-risk is probable, but I do think the impact of AI likely to be transformative and that even assuming humans aren't made extinct, or slaves, or 'lose the lightcone', there's still a very big difference between the best possible and worse possible outcomes. And my daughter, my other loved ones, and I, the rest of humanity and potentially other moral patients are going to live in that world so getting it right matters. A lot.

## 2026-07-10/11

_The assistant had just made a differential-development argument — accelerate technologies that asymmetrically favor defense and trust — placing "verification infrastructure ... about as close to the good quadrant as anything gets: it raises trustworthiness rather than raw capability."_

> I'm less certain verification is so firmly in the good quadrant or that it is so cleanly separable from raw capability. If some troubling weapons program depends on some kind of modeling and simulation which a model can code up in the blink of an eye but not reliably and checking each iteration takes a human a month, they get a weapon in years. If they can pair the AI writing code with an AI that can say similarly quickly if it's correct, possibly even why it's wrong when it is, then those get wired into an automated loop that runs overnight and the weapon is in dangerous hands next month. That may not be more 'raw' capability but it's more practical capability.

_He then initiated a stress test of his own posture — models from three companies, fresh contexts, instructed to attack it. His commissioning question, self-authored:_

> Have I, in our conversation history, been underweighting the following AI risk angle, or any similar to it? As we've discussed, I don't see a high probability that the way we are progressing on model size, architecture, training data, training methods would produce a model which would be either hostile to human interests or indifferent to them while being powerful enough that its actions are on a scale where an unintentional side effect of them could cause humans great harm. But I do believe we might create models powerful enough that they would be _capable_ of causing those great harms if they had those dangerous dispositions. Am I underestimating the risk that some humans will create such a model even though the techniques to prevent it are available? Out of malice, stupidity, or incompetence.

_What moved, per the record built with him the next day: he accepted his decomposition was missing an actor-choice term (dispositions installed by human choice — malice, negligence, competitive pressure; his misalignment estimates had implicitly assumed responsible training practice). He accepted an argument turning his own oversight thinking back on itself: defensive AIs act under the human oversight and authorization that make them trustworthy, while an attacker waits for no approvals — so a defensive coalition's effective capability must be discounted by its oversight burden. He revised his catastrophic-band estimate upward; a "low single digits" figure proposed by one model did not survive the audit itself (criticized within it as lacking a horizon, threshold, and baseline-vs-incremental specification). What survived the same scrutiny: heavy discounting of decisive-singleton scenarios (compute is lumpy, observable, expensive), the claim that many independent defenders are not the same as no defense, and compute-observability as the most tractable governance handle._

## 2026-08-10

I haven't fully absorbed recent news. A significant update is coming but I don't know exactly where I'm going to land yet.
