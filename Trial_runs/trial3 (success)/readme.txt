So on 20th December I started to setup a simulation for eciting my CPW structures. 

Initially I used lumped terminal ports and wave terminal ports but in both cases I had to have both ground traces connected with each other somehow. To do this I used some structures, small traes shorting both grounds, assigning perf E boundary to both grounds. 

Only the perf E boundry condition simulation yielded results closer to measurements of a through line. 

Then I tried simuation with a modal wave port. I set the number of modes as 1 and drew the integration line from the edge of the center conductor to the edge of the ground conductor. 

The simuation took a small time to run, the results were closer to the measured values. I have written to CADFEM India and also to Alex Shalaby asked whether the setup is correct or not. I will now simulate SiC substarte..

SiC substrate is the first samle which I made and measured the S parameter using a VNA. 