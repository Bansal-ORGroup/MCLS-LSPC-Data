We provide details of what each of the instances include and what the parameter denote using the 40x1x1 as an example:

T = 40;
T is Number of time periods in the planning horizon


Demand = [571, 495, 592, 488, 427, 561, 459, 537, 506, 471, 508, 541, 538, 594, 556, 480, 532, 435, 495, 548, 560, 402, 585, 546, 446, 450, 557, 551, 454, 534, 501, 454, 527, 498, 592, 423, 440, 403, 549, 424];
Demand is an array of size T consisting of demands in each period of the planning horizon


p_t = [0.58, 0.71, 0.88, 0.53, 0.71, 0.84, 0.63, 0.84, 0.51, 0.92, 0.96, 0.8, 0.64, 0.74, 0.6, 0.63, 0.91, 0.96, 0.81, 0.54, 0.52, 0.65, 0.82, 0.89, 0.59, 0.62, 0.77, 0.93, 0.56, 0.85, 0.88, 0.97, 0.84, 0.92, 0.83, 0.56, 0.84, 0.97, 0.75, 1];
p_t is an array of size T consisting of per unit production cost in each period of the planning horizon


q1t = [2979, 2905, 2920, 2937, 3086, 3100, 2867, 3002, 2885, 3093, 2895, 3016, 2930, 2884, 3134, 2911, 2958, 3137, 3088, 3044, 2915, 2877, 3083, 2965, 2970, 2904, 3020, 2870, 3069, 3046, 3133, 2980, 3056, 3035, 3000, 2951, 3114, 2928, 3096, 3003];
q2t = [6066, 6059, 6177, 5906, 6191, 5899, 6001, 6124, 6069, 6173, 5873, 5999, 5901, 5896, 5881, 6125, 5936, 6042, 6118, 6086, 6112, 6119, 6194, 5961, 6130, 6141, 6184, 6164, 5863, 6145, 6064, 5947, 6012, 5980, 5974, 6051, 5921, 6001, 6057, 6007];
q1t and q2t are arrays of size T consisting of setup costs of machines 1 and machine 2, respectively in each period of the planning horizon


C1 = 670;
C2 = 1280;
C1 and C2 are capacities of machines 1 and 2, respectively.