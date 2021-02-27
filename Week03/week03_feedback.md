Part 1:  5/5

Part 2:  3.5/5

14.3 - 

Remember that the `range(start, end)` function does not actually include `end` in the results.  So, you have some length of stay conditions that don't quote work.

Your syntax also took a bit of a wrong turn here with you adding extra `def LACE(...)` lines in the middle of your function.  Each time you type `def LACE(...)`, you are telling Python that you want to erase and rewrite the definition of the LACE function.  As a result, the only LACE function that exists at the end of your code there is the last one, the one that only takes into account the `ed_visits`.

You very much had the right idea here, though.  Instead of returning "score += #", though, just keep adding up the score.  When you `return("score += 1")` it actually returns a string with all the characters "score += 1" rather than actually doing the math you want it to do.  -1


14.4 -

Similar pattern here, but your logic is basically correct. -0.5


14.5 -

Similar pattern here, but your logic is basically correct. -0.5