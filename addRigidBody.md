# addRigidBody

## Description:  
Add a Rigid Body of type Sphere or Brick  
*Sphere – specified by Sphere center and radius  
*Brick – specified by 8 vertices  
## Syntax:  
### Sphere:  
>MPM. addRigidBody (NewBodyName='***’, SphereCenter='***’, SphereRadius='***’)  
### Datatypes:  
*NewBodyName - string  
*SphereCenter - double float (3 x 1 array)
*SphereRadius – double float  
### Brick:  
>MPM. addRigidBody (NewBodyName='***’, BrickNodes='***’)  
### Datatypes:  
*NewBodyName - string  
*BrickNodes - double float (3 x 8 array) 
