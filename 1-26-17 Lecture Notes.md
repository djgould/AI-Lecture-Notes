# Lecture Notes
---
## Reflex Agent
* Reaction based on current inputs
	- No planning ahead
	- "Go to nearest dot"
	- Fails in complex situations
---

## Planning Agents
* Ask "what if"
* Makes decisions based on consequences of actions
* Must model world that evolves with action
* Complete Planning
	* Guarantees solution
*  Optimal Planning
	* Tries to get best solution
* Planning Vs Replanning
	* Replanning
		* Plans short term steps then replans after actions
		* Might not get optimal solution

---
# Search Problems
- A search problem consists of:
	- A state space
		- 3 x 3 board has `(2 ^ 9 ) * 9 = 512` permutations
