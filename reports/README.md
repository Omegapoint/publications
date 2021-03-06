# Abstracts

## Detection of Illicit Access of Medical Records using Machine Learning
**Author** Ciwan Ceylan  
**Supervisor** David Strömberg  
**Published**  July, 2017

This is a preliminary study of possible application of machine learning and data mining methods to discover illicit use of Stockholm county’s medical record system. The users of the system have access to far more patient records than they are legally permitted to open, and therefore, information about each access event is registered for later analysis. Currently, the analysis is done via a rule-based system which is manually tuned, and supplemented by manual auditing. The aim of this study is to survey the literature and to suggest how the current analysis system could be complemented with the help of machine learning and data mining methods. The ambition is to increase both the precision and the coverage of the misconduct detection.

## Privacy Preserving Audit Proofs
**Author** Anton Lindqvist  
**Supervisor** Hannes Salin  
**Published**  June, 2017

The increased dependence on computers for critical tasks demands sufficient and trans- parent methods to audit its execution. This is commonly solved using logging where the log must not only be resilient against tampering and rewrites in hindsight but also be able to answer queries concerning (non)-membership of events in the log while preserv- ing privacy. Since the log cannot assume to be trusted the answers must be verifiable us- ing a proof of correctness.This thesis describes a protocol capable of producing verifiable privacy preserving membership proofs using Merkle trees. For non-membership, a method used to authenti- cate Bloom filters using Merkle trees is proposed and analyzed. Since Bloom filters are a probabilistic data structures, a method of handling false positives is also proposed.

## Analysis of Entropy Usage in Random Number Generators
**Author** Joel Gärtner  
**Supervisor** Hannes Salin  
**Published**  June, 2017


Cryptographically secure random number generators usually require an outside seed to be initialized. Other solutions instead use a continuous entropy stream to ensure that the internal state of the generator always remains unpredictable.
This thesis analyses four such generators with entropy inputs. Furthermore, different ways to estimate entropy is presented and a new method useful for the generator analy- sis is developed.The developed entropy estimator performs well in tests and is used to analyse en- tropy gathered from the different generators. Furthermore, all the analysed generators exhibit some seemingly unintentional behaviour, but most should still be safe for use.

## Predicting Customer Churn Using Recurrent Neural Networks
**Author** Jesper Ljungehed  
**Supervisor** David Strömberg  
**Published**  June, 2017


Churn prediction is used to identify customers that are becoming less loyal and is an im- portant tool for companies that want to stay competitive in a rapidly growing market. In retail, a dynamic definition of churn is needed to identify churners correctly. Customer Lifetime Value (CLV) is the monetary value of a customer relationship. No change in CLV for a given customer indicates a decrease in loyalty.
This thesis proposes a novel approach to churn prediction. The proposed model uses a Recurrent Neural Network to identify churners based on Customer Lifetime Value time series regression. The results show that the model performs better than random. This thesis also investigated the use of the K-means algorithm as a replacement to a rule- extraction algorithm. The K-means algorithm contributed to a more comprehensive an- alytical context regarding the churn prediction of the proposed model.
