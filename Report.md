Name: Angelina Ibarra 

EID: asi354

Team Number: 

## Questions

1. Why does your program need a setup and a loop?
    Your program uses the setup to initialize the program and only runs once whereas a loop runs continuously until the program is           manually stopped. 
    

2. What is the downside to putting all your code in a loop?
    If we put all our code in a loop it would be slower and would unnecessarily run code over and over again that does not need to be       re-run.
    

3. Why does your code need to be compiled?

    Because the code we write cannot be immediaetly understood by the computer. When we compile it, it converts our code to something       that can be understood by the computer. 

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?
    When lowering the frequency rather than the duty cycle the light flashed rather than dimmed because the frequency is the number of cycles per second whereas the duty cycle is the fraction of one cycle for which the signal is high. Therefore the frequency only needs to be fast enough to where the human eye cannot see the change and use the duty cycle to dim. 
    

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    You connect it to ground so you can have a complete circuit. 

6. What is the difference between synchronous and asynchronous communication?

    Synchronus communication means that two devices share the same clock and asynchronus means they       have seperate clocks. 

7. Profile of UART: Sent X bytes in Y time 

   11 bytes in 1.033ms

8. Profile of SPI: Sent X bytes in Y time

   11 bytes in 0.3165ms

9. Why is SPI so much faster than UART?

    Because each direction of communication has its own wire meaning data can be sent and recieved simultaneously. 

10. list one pro and one con of UART

    UART requires less wires but is slower than SPI.

11. list one pro and one con of SPI

    SPI is faster but requires more wires.

12. list one pro and one con of I2C

    I2C is faster than UART but requires an external device. 

13. Why does I2C need external resistors to work?

    Becuase the bus drivers are open drain making it susceptible to damage if there are no resistors. 

## Screenshots

Procedure A, step 1:
![Put path to your image here ->](C:\Users\angel\Documents\arduino-lab-1-Angie2414\img\Screenshot (7).png)

Procedure A, step 4:
![Put path to your image here ->](C:\Users\angel\Documents\arduino-lab-1-Angie2414\img\Screenshot (8).png)

Procedure B, UART:
![Put path to your image here ->](C:\Users\angel\Documents\arduino-lab-1-Angie2414\img\Screenshot (12).png)

Procedure B, SPI:
![Put path to your image here ->](C:\Users\angel\Documents\arduino-lab-1-Angie2414\img\Screenshot (13).png)
