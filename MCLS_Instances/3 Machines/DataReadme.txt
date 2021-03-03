We provide details of what each of the MCLS with n=3 instances include and what the parameter denote using the 40x1x1 as an example:

T = 40;
T is Number of time periods in the planning horizon


Demand = [599, 413, 404, 569, 437, 409, 432, 567, 585, 575, 495, 459, 536, 442, 405, 417, 592, 553, 401, 503, 498, 528, 570, 413, 513, 514, 499, 491, 567, 506, 486, 543, 417, 420, 424, 450, 599, 429, 434, 463];
Demand is an array of size T consisting of demands in each period of the planning horizon


p_t = [0.66, 0.51, 0.82, 0.92, 0.72, 0.94, 0.61, 0.82, 0.55, 0.96, 0.72, 0.74, 0.96, 0.7, 0.54, 0.64, 0.86, 0.97, 0.84, 0.89, 0.62, 0.94, 0.69, 0.81, 0.83, 0.65, 0.62, 0.77, 0.99, 0.74, 0.72, 0.55, 0.74, 0.84, 0.97, 0.61, 0.66, 0.52, 0.61, 0.91];
p_t is an array of size T consisting of per unit production cost in each period of the planning horizon


q1t = [3023, 2953, 2894, 3132, 3092, 3058, 2859, 3082, 3038, 3048, 3053, 3016, 2921, 2964, 3024, 3130, 2876, 2887, 3129, 3150, 2916, 3086, 3124, 2942, 3147, 2936, 2900, 3126, 3069, 3040, 2906, 2855, 3129, 3072, 3137, 2919, 3046, 2868, 2873, 2979];
q2t = [5871, 5970, 5872, 5871, 6079, 5991, 6117, 5914, 5885, 6088, 6005, 6196, 6074, 5900, 5948, 5853, 6013, 6047, 5969, 5867, 5973, 6027, 6031, 6159, 5855, 5859, 6002, 6007, 5962, 5888, 5903, 5858, 6148, 6198, 6183, 5952, 5896, 5877, 6016, 5877];
q3t = [9062, 9165, 8879, 9088, 8932, 9062, 9106, 8919, 9193, 9071, 9087, 8850, 9111, 8915, 9093, 9065, 9140, 9003, 9055, 9162, 8876, 9145, 8818, 9114, 8827, 9076, 8977, 8956, 9185, 9090, 8955, 8947, 8945, 9118, 9163, 9045, 9065, 8888, 9184, 8909];
q1t, q2t, and q3t are arrays of size T consisting of setup costs of machines 1, machine 2, and machine 3, respectively in each period of the planning horizon


C1 = 970;
C2 = 1950;
C3 = 2810;
C1, C2, and C3 are capacities of machines 1, 2 and 3, respectively.



