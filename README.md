# naturalBlend
This repository contains information and data to reproduce our experiments on combining acoustic and linguistic features for expressive prosody analysis and generation as described in the author's publication [1].

In order to reproduce the experiments described in Dominguez et al., 2016 you need to firstly download and install the Weka Data Mining software [2] from the following link http://www.cs.waikato.ac.nz/ml/weka/downloading.html

###################

Once you launch Weka, you can open the arff file containing the data you want to reproduce, select the J48 tree classifier and run the classification.

The following datasets are currently available:

- "hierarchical_ispros.arff": contains labeled data following the prosodic schema described in (Dominguez et al., 2016) and the hierarchical information structure annotation described in [3,4]
- "baseline.arff": contains a lalebed data as described in the ToBI convention [5] 
- "spk1f.arff": a filtered selection of data from spk1f (extracted from "hierarchical_ispros.arff") 
              Speaker's State of origin: New York
- "spk1m.arff": a filtered selection of data from spk1m (extracted from "hierarchical_ispros.arff")
              Speaker's State of origin: Illinois
- "spk2m.arff": a filtered selection of data from spk2m (extracted from "hierarchical_ispros.arff")
              Speaker's State of origin: Texas
- "spk4m.arff": a filtered selection of data from spk4m (extracted from "hierarchical_ispros.arff")
              Speaker's State of origin: Massachusetts
- "spk5f.arff": a filtered selection of data from spk5f (extracted from "hierarchical_ispros.arff")
              Speaker's State of origin: Arizona



###################
# References

- [1] Domínguez M, Farrús M, Wanner L.  2016.  Combining Acoustic and Linguistic Features in Phrase-Oriented Prosody Prediction. 8th International Conference on Speech Prosody (SP2016).
- [2] Mark Hall, Eibe Frank, Geoffrey Holmes, Bernhard Pfahringer, Peter Reutemann, Ian H. Witten (2009). The WEKA Data Mining Software: An Update. SIGKDD Explorations, Volume 11, Issue 1.
- [3] Domínguez M, Farrús M, Burga A, Wanner L.  2016.  Using Hierarchical Information Structure for Prosody Prediction in Content-to-Speech Application. 8th International Conference on Speech Prosody (SP2016).
- [4] Domínguez M, Farrús M, Burga A, Wanner L.  2014.  The Information Structure-Prosody Interface Revisited. Proceedings of the 7th International Conference on Speech Prosody (SP2014).
- [5] Silverman K, Beckman M, Pitrelli J, Ostendorf M, Wightman C, Price P, Pierrehumbert J, and
Hirschberg J. 1992. TOBI: A Standard for Labeling English Prosody. In 2nd Internatioanl Conference on Spoken Language Processing (ICSLP 92), no. October, pp. 867–870.
