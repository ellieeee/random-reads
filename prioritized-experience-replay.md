Link: https://arxiv.org/abs/1511.05952

Title: Prioritized experience replay

Notes:
- Vanilla experience replay, due to keeping limited experiences, may result in some experiences never replayed
- Vanilla experience replay also made only replay old experiences after thousands of updates
- Vanilla experience replay also prone to sampling old but seen experiences, which provides lesser learning value
- Prioritized experience replay allows the model to learn moderately fresh and unseen experiences mostly and thus maximizes learning, as a result the learning effort generally reduces significantly
