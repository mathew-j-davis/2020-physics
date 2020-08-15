# Derive Acceleration from Displacement and Velocities

@import "./math.less"

In the example below acceleration  $$a$$ is derived from:
- initial velocity $$v_i = 0$$ 
- final velocity $$v_f$$
- displacement $$\Delta x$$

where time $$\Delta t$$ is not known.

$$
a = {
  \frac
  {v_i^2 +  v_i^2}
  {2Δx}
} 
$$


### Derivation

Acceleration is the rate of change of velocity.

$$ 
a = \frac{Δv}{Δt}
$$

Final velocity is initial velocity + the change in velocity:

$$ 
v_f = v_i + Δv
\\
\therefore  v_f = v_i + aΔt
$$

$$ 
a = {
  \frac
  {v_i^2 +  v_i^2}
  {2Δx}
} 
\\
$$


Dividing both sides of displacement formula by final velocity formula to remove time 

$$ 
{
  \frac
  {Δx}
  {v_f - v_i}
} 
{=}
{
  \frac
  {(v_i + v_f)  Δt }
  { 2aΔt}
}
\\
$$


Multiply each side by $$2$$ and Cancelling $$\sout{2Δt}$$ on the right.

$$ 
\therefore
{
  \frac
  {2Δx}
  {v_f - v_i}
} 
{=}
{
  \frac
  {\sout{2}(v_i + v_f)\sout{Δt}}
  {\sout{2}a\sout{Δt}}
}
\\
$$


Invert both sides, multiply by $$(v_i + v_f)$$ and cancel on the right
$$ 
\therefore
{
  \frac
  {(v_i + v_f)(v_f - v_i)}
  {2Δx}
} 
{=}
{
  \frac
  {\sout{(v_i + v_f)}a}
  {\sout{(v_i + v_f)}}
}
$$

Simplify

$$ 
\therefore 
a = {
  \frac
  {v_i^2 +  v_i^2}
  {2Δx}
} 
\\
$$

If initial velocity $$v_i = 0$$

$$ 
\therefore
a =
{
  \frac
  {v_f^2}
  {2Δx}
} 
\\
$$
