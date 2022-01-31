# technics_remote_control
 technics remote control
```
It looks like modified NEC code.

|   head pulse    |custom code|data code|inverted custom code|inverted data code|

|   head pulse    |   0   |    1    |
 ______        ___     ___       ___                                        
|      |      |   |   |   |     |   |...........................................
|      |______|   |___|   |_____|   |                                      
  3657   3657  914 914 914  2742 914  microseconds                                      

EUR64758 for SA-R230 SA-R330

cmd	     custom code       data code

deck >		01001 		001010
deck stop 	01001 		000000
on/off 		01001		100000
vol+ 		01001 		100100
vol- 		01001 		100101
muting 		01001 		100111

tuner 1 	01001 		010000
tuner 2 	01001 		010001
tuner 3 	01001 		010010
tuner 4 	01001 		010011
tuner 5 	01001 		010100
tuner 6 	01001 		010101
tuner 7 	01001 		010110
tuner 8 	01001 		010111
tuner 9 	01001 		011000
tuner 0 	01001 		011001

cd > 		01100 		001010
cd stop 	01100 		000000
cd |<< 		01100 		000010
cd >>| 		01100 		000011
cd +10 		01100 		011010
cd prg/cnt  	01100		011101
cd 1 		01100 		010000
cd 2 		01100 		010001
cd 3 		01100 		010010
cd 4 		01100 		010011
cd 5 		01100 		010100
cd 6 		01100 		010101
cd 7 		01100 		010110
cd 8 		01100 		010111
cd 9 		01100 		011000
cd 0 		01100 		011001

RAK-SA301E, RAK-SA301P, RAK-SA302E for SA-GX100, SA-GX190, SA-GX200, SA-GX230

It's the same as EUR64758 but LSB first and more buttons

cmd	     custom code   data code

deck 1/2	10010 		001000
deck >>		10010		010000
deck <<		10010		010000?
deck >		10010		010100
deck <		10010		100100
deck ||		10010		011000
deck rec	10010		000100
deck stop 	10010		000000
on/off 		10010 		000001 
vol+ 		10010       	001001
vol- 		10010		101001
muting		10010		111001
vcr 1		10010		011111 		

tuner 1 	10010		000010
tuner 2 	
tuner 3 	
tuner 4 	
tuner 5 	
tuner 6 	
tuner 7 	
tuner 8 	
tuner 9 	
tuner 0 	

cd > 		00110		010100
cd stop 	00110		000000
cd |<< 		00110		010000
cd >>| 		00110		110000
cd +10 		00110		010110
cd prg/cnt	00110		101110
disc		00110		011001
cd 1 		
cd 2 		
cd 3 		
cd 4 		
cd 5 		
cd 6 		
cd 7 		
cd 8 		
cd 9 		
cd 0 	
```	