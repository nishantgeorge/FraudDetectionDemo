- [x] TODO file
- [ ] Raw data generator. user<-->sorted sets of <timestamp, hash key name>. Transactions<--> hashes.
- [ ] Transactions generator. Samples a user id and transaction from https://www.kaggle.com/mlg-ulb/creditcardfraud
- [ ] KeysReader gear -> map(hashToTensor) on hash set event
- [ ] Execution gear trigger - (user(sorted set) id, timestamp1, timestamp2, transaction) - transaction is passed as raw data/tensoer?
- [ ] Naive Execution gear - Collector torch script over fixed amount of transaction tensors. Parallel execution (python threads) on two models and collect.
- [ ] AI develpop VARARGS scripts
- [ ] Move gear to use VARARGS script