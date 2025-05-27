# Prize Pool
- Epitech Hall of Fame
- Zappy custom Sweats

# Rules
- `cd zappy_ai && make` will create zappy_ai binary `./zappy_ai/zappy_ai`
- must run natively on epitest docker
- must be at least able to get to level 6
- A.I name will be placed in a dedicated file `./zappy_ai/ai_name.txt`
- A.I name should be ASCII Alphanum letters only
- A.I name should be T.O.S compliant (no offensive names etc...)

# Tournament parameters (may change if required)
- map size: 30x30
- game time: 5 min
- initial nb clients: 3
- initial seeding: swiss round
- live tournament: 1vs1 match, BO3 and BO5, winner/loser bracket format


# Victory condition
- First A.I to reach level 8 wins the game
- If no A.I was able to reach level 8 at the end of the game, the winning team is the team
with the higher level.
- If both teams are at the same level, the team with the highest number of A.I alive at the highest level wins.
- If the number of A.I at the highest level is equal, the first team to have reach that level wins.

# Notes
- Exploiting the server in a intentional malicious way (fork bomb, OOM, unsupported encoding) is not allowed and would result in a ban.
- If you think you found a bug, double check, it's a feature.
- If you still think you found a bug, please contact me at <christophe1.sundas@epitech.eu>
