# spartan2:

**spartan2** is a collection of data mining algorithms on **big graphs** and
**time series**, as graphs and time series are fundamental representations of many key applications 
in a wide range of users' online behaviors (e.g. social media, shopping, Apps), 
finance (e.g. stock tradings, bank transfers), IoT networks (e.g. sensor readings, smart power grid), and healthcare (e.g. electrocardiogram, photoplethysmogram, respiratory inductance plethysmography). 

In practice, we find that thinking graphs and time series as matrices or tensors
can enable us to find efficient (near linear), interpretable, yet accurate solutions in many applications.

Therefore, we want to develop a collectioin of algorithms on graphs and time series based
on tensors (matrix is a 2-mode tensor). In real world, those tensors are sparse, and we
are required to make use of the sparsity to develop efficient algorithms. That is why
we name the package of algorithms as 

**SparTan**: **Spar**se **T**ensor **An**alytics.

spartan2 is backend of SparTAn.
Everthing here is viewed as a tensor (sparse).

## install requires

 This project is written in Python 3.6
 We suggest recreating the experimental environment using Anaconda through the following steps.
 
1. Clone the project
```bash
git clone https://github.com/shenghua-liu/spartan2.git
```
2. Install the appropriate version for Anaconda from here - https://www.anaconda.com/distribution/

3. Create a new conda environment named "eigenpulse" and install requirements.
```bash
conda create -n spartan python=3.6
conda activate spartan
pip install --user --requirement requirements
```

4. install code in development mode
```bash
pip install -e spartan2
```

## run the project demos in jupyter notebook:

1. start jupyter notebook
2. click to see each jupyter notebook (xxx.ipynb) demo for each algorithm, or see the following guidline.


## Table of Contents

**Part 1: Basic**
* [Quick start](https://github.com/shenghua-liu/spartan2/blob/master/quick_start.ipynb)


**Part 2: Big Graphs**
* [Load graph](https://github.com/shenghua-liu/spartan2/blob/master/ioutil_demo.ipynb)
* [SVD](https://github.com/shenghua-liu/spartan2/blob/master/SVD_demo.ipynb)
* [Eaglemine](https://github.com/shenghua-liu/spartan2/blob/master/Eaglemine_demo.ipynb)
* [Fraudar](https://github.com/shenghua-liu/spartan2/blob/master/Fraudar_demo.ipynb)
* [Holoscope](https://github.com/shenghua-liu/spartan2/blob/master/Holoscope_demo.ipynb)

**Part 3: Time Series**
* [Load time series](https://github.com/shenghua-liu/spartan2/blob/master/TimeseriesData_demo.ipynb)
* [Beatlex](https://github.com/shenghua-liu/spartan2/blob/master/Beatlex_demo.ipynb)

## References
1. Shenghua Liu, Bryan Hooi, Christos Faloutsos, A Contrast Metric for Fraud Detection in Rich Graphs, IEEE Transactions on Knowledge and Data Engineering (TKDE), Vol 31, Issue 12, Dec. 1 2019, pp. 2235-2248.
1. Shenghua Liu, Bryan Hooi, and Christos Faloutsos, "HoloScope: Topology-and-Spike Aware Fraud Detection," In Proc. of ACM International Conference on Information and Knowledge Management (CIKM), Singapore, 2017, pp.1539-1548.
2. Prakash, B. Aditya, Ashwin Sridharan, Mukund Seshadri, Sridhar Machiraju, and Christos Faloutsos. "Eigenspokes: Surprising patterns and scalable community chipping in large graphs." In Pacific-Asia Conference on Knowledge Discovery and Data Mining, pp. 435-448. Springer, Berlin, Heidelberg, 2010.
3. Wenjie Feng, Shenghua Liu, Christos Faloutsos, Bryan Hooi, Huawei Shen, Xueqi Cheng, EagleMine: Vision-Guided Mining in Large Graphs, ACM SIGKDD 2018, ODD Workshop on Outlier Detection De-constructed, August 20th, London UK.
4. Bryan Hooi, Shenghua Liu, Asim Smailagic, and Christos Faloutsos, “BEATLEX: Summarizing and Forecasting Time Series with Patterns,” The European Conference on Machine Learning & Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD), Skopje, Macedonia, 2017.
5. Hooi, Bryan, Hyun Ah Song, Alex Beutel, Neil Shah, Kijung Shin, and Christos Faloutsos. "Fraudar: Bounding graph fraud in the face of camouflage." In Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, pp. 895-904. 2016.
