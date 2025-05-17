Think like a game...
You take some finite steps, the game will end. Then if you start, you start from scratch with no previous memory
This are called episodic tasks

The final state in an episodic task is called `Terminal State`
Time needed (Step needed) to Terminate is a Random Variable

Example:
- Chess (Final Step is ending the game)
- Maze (Final Step is completing the maze)

We can construct a natural [[Expected Return]] formulation
$G_t = R_t + R_{t+1} + \dots +R_{T}$
This is different than [[Continuing Task]] Where we cannot create this simple formulation