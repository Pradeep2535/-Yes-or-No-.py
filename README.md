# -Yes-or-No-.py
q=list(map(int,input().split()))
print("YES" if (q[0]-q[2])%q[1]==0 else "NO")
