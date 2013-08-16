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

![Example 1](figures/bg-banana-roc.png)
![Example 2](figures/bg-multiclass.png)
![Example 3](figures/eval-boxplot-preprocessing-pca.png)
![Example 4](figures/mlc-mapping-auc-overview.png)
![Example 5](figures/sos-densities.png)
![Example 6](figures/sos-graph-matlab-binding.png)
![Example 7](figures/sos-graphs-sample.png)
![Example 8](figures/sos-nemenyi.png)
