# SpringMassTemplate



CSC486A - Aj Gray



1\) All relevant variables are provided publicly or privately as needed (groundPlane, handlePlaneCollisions, particleMass set to 1kg, useGravity, gravity vector of (0, -9.8, 0), Mesh, particles, and plane.



2\) Every vertex has a particle without duplicates and hopefully in the right coordinate system using transform.transformPoint.



3)There should be a spring connecting all particles to all other particles (1 for each connection) on lines 126-139. Wasn't sure how to compute restLength



4\) groundplane should be properly initialized to that of the GroundPlane objects transform



5\) Wasn't able to get to ground collision, though the default ks and kd values are set appropriately at 1000 and 20 respectively.



6\) Ground contact springs not updated



7\) vertices are not updated



8\) particle-particle forces are not calculated



9\) bounds+normals not updated



10\) symplectic Euler integration scheme not implemented



11\) loop doesn't update



12\) blue cube has ks=200 and kd=0, red cube has ks=80 and kd=0.8, and green cube has ks=45 and kd=0.3

