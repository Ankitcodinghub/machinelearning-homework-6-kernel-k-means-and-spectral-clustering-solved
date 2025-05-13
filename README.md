# machinelearning-homework-6-kernel-k-means-and-spectral-clustering-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Homework 6-Kernel K-means and Spectral Clustering Solved](https://www.ankitcodinghub.com/product/machinelearning-homework-6-kernel-k-means-and-spectral-clustering-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92057&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Homework 6-Kernel K-means and Spectral Clustering Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

<ol>
<li>Homework Objective: Use whatever your favorite language to code out kernel k-means, spectral clustering (both normalized cut and ratio cut). You should consider spatial similarity and color similarity upon the clustering.</li>
<li>Data: Two 100*100 images are provided, and each pixel in the image should be treated as a data point, which means there are 10000 data points in each image.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
III. Kernel: For both kernel k-means and spectral clustering, please use the new kernel defined below to compute the Gram matrix.

</div>
</div>
<div class="layoutArea">
<div class="column">
−𝛾𝛾𝑠𝑠∥𝑆𝑆(𝑥𝑥)−𝑆𝑆(𝑥𝑥′)∥2 −𝛾𝛾𝑐𝑐∥𝐶𝐶(𝑥𝑥)−𝐶𝐶(𝑥𝑥′)∥2 𝑘𝑘(𝑥𝑥,𝑥𝑥′)= 𝑒𝑒 × 𝑒𝑒

</div>
</div>
<div class="layoutArea">
<div class="column">
This new defined kernel is basically multiplying two RBF kernels in order to consider spatial similarity and color similarity at the same time. 𝑆𝑆(𝑥𝑥) is the spatial information (i.e. the coordinate of the pixel) of data 𝑥𝑥, and 𝐶𝐶(𝑥𝑥) is the color information (i.e. the RGB values) of data 𝑥𝑥. Both 𝛾𝛾𝑠𝑠 and 𝛾𝛾𝑐𝑐 are hyper-parameters which you can tune in your own way.

<ol start="4">
<li>Requirements:
‣ Part1: You need to make videos or GIF images to show the clustering procedure (visualize the cluster assignments of data points in each iteration, colorize each cluster with different colors) of your kernel k-means and spectral clustering (both normalized cut and ratio cut) programs. (Hint : Numpy can help you to solve the eigenvalue problem.)

‣ Part2: In addition to cluster data into 2 clusters, try more clusters (e.g. 3 or 4) and show your results. (You also need to make videos or GIF images)

‣ Part3: For the initialization of k-means clustering used in kernel k-means, (e.g. k- means++) and spectral clustering (both normalized cut and ratio cut), try different ways and show corresponding results. (You also need to make videos or GIF images)

‣ Part4: For spectral clustering (both normalized cut and ratio cut), you can try to examine whether the data points within the same cluster do have the same coordinates in the eigenspace of graph Laplacian or not. You should plot the result and discuss it in the report.
</li>
<li>Report:</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
●

</div>
</div>
</div>
