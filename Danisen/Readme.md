# What is Danisen?

Danisen is a FT5 ranking ladder run in SGOCE. The ranking rules are as follows.

- There are 5 ranks: S, A, B, C, D, E
- People can play each other within ranks to gain points. The winner of the set gains one point and the loser of the set loses one point.
- You can only gain points from beating people within +1/-1 rank of you. You can only lose points from losing to people at most one rank above you. Example: If an A rank player and a D rank player play, and the A rank wins, then they will not gain any points and the D rank player will not lose any points either. However, if the D rank player won, the D rank player gains one point and the A rank player loses one point.
- The thresholds for S rank and E rank are unique, however all other ranks will require a cumulative gain or loss of 5 points to improve or worsen. Example: A player at C rank could start off at 0 points, lose 4 relevant matches and get down to -4, win 3 points and get up to -1, and then lose 4 matches in a row to be at -5, at which point they would be demoted to D rank.
- At E rank, you need a score of +1 to graduate to D rank, and you cannot accumulate a negative score. The threshold for E rank is thus (+1/0).
- At S rank, you cannot accumulate any points, and losing any match will cause you to lose S rank. The threshold for S rank is this (0/-1).
- Matches for Danisen can be arranged at any point. Tournament rules apply - the winner is locked into their team and assists, but is allowed to change team order.
- When a Danisen set is played, the winner submits it to #danisen in the following format

```
[danisen]
(winner name) vs (loser name)
(winner's team) vs (loser's team)
(score)
Replays: [Link the replays here in a ZIP, format the replay folder with the following format: VictorName_vs_LoserName_DateOfSet]
```

# I heard there is weekly matchmaking for Danisen. How does that work?

We use Neffytron to help do weekly matchmaking for Danisen.

- Sign up to get weekly matchmade (?) in #danisen or #bot-commands using the command `!danisen set x` where x is the maximum number of sets you want the bot to find for you. The bot currently only finds up to 5 matches for one player.
- To sign off from weekly matchmaking, you can use `!danisen set 0` so the bot does not give you any matches for that week.
- Matches are rolled every Tuesday 9:00 AM AEST.

# What is Danisen night?

The latest addition to SGOCE weekly events, Danisen night is hosted every Wednesday night (9:00 PM NZT to 11:00PM NZT) and is a time for people to come together and play some Danisen matches, possibly on stream. I (chimps) host the stream, commentate and can provide feedback on live sets played.
