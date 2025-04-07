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
Developed by: Hari Sudhan S
RegisterNumber: 212224240048

Ex 2.a
module exp2a(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~a&b&d)|(~b&~d)|(a&b&~c));
endmodule


Ex 2.b
module exp2b(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```


**RTL realization**
```
2.a
```
![Screenshot (158)](https://github.com/user-attachments/assets/866df5bd-fb10-45f7-a974-63091dba6cde)


```
2.b
```
![Screenshot (162)](https://github.com/user-attachments/assets/907d0cc2-c7d9-4344-ad02-c97818229ab0)





**Timing Diagram**
```
2.a
```
![Screenshot (160)](https://github.com/user-attachments/assets/a7aed4ed-7139-4e2b-8976-63b978337f08)

```
2.b
```
![Screenshot (161)](https://github.com/user-attachments/assets/6d33912a-8d9c-4196-809a-8863b20d55f0)






**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

