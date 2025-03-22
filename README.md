# PAN-OTFM: Taming Flow Matching with Unbalanced Optimal Transport into Fast Pansharpening

<div align="center">
  <a href=https://scholar.google.com/citations?user=pv61p_EAAAAJ&hl=en>Zihan Cao </a> |
  <a href=https://scholar.google.co.il/citations?user=UgD8AtkAAAAJ&hl=de> Yu Zhong </a> |
  <a href=https://scholar.google.com/citations?user=TZs9NxkAAAAJ&hl=zh-CN> Liang-Jian Deng </>
  
  <a>University of Science and Technology of China (UESTC)</a>
</div>


<div>
<strong>Abstract</strong>:
Pansharpening, a pivotal task in remote sensing for fusing high-resolution panchromatic and multispectral imagery, has garnered significant research interest. Recent advancements employing diffusion models based on stochastic differential equations (SDEs) have demonstrated state-of-the-art performance. However, the inherent multi-step sampling process of SDEs imposes substantial computational overhead, hindering practical deployment. While existing methods adopt efficient samplers, knowledge distillation, or retraining to reduce sampling steps (e.g., from 1,000 to fewer steps), such approaches often compromise fusion quality. In this work, we propose the Optimal Transport Flow Matching (OTFM) framework, which integrates the dual formulation of unbalanced optimal transport (UOT) to achieve one-step, high-quality pansharpening. Unlike conventional OT formulations that enforce rigid distribution alignment, UOT relaxes marginal constraints to enhance modeling flexibility, accommodating the intrinsic spectral and spatial disparities in remote sensing data. Furthermore, we incorporate task-specific regularization into the UOT objective, enhancing the robustness of the flow model. The OTFM framework enables simulation-free training and single-step inference while maintaining strict adherence to pansharpening constraints. Experimental evaluations across multiple datasets demonstrate that OTFM matches or exceeds the performance of previous regression-based models and leading diffusion-based methods while only needing one sampling step.
</div>

## We are working on the release of the code.
