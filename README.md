This is the implementation of the paper "Which attributes matter the most for loan origination? A neural attention approach". The paper was published in the Robust AI for Financial Services workshop in NeurIPS 2019. You can find the paper [here](https://sites.google.com/view/robust-ai-in-fs-2019/paper-downloads).


The data were from Home Mortgage Disclosure Act(HMDA), which you can find [here](https://www.consumerfinance.gov/data-research/hmda/). More specificallly we chose the "HDMA Washington State Home Loans, 2016".


Also you can read on the paper, that I made some simple preprocessing on the data, which are not included in this repository.

<h3>Overview of the files</h3>
<ul>
  <li><b>main_code.ipynb:</b> this is the main code with the Encoder Decoder with neural attention model.</li>
  <li><b>simple_nn.ipynb:</b> this is the file that has the implementation of a simple NN with the data.</li>
  <li><b>basic_ml_methods:</b> in this file you can find simple implenetations of some basic ML methods that we used for comparison </li>
</ul>

<h3>Abstract</h3>
In this paper we address the problem that we get an understanding of why a deep learning model decides that an individual is eligible for a loan or not. Here we propose a novel approach for inferring, which attributes matter the most for making a decision in each specific individual case. Specifically we leverage concepts from neural attention to devise a novel feature wise attention mechanism. As we show, using real world datasets, our approach offers unique insights into the important of various features. At the same time, we observe that our novel mechanism, generates decisions which are much closer to the decision generated human experts, compared to the existent competitors.
