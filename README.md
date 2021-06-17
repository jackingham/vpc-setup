# Setting up a VPC 

- Click the create vpc 

![image](https://user-images.githubusercontent.com/32297246/122246672-a9095000-cebe-11eb-9d05-af60df075d84.png)
- name the vpc and specify the cidr

- create a new internet gateway
![image](https://user-images.githubusercontent.com/32297246/122251185-313d2480-cec2-11eb-92e9-98aad06c897d.png)

- Link the vpc and gateway 
![image](https://user-images.githubusercontent.com/32297246/122253171-d6a4c800-cec3-11eb-87ed-21e1b8cbaca8.png)

- Create a new subnet and specify a CIDR block
![image](https://user-images.githubusercontent.com/32297246/122370295-dd304f80-cf56-11eb-9a1b-cc29ccf9413c.png)

- Create both a private and publci subnet consecutively with a /24 mask:
![image](https://user-images.githubusercontent.com/32297246/122371390-bf171f00-cf57-11eb-8767-9e88ea7f9fb4.png)

- Create a routing table and link to internet gateway:
![image](https://user-images.githubusercontent.com/32297246/122372785-de627c00-cf58-11eb-9abd-63a94ce70fff.png)

- Add an association to your public subnet
![image](https://user-images.githubusercontent.com/32297246/122373684-9728bb00-cf59-11eb-9515-c98e82b43df3.png)

