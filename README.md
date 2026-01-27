<img width="1920" height="1080" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/21944fc9-b58e-4505-849b-3b486d26978e" />






# siddu
NOTE: PCB Design , Code , Circuit diagram also provided 

Detailed build of a lfr using pid code and nano . Here you can get an idea of all possible problems you
need to face and I tried my level best to explain so that you guys don't make mistakes I made which results
in securing 2nd place insted of 1st.



points to be remembered

1.Always make your bot as balanced as possible no need to go with 4 wheel drive 2 wheel and one caster works pritty well

2.Always tune your bot in dark and cover the sensor from sides so that no sun light district it

Explanation

In my case for the compitition I didn't used any shade cover to my sensor I tuned the bot in day time but unfortunately the compitition was held in indoor at evening which results in low sunlight which is not the situation I tuned for . So my bot starts miss reading the turns I tested it again in light it worked . After a certain period of time I realised that qtr array is nothing but IR sensors in arranged manner .As you know IR sensor malfunction due to extreme sunlight as it contains ir rays .

SO WHAT IS THE SOLUTION

the major changes you can make is 1st completely cover the sensor by side ways dont allow any light to enter and then tune accordingly it should work finely .

3.Always use a buck convert to supply study voltage for nano
4.Better to use n20 motors ,make lfr as compact as possible using Bo motors also works

Tuning require a lot of patience if you still need better performance sacrifice the speed slow speed implies more stability.
Below I provided the list of components I used in my lfr

1.Arduino nano
2.TB6612fng motor driver
3.XL6009 voltage booster
4.8v battery pack
5.LED
6.Resistor
7.Bo motors / N20 motors X2
8.8 channel qtr array sensor
Below I attached a photo of my bot and also the circuit diagram and code

I used code from ROBO JUNKIES thanks for them for providing code
I used it as Raw code and modified a little as I needed .

