# A List of simulations has been performed for the estimation of **ground state** properties for many nonlinear rotors systems.

:one: A list of simulations for **water molecules**

Rotational constants are - 
   A = 27.877 cm <sup>-1</sup>,
   B = 14.512 cm <sup>-1</sup>,
   C = 9.285 cm <sup>-1</sup>,

Type of potential: **caleng_tip4p_2005.f**;   unit: inverse Kelvin

-----------------------------------------------------------------------------------------------------------------

- [x] Simulations for **N=2** and **N=10** at **fixed tau = 0.005 K<sup>-1</sup>**
   
   - A set of nearest neighbouring distances - 
   
   ```
   
   r = [2.5, 3.0, 3.5, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0] Angstrom
    
   P = [11, 21, 31, 41, 51, 61, 71, 81, 91, 101] 
   
   MC Blocks=10,000
   MC Pass=100
   
   ```
   
   **Expectation values are estimated at the last MC Pass in MC simulations.**
   
   - Data stored in **graham**
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-TIP4P-2005-RotDOFs-RptrVALUEAngstrom-tau0.005Kinv-Blocks10000-Passes100-System2-p-H2O-e0vsbeads*~ ***!Done***
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-TIP4P-2005-RotDOFs-RptrVALUEAngstrom-tau0.005Kinv-Blocks10000-Passes100-System10-p-H2O-e0vsbeads*~
     
   - **self.step in inputFile.py is a list of MC step size for angular DOFs.**
  
   ``` 
   self.step = [0.3 for i in range(10)] r = [5.0, 6.0, 7.0, 8.0, 9.0, 10.0] Angstrom
   self.step = [0.2 for i in range(10)] r = [3.5, 4.0] Angstrom
   self.step = [0.15 for i in range(10)] r = 3.0 Angstrom
   self.step = [0.1 for i in range(10)] r = 2.5 Angstrom
   self.step = [0.07 for i in range(10)] r = 2.0 Angstrom
   ```
   
   - Analysis incomplete: Skipped data from the begining - 0, 10000, 15000. Final results are shown for preskip 0.
   
 -----------------------------------------------------------------------------------------------------------------
   
 - [x] Simulations for **N=10** at **fixed beta = 0.2 K<sup>-1</sup>**
   
   - A set of nearest neighbouring distances - 
   
   ```
   
   r = [2.2*i for i in range(79)] Angstrom
        
   P = [11, 21, 31, 41, 51, 61, 71, 81, 91, 101] 
   
   MC Blocks=20,000
   MC Pass=100
   
   ```
   
   **Expectation values are estimated at the last MC Pass in MC simulations.**
   
   - Data stored in **graham**
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-TIP4P-2005-RotDOFs-RptrVALUEAngstrom-beta0.2Kinv-Blocks20000-Passes100-System10-p-H2O-e0vsbeads*~
   
   - **self.step in inputFile.py is a list of MC step size for angular DOFs.**
  
   ``` 
   self.step = [2.0, 0.4, 0.3, 0.25, 0.20, 0.20, 0.18, 0.15, 0.15, 0.15] r = [8.0-10.0] Angstrom
   self.step = [1.0, 0.4, 0.3, 0.25, 0.20, 0.20, 0.18, 0.15, 0.15, 0.15] r = [6.0-8.0] Angstrom
   self.step = [0.6, 0.4, 0.3, 0.25, 0.20, 0.20, 0.18, 0.15, 0.15, 0.15] r = [5.0-5.9] Angstrom
   self.step = [0.4, 0.4, 0.3, 0.25, 0.20, 0.20, 0.15, 0.15, 0.15, 0.15] r = [4.0-5.0] Angstrom
   self.step = [0.3, 0.3, 0.3, 0.25, 0.20, 0.20, 0.15, 0.15, 0.15, 0.15] r = 3.8 3.9 Angstrom
   self.step = [0.2, 0.2, 0.2, 0.2, 0.2, 0.2, 0.15, 0.15, 0.15, 0.15] r = 3.4, 3.5, 3.6, 3.7 Angstrom
   self.step = [0.1, 0.12, 0.16, 0.18, 0.2, 0.2, 0.15, 0.15, 0.15, 0.15] r = 3.0 Angstrom
   self.step = [0.08, 0.10, 0.12, 0.12, 0.12, 0.12, 0.15, 0.15, 0.15, 0.15] r = [2.6, 2.8] Angstrom 
   self.step = [0.05, 0.06, 0.08, 0.1, 0.1, 0.1, 0.1, 0.1, 0.1, 0.1] r = [2.2, 2.3, 2.4, 2.5] Angstrom
   ```
   
   - Analysis incomplete: Skipped data from the begining - 0, 10000, 15000. Final results are shown for preskip 0.
   
   
 - [x] Simulations at **fixed beta = 0.256 K<sup>-1</sup>** for **N=[2, 4, 6, 8, 10, 12, 14, 16]**

   -----------------------------------------------------------------------------------------------------------------
   ```
   Type of potential: caleng_tip4p_gg.f;   unit: inverse Kelvin
   ```
   
   ```      
   P    = [5, 9, 17, 33, 65, 129] 
   ```		
   
   -----------------------------------------------------------------------------------------------------------------
   
    ```
   MC Blocks=40,000
   MC Pass=100
   
   **Expectation values are estimated at the last MC Pass in MC simulations.**
   ```
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks40000-Passes100-System2-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks40000-Passes100-System4-p-H2O-e0vsbeads*~
   
   P=129 is not finished!
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks40000-Passes100-System6-p-H2O-e0vsbeads*~
   
   P=65, 129 are not completed!
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks40000-Passes100-System8-p-H2O-e0vsbeads*~
   
   P=65, 129 are not completed!
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks40000-Passes100-System10-p-H2O-e0vsbeads*~
   
   P=65, 129 are not completed!
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks40000-Passes100-System12-p-H2O-e0vsbeads*~
   
   P=33, 65, 129 are not completed!
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks40000-Passes100-System14-p-H2O-e0vsbeads*~
   
   P=33, 65, 129 are not completed!
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-beta0.256Kinv-Blocks40000-Passes100-System16-p-H2O-e0vsbeads*~
   
   P=33, 65, 129 are not completed!
   
   Analysis incomplete: Skipped data first 0, 20000, 30000, 35000. Final results are shown for preskip 0.
   
   
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
   
 - [x] Simulations at **fixed beta = 0.256 K<sup>-1</sup>** for **N=1**
   
   -----------------------------------------------------------------------------------------------------------------
   ```
   Type of potential: -F.cos(theta); F=[10, 20, 30, 40, 50] inverse Kelvin
   ```
   
   ```      
   P    = [5, 9, 17, 33, 65, 129, 257] 
   ```		
   
   -----------------------------------------------------------------------------------------------------------------
   
    ```
   MC Blocks=20,000
   MC Pass=50
   
   **Expectation values are estimated at the last MC Pass in MC simulations.**
   ```
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field10.0Kinv-beta0.256Kinv-Blocks20000-Passes50-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field20.0Kinv-beta0.256Kinv-Blocks20000-Passes50-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field30.0Kinv-beta0.256Kinv-Blocks20000-Passes50-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field40.0Kinv-beta0.256Kinv-Blocks20000-Passes50-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field50.0Kinv-beta0.256Kinv-Blocks20000-Passes50-System1-p-H2O-e0vsbeads*~
   
    
   Analysis complete: Final results are esimated after skipping 0, 10000 and 15000 lines from the begining.
   
   
   -----------------------------------------------------------------------------------------------------------------
  
   ```
   MC Blocks=10,000
   MC Pass=100
   ```		
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field10.0Kinv-beta0.256Kinv-Blocks10000-Passes100-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field20.0Kinv-beta0.256Kinv-Blocks10000-Passes100-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field30.0Kinv-beta0.256Kinv-Blocks10000-Passes100-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field40.0Kinv-beta0.256Kinv-Blocks10000-Passes100-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field50.0Kinv-beta0.256Kinv-Blocks10000-Passes100-System1-p-H2O-e0vsbeads*~
   
    
   Analysis complete: Final results are esimated after skipping 0, 10000 lines from the begining.   
   
   -----------------------------------------------------------------------------------------------------------------
   
   ```
   MC Blocks=5000
   MC Pass=200
   ```
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field10.0Kinv-beta0.256Kinv-Blocks5000-Passes200-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field30.0Kinv-beta0.256Kinv-Blocks5000-Passes200-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field40.0Kinv-beta0.256Kinv-Blocks5000-Passes200-System1-p-H2O-e0vsbeads*~
   
   - ~/scratch/tapas/nonlinear-rotors/PIGS-RotDOFs-Rpt10.05Angstrom-Field50.0Kinv-beta0.256Kinv-Blocks5000-Passes200-System1-p-H2O-e0vsbeads*~
   
    
   Analysis complete: Final result is esimated after skipping 0 lines from the begining.  
   
  
./symrho.x  0.37  128  3 0  0   5.1820   0.851794  66
   


