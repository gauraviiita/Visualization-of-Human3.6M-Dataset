# Visualization-of-Human3.6M-Dataset
Plot and save the ground truth  and predicted results of human 3.6 M and CMU mocap dataset.


## human-motion-prediction

This is the code for visulalizing the ground truth and predicted results of human 3.6M dataset. 


To save the gif for ground truth data, ru
```bash
python forward_kinematics.py --save --save_name "figs/walking.gif"

```

To save visualization for trained modeld sample.h5, run
```bash
 python forward_kinematics.py --sample_name samples.h5 --save --save_name "figs/walking_py_0.gif"
```

Finally, to visualize the samples run
```bash
python forward_kinematics.py
```


This should create a visualization similar to this one

<p align="center">
  <img src="https://raw.githubusercontent.com/una-dinosauria/human-motion-prediction/master/imgs/walking.gif"><br><br>
</p>


In data folder it has only subject 5 due to space constraint.

## To download full dataset follow this

mkdir data
cd data
wget http://www.cs.stanford.edu/people/ashesh/h3.6m.zip
unzip h3.6m.zip
rm h3.6m.zip
cd ..

### Acknowledgments

Julieta Martinez, Michael J. Black, Javier Romero.
_On human motion prediction using recurrent neural networks_. In CVPR 17.

It can be found on arxiv as well: https://arxiv.org/pdf/1705.02445.pdf

The code in this repository was written by [Julieta Martinez](https://github.com/una-dinosauria/) and [Javier Romero](https://github.com/libicocco/).

### Thank you
Gaurav
