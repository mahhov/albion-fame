# Albion Fame

A [tool](https://mahhov.github.io/albion-fame/) to help plan your combat specs.

Now that everyone is fame farming, maybe some of you are wondering whether it's better to get e.g., elite level 120 on your main gear, or level up the other gear. Or when you should use your learning points. Or how much fame credits you need to max everything out.

- The left side shows the efficient levels for each gear to maximize IP/fame.
    - E.g., You get more IP/fame leveling your artifact gear up to 11 than leveling your main non artifact gear past 105.
- The right side shows the fame, fame credit, learning point, and silver costs of leveling.

![screenshot](screenshot.png)

## Guide

### Fame per IP (left)

This column will help you decide what spec level you want on all your items. E.g., if you're leveling your cleric robe to 105, you want your non artifact robes (e.g., mage robe) leveled to 35 and your artifact robes (e.g., druid robe) leveled to 11.

#### Game mechanics

Leveling gear spec gives you IP for that gear as well as similar gears; e.g., leveling any robes will give your cleric robe IP. You get 0.1 to 2.2 IP per level depending on a) whether the gear is artifact (e.g., druid robe) or not (e.g., mage robe) and b) whether it's the main gear (e.g., cleric robe) or just similar gear (e.g., druid robe). In general, leveling your main gear is most efficient, then your non artifact similar gear (e.g., mage robe), then your artifact similar gear (e.g., druid robe).

However, the higher level you have in a particular gear, the more fame it requires continuing to level; efficiency decreases. So rather than level one gear (e.g., druid robe) to 16 and other gear (e.g., fiend robe) to 6, you'd get the same IP with less fame if you leveled both to 11. This is why it's inefficient to simply focus on your main gear (e.g., cleric robe) until it's maxed, then move on to you non-artifact gear (e.g., mage robe), then your artifact gear (e.g., druid robe).

#### UI

1) At the top, there are 2 inputs.
  - 1st, select whether your main gear is artifact or non-artifact. E.g., if you're maximizing your cleric robe IP, select 'non-artifact'.
  - 2nd, select the combat spec (not mastery) for your main gear. This can be your current spec, or the spec you plan to level it to, or any other spec you're considering.
2) Below the inputs, you'll see 2 lines summarizing the most efficient spec for your other robes. Following the recommendation will maximize your IP per fame.
  - E.g., when you have 105 spec in your cleric robe, for maximum IP efficiency, you should have your non artifact robes (e.g., mage robe) leveled up to 35, and your artifact robes (e.g., druid robe) leveled up to 11.
3) Next, we have a table showing the fame required for each additional IP. Green values indicate IP efficient levels that you should level up, white values indicate inefficient levels you should hold off on.
  - E.g., if leveling up mage robe in the 16-23 range requires about half a million fame per IP. This can help guide you when to switch between your artifact and non artifact gear and how inefficient it would be to slightly bend the recommendations.

Disclaimer, the recommendations aren't hard rules written in stone. Going a few levels less or more than the recommendation isn't a big deal, especially since some gear is easier to level than others. The recommendations are guidelines.

### Fame Cost (right)

This column will help you predict how much fame, learning points, fame credit, and silver it will cost to level up a spec from a certain level to another level. E.g., leveling a realmbreaker from 105 to 115 costs 21.6m fame and 6.5m silver.

#### Game mechanics

Leveling gear up to 100 requires fame. The fame cost can be decreased by 80% if you supplement learning points. Alternatively, fame credits can be used. Leveling past 100 for elite levels requires no fame, but instead fame credits and silver. Learning points can't be supplemented for elite levels.

Learning point efficiency increases with level. E.g., at 15 spec each learning point supplements 8k fame, while at 86 spec each learning point supplements 15k fame.

Fame credit costs depend on gear slot. E.g., feet gear cost 4x less fame credits than 2h weapons, for both non-elite and elite levels.

#### UI

1) At the top, there are 2 inputs.
  - 1st, select the gear slot. E.g., if you're leveling realmbreaker, select '2h weapon'
  - 2nd, select the level you are considering leveling it to.
2) Below the inputs, you'll see 2 lines summarizing the cost of leveling the specified gear slot to the specified level.
 - E.g., leveling a realmbreaker from 105 to 115 costs 21.6m fame and 6.5m silver.
3) Next, we have a table showing the costs for each level along with the learning point efficiency for non elite levels.

## Credits

This wouldn't be possible without [broderickhyman/ao-bin-dumps](https://github.com/broderickhyman/ao-bin-dumps) and phendryx.
Thank you!
