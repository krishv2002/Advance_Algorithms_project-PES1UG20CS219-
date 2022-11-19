# Advance_Algorithms_project-PES1UG20CS219-
Comparitive study on PageRank and Link Analysis Algorithms - 
This repo contains the implimentation of PageRank and HITS(Hyper-text induced search) link analysis methods using the netwrokx library of python.
Graphs are created for the input files whihc contain the edges in the webGraph in the format -   source   destination. The main file used for the computation is web-Google.txt(source - https://snap.stanford.edu/data/web-Google.html). Nodes represent web pages and directed edges represent hyperlinks between them. 
web-Google.txt contains 875713 nodes and 5105039 edges.

The repo contains two files - 
1. Adv_algo_final_project_differefnt_edges.ipynb - 
   The web-Google.txt is used to make 4 files - input1.txt,input2.txt,input3.txt,input4.txt which contain 20000,40000,60000 and 80000 edges respectively. Only these 4    files have been used as dataset here.
   The PageRank and HITS for these files have been computed with max_iter=10 for the 4 input files used as dataset.
   
2. Adv_algo_proj_differnet_max_iter.ipynb
   Here, the web-Google.txt is used to compute the PageRank and HITS of the graph structure. The computation is done for 20 iterations with a step size of 5 till          max_iter=100.
   
The time taken for computing each of the PageRank and HITS iteration is printed in both the files.

