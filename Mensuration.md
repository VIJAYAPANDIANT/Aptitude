# Quantitative Aptitude: Mensuration

## 1. 2D Shapes (Area & Perimeter)

| Shape | Area | Perimeter / Circumference | Key Variables |
| :--- | :--- | :--- | :--- |
| **Rectangle** | $L \times B$ | $2(L + B)$ | $L = \text{Length}, B = \text{Breadth}$ |
| **Square** | $a^2$ or $\frac{d^2}{2}$ | $4a$ | $a = \text{Side}, d = \text{Diagonal } (a\sqrt{2})$ |
| **Triangle** | $\frac{1}{2} \times b \times h$ | $a + b + c$ | $b = \text{Base}, h = \text{Height}$ |
| **Scalene Triangle** | $\sqrt{s(s-a)(s-b)(s-c)}$ | $2s = a+b+c$ | $s = \text{Semi-perimeter}, a,b,c = \text{Sides}$ |
| **Equilateral Triangle**| $\frac{\sqrt{3}}{4} a^2$ | $3a$ | $a = \text{Side}, \text{Height } (h) = \frac{\sqrt{3}}{2}a$ |
| **Circle** | $\pi r^2$ | $2\pi r$ | $r = \text{Radius}$ |
| **Sector of Circle** | $\frac{\theta}{360} \times \pi r^2$ | $2r + \left(\frac{\theta}{360} \times 2\pi r\right)$| $\theta = \text{Angle of Sector}$ |

---

## 2. 3D Shapes (Volume & Surface Area)

| Shape | Volume | Lateral / Curved Surface Area (LSA/CSA) | Total Surface Area (TSA) | Key Variables |
| :--- | :--- | :--- | :--- | :--- |
| **Cuboid** | $l \cdot w \cdot h$ | $2h(l + w)$ | $2(lw + wh + hl)$ | $l, w, h = \text{dimensions}$, $\text{Diagonal} = \sqrt{l^2+w^2+h^2}$ |
| **Cube** | $a^3$ | $4a^2$ | $6a^2$ | $a = \text{Side}$, $\text{Diagonal} = a\sqrt{3}$ |
| **Cylinder** | $\pi r^2 h$ | $2\pi r h$ | $2\pi r (h + r)$ | $r = \text{Radius of base}, h = \text{Height}$ |
| **Cone** | $\frac{1}{3} \pi r^2 h$ | $\pi r l$ | $\pi r (l + r)$ | $r = \text{Radius}, h = \text{Height}, l = \text{Slant height } (\sqrt{r^2+h^2})$ |
| **Sphere** | $\frac{4}{3} \pi r^3$ | $4\pi r^2$ | $4\pi r^2$ | $r = \text{Radius}$ |
| **Hemisphere**| $\frac{2}{3} \pi r^3$ | $2\pi r^2$ | $3\pi r^2$ | $r = \text{Radius}$ |

---

## 3. Practice Problems

### Problem 1
Find the cost of fencing a circular field of radius 28 meters at the rate of Rs. 15 per meter.

### Problem 2
A copper sphere of radius 6 cm is melted and drawn into a wire of cylinder shape of radius 0.2 cm. Find the length of the wire.

### Problem 3
If the radius of a cylinder is increased by 20% and its height is decreased by 10%, find the percentage change in its volume.

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Identify the parameter to calculate**:
   - Fencing is done along the boundary (Circumference).
   - Circumference $C = 2\pi r$.
2. **Calculate the circumference**:
   - Given radius $r = 28$ m, and $\pi \approx \frac{22}{7}$:
     $$C = 2 \times \frac{22}{7} \times 28 = 2 \times 22 \times 4 = 176 \text{ meters}$$
3. **Calculate the total cost**:
   $$\text{Total Cost} = \text{Circumference} \times \text{Rate} = 176 \times 15 = \text{Rs. } 2,640$$
4. **Answer**: The cost of fencing is **Rs. 2,640**.

### Solution 2
1. **Formulate the volume conservation**:
   - Volume of Sphere melted = Volume of Cylinder wire created.
2. **Set up the values**:
   - Sphere radius $R = 6$ cm.
   - Cylinder radius $r = 0.2$ cm.
   - Cylinder length (height) $= h$.
3. **Equate the volumes**:
   $$\text{Volume of Sphere} = \text{Volume of Cylinder}$$
   $$\frac{4}{3} \pi R^3 = \pi r^2 h$$
   $$\frac{4}{3} \times 6^3 = (0.2)^2 \times h$$
   $$\frac{4}{3} \times 216 = 0.04 \times h$$
   $$4 \times 72 = 0.04 \times h$$
   $$288 = 0.04 \times h \implies h = \frac{288}{0.04} = 7200 \text{ cm}$$
4. **Convert to meters**:
   - $7200 \text{ cm} = 72$ meters.
5. **Answer**: The length of the wire is **72 meters**.

### Solution 3
1. **Understand volume dependence**:
   - Volume of a cylinder $V = \pi r^2 h$.
   - The volume depends on $r \times r \times h$.
2. **Use successive percentage formula**:
   - First, calculate percentage change in $r^2 = r \times r$ (both increased by 20%):
     $$\text{Change in } r^2 = 20 + 20 + \frac{20 \times 20}{100} = 40 + 4 = 44\% \text{ increase}$$
   - Next, combine this $44\%$ increase with the $10\%$ height decrease ($h$):
     $$\text{Net Change in } V = 44 - 10 + \frac{44 \times (-10)}{100} = 34 - 4.4 = 29.6\%$$
3. **Answer**: The volume increases by **29.6%**.
