# Algorithms-for-DS-UW

## Task1
Task:
'Input: positive integers m, u, c, a list regist_times containing the registration time of each of the u many users, and two lists start_times and durations containing the start time and duration, respectively, of each of the c many advertising campaigns.

The i-th campaign has the start time start_times[i] and the duration durations[i].
All time values of the input (regist_times, start_times, durations) are minutes in the range from 1 to m.
A campaign that starts at minute x and ends at minute y has duration y-x+1.
We say that a user registered during a campaign if the user registered between the start and end time of the campaign.
The peek of a campaign is the first time when at least half of the users registered. In other words, if n is the total number of users that registered during a campaign that starts at time x, then the peek is the first minute z such that the number of users that registered between x and z is at least n/2.
The task: For each campaign, compute after how many minutes its peek is reached.

Output: A list of c integers (for each campaign, time to reach its peek).'


## Task2
Input: positive integers p, n, m, a list a[0..n-1] containing n non-negative integers, and a list b[0..m-1] containing m non-negative integers.

The grid cell (i,j) is filled with value (a[i]*b[j])%p. (% is the modulo operator.)
Neo is at grid cell (0,0).
Every grid cell with coordinates (n-1,j) (for 0 ≤ j < m) is an exit point.
Neo can move only to the right (from position (i,j) to (i,j+1)), or to the bottom (from position (i,j) to (i+1,j)).
Moving to the right costs 2*x seconds, where x is the value of the target cell.
Moving to the bottom costs x seconds, where x is the value of the target cell.
The task: For each exit point, compute how fast it can be reached by Neo.

Output: A list of m integers (numbers of seconds to reach each exit point).
