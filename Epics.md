
## Abstract 
The study of wildlife activity patterns provides insights into evolutionary adaptations, bioenergetics, foraging strategies, and physiological
responses to environmental cues. Activity patterns have been studied intensively and for a vast range of taxa with methods ranging from direct observations to displacement indices obtained from GPS-tags. However, there is a strong and methological determined bias towards larger taxa while most species inhabiting and shaping this planet are small. Existing technological solutions for activity data generation are either to large and heavy for most species (GPS, accelerometer) or require many hours of filedwork resulting in poor resolution data (manual VHF-telemetry). Kays et al 2011 proposed, that analysing the signal strength variation of autmatically detected VHF-signals enables the distinction between active and passive behaviour by a simple threshold. However, despite the promising possibilities offered by this technology, the studies applying the method are scarce. This may be partially explained by the expensive and customized technology the authors used. Recent developments allow a low-cost and open-source implementation of automatic radio-tracking. In this study we deployed an automatic radio-tracking system in a managed forest in mid Germany. XX Birds and XX Bats were equipped with vhf-tags and permanently recorded, resulting in 0.5-2 signals per second. In total the behaviour of xx Birds was observed in the field for xx hours resulting in xx hours of behavioural observaion. The behavior of xx bats was automatically observed by a system specially developed for this purpose (BatRack) and recordings were manually classified resulting in xx hours of behavioural observations. We will use the classified behavioural episodes to tune a machine learning classifier and will predict the behaviour of xx bats and xx birds. We calculated actograms and activity overlaps between individuals and species and investigate the influence of climatic factors on activity patterns.

- Author List: Jannis Gottwald, Kim Lindner,Patrick Lampe, Sascha Rösner, Dana Schabo, Raphaël Royauté, Julia Maier, Lea Leister, Sven Portig, Daniel Linke, Nicolas Friess, Thomas Müller, Nina Farwig and Thomas Nauss



- [x] Story 1: collect field data and tag it 
    - [x] Tag bats and birds (ÖP4, ÖP6)
    - [x] Observe behaviour of birds (Sven & Daniel)
    - [x] Tag VHF data according to behavioural observations of Birds (Sven & Daniel) (completed 27.01.2021)
    - [x] Classify BatRack observations (Lea & Julia) [Done]
    - [x] Tag VHF data according to behavioural observations of bats (Lea & Julia) (completed 27.01.2021)

- [ ] Story 2: calculate machine learning model 
    - [x] Control quality of tagge data (Jannis) [Done] (completed 10.02.2021)
    - [x] Create data set (Jannis) [Done] (completed 10.02.2021)
    - [x] Generate additional features to support modelling quality (Jannis) (completed 10.02.2021)
    - [x] Conduct ffs modelling testing svm and rf (Jannis) (completed 15.02.2021)
    - [x] Predict based on best model (Jannis) (completed 15.02.2021)
    - [ ] Manual filtering of bird datasets 2019 (Raph) [Todo]
    - [ ] Manual filtering of bird datasets 2020 (Raph) [70%]
    - [ ] Predict based on bat model (Jannis) 2020 [33%]
    - [ ] Predict based on bat model (Jannis) 2019 [Todo]
 
 - [ ] Story 3: Data analysis - Effect of abiotic conditions on bird & bat activity
    - [x] Preliminanry analyses based on bat 2020 dataset (Raph) (completed 10.05.2021)
    - [ ] Discuss analyses and how to deal with measurement biases/error (Sascha, Dana, Jannis, Nina, Raph, Thomas) [Todo]
    - [ ] Integrate bird & bat 2019-2020 datasets (Raph) [Todo]
    - [ ] Run final analyses (Raph, Dana, Jannis) [Todo]
    
    ..................
