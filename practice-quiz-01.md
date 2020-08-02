
@import "./math.less"


Takeoff velocity : 188 km/h  
Runway : 2.5 km
Initial Velocity : 0 km/h

What acceleration is required?


\(
a = {
  \frac
  {v_i^2 +  v_i^2}
  {2Δx}
} 
\)



```python

take_off_velocity = 188 * 1000 / (60 * 60)
runway = 2.5 * 1000

acceleration = ( take_off_velocity * take_off_velocity) / (2 * runway)

round(acceleration,3)

# answer 0.545 m / s^2
# print("{:.2e}".format(acceleration))

```


Initial Velocity : 55 km/h 
Constant acceleration : 1.5 m/s^2 
Final Velocity : 110 km/h

Calculate time to final velocity.

\(
Δt = \frac{v_f - v_i}{α}
\\   
\)


```python

velocity_initial = 55 * 1000 / (60 * 60) # m/s
print(round(velocity_initial,2)) 

velocity_final = 110 * 1000 / (60 * 60) # m/s
print(round(velocity_final,2)) 

α = 1.5 # m/s^2 


Δt = (velocity_final - velocity_initial) / α
print(round(Δt,2)) 
print("{:.2e}".format(Δt))
# Δt = 10.19

sanity_check = (10 * 1.5) * 60 * 60 / 1000
print(round(sanity_check,2))

```


displacement_1 = 30m E
displacement_2 = 20m E

total displacement = 50m E


```python

d = []
d.append( 30 ) # m W
d.append( 20 ) # m w

print(round(sum(d),2))

# answer : 20 m west

```



```python

d = []
d.append( -980 ) # m W
d.append(  670 ) # m E
d.append( -200 ) # m w

print(round(sum(d),2))

# answer : 510 m west

```




```python

# 500 m E
# 800 m W
# 40  m W

d = [500,-800, -40 ]
print(round(sum(d),2))

# answer 340 m W

```


```python

total_displacement = -3.0 # km 
time = 5.0 # h


v = total_displacement / time # km / h

round(v,2)

# answer -0.6 km / h

```

```python
v1 = 17 * 1000 / (60 * 60) # m /s
d1 = 119 * 1000 # m
t1 = d1 / v1

v2 = 11 * 1000 / (60 * 60)
t =  ((11 * 60) + 40 ) * 60
t2 = t - t1

d2 = t2 * v2

d = d1 + d2

# answer 170 km

# sanity check

170 / 12  

```



```python

t = 5.2 # s
t_mid = 2.6

α = 9.8 # m/s^2

v = α * t_mid

v

# answer 25 m/s^2

```

```python

v0 = 0 # m / s
v1 = 55 * 1000 / (60 * 60) # m / s
a = 4.4 # m / s^2


v1 /  a

# answer 3.5 s

```

If a truck accelerates at a steady 4.4 m/s2, how long will it take to reach a speed of 55 km/h, starting from rest?


5 6 7 8 9 10 11 12 1 2 3 4

5 6 7 8 9 10 11 12 13 14 15 16


- 20 m 5 am
+ 30 m 4 pm


t = 16 - 5

```python

50 / (16-5)
```


question 2 - assuming constant velocity




```
dv = (95 - 48) * 1000 / (60 * 60)

dv / 3.1

```



```
dv = (80 - 25) * 1000 / (60 * 60)

dv / 1.4

```


```
dv = (110 - 55) * 1000 / (60 * 60)

dv / 1.5

```

```python

t = 17 - 11.5 
d = 3.5 + 7

d / t








```



```
v = 75 * 1000 / (60 * 60)
a = 3.9

v / a

```

```python

t = 17 - 11.5 
d = 3.5 + 7

d / t

```



```python

v1 = 3.5     # m/s

t = 8
a = 1.7

v2 = v1 + ( a * t)
v2


d = t*( v1 + v2) / 2
d



4.0 / 5.0

82 / 8

```