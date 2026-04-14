Let's break down these vector calculations step-by-step.

a) The magnitude of each vector

The magnitude of a 3D vector $$[x, y, z]$$ is given by the formula $$\sqrt{x^2 + y^2 + z^2}$$.

For $$\vec{a} = [2, 1, -3]$$:
$$||\vec{a}|| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14} \approx 3.74$$

For $$\vec{b} = [4, -2, 1]$$:
$$||\vec{b}|| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21} \approx 4.58$$

b) The dot product $$\vec{a} \cdot \vec{b}$$

The dot product of two vectors $$\vec{a} = [ax, ay, az]$$ and $$\vec{b} = [bx, by, bz]$$ is given by $$ax bx + ay by + az bz$$.

$$\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1) = 8 - 2 - 3 = 3$$

c) The cross product $$\vec{a} \times \vec{b}$$

The cross product of two vectors $$\vec{a} = [ax, ay, az]$$ and $$\vec{b} = [bx, by, bz]$$ is given by the formula:
$$ \vec{a} \times \vec{b} = [ (ay bz - az by), (az bx - ax bz), (ax by - ay bx) ] $$

Let's plug in the values:
$$ \vec{a} \times \vec{b} = [ ((1)(1) - (-3)(-2)), ((-3)(4) - (2)(1)), ((2)(-2) - (1)(4)) ] $$
$$ \vec{a} \times \vec{b} = [ (1 - 6), (-12 - 2), (-4 - 4) ] $$
$$ \vec{a} \times \vec{b} = [ -5, -14, -8 ] $$

d) The angle between vectors $$\vec{a}$$ and $$\vec{b}$$

The angle $$\theta$$ between two vectors can be found using the dot product formula:
$$\vec{a} \cdot \vec{b} = ||\vec{a}|| \cdot ||\vec{b}|| \cdot \cos(\theta)$$
So,
$$\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{||\vec{a}|| \cdot ||\vec{b}||}$$

We already calculated:
   $$\vec{a} \cdot \vec{b} = 3$$
   $$||\vec{a}|| = \sqrt{14}$$
• $$||\vec{b}|| = \sqrt{21}$$

Now, substitute these values:
$$\cos(\theta) = \frac{3}{\sqrt{14} \cdot \sqrt{21}} = \frac{3}{\sqrt{294}}$$
$$\cos(\theta) = \frac{3}{17.1464} \approx 0.17496$$

To find $$\theta$$, we take the inverse cosine:
$$\theta = \arccos(0.17496) \approx 1.393 \text{ radians}$$
$$\theta \approx 79.82^\circ$$