# cqf-exam-three-machine-learning-solved
**TO GET THIS SOLUTION VISIT:** [CQF Exam Three Machine Learning Solved](https://www.ankitcodinghub.com/product/cqf-exam-three-machine-learning-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126093&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CQF Exam Three  Machine Learning Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<u>Instructions: </u>The submitted report must present work and outputs clearly separated by Question. Submit ONLY ONE zip file named LASTNAME.zip that includes pdf file, code, html, data and any other supporting or working files. Python notebook with auxiliary output (data, plots) is not an analytical report: such submission will receive a deduction.

Please do not discuss this assignment in groups or messengers. Raise a support ticket for your queries.

Only clarifying questions are allowed.

<u>Introduction: </u>Short-term asset return is a challenging quantity to predict. Efficient markets produce near-Normal daily returns with no significant correlation between <em>r<sub>t</sub></em>, <em>r<sub>t</sub></em><sub>−1</sub>. This exam is a limited exercise in supervised learning. You are expected to explore multiple features or may use a set of features from Table 1 without an expectation of predictive powers. Original and final selected features should be sufficiently large.

<h1>Objective</h1>
Your objective is to produce a model to predict positive moves (up trend) using machine learning models as specified in the below section. Your proposed solution should be comprehensive with the detailed feature engineering and model architecture.

<ul>
<li>Choose one ticker of your interest from the index, equity, ETF, crypto token, or commodity.</li>
<li>Predict trend only, for a short-term return (example: daily, 6 hours). Limit prediction to binomial classification: the dependent variable is best labeled [0, 1]. Avoid using [-1, 1] as class labels.</li>
<li>Analysis should be comprehensive with detailed feature engineering, data pre-processing, model building, and evaluation.</li>
</ul>
Devise your own approach on how to categorise extremely small near-zero returns (drop from training sample, group with positive/negative). The threshold will strongly depend on your ticker. <em>Example: </em>small positive returns below 0.25% can be labelled as negative.

1

Table 1: Features List

<table width="579">
<tbody>
<tr>
<td width="119"><strong>Feature</strong></td>
<td colspan="2" width="263"><strong>Formula</strong></td>
<td width="196"><strong>Description</strong></td>
</tr>
<tr>
<td width="119"><em>O-C, H-L</em></td>
<td colspan="2" width="263">Open – Close, High – Low</td>
<td width="196">intraday price range</td>
</tr>
<tr>
<td width="119"><em>Sign</em></td>
<td width="132"></td>
<td width="131">&nbsp;</td>
<td width="196">sign of return or momentum</td>
</tr>
<tr>
<td width="119"><em>Past Returns</em></td>
<td width="132"><em>r<sub>t</sub></em>−1, <em>r<sub>t</sub></em>−2, …</td>
<td width="131">&nbsp;</td>
<td width="196">lagged returns</td>
</tr>
<tr>
<td width="119"><em>Momentum</em></td>
<td width="132"><em>P</em><em>t </em>−<em>P</em><em>t</em>−<em>k</em></td>
<td width="131">&nbsp;</td>
<td width="196">price change over k period</td>
</tr>
<tr>
<td width="119"><em>Moving Average</em></td>
<td width="132"></td>
<td width="131">&nbsp;</td>
<td width="196">simple moving average</td>
</tr>
<tr>
<td width="119"><em>Exponential MA</em></td>
<td width="132"><em>EMA<sub>i </sub></em>= <em>EMA<sub>t</sub></em>−<sub>1</sub></td>
<td width="131">+ <em>α</em>[<em>P<sub>t </sub></em>−<em>EMA<sub>t</sub></em>−<sub>1</sub>]</td>
<td width="196">recursive, <em>α </em>= 2/(<em>N<sub>obs </sub></em>+ 1)</td>
</tr>
</tbody>
</table>
Number of features to include is a design choice. There is no one recommended set of features for all assets. Length of dataset is another design choice. If predicting short-term return sign (for daily move), then training and testing over up to 5-year period should be sufficient. Making sense of instructions below is part of the task: the tutor will not assist in designing your computational implementation.

<h1>Questions</h1>
<ol>
<li>What is the cost function of Logistic Regression? Explain in Detail. <strong>[20 Marks]</strong></li>
<li>What are voting classifiers in ensemble learning? <strong>[10 Marks]</strong></li>
<li>Follow the 7-steps to model building for your selected ticker, <strong>[70 Marks]</strong></li>
</ol>
<ul>
<li>produce a model to predict positive moves (up trend) using Support Vector Machine (SVM) model.</li>
<li>tune hyperparameters for the estimator and present the best model.</li>
<li>investigate the prediction quality using area under ROC curve, confusion matrix and classification report.</li>
</ul>
Note: Choice of kernels and number of hyperparameters to be optimized for the best model are design choices.

∗∗∗

2
