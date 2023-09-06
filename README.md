# -Travelling-Sales-Person-problem using Dynamic programming
d[i, j] = min(d[i, j], d[i, k] + d[k, j])

Traveling salesman problem is stated as, “Given a set of n cities and 
distance between each pair of cities, find the minimum length path such 
that it covers each city exactly once and terminates the tour at starting 
city.”
