# Design-a-CMOS-inverter - cadence virtuoso 
## Aim:
Design using cadence virtuouso a CMOS Inverter using TCMC65n technology & cal Vth – TpHL – TpLH – Power consumption
and draw its layout, calculate parasitic capacitance 
 for NMOS we use W/L = 1.5um/65nm && for PMOS W/L=2um/65nm 

![image](https://user-images.githubusercontent.com/66570093/170603308-892ff418-8b1f-49b4-84bc-fed1c576a21b.png)


### create a symbol 

![image](https://user-images.githubusercontent.com/66570093/170602670-b4c63c81-b8ed-4ccd-8be2-5406dd7bdf29.png)

### Run Trans simulation 


![image](https://user-images.githubusercontent.com/66570093/170602783-5952bf87-4a1b-4545-8aa0-c613062a42c9.png)



![image](https://user-images.githubusercontent.com/66570093/170602846-55a148fe-7698-4f25-ae5e-6fbe27b16540.png)

  ![image](https://user-images.githubusercontent.com/66570093/170602920-2f76c177-cb6b-4b67-819c-d05b8b845aad.png)


### Run dc simulation with design parameters Vbias 
 ![image](https://user-images.githubusercontent.com/66570093/170602942-1e339186-73fa-41d7-94db-81864d815d9f.png)
![image](https://user-images.githubusercontent.com/66570093/170603635-0ad98855-10d4-4cdb-a5d0-0a8a4cad874d.png)

 
![image](https://user-images.githubusercontent.com/66570093/170602979-9529cd88-7020-4af1-9e1f-07746b0622d3.png)


 ### Vth


 ![image](https://user-images.githubusercontent.com/66570093/170603003-ed4400e0-e045-4801-9cdb-c4226720fa70.png)
![image](https://user-images.githubusercontent.com/66570093/170603012-fb5fe2cc-ff28-4dcf-9041-185dd7fca490.png)
 

### using Tpulse=5s  - TpHL=TpLH ?
![image](https://user-images.githubusercontent.com/66570093/170603106-7e6c6421-0f06-4af9-865d-02f8f3ed7248.png)
![image](https://user-images.githubusercontent.com/66570093/170603176-4dc66d90-6fec-4de2-ab95-0b1d5985d131.png)



 
## LAYOUT : 
![image](https://user-images.githubusercontent.com/66570093/170603226-10a462d4-4bd0-4fc1-88cc-6b1b20811e1b.png)

 
### DRC :
 
![image](https://user-images.githubusercontent.com/66570093/170603236-90b79fdd-d472-43fb-b8e8-73a9b1f1ccc9.png)


 

