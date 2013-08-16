Outlier Selection and One-Class Classification
==============================================

Currently, only the PDF of my thesis is available for download. In the future I may add the LaTeX, figures, and data as well.

![Thesis cover](cover.png)

Figures
-------

The figures in the thesis are created using Python, MATLAB and TikZ. The TikZ code of the figures can be found in `/figures/tikz`. To compile all the figures to PDF, I wrote a script called [tikz2pdf](https://github.com/jeroenjanssens/tikz2pdf).

```bash
$ tikz2pdf figures/tikz/*.tikz --template figures/thesis-template.tex --output figures/pdf/
```

Below are some figures from the thesis. Please note that these are rendered with a different font. Also, the conversion from PDF to PNG with ImageMagick isn't all that great.

### figures/tikz/bg-banana-roc.tikz
![Example 1](figures/examples/bg-banana-roc.png)

### figures/tikz/bg-multiclass.tikz
![Example 2](figures/examples/bg-multiclass.png)

### figures/tikz/eval-boxplot-preprocessing-pca.tikz
![Example 3](figures/examples/eval-boxplot-preprocessing-pca.png)

### figures/tikz/mlc-mapping-auc-overview.tikz
![Example 4](figures/examples/mlc-mapping-auc-overview.png)

### figures/tikz/sos-densities.tikz
![Example 5](figures/examples/sos-densities.png)

### figures/tikz/sos-graph-matlab-binding.tikz
![Example 6](figures/examples/sos-graph-matlab-binding.png)

### figures/tikz/sos-graphs-sample.tikz
![Example 7](figures/examples/sos-graphs-sample.png)

### figures/tikz/sos-nemenyi.tikz
![Example 8](figures/examples/sos-nemenyi.png)
