Summary of data files associated with the paper:
    Response bounds for complex systems with a localised and uncertain nonlinearity
    Tore Butlin
    Journal of Sound and Vibration

	
	
	
***FILE: data-1-experimental-impacts.mat***
This file contains the experimental data for the impacting beam test case.
All data is stored within the structure 'd'.
The structure contains:

d =

    input-frequency: excitation frequency (Hz)
         coil-force: excitation amplitude (N)
     amp-normalised: excitation amplitude normalised [0,1]
       rms-left-dsp: RMS steady-state displacement amplitude for left (Site 1) accelerometer (m)
      rms-right-dsp: RMS steady-state displacement amplitude for right (Site 2) accelerometer (m)
       rms-left-vel: RMS steady-state velocity amplitude for left (Site 1) accelerometer (m/s)
      rms-right-vel: RMS steady-state velocity amplitude for right (Site 2) accelerometer (m/s)
       rms-left-acc: RMS steady-state acceleration amplitude for left (Site 1) accelerometer (m/s^2)
      rms-right-acc: RMS steady-state acceleration amplitude for right (Site 2) accelerometer (m/s^2)
         pulsecount: 0 = no initial pulse; 1 = initial pulse
       gap-material: end-stop material
        gaptotal-mm: total clearance (mm)
        coilwarning: 0 = no warning; 1 = possible impact between beam and excitation coil
     walkingwarning: 0 = no warning; 1 = possible disruption to test from people walking near test rig
          good-data: 0 = one of the two warnings; 1 = no known problem with the data



		  
***FILE: data-1-numerical-impacts.mat***
This file contains the numerical data for the impacting beam test case.
All data is stored within the structure 'r'.
The structure contains:

r =

    input-frequency: excitation frequency (Hz)
        input-force: excitation amplitude (N)
       rms-left-dsp: RMS steady-state displacement amplitude for left (Site 1) (m)
       rms-left-vel: RMS steady-state displacement amplitude for right (Site 2) (m)
       rms-left-acc: RMS steady-state velocity amplitude for left (Site 1) (m/s)
      rms-right-dsp: RMS steady-state velocity amplitude for right (Site 2) (m/s)
      rms-right-vel: RMS steady-state acceleration amplitude for left (Site 1) (m/s^2)
      rms-right-acc: RMS steady-state acceleration amplitude for right (Site 2) (m/s^2)
         pulsecount: 0 = no initial pulse; 1 = initial pulse
                 k0: contact property, see paper
                 kc: contact property, see paper
           powerlaw: contact property, see paper
                  c: contact property, see paper
        gaptotal-mm: total clearance (mm)


		
		
***FILE: data-2-numerical-friction.mat***
This file contains the numerical data for the friction damped test case.
All data is stored within the structure 'f'.
The structure contains:
	
		
f = 

    input-frequency: excitation frequency (Hz)
        input-force: excitation amplitude (N)
       rms-left-dsp: RMS steady-state displacement amplitude for left (Site 1) (m)
       rms-left-vel: RMS steady-state displacement amplitude for right (Site 2) (m)
       rms-left-acc: RMS steady-state velocity amplitude for left (Site 1) (m/s)
      rms-right-dsp: RMS steady-state velocity amplitude for right (Site 2) (m/s)
      rms-right-vel: RMS steady-state acceleration amplitude for left (Site 1) (m/s^2)
      rms-right-acc: RMS steady-state acceleration amplitude for right (Site 2) (m/s^2)
         pulsecount: 0 = no initial pulse; 1 = initial pulse
                mus: friction property, see paper
                mud: friction property, see paper
              beta1: friction property, see paper
              beta2: friction property, see paper