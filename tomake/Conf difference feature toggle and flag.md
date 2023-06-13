

# For business
- goal: enabling (or not) a feature on a defined scope (environnement, BU, country, sub-set of users..), on a defined timeframe
- long/mid lifetime
- business has access on it
- business is responsible for it
- is the implementation of A/B testing

# For dev
- goal: allow to push code faster (because disabled) on production, and optionaly allow to test for longer time in test environnement
- short lifetime (< 1 week)
- only dev has access and knowledge of it (this is not business matter)
- dev should not ask permission for it (antipattern)
- dev is responsible for it
- is one tool of Trunkbase developement
- should be included (de-facto) in feature workflow (first step is designing the US, last step is to remove the flag) => so you don't forget it !
