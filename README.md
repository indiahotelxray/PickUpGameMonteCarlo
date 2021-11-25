A quick analysis of a pick-up basketball group's method of choosing teams.

# Background
I was playing in a pick-up basketball group that choose teams based on sequentially shooting free-throws.  I wanted to see if the method used to pick teams was biasing towards stronger teams.  

The method to pick teams consisted of:
- Randomly line up players, shoot free throws in order.
- The first four successful free throws got on one team.
- The next four on the second team.
- The remainder playing the winner of the game between the first two.

Alwas being stuck on the last team and watching the first team always seem to win due to higher skill, I wanted to see if we could switch this up.

This was a quick project and the code is not well organized.  Please don't use it for anything serious.

# Methods
Randomly simulate picking teams with a binomial distribution.  Test different methods of assigning teams (sequential versus alternating teams)

# Assumptions
I really have no idea how to play basketball, nor do I follow the sport in any seriousness.  My guess at free-throw skill distributions is probably totally off from reality.  I also assumed that the average free-throw skill was representative of the team's overall skill, which is a gross simplification.

# Results
We switched to alternating first and second team when shooting for free throws.  While I didn't measure it, the couple of seasons we played since (before COVID) seemed to result in the first-team having fewer runs where they get to stay on the court all night.