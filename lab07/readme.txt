#Comment from Mark A. Yoder

# Demo       5
# ReadMe.txt 5
# Fritzing   0
# Code       10


Grade:  20/25

================================================


Date:14/10/2015
 
 To   :Mark Yoder
  From :K Sri Venkat
        B13213
  Subject:lab07 
  



Gyroscope.js and gyroscope2.js
 		data is sent in form of an array of length 14 with each element of data 8 bits each. The elements from 0 to 5 corresponds to accelorometer readings, 6 and 7, temperature sensor and 8 to 13 correspond to gyroscope readings. The gyroscope sends data in 8 bits each. Afer shifting by 8 bits and adding the corresponding elements together, we get the respective values of acceleration, temperature and gyroscope. But we need to propogate 32 bit data. so we perform sign extension by forwarding and backwarding the 16 bit data by 16 bits, thus sending a 32 bit data with the same value
