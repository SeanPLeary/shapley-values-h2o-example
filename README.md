# Shapley Values with H2O AutoML Example (ML Interpretability)
## Example using [H2O's AutoML](http://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html) with the [SHAP (SHapley Additive exPlanations)](https://github.com/slundberg/shap) library

## Task List
- [x] Classification Example
- [ ] Regression Example
- [x] Use Plotly for visualizations


## Notebooks
| Filename | Description | 
| --- | --- |
| [shap_h2o_automl_classification.ipynb](shap_h2o_automl_classification.ipynb) | jupyter notebook w/ classification examples |
| [shap_h2o_automl_classification.html](shap_h2o_automl_classification.html) | html version for viewing force_plots |
| [plotly_force_plot.ipynb](plotly_force_plot.ipynb) | jupyter notebook plotly force-plots |
| [plotly_force_plot.html](plotly_force_plot.html) | html version plotly force-plots |

## Step-by-step guide
[1] 
```
conda env create -f environment.yml
```
[2]
```
source activate shap_h2o
```
[3] open jupyter notebook


### References:
- [An Introduction to Machine Learning Interpretability](https://learning.oreilly.com/library/view/an-introduction-to/9781492033158/)
- [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)
- [A Unified Approach to Interpreting Model Predictions](http://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions)
- [SHAP (SHapley Additive exPlanations)](https://github.com/slundberg/shap)
- https://shap.readthedocs.io/en/latest/

