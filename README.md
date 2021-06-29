# To recreate graphs from the paper: 
Delfosse, Quentin, et al. "Recurrent Rational Networks." arXiv preprint arXiv:2102.09407 (2021).


# Clone:
first clone the project repos from https://github.com/ml-research/rational_rl

# Update env:
pip install -r requirements.txt

# Train commands:
py train.py -g Asterix -alg DQN -af lrelu -s 0
py train.py -g Asterix -alg DDQN -af lrelu -s 0
py train.py -g Asterix -alg DQN -af rat -s 0
py train.py -g Asterix -alg DQN -af recrat-s 0

# Plot command:
py scores_evolutions_graph.py -g Asterix -s

# Dest graph will be saved under:
/images/scores_graphs/Asterix_scores.svg

