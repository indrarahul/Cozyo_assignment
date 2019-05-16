# Cozyo Assignment



### 1. What are the main drawbacks, if any, of training models in visual recognition tasks through the use of synthetic data?
The following may be the drawbacks in training visual recognition models using synthetic data-
- The success of the venture depends largely on the goodness of the model, which cannot be taken for granted unless it performs well in real life situations. Thus, it is difficult to ensure the success of the model without rendering it in the real world, which in turn may be risky.
- The "simulation-to-reality" gap is often significant enough to make the model unfit for use in real life.
- The synthetic data is generated following some algorithm, designed by a human. As human imagination is limited by experience, nature might throw in some surprises to the application trained on the synthetic data, which it might not be able to process correctly.
- Any simulation based on synthetic data, thus, has to take into account the exception handling risk, i.e., the risk associated with the scenario where the application based on the simulation faces some unforeseen exception.
- More often than not, the synthetic data generated cannot be considered fool-proof on its own, and has to be validated against real-life data. This validation process might defeat the original purpose behind generating synthetic data, as it can take significant time and effort.
- Synthetic data generating algorithms often result in inconsistencies when trying to replicate complexities or anomalies within the original datasets.
- One possible motivation behind trying to generate synthetic data might be lack of experience in certain fields. This cannot reasonably be solved by synthetic data generating algorithms, for obvious reasons.

### 2. What pitfalls can you identify, that may cause a straight-forward utilization of this training approach to produce models with very poor inference accuracy on real test samples?
It is possible for a model trained on synthetic data to give poor accuracy on real test samples. This might occur due to the following reasons-
- The algorithm generating the synthetic data for training may have made improper generalizations on the original dataset, thus causing the model being trained to stray from the original distribution.
- In some applications like disease detection from symptoms, the available data for positive diagnosis is likely to be outweighed by the data available for negative diagnosis. This might make it even more difficult for the generating algorithm to produce useful data for the positive diagnosis set, defeating the purpose of the application.
- The limitation of human imagination may result in a restricted view of the dataset, which in turn would cause the synthetic dataset to be incomplete, thus failing to properly represent the actual real life scenario.
- Some anomalies like those during natural disasters are not possible to be represented accurately beforehand. If the model is not robust enough to deal with such anomalies, poor accuracy and improper behaviour of the resulting application would take place.

### 3. Putting aside the case of autonomous driving, what are some use cases that may not be suited for visual recognition training with synthetic data, and why are they not suitable?
- Fraudulent activity detection
    - Fraudulent activities are usually outliers from the general user activities, and models can be trained to detect such activities. Using synthetic data, however, fraudulent activities which are unique or unforeseen might not be able to be represented. Also, some anomalous user activity, though innocent, may be replicated by the generating algorithm, therefore jeopardizing the stability of the model.
- Face Recognition
    - Real faces are required for this purpose, with a real identity. Generating synthetic data would, therefore, be meaningless for face recognition.
- Object Recognition
    - Models trained on only synthetic data are usually worse than a model trained on small data set containing real images.
    - Synthetic data might not be good enough yet for a model to train on exclusively but it can be used as a tool when no other data exists. 

- Use of Visual Recognition in Healthcare Industry
    - eg., in disease diagnosis- As discussed earlier, this might lead to incorrect diagnosis as the data for negative diagnosis usually outweighs that for a positive diagnosis.



### Resources
- Google
- arxiv.org
- https://www.analyticsindiamag.com/can-synthetic-data-solve-the-bulk-data-problem-in-deep-learning/
- https://www.forbes.com/sites/bernardmarr/2018/11/05/does-synthetic-data-hold-the-secret-to-artificial-intelligence/#62db63e542f8
- https://www.ingedata.net/blog/machine-learning-algorithms-fake-data
- https://blog.aimultiple.com/synthetic-data/
- https://www.analyticsindiamag.com/8-uses-cases-of-image-recognition-that-we-see-in-our-daily-lives/
- Junyao Guo, Unmesh Kurup, Mohak Shah "Is it Safe to Drive? An Overview of Factors,
Challenges, and Datasets for Driveability Assessment in Autonomous Driving" ,  arXiv:1811.11277v1 27 Nov 2018
- Braden Hurl, Krzysztof Czarnecki, Steven Waslander "Precise Synthetic Image and LiDAR (PreSIL) Dataset for Autonomous Vehicle Perception" , arXiv:1905.00160v2 7 May 2019
- Magnus Wrenninge, Jonas Unger "Synscapes: A Photorealistic Synthetic Dataset for Street Scene Parsing", arXiv:1810.08705v1 19 Oct 2018
- Love Lidberg "Object Detection using deep learning and synthetic data", LiU ITN-TEK A 18/030 SE

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
