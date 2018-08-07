# functionMaximize
Genetic algorithm for function maximization

## Steps:
  1. Initialization with random numbers from specified numbers section
  2. Tournament selection
  3. Binary crossing
  4. Mutation by inverting bit with specified probability

## Example:  
  representation - 10b number  
  population = 30  
  mutation probability = 0.01 (for each bit)
  function = 0.3 * sin(x) + sin(1.3 * x) + 0.9 * sin(4.2 * x)
  interval = <-5, 4>
    
## Results:  
  #### Average population score:  
  ![Average score](https://github.com/bartas28/functionMaximize/blob/master/results/averages.png)  
  
  #### Generation 1 (Best val: 1.53702158431 best x: 0.472140762463 avg: 0.336649064865)   
  ![Generation 1](https://github.com/bartas28/functionMaximize/blob/master/results/gen1.png)  
  Unfortunatelly the best units are on the wrong slope, they will probably dominate the population.  
  
  #### Generation 2 (Best val: 1.53782221007 best x: 0.454545454545 avg: 0.605362455655)  
  ![Generation 2](https://github.com/bartas28/functionMaximize/blob/master/results/gen2.png)  
  
  #### Generation 3 (Best val: 1.53782221007 best x: 0.454545454545 avg: 0.827660819709)  
  ![Generation 3](https://github.com/bartas28/functionMaximize/blob/master/results/gen3.png)  
  
  #### Generation 4  
  ![Generation 4](https://github.com/bartas28/functionMaximize/blob/master/results/gen4.png)  
  
  #### Generation 5  
  ![Generation 5](https://github.com/bartas28/functionMaximize/blob/master/results/gen5.png) 
  
  #### Generation 6 (Best val: 1.53782221007 best x: 0.454545454545 avg: 1.36107518129)  
  ![Generation 6](https://github.com/bartas28/functionMaximize/blob/master/results/gen6.png)  
  
  #### Generation 7  
  ![Generation 7](https://github.com/bartas28/functionMaximize/blob/master/results/gen7.png)  
  
  #### Generation 8 (Best val: 1.53803571627 best x: 0.463343108504 avg: 1.44312932617)  
  ![Generation 8](https://github.com/bartas28/functionMaximize/blob/master/results/gen8.png)  
  
  #### Generation 9  
  ![Generation 9](https://github.com/bartas28/functionMaximize/blob/master/results/gen9.png)  
  
  #### Generation 10  
  ![Generation 10](https://github.com/bartas28/functionMaximize/blob/master/results/gen10.png)  
  Every unit managed to find local function maximum. To escape this situation there must be lucky mutation.  
  
  #### Generation 15 (Best val: 1.95020379511 best x: -4.04105571848 avg: 1.54520806638)  
  ![Generation 15](https://github.com/bartas28/functionMaximize/blob/master/results/gen15.png)  
  Nothing happened for 4 generations, but luckily an unit mutated and got to global maximum. It will probably dominate the population.  
  
  #### Generation 16  
  ![Generation 16](https://github.com/bartas28/functionMaximize/blob/master/results/gen16.png)  
  
  #### Generation 17  
  ![Generation 17](https://github.com/bartas28/functionMaximize/blob/master/results/gen17.png)  
  
  #### Generation 19  
  ![Generation 19](https://github.com/bartas28/functionMaximize/blob/master/results/gen19.png)  
  
  #### Generation 20 (Best val: 1.95020379511 best x: -4.04105571848 avg: 1.67538949152)  
  ![Generation 20](https://github.com/bartas28/functionMaximize/blob/master/results/gen20.png)  
  
  #### Generation 22 (Best val: 1.96278793785 best x: -4.07624633431 avg: 1.69613965544)  
  ![Generation 22](https://github.com/bartas28/functionMaximize/blob/master/results/gen22.png)  
  
  #### Generation 23  
  ![Generation 23](https://github.com/bartas28/functionMaximize/blob/master/results/gen23.png)  
  
  #### Generation 26  
  ![Generation 26](https://github.com/bartas28/functionMaximize/blob/master/results/gen26.png)  
  
  #### Generation 27 (Best val: 1.96278793785 best x: -4.07624633431 avg: 1.95809609464)  
  ![Generation 27](https://github.com/bartas28/functionMaximize/blob/master/results/gen27.png)  
  So it happened. Every unit got to the best slope.  
  
  #### Generation 28  
  ![Generation 28](https://github.com/bartas28/functionMaximize/blob/master/results/gen28.png)  
  
  #### Generation 29  
  ![Generation 29](https://github.com/bartas28/functionMaximize/blob/master/results/gen29.png)  
  
  #### Generation 30  
  ![Generation 30](https://github.com/bartas28/functionMaximize/blob/master/results/gen30.png)  
  
  #### Generation 31  
  ![Generation 31](https://github.com/bartas28/functionMaximize/blob/master/results/gen31.png)  
  
  #### Generation 32  
  ![Generation 32](https://github.com/bartas28/functionMaximize/blob/master/results/gen32.png)  
  
  #### Generation 33  
  ![Generation 33](https://github.com/bartas28/functionMaximize/blob/master/results/gen33.png)  
  
  #### Generation 34  
  ![Generation 34](https://github.com/bartas28/functionMaximize/blob/master/results/gen34.png)  
  
  #### Generation 35  
  ![Generation 35](https://github.com/bartas28/functionMaximize/blob/master/results/gen35.png)  
  
  #### Generation 38  
  ![Generation 38](https://github.com/bartas28/functionMaximize/blob/master/results/gen38.png)  
  
  #### Generation 41 (Best val: 1.96278793785 best x: -4.07624633431 avg: 1.9627445946)  
  ![Generation 41](https://github.com/bartas28/functionMaximize/blob/master/results/gen41.png)  
  
  #### Generation 44  
  ![Generation 44](https://github.com/bartas28/functionMaximize/blob/master/results/gen44.png)  
  
  #### Generation 45  
  ![Generation 45](https://github.com/bartas28/functionMaximize/blob/master/results/gen45.png)  
  
  #### Generation 50 (Best val: 1.96278793785 best x: -4.07624633431 avg: 1.96266648073)  
  ![Generation 50](https://github.com/bartas28/functionMaximize/blob/master/results/gen50.png)  
  
