# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

```
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule 
```
```
module funct2(w,x,y,z,f2); 
input w,x,y,z; 
output f2; 
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule
```



Developed by:AJAIRAJ.J

RegisterNumber:212225220004


**RTL realization**



<img width="1920" height="1017" alt="517717354-24673b21-3016-4000-bd32-0a7ce387c12a" src="https://github.com/user-attachments/assets/7da9b416-8308-47cf-96a3-c1899b7f5e83" />


<img width="1920" height="1017" alt="519599136-fec64461-2a47-4c73-bc02-45ca44f85549" src="https://github.com/user-attachments/assets/55d22445-687d-4446-af8a-b7e878d1e2bd" />




**RTL**


<img width="1920" height="1017" alt="517716860-29ffd28e-4448-462c-8b27-bc6b88632354" src="https://github.com/user-attachments/assets/6f266ebf-28f1-4b08-8f42-20f10ff629e4" />



<img width="1920" height="1017" alt="519599440-5603f803-cbc3-4186-b02c-859cc4c910ad" src="https://github.com/user-attachments/assets/08f73ee7-cd2b-4fa8-b413-16ceacc96334" />




**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming is verified successfully.

