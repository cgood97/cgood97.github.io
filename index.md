## Background

We first tried to recreate "Predicting digital asset market based on blockchain activity data" found [here](https://arxiv.org/pdf/1810.06696.pdf).

After multiple roadblocks, we were able to start the initial sync with Parity Client. After 24 hours at full CPU usage, the inital sync was not even half complete. 

As a result, we decided to recreate a similar project, "Predicting Cryptocurrency Prices With Deep Learning" found [here](https://dashee87.github.io/deep%20learning/python/predicting-cryptocurrency-prices-with-deep-learning/).

Although this second source is not technically a "research paper," it is a good example of real world experience with deep learning. It is also extremely readable and requires very little technical roadblocks to setup.



## Summary of Original Paper

## Steps to Reproduce Original Experiment

Since the blog post provided a Jupyter Notebook with code and explanation on how to reproduce the experiment, it didn't take too many steps to get everything working. Here are the steps we took (using a Windows machine):

1. Download Repo located [here](https://github.com/dashee87/blogScripts)
2. Open Jupyter Notebook titled: 2017-11-20-predicting-cryptocurrency-prices-with-deep-learning located in the Jupyter folder.
3. Using Anaconda Prompt:<br/>
  a. Install Keras and Tensorflow<br/>
  b. Update Conda<br/>
  c. Downgrade Pandas to version 0.23.4<br/>
4. Install any other libraries using pip that throw an error in the Jupyter Notebook
5. Uncomment block 37 in Jupyter Notebook
6. Restart and run Jupyter Notebook
7. Wait until everything finishes (could take a few hours)

## Results of Original Experiment
<p align="left">
  <img src="https://i.ibb.co/TtfxxwZ/Training-Testing-Set.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/Wy2F6wb/Simple-Lag-Model.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/wB9jygY/Single-Point-Random-Walk-Test-Set.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/RPvHyVk/Full-Interval-Random-Walk.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/4SBLtcb/Single-Point-Random-Walk.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/j3brqPx/Training-Error.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/82K3n32/Training-Set-Single-Point-Timepoint-Prediction.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/TwqDLQR/Test-Set-Single-Timepoint-Prediction.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/KNzj3KD/Training-Set-Single-Point-Timepoint-Prediction-Bitcoin.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/3rxGZXP/Test-Set-Single-Timepoint-Prediction-Bitcoin.png">
</p>
<p align="left">
  <img src="https://i.ibb.co/FVTR385/Test-Set5-Timepoint-Predictions.png">
</p>
<p align="left">
  <img src="https://imgbb.com/"><img src="https://i.ibb.co/dcVy8VL/MAECharts.png">
</p>


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cgood97/cgood97.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
