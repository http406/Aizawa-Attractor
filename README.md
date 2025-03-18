# Aizawa-Attractor

The equation used in this code describes the **Aizawa Attractor**, which is a system of **nonlinear differential equations** that exhibits chaotic behavior. The equations are as follows:

![Image](https://github.com/user-attachments/assets/c5fe25a3-ef18-4597-883c-64f59ad61f2d)

### Breakdown of Each Term:
- \( x, y, z \) represent the state variables that define the system's position in 3D space.
- \( a, b, c, d, e, f \) are constants that control the shape and behavior of the attractor.

![Image](https://github.com/user-attachments/assets/75dfc0cb-912a-4a90-881e-80fed64d1aed)

### **Why Does This System Create a Strange Attractor?**
- The equations involve **nonlinear** interactions, meaning small changes can lead to vastly different outcomes.
- The attractor has a **chaotic yet structured** shape, forming a swirling 3D curve.
- The cubic and quadratic terms contribute to the system’s **sensitivity to initial conditions**, a key characteristic of chaos theory.

### **Footnote**
- The code **numerically integrates** these equations using small steps (\( dt = 0.01 \)).
- It calculates a sequence of points and **renders them in 3D** using Three.js.
- The attractor rotates slowly, showing its **intricate and beautiful structure**.
