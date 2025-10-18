# FIR Low-Pass Filter Design and Analysis

## Author
Md Mahfuzur Rahaman 
Date: 2025-10-18 

## MATLAB Version
MATLAB R2025a

## Figures
- `figures/hLP_M20.png` → Impulse response for M=20  
- `figures/hLP_M64.png` → Impulse response for M=64  
- `figures/HLP_compare.png` → Comparison of magnitude responses for M=20 and M=64  

## Observations
1. Increasing the filter order M makes the transition band narrower, producing a sharper cutoff.  
2. The impulse response becomes longer as M increases.  
3. Higher M reduces frequency ripples in the passband and stopband, giving a smoother frequency response.  
4. For M=64, the filter approximates an ideal low-pass filter more closely than M=20.  

## Notes
- The special case n = M/2 is handled to avoid division by zero in the impulse response formula.
