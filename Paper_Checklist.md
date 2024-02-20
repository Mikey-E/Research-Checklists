# Paper Checklist

## General

- Remember that publishing only the really exceptional papers will help your
career that much. Bad ones may even hurt it depending on how bad. No doubt there
is a power-law distribution here. However perfection is only ever reached thru
practice, so don't be discouraged. Your portfolio over time will have mostly
prosaic papers and some that are significant. None should be sloppy nor
methodologically weak nor misleading.
    - It's better to be one of many authors on a great paper than to be one of just a few on a mediocre paper.
- It's tempting to feel like "more" is better. This is often false - simplicity
is usually better. Have every word matter. "For every sentence, consider
deleting the whole sentence." Quality over quantity the whole way. Research
communities don't need more quantity. In that sense some papers make a negative
contribution; they add to the noise but not signal.
    - LLMs (ChatGPT et al.) can help re-write a paragraph you've written in a
    shorter form. But keep in mind you may be asked if AI was used to generate
    any part of your paper (as a simple yes/no without you having the
    opportunity to explain).
- It should be easy to get the gist of the paper in a big hurry. Remember that
the vast majority of researchers in the community will only ever see your title,
figures, results, abstract, *in that order of frequency*. An infinitesimal
minority will actually read the wall of text you've made. Write with that in
mind.
- Don't oversell or hide drawbacks. This is a long-game.
- Sometimes you should "crowd the ball"; work on the popular thing. After all, the
popular thing is popular for a reason. But other times it's better to work on
something unique and not be the 99th deep-learning paper in a row that has made
its way in front of a reviewer.
- Write to *teach*, not to impress.

## Finding research directions

- Reimplement the SOTA
    - Reproduce the results, then bombard it with controlled experiements - look for surprises and cracks that lead to deeper realizations.
- Keep track of your favorite problems, revisit that list occasionally.
- Remember the overall goals of the research community. What are we trying to figure out or solve?
- Research should be a social endeavor. Be discussing and sanity-checking ideas with others.
- Research begets research. The more you do, the more avenues are opened up for you to do even more.

## Reasons papers are commonly rejected (from conferences or otherwise)

- Authors do not deliver what they promised.
- Important references missing. A reviewer may take that as an indication you're not familiar w/ the SOTA for an area.
- Results are too similar to previous work (i.e. getting 93.1% over the previous SOTA of 93% may not be considered original enough).
- Results are so unbelievably good that they are suspect.
- Poorly written (mistakes, incorrect statements, typos).
- Try to have one big idea per paper. More than one means the entire paper could
be rejected wholesale because there was a problem with one idea while the other
idea was spotless.
- Using weak baselines to try to make the gap in improvement look bigger.
- Tuning parameters based on results on a test set.
    - Instead use [nested resampling](https://mlr.mlr-org.com/articles/tutorial/nested_resampling.html) to get an unbiased performance estimate.

## Title

- Having a figure right by the title showing the most exciting result(s) is
great for immediately getting the point across. This is called a "teaser
figure".
- Will a title stick in someone's mind?
    - Will it be remembered 10 years from now?
    - Could it be meme-able like *Attention is all you need* and the variations that followed?
- Could your title fit on someone else's paper in the conference? If so, it's too vague.

## Keywords

- A keywords section may be helpful and worth having.

## Introduction

- Very important section because by the time a reviewer is finished reading it, psychologically they will probably already have formed and accept/reject decision in their mind.
- Have a justification for an approach.
- Tell them why they should care about your paper. It's not necesarily obvious. (Abstract/Intro?)
- State why other solutions aren't satisfactory. State why yours is better.

## Methodology

- Ideally read at least 2 different sources for a fair view on an issue/process/algorithm.
- Analyze bottlenecks. Really analyze what's stopping your thing from being better.
- Look for unwarranted assumptions.
- Look for the limitations. When will this break? How could it be done better?
- Write so that someone could reproduce these results.
- Have more than one dataset. If you have good results on only one, it may suggest you cherrypicked an unusual situation where your approach works well.
- Evaluate the contribution of individual components (Ablation).
- Have a precise description of how the params were set.

## Figures
- Be *generous* with figures. We *like* them. A picture is worth 1,000 words!
    - Consider: if you put all the figures into a slide deck, could you give a presentation about them? It might even be better to be able to give a talk about something before writing a paper on it.
- Captions should point out what to *notice*; what is *significant*. Not merely label the figure with something that's obvious just by glancing at the figure.

## Results

- Compare your solution(s) to others' and to baselines.
- If you have a new benchmark in your paper, you still want to compare to the
closest benchmark from before, and explain why your new benchmark is warranted.
- Should discuss the limitations of the model, including critical cases.

## Conclusion

- Talk about related work where similar techniques and experiments have been used, but applied to a different problem.
- Focus on the *significance* of the research.
    - Think carefully about the effect this will have on the world if the research is released. There is no uninventing a technology.

## Misc notes

- It's possible that a paper may be rejected yet go on to receive a tsunami of citations across time. This has happened before. i.e. getting rejected may be an indication that the paper is bad but it is not *proof* that it is bad.
- You can rarely propose a new kind of problem even if you can't solve it. This is a good thing to do, but generally don't make an entire paper out of it.
- Contrary to the belief of some, research *should* be personally meaningful. Without that, people tend to burnout and quit. It should be something you're obsessed with.
- There is an element of luck to research, but the luck only happens to those who were working hard to begin with.
- Insofar as you can manage to have someone mentoring you as you write, try to have mentors with a variety research styles.
- Should you publish a negative/bad result? If it is really rock-solid about
teaching researchers what is a *wrong* direction to go in, then you could
consider it. But if the way you went wrong is so idiosyncratic that it's of no
use to anyone, then probably not. The negative result should have generality in
order to be worth publishing.
- "Future Work" sections are bad. There's no credit for what you didn't do.
- Having a small subsection where the contributions of the paper are bulleted out may be good.