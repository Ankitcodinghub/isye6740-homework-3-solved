# isye6740-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [ISYE6740 Homework 3 Solved](https://www.ankitcodinghub.com/product/isye6740-homework-3-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;84481&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISYE6740 Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<h1>1.&nbsp;&nbsp;&nbsp;&nbsp; Order of faces using ISOMAP</h1>
This question aims to reproduce the ISOMAP algorithm results in the original paper for ISOMAP, J.B. Tenenbaum, V. de Silva, and J.C. Langford, Science 290 (2000) 2319-2323 that we have also seen in the lecture as an exercise (isn’t this exciting to go through the process of generating results for a high-impact research paper!)

The file isomap.mat (or isomap.dat) contains 698 images, corresponding to different poses of the same face. Each image is given as a 64 × 64 luminosity map, hence represented as a vector in R<sup>4096</sup>. This vector is stored as a row in the file. [This is one of the datasets used in the original paper] In this question, you are expected to implement the ISOMAP algorithm by coding it up yourself. You may use the provided functions in ShortestPath.zip to find the shortest path as required by one step of the algorithm. To load data in Python, for instance, you can use from scipy.io import loadmat, images = loadmat(‘isomap.mat’)[‘images’]. To load data in Matlab, you can directly use load() function.

Choose the Euclidean distance (i.e., in this case, a distance in R<sup>4096</sup>) to construct the nearest neighbor graph—vertices corresponding to the images. Construct a similarity graph with vertices corresponding to the images, and tune the threshold <em>&nbsp;</em>so that each node has <em>at least K </em>= 50 neighbors (this approach corresponds to the so-called -Isomap).

<ul>
<li>(10 points) Visualize the similarity graph (you can either show the adjacency matrix,or similar to the lecture slides, visualize the graph using graph visualization packages such as Gephi (https://gephi.org) and illustrate a few images corresponds to nodes at different parts of the graph, e.g., mark them by hand or use software packages).</li>
<li>(20 points) Implement the ISOMAP algorithm yourself to obtain a two-dimensionallow-dimensional embedding. Plot the embeddings using a scatter plot, similar to the plots in lecture slides. Find a few images in the embedding space and show what these images look like. Comment on do you see any visual similarity among them and their arrangement, similar to what you seen in the paper?</li>
<li>(10 points) Now choose <em>`</em><sub>1 </sub>distance (or Manhattan distance) between images (recall the definition from “Clustering” lecture)). Repeat the steps above. Use -ISOMAP to obtain a <em>k </em>= 2 dimensional embedding. Present a plot of this embedding. Do you see</li>
</ul>
any difference by choosing a different similarity measure by comparing results in Part (b) and Part (c)?

<ul>
<li>(10 points) Perform PCA (you can now use your implementation written in Question1) on the images and project them into the top 2 principal components. Again show them on a scatter plot. Explain whether or you see a more meaningful projection using ISOMAP than PCA.</li>
</ul>
<h1>2.&nbsp;&nbsp;&nbsp;&nbsp; Density estimation: Psychological experiments.</h1>
We will use this data to study whether or not the two brain regions are likely to be independent of each other and considering different types of political view <strong>For this question; you can use the proper package for histogram and KDE; no need to write your own.</strong>

The data set n90pol.csv contains information on 90 university students who participated in a psychological experiment designed to look for relationships between the size of different regions of the brain and political views. The variables amygdala and acc indicate the volume of two particular brain regions known to be involved in emotions and decision-making, the amygdala and the anterior cingulate cortex; more exactly, these are residuals from the predicted volume, after adjusting for height, sex, and similar body-type variables. The variable orientation gives the students’ locations on a five-point scale from 1 (very conservative) to 5 (very liberal). Note that in the dataset, we only have observations for orientation from 2 to

5.

Recall in this case, the kernel density estimator (KDE) for a density is given by

<em>,</em>

where <em>x<sup>i </sup></em>are two-dimensional vectors, <em>h &gt; </em>0 is the kernel bandwidth, based on the criterion we discussed in lecture. For one-dimensional KDE, use a one-dimensional Gaussian kernel

<em>.</em>

For two-dimensional KDE, use a two-dimensional Gaussian kernel: for

<em>,</em>

where <em>x</em><sub>1 </sub>and <em>x</em><sub>2 </sub>are the two dimensions respectively

<em>.</em>

<ul>
<li>(10 points) Form the 1-dimensional histogram and KDE to estimate the distributionsof amygdala and acc, respectively. For this question, you can ignore the variable orientation. Decide on a suitable number of bins so you can see the shape of the distribution clearly. Set an appropriate kernel bandwidth <em>h &gt; </em> For example. for one-dimensional KDE, you are welcome to use a rule-of-thumb bandwidth estimator</li>
</ul>
<em>h </em>≈ 1<em>.</em>06<em>σn</em>ˆ <sup>−1<em>/</em>5</sup><em>,</em>

where <em>n </em>is the sample size, ˆ<em>σ </em>is the standard error of samples; this is shown to be optimal when Gaussian kernel functions are used for univariate data.

<ul>
<li>(10 points) Form 2-dimensional histogram for the pairs of variables (amygdala, acc). Decide on a suitable number of bins so you can see the shape of the distribution clearly.</li>
<li>(10 points) Use kernel-density-estimation (KDE) to estimate the 2-dimensional densityfunction of (amygdala, acc) (this means for this question, you can ignore the variable orientation). Set an appropriate kernel bandwidth <em>h &gt; </em></li>
</ul>
Please show the two-dimensional KDE (e.g., two-dimensional heat-map, two-dimensional contour plot, etc.)

Please explain based on the results, can you infer that the two variables (amygdala, acc) are likely to be independent or not?

<ul>
<li>(10 points) We will consider the variable orientation and consider conditional distributions. Please plot the estimated conditional distribution of amygdala conditioning on political orientation: <em>p</em>(amygdala|orientation = <em>c</em>), <em>c </em>= 2<em>,…,</em>5, using KDE. Set an appropriate kernel bandwidth <em>h &gt; </em> Do the same for the volume of the acc: plot <em>p</em>(acc|orientation = <em>c</em>), <em>c </em>= 2<em>,…,</em>5 using KDE. (Note that the conditional distribution can be understood as fitting a distribution for the data with the same orientation. Thus you should plot 8 one-dimensional distribution functions in total for this question.)</li>
</ul>
Now please explain based on the results, can you infer that the conditional distribution of amygdala and acc, respectively, are different from <em>c </em>= 2<em>,…,</em>5? This is a type of scientific question one could infer from the data: Whether or not there is a difference between brain structure and political view.

Now please also fill out the <em>conditional sample mean </em>for the two variables:

<table width="283">
<tbody>
<tr>
<td width="77">&nbsp;</td>
<td width="51"><em>c </em>= 2</td>
<td width="51"><em>c </em>= 3</td>
<td width="51"><em>c </em>= 4</td>
<td width="51"><em>c </em>= 5</td>
</tr>
<tr>
<td width="77">amygdala</td>
<td width="51">&nbsp;</td>
<td width="51">&nbsp;</td>
<td width="51">&nbsp;</td>
<td width="51">&nbsp;</td>
</tr>
<tr>
<td width="77">acc</td>
<td width="51">&nbsp;</td>
<td width="51">&nbsp;</td>
<td width="51">&nbsp;</td>
<td width="51">&nbsp;</td>
</tr>
</tbody>
</table>
Remark: As you can see this exercise, you can extract so much more information from density estimation than simple summary statistics (e.g., the sample mean) in terms of explorable data analysis.

<ul>
<li>(10 points) Again we will consider the variable orientation. We will estimate the conditional <em>joint </em>distribution of the volume of the amygdala and acc, conditioning on a function of political orientation: <em>p</em>(amygdala<em>, </em>acc|orientation = <em>c</em>), <em>c </em>= 2<em>,…,</em> You</li>
</ul>
will use two-dimensional KDE to achieve the goal; et an appropriate kernel bandwidth <em>h &gt; </em>0. Please show the two-dimensional KDE (e.g., two-dimensional heat-map, two-dimensional contour plot, etc.).

Please explain based on the results, can you infer that the conditional distribution of two variables (amygdala, acc) are different from <em>c </em>= 2<em>,…,</em>5? This is a type of scientific question one could infer from the data: Whether or not there is a difference between brain structure and political view.
