# Model of Gyrosphere
The Sphere model consists of an **Internal driving unit (IDU)** enclosed by two hemispherical shells joined together. The IDU is a tetrahedral skeleton made by joining four cylindrical rods connecting them tetrahedrally. End of the rods are attached with **omni wheels** which are in contact with the internal surface of the spherical unit except the top rod which has a **ball and socket joint** for maintaining the upright position of the IDU. Omniwheels used are controlled by **BLDC motors**. The central mass is attached below the driving unit.
<p align="center">
 <img  width="550" height="375" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/gyro_matplotlib-model.png">
 <img  width="450" height="350" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/gyro_pybullet_model.png"><br>
</p>

# Kinematics of Gyrosphere
Let the angle of rotation of sphere about Z axis be ɸ. Let the angle of rotation of sphere with respect to its centre about X axis be θ.<br>
So **Rotation matricies** of sphere with respect to the arena are : 

<p align="center">
 <img  width="300" height="150"  src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/z_rot_matrix.gif">
 <img  width="300" height="150"  src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/x_rot_matrix.gif"><br>
</p>

Here let **(Wr)actual**  be the actual angular velocity of the outersphere with respect to the arena and **(Wr)IDU**  be the angular velocity of the internal driving unit. Then ,

<p align="center">
 <img  width="300" height="50" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/formula.gif"><br>
</p>

So we get 
<p align="center">
 <img  width="650" height="150" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/step1.gif"><br><br>
 <img  width="650" height="150" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/step2.gif"><br>
</p>

We can say that
<p align="center">
 <img  width="300" height="100" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/step3.gif"><br>
</p>
where W1, W2, W3 are anguler velocities of omni wheels in IDU. 'R' and 'r' are radii of outer sphere and omni wheel respectively.
Also , from the diagram we can resolute the angular velocity components as<br><br>
<p align="center">
 <img  width="500" height="260" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/w_values.gif"><br>
</p>

So by substituting the values in the relation that we have , we get 
<p align="center">
 <img  width="700" height="200" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/step4.gif"><br>
</p>

Finally, by rearranging it we get the equation for knowing the magnitude of angular velocities of each omni wheel .
<p align="center">
 <img  width="650" height="150" src="https://github.com/naval-selvan-1214/kinematics_equation/blob/main/media/step5.gif"><br>
</p>
