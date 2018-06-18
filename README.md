# TIMBERWOLF-SIMULATED-ANNEALING
Determining a perfect placement solution is an NP-complete problem. For any design of considerable size, finding a complete solution requires overwhelming computational effort. Placement is a minimization problem meaning that one placement which has lower cost than another is more desirable and a placement which has the least cost is considered as the optimum
Given: A set of n rectangular blocks 𝑖=1,2…𝑛
Circuit area 𝐴𝑖
Set of netlists (netlist) 𝑁={𝑁1,𝑁2… 𝑁𝑛} Interconnect length 𝐿𝑖 for net 𝑁𝑖 Timing of each building block 𝑇𝑖 Position of I/O pins on the pad frame
Goal: Minimized total IC area 𝐴𝑖(𝑛𝑒𝑤) Maximized routability of the interconnect 𝐶𝑖𝑗(𝑛𝑒𝑤) Minimized interconnect length 𝐿𝑖(𝑛𝑒𝑤) and Minimized time delay 𝑇𝑖(𝑛𝑒𝑤) of the critical net
