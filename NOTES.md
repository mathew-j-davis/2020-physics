@import "./math.less"

# Position

Position describes a location relative to an origin.

# Distance Travelled

If an object has moved from position *a* to position *b*,
distance travelled is the length of the path it followed to get from *a* to *b*. 

# Distance

If an object has moved from position *a* to position *b* 
*distance* describes *how far* it has moved, how far *a* is from *b*.
Distance is a *scalar* quantity - it has magnitude only.
The SI unit for distance is metre (m)

# Displacement
If an object has moved from position *a* to position *b* 
displacement describes *how far* and *in what direction* it has moved.

Displacement is a *vector* quantity - it has magnitude and direction.

# Speed

Speed is the rate of change of distance travelled.
Distance travelled is a scalar quantity, so speed is a scalar quantity.

\(
speed =  \frac{distance}{\Delta t} = \frac{distance} { t_{final} - t_{initial} }
\)

# Velocity 

Velocity is the rate of change of displacement.
Displacement is a vector quantity, so velocity is also a vector quantity.
Velocity has magnitude and direction

\(
velocity =  
\frac
{\Delta displacement}{\Delta t} 
= \frac{ x_{final} - x_{initial} } { t_{final} - t_{initial} }
\)

# Acceleration  

Acceleration is the rate of change of Velocity 
Acceleration is a vector quantity
Acceleration has magnitude and direction

\(
acceleration =  \frac{\Delta v}{\Delta t} = \frac{ v_{final} - v_{initial} } { t_{final} - t_{initial} }
\)

# Displacement, time, velocity and acceleration

Where acceleration is constant the following two formula describe the relationship between displacement, time, initial velocity, final velocity and acceleration:

Formula for displacement:

\(  
Δx = \frac{1}{2} (v_i + v_f)  Δt 
\)

Formula for final velocity

\(
v_f = v_i + aΔt
\)



### Displacement

An object with average velocity *v* for time *Δt* will be displaced *Δx* 

\(
Δx = v * Δt
\)


If acceleration is constant, then we can say the average velocity is 

\(
v_{average} = \frac{v_{final} + v_{initial}}{2} 
\)


substituting the second equation into the first gives us

\(
Δx = \frac{v_{final} + v_{initial}}{2}  Δt
\)

If the acceleration is from rest then initial velocity is zero, in which case the equation can be simplified as:

{% raw %}
\( 
Δx = \frac{v_{final}}{2}  Δt
\)
{% endraw %}

### Final Velocity, acceleration and time

Acceleration is the rate of change of velocity.

\( 
a = \frac{Δv}{Δt}
\)

Final velocity is initial velocity + the change in velocity:
\( 
v_f = v_i + Δv
\\
\therefore  v_f = v_i + aΔt
\)


### Deriving unknown values from known values



These formula can be re arranged to derive unknown values from values that are known.

[Derive acceleration from displacement and velocities](derive-acceleration-from-displacement-and-velocities.md)

\( 
a = {
  \frac
  {v_i^2 +  v_i^2}
  {2Δx}
} 
\\
\)



<!-- 

Substituting in the acceleration formula we can remove the final velocity if it is not known:



\(\sf 
acceleration =  \frac{  v_{final} - v_{initial} } {\Delta t} 
\)



\(\sf 
\therefore acceleration * {\Delta t} =   v_{final} - v_{initial}  
\)


\(\sf 
\therefore  v_{final}  = a * {\Delta t} + v_{initial} 
\)

\(\sf  
Δx = \frac{1}{2} * (v_{initial} + v_{final})  * Δt
\)

\(\sf  
= \frac{1}{2} * (v_{initial} + a * {\Delta t} + v_{initial} )  * Δt
\)

\(\sf  
= ( \frac{1}{2} * 2  v_{initial} * Δt)  + (\frac{1}{2} a  * Δt * Δt)
\)

\(\sf  
= v_{initial}Δt + \frac{1}{2}aΔt^2
\)


or we can remove the time if it is not known:

\(\sf 
a =  \frac{  v_{final} - v_{initial} } {\Delta t} 
\)

\(\sf 
\therefore  Δt =  \frac{  v_{final} - v_{initial} } a
\)


\(\sf  
Δx = \frac{1}{2} * (v_{initial} + v_{final})  * Δt
\)

\(\sf  
\therefore 2Δx = (v_{initial} + v_{final})  * Δt
\)

\(\sf  
= (v_{initial} + v_{final})  * \frac{  v_{final} - v_{initial} } a
\)

\(\sf  
\therefore 2Δxa = (v_{initial} + v_{final})  *  ( v_{final} - v_{initial} )
\)

\(\sf  
\therefore 2Δxa = v_{initial}^2 - v_{initial}^2
\)

 -->
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>