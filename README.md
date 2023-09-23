# metric
```shell
1. CLIP-R precision:
  - reference paper: Benchmark for compositional text-to- image synthesis  
  - CLIP-R precision calculates the top-R retrieval accuracy when retrieving the matching text from 100 text candidates using the generated image as a query.
2. CLIP score:
  1. reference paper: A reference-free evaluation metric for image captioning 
  2. reference paper: Learning transferable visual models from natural language supervision
  - CLIP Score metric measures how well images rendered from the generated geometry correlate with the provided input text prompt. 
3. FID:
  - Reference paper: Gans trained by a two time-scale update rule converge to a local nash equilibrium. 
  - FID evaluates the quality and photorealistic appearance of the generated shapes. 

papers with metric：
- DreamFields: 153 coco caption, CLIP-R precision
- EfficientDream: 22 prompts. imagenet2012 validation, CLIP Score, FID  
- Point-E/Shap-E: CLIP R-Precision & CLIP Score  on a set of COCO validation prompts.  
- Dreamhuman: CLIP R-Precision top1-3-5, 160 prompts with descriptions of people. 
- Cap3D: CLIP R-Precision, CLIP Score, FID, caption dataset
```
