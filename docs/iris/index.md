

# Iris EDA Data Analysis

This notebook presents an exploratory data analysis (EDA) of the famous Iris flower dataset. It includes:

- A description of the dataset, including the characteristics of the three Iris species and a description of the features (sepal length and width, petal length and width).
- Loading the data and checking its completeness and basic statistics.
- Analysis of the number of samples in each class and the distributions of features.
- Checking for missing values and confirming that the data is complete.
- Correlation analysis between features with a visualization of the correlation matrix.
- Visualizations of feature distributions and comparisons between species (scatter plots, histograms, boxplots).
- Identification of outliers.
- Summary of the most important observations regarding differences between Iris species.

This notebook is an example of a classic EDA, showing step by step how to explore and visualize biological data.

<a href="iris.ipynb" class="md-button md-button--primary">Download Notebook</a>

<iframe
    id="content"
    src="iris.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
