Guidelines for using the Project Files:
1. The file "Propeller_Control_Prime_Mover.slx" contains the final thruster control model (without thrust vectoring).
2. The file "Propeller_Control_Multibody_Actuation.slx" contains the Multibody version of thrust control model (the one we don't prefer).
3. The file "Vectored_Thruster.slx" contains the combined Control and Simulation of the complete optimised vectored thruster.
4. All the CAD models (stl files) have been submitted as well, but to run them, you will have to download them and change its path to where you have downloaded these files locally in the File Solid Blocks in the simulink file.
5. You will have to manually initialize the Kp, Ki and Kd for each of the linear actuator's PID by running the matlab script "PID_initialization.mlx".
Feel free to contact us for any queries regarding the file operations at: 
rk4200@nyu.edu
av3032@nyu.edu
pc3088@nyu.edu