# A List of simulations has been performed for the estimation of **ground state** properties for many nonlinear rotors systems.

:one: A list of simulations for **water molecules**

The following parameters has been used for all simulations -
 
```
R    = 10.05 Angstrom
		
# of Blocks = 20,0000
# of Pass   = 100
```

Rotational constants are - 
   A = 27.877 cm <sup>-1</sup>,
   B = 14.512 cm <sup>-1</sup>,
   C = 9.285 cm <sup>-1</sup>,

- [x] Simulations at **fixed tau = 0.01 K<sup>-1</sup>** for **N=2**

   ```
   Type of potential: caleng_tip4p_gg.f
   ```

   _The list of beads P is_
    
   ```
   P    = [4, 8, 16, 32, 64, 128] 
   ```		
		
   **In graham**
   
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-tau0.01Kinv-Blocks20000-Passes100-System2H2O-e0vsbeads*~
       
   Analysis incomplete: Skipped data first 0
   
 - [x] Simulations at **fixed beta = 0.32 K<sup>-1</sup>** for **N=[2-16]**

   ```
   Type of potential: caleng_tip4p_gg.f
   ```

   _The list of beads P is_
    
   ```
   P    = [4, 8, 16, 32, 64, 128] 
   ```		
		
   **In graham**
   
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.32Kinv-Blocks20000-Passes100-SystemNH2O-e0vsbeads*~
       
   Analysis incomplete: Skipped data first 0
   
   
The following parameters has been used for the below simulations -
 
```
R    = 10.05 Angstrom
		
# of Blocks = 10,000
# of Pass   = 50
```
   
 - [x] Simulations at **fixed beta = 0.256 K<sup>-1</sup>** for **N=[2]**

   ```
   Type of potential: caleng_tip4p_gg.f
   ```

   _The list of beads P is_
    
   ```
   P    = [4, 8, 16, 32, 64, 128, 256] 
   ```		
		
   **In graham**
   
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks10000-Passes50-System2-p-H2O-e0vsbeads*~
       
   Analysis incomplete: Skipped data first 0, 5000. Final results is displayed for 5000.
   
:two: A list of simulations for **one water molecule**

The following parameters has been used for all simulations -
 
```
R    = 10.05 Angstrom
		
# of Blocks = 20,0000
# of Pass   = 100
```

- [x] Simulations at **fixed tau = 0.002 K<sup>-1</sup>** for **N=1**

   ```
   Type of potential: -F.cos(theta); F=20 inverse Kelvin
   ```

   _The list of beads P is_
    
   ```
   P    = [5, 9, 17, 33, 65, 129, 257] 
   ```		
		
   **In graham**
   
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field20.0Kinv-tau0.002Kinv-Blocks20000-Passes100-System1-p-H2O-e0vsbeads*~
       
   Analysis incomplete: Skipped data first 0, 10000. Final result is shown for 10000.
   
 - [x] Simulations at **fixed beta = [0.128, 0.256] K<sup>-1</sup>** for **N=1**

   ```
   Type of potential: -F.cos(theta); F=20 inverse Kelvin
   ```

   _The list of beads P is_
    
   ```
   P    = [5, 9, 17, 33, 65, 129, 257, 513] 
   ```		
		
   **In graham**
   
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field20.0Kinv-beta0.128Kinv-Blocks10000-Passes50-System1-p-H2O-e0vsbeads*~
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field20.0Kinv-beta0.256Kinv-Blocks10000-Passes50-System1-p-H2O-e0vsbeads*~
   
   Averaged over all passes in MC simulations. 
   Analysis complete: Skipped data first 0, 5000. Final results are shown for preskip 5000.
   
   N.B.: for beta=0.256 inverse Kelvin cases, the data for P=513 should be removed as the energy is not converged. 
   
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field10.0Kinv-beta0.256Kinv-Blocks10000-Passes50-System1-p-H2O-e0vsbeads*~
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field30.0Kinv-beta0.256Kinv-Blocks10000-Passes50-System1-p-H2O-e0vsbeads*~
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field40.0Kinv-beta0.256Kinv-Blocks10000-Passes50-System1-p-H2O-e0vsbeads*~
   ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field50.0Kinv-beta0.256Kinv-Blocks10000-Passes50-System1-p-H2O-e0vsbeads*~
   
   Averaged over all passes in MC simulations. 
   Analysis incomplete: Skipped data first 0, 5000. Final results are shown for preskip 5000.
   
   N.B.: for beta=0.256 inverse Kelvin cases, the data for P=513 should be removed as the energy is not converged. 
   

