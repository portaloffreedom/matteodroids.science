---
title: "Morpho-evolution with learning using a controller archive as an inheritance mechanism"
date: 2022-02-02T16:05:42+01:00
draft: false
pub_type: "journal"
journal: "IEEE Transactions on Cognitive and Developmental Systems"
authors: ["Léni K. Le Goff","Edgar Buchanan","Emma Hart","Agoston E. Eiben","Wei Li","Matteo De Carlo","Alan F. Winfield","Matthew F. Hale","Robert Woolley","Mike Angus","Jon Timmis","Andy M. Tyrrell"]
doi: "10.1109/TCDS.2022.3148543"
---

Most work in evolutionary robotics centres on evolving a controller for a fixed body-plan. However, previous studies suggest that simultaneously evolving both controller and body-plan could open up many interesting possibilities. However, the joint optimisation of body-plan and control via evolutionary processes can be challenging in rich morphological spaces. This is because offspring can have body-plans that are very different from either of their parents, leading to a potential mismatch between the structure of an inherited neural controller and the new body. To address this, we propose a framework that combines an evolutionary algorithm to generate body-plans and a learning algorithm to optimise the parameters of a neural controller. The topology of this controller is created once the body-plan of each offspring has been generated. The key novelty of the approach is to add an external archive for storing learned controllers that map to explicit ‘types’ of robots (where this is defined with respect to the features of the body-plan). By initiating learning from a controller with an appropriate structure inherited from the archive, rather than from a randomly initialised one, we show that both the speed and magnitude of learning increases over time when compared to an approach that starts from scratch, using two tasks and three environments. The framework also provides new insights into the complex interactions between evolution and learning.
