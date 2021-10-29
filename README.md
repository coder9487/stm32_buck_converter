# stm32_buck_converter

Hardware:
Design a simple buck converter, switching by power mosfet IRFP250, push mosfet by optical coupler mosfet driver TLP250

Software:
Using Stm32f401re as controller. Using PI control algorithm to keep secondary side voltage constant.

#############################      Build       ########################################


1. Create a cubeide project and select stm32f401re( or your board ) as controller
2. Dowload code from github and replace original .ico file with "buck.ico".
3. Replace "Core" directory with mine.
4.In final. Build code.
