# Python-_program
n = int(input())
max_runs = 0
top_scorer = ""

for _ in range(n):
    name, runs = input().split(',')
    runs = int(runs)
    if runs > max_runs:
        max_runs = runs
        top_scorer = name

print(top_scorer)
