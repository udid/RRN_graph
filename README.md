# RRN_graph



# train commands:
py train.py -g Asterix -alg DQN -af lrelu -s 0
py train.py -g Asterix -alg DDQN -af lrelu -s 0
py train.py -g Asterix -alg DQN -af rat -s 0
py train.py -g Asterix -alg DQN -af recrat-s 0

# plot command:
py scores_evolutions_graph.py -g Asterix -s

# the dest graph will be saved under:
/images/scores_graphs/Asterix_scores.svg

