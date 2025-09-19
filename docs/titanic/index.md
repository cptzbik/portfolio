

# Titanic EDA Data Analysis

This notebook presents an exploratory data analysis (EDA) of the Titanic passengers dataset. It includes a description of the dataset, an initial data quality analysis (missing values, duplicates), basic statistics about the passengers (number of women, men, average ticket price, number of people boarding at each port), as well as visualizations of class, age, and ticket price distributions.

In the further part of the notebook, relationships between passenger features and their chances of surviving the disaster are analyzed – including the impact of gender, travel class, age, and traveling with family on survival. The results are presented in the form of charts and short text summaries.

<a href="titanic.ipynb" class="md-button md-button--primary">Download Notebook</a>

<iframe
    id="content"
    src="titanic.html"
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
