# Review Checklist

## Before choosing what to review

- It helps greatly that you have a direction and topic in mind before choosing what to review.
- Knowing the topic well has a big impact on whether you'll be a good reviewer
or not. With that in mind, it may be worth noting your own confidence level with
respect to any points that you make if you're unsure on them.
- Don't only consider if the paper would be interesting to you, consider if it would be interesting to the *field*.
    - Rejecting an important new idea is worse (for the field) than accepting a mediocre one.

## Summary

- Briefly describe the contributions of the paper in your own words. If you can't, you don't understant it enough to be accepting/rejecting it.
- Note why the paper is interesting to the research community.
- 1 to 2 sentences per section of the paper is sufficient.
- Mention any discrepancies between the contributions claimed by the authors and
the actual contributions from your point of view. If you're wrong about that,
don't worry too much because the authors will have a chance to rebut.

## Strengths

- A runtime analysis might be a good thing to have in a paper. Not that you should necessarily always ask for this as a reviewer, but it's nice to have.
- Beating the SOTA is not always necessary - you could have worse performance
than the SOTA yet massive improvements in algorithm/time/space/etc. Likewise
better numbers alone are not always noteworthy because they could have just
thrown more data/compute at an old method.

## Weaknesses

- When noting any weaknesses, provide solid evidence and arguments for your
claims. The paper authors try to make a bulletproof argument in their paper, so
you should try to do the same with your review.
- If they say something has been done before, they should cite that.

## Suggestions

- Could all the work be reproduced from the information in the paper? If not, they haven't given enough detail.
- Include suggested publication alternatives, if applicable.
- If they should have better references, experiments, or diagrams, note that.
- Don't just say something is wrong, let them know what should be different.

### Importance/Relevance

- Is the problem clearly stated and motivated?

### Novelty/Originality
- Novelty is desirable but not always quantifiable/defined/clear-cut.
    - New questions.
    - New solutions.
    - Better analysis.
    - Better results.

### Technical Correctness

### Experimental Validation

- Are results shown with error bars, so that conclusions are statistically significant?

### Clarity of presentation

### Reference to prior work

- Should not just have them, but they should be the most up-to-date ones for a topic.

## Ratings breakdown - Overall evaluation of the paper

- Should be based on scientific robustness, not your personal taste.
- You want to judge and note the magnitude of the contribution. This make take significant experience in the field to do well.
- Consider sorting by importance.
- Are all claims validated?

## Misc notes

- Know that most papers were written under deadlines so there is probably something wrong with them.
- Are the limitations and drawbacks clear? They should be noting failure cases. You should be able to tell "what is the box within" this thing operates.
- When you ask questions for their rebuttal, you should not be asking them to
produce new results or conduct additional experiments, just to explain things
better.
- Highly consider using a tool like Acrobat to mark up papers.
- Read the reviews of other reviewers too, but only after writing your own so as to not bias your own review.
- Ensure you don't have a conflict of interest in reviewing the particular paper.
    - If you are not a person who can do a fair review of a paper, let the area chair (AC) know ASAP.
- If possible, avoid looking at the names of the authors beforehand to avoid bias from:
    - Any personal connection you may have.
    - Race.
    - Gender.
    - Etc.
- Ideally this is a dialogue with the authors, but in practice it will just be review -> rebut -> final decision.

## The 3-pass approach (S. Keshav - How to read a paper)

- Idea is to get a bird's eye view before drowning in the details

### First pass

- Should take about 5-10 minutes
- Get general idea of paper
- Carefully read
    - title
    - abstract
    - introduction
    - section and subsection headings
        - ignore everything else
    - conclusion
- Glance over the references, mentally ticking off ones you've already read/discovered
- At the end, you should be able to answer the 5 Cs:
    - Category
    - Context
    - Correctness
    - Contributions
    - Clarity
- At this point, you might choose not to read any further

### Second pass

- Should take about 1 hour
- Grasp content but not details
- Ignore proofs
- Make comments in notes or margins as you read
- Look at figures. Graphs should be labeled properly and have error bars
- Mark relevant unread references for further reading (i.e. decide which references are worth reading/skimming yourself)
- Should be able to summarize the main points of the paper, with supporting evidence, to someone else, even if this paper topic is not your specialty
    - But you may not necessarily understand the paper at the end of the second pass. It's fine to set it aside for later

### Third pass

- Can take about 4+ hours
- Understand the paper in depth
- You are virtually reimplementing it
    - This allows you to spot its hidden failings and assumptions
- Jot down any ideas for future work
- Identify implicit assumptions, missing citations or relevant work, potential issues with experimental or analytical techniques

### Doing a Lit Survey (may become it's own list in the future)

- Google scholar
- CiteSeer
- Find the 3-5 most popular papers in your area, do one pass to get a sense of the work, then note down the references and authors. These are the key works and researchers in the field
    - Go to websites of key researchers and see what/where they've published recently
- Keep an eye out for survey papers
- Go to websites of top conferences in your field and look thru the recent papers
- Recursively find more works as you read the papers