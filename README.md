# RealTimeCommunityDetection

This repository is the supplementary material to my intervention to CAID conference: https://www.european-cyber-week.eu/conference-caid

One can find here a notebook used to generate plots of the graph with display options.
For this notebook, one needs the list of the 86346 events the occured on system 201 on attack day 1.

This list is precessed to extract a smaller one named "list_edges_successively_unique" without any dobbled consecutive events with respect to: start, end, action, command_line and pid.
That is to say that changing timestamp makes consecutive edges different.

Then, for the plots, the file "pos_kamada_whole_graph.pkl" is used. This file contains the positions of all nodes of the graph.

Videos are also available at:  https://www.youtube.com/watch?v=caWTa7xIFPs and https://www.youtube.com/watch?v=LPBuE0kBIr4

In addition, one can find some images and gif in file "annexe".
Sorry, I was not able to upload raw data concerning system 201 because the dataframe is 29Mo big.
Send me an email at genetay.edouard@gmail.com or egenetay@lumenai.fr if your are interested in.
