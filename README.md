# latestHPX_Rotate

1. Results listed in Three status rotate results_latestHPX.pptx: https://github.com/hcq9102/latestHPX_Rotate/blob/main/Three%20status%20rotate%20results_latestHPX.pptx

327 updated: https://github.com/hcq9102/latestHPX_Rotate/blob/main/327Three%20status%20rotate%20results_latestHPX.pptx

401 updated: 


2. Three status_latestHPX_rawdata/

        o_324test file : original rotate
    
        s_324test file : splitcore func added rotate

        a_324test file : asynchronous(unneed) removed rotate 
        
        
3. LatestHPX:

        git log: commit 4b087d4341b65e4ae8c5fa636a3978c8f45aaa1c (HEAD -> master, origin/master, origin/HEAD)
        
4. Benchmark:        

        -> newfirst: set at inputsize/8
        -> dont consider the first 5 iterations(total 10) : 
                   modify if( NUM_ITERATIONS < 5) ... 
                   to         if (i < 5) ....
        

notice: 327 redo async part tests(the former modified hpx/rotate.hpp has a minor error ), the correct results updated in the ppt file as well. 
        ie. 327Three status rotate results_latestHPX.ppt

5. redo test on buran node:

        buranNodeTest401
