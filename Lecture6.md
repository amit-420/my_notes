# Lecture 6

[![hackmd-github-sync-badge](https://hackmd.io/YECO-xr6TD6UXXufUTpzNA/badge)](https://hackmd.io/YECO-xr6TD6UXXufUTpzNA)


### Movie section
 polypod: reconfiguarable robots

### instantaneous kinematics

#### - Differential motion 
![](https://i.imgur.com/hizRP88.png)

$\delta\theta$ is related to $\delta$x with jacobian

![](https://i.imgur.com/yRkd2tZ.png)

Explicit form:
*  We are going to examine another way of doing this velocity propogation analysis rather than propagating velocities we're going to examine the structure of the kinematics of a robot and its impact on the end of factor velocities and that would lead us to something very interesting we call the explicit form of the Jacobian matrix 
*  i.e, we will see that each column in this matrix have an association with the specific joint.

Static forces:

*   relationship btw forces and torques resulting in end-effector come from same jacobian so basically there is dual relationship btw velocities and static forces.

Joint Coordinates:
![](https://i.imgur.com/Q85cel4.png)


Jacobians: Direct Differentiation
![](https://i.imgur.com/K7JwTZp.png)

Jacobian:
![](https://i.imgur.com/p6OYvIp.png)
* $\dot{q}$  and $\dot{x}$ are connected through same jacobian as $\delta$x and $\delta$q 

Example:
![](https://i.imgur.com/1JuDB3r.png)

Stanford sheinman arm: 
* we know its DH parameters which we have calculated in prievous lecture and we found out x,y,z for positions and also 
* Doubt at 22:38
* Didn't understood what does this means

![](https://i.imgur.com/f3L93zx.png)

His Quote:
>  "" This is the x axis of the last
frame that is the axis attached to the
end-effactor expressed in the base frame
and the second set of ops and this is
the y axis and this is the z axis ""

* 






