## IndependenceDegree_OverlapDegree_Software
   Quantification of two adsorption behaviors discovered by big data mining
## Software function：
   The software quantifies the distribution of adsorption positions of two molecular clusters in the nanoporous material, and can intuitively judge their adsorption distances by the degree of independence and overlap.
## Steps to use the software
     1.Input atomic three-dimensional coordinate files of all molecules in two molecular clusters into the software respectively.
       The following is an example of A molecular cluster coordinate file. Example file format:“A.txt”
           1.4686	2.0112	0.8942
           1.4420	2.0368	0.9513
           1.4700	1.9910	0.9004
           1.4311	2.0395	0.9629
           1.4680	2.0119	0.9050
           1.4247	2.0463	0.9788
           1.4531	2.0146	0.9183
           1.4420	2.0501	0.9794
           1.4614	2.0126	0.9186
           1.4476	2.0528	0.9091
           1.4809	2.0072	0.8613
           1.4415	2.0471	0.9861
           1.4788	2.0139	0.9314
           1.4392	2.0570	0.9297
           1.4783	2.0111	0.8868
           1.4314	2.0378	0.9197
           1.4641	1.9951	0.8689
           1.4422	2.0564	0.9413
           1.4839	2.0205	0.8918
           1.4349	2.0535	0.9309
        (Tip: All the coordinates above are in nanometers.)
     2.Enter the threshold value and click calculation to obtain the percentage of overlap degree and independence degree between the adsorption positions of two molecular clusters
## Note: 
     If the distance between each molecule in two molecular clusters is too far for competitive adsorption to exist, it will directly indicate "No competitive adsorption occupancy phenomenon".
     If each molecule in two molecular clusters is too close to each other to have independent occupying phenomenon, the direct indication is "No independent occupancy phenomenon".
