# Design-Optimization-of-Drone-Arm-

An exploratory team project under Professor Pawan Sharma, Mechanical Dept, IIT BHU, in which I, along with my team, tried to optimize drone arm structure using the SIMP algorithm of SOLIDWORKS and using naturally topology optimized structures like gyroids. We evaluate their strength using Ansys Mechanical by Finite Element Analysis (FEA).

* **Usage of SIMP algorithm of SOLIDWORKS**

We used the Solid Isotropic Material with Penalization method (SIMP) algorithm  for topology optimization. The SIMP method predicts an optimal material distribution within a given design space for load cases, boundary conditions, manufacturing constraints, and performance requirements.

![image](https://github.com/nk-16/Design-Optimization-of-Drone-Arm-/assets/128499808/2a9e6ebb-6828-448e-8786-3f87d1da91b7)

![image](https://github.com/nk-16/Design-Optimization-of-Drone-Arm-/assets/128499808/d5b1de16-c0aa-415f-8521-14036cb4aa32)

* **Usage of gyroids**

Gyroid structures are complex, three-dimensional structures characterized by repeating patterns of interconnected, curved surfaces. They are often found in nature, such as in certain corals and butterfly wings, but can be created synthetically using 3D printing or other fabrication methods. We tried to create a drone arm using topology-optimized structures and then simulate it using Ansys.

![image](https://github.com/nk-16/Design-Optimization-of-Drone-Arm-/assets/128499808/0211ec11-6773-4f34-964e-337320b94b2f)

![image](https://github.com/nk-16/Design-Optimization-of-Drone-Arm-/assets/128499808/77ab9dfe-8a93-4512-a921-42655fe3a2a5)

* **Results and Conclusion**
  
|                                 | Weight (grams) | Maximum deformation (mm)| Average stress(MPa) | Average Factor Of Safety(FOS) | FOS/Weight (grams)^-1 |
|---------------------------------|----------------|-------------------------|---------------------| ------------------------------|-----------------------|
|        Standard Drone Arm       |     680.4      |         0.010           |        1.585        |               15              |          0.022        |
|      Drone arm with gyroids     |     100.2      |         0.319           |        28.599       |               9.9             |          0.098        |
|       Drone arm using SIMP      |     113        |         0.100           |        6.574        |               15              |          0.133        |

The above table shows that the drone arm made using the SIMP algorithm is the most efficient. In contrast, the standard drone arm is the least efficient. In the drone arm with gyroids, we have chosen a thickness of 1 mm; varying its thickness will give us different results. Increasing thickness will increase weight, but
at the same time, it will also increase the average safety factor.

