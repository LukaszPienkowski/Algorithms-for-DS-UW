# Algorithms-for-DS-UW-

## 01.04
Task:
'Input: positive integers m, u, c, a list regist_times containing the registration time of each of the u many users, and two lists start_times and durations containing the start time and duration, respectively, of each of the c many advertising campaigns.

The i-th campaign has the start time start_times[i] and the duration durations[i].
All time values of the input (regist_times, start_times, durations) are minutes in the range from 1 to m.
A campaign that starts at minute x and ends at minute y has duration y-x+1.
We say that a user registered during a campaign if the user registered between the start and end time of the campaign.
The peek of a campaign is the first time when at least half of the users registered. In other words, if n is the total number of users that registered during a campaign that starts at time x, then the peek is the first minute z such that the number of users that registered between x and z is at least n/2.
The task: For each campaign, compute after how many minutes its peek is reached.

Output: A list of c integers (for each campaign, time to reach its peek).'
