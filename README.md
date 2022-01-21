# For from Giseldah.github.io

The goal is to explore the posibilities of expanding Giseldah's work.

I would like to explore:
- Add weight to each percentage: how important is it to reach.
-- It could be a target%-value (a range without min%),
-- a range (min%-value and max%-value) where anything bellow min is not accepted or 0 and over max has no more value,
-- or a function to smooth the value (like logaritmic so the last 1% is not as important as the first 1%)
- Add an item database
-- the items can be evaluated against the target values to see how much each item adds to the objective
-- restrictions like instance tier, reputation, crafted, missions, embers, etc. so the set of ideal items can be restricted to the ones accessible to the user (I don't need lists full of embers or tier 4-5 items when I have just reached the cap level)
- Selecting equipment and virtues manually
-- First step before the optimisation algorithm, to evaluate a build against the target
-- Save the combination as a URL so it can be shared or saved as a link
- Optimisation algorithm to suggest equipment and virtues
-- It will take the items after restrictions applied to find the best combination including essences
-- Item sets will be a challenge to generalise
-- Essence triggers will be a challenge to evaluate
-- Should consider base values and stat tomes
-- Suggesting traceries will be a nightmare, first approach is selecting them manually
-- Iterative approach, adding one type of item each iteration, to move from manual to automated
-- Being able to force specific items
