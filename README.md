### avg_norm_activation_vectors.ipynb
We analyzed the activation norms of residual streams in GPT-2 small after layer 6 by computing their L2 norms and visualizing their distribution across tasks and tokens. This included generating histograms for the full range of norms, as well as subsets (norms below 500 and above 2500), to understand the role of LayerNorm in stabilizing activations. Some task-specific analysis laid the groundwork for identifying tasks most sensitive to LayerNorm removal.


### compare_sae_mse
We calculate & compare the MSE of two SAEs on the pile-10k dataset. 
