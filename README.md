# sae_overlap
Acompanying code for our research on SAE feature overlap when trained on different seeds.

We provide a script to calculate the alignment between two SAEs using the hungarian algorithm, [hungarian_alignment.py](hungarian_alignment.py).

We also provide a script to plot all the figures in the paper, [sae_overlap.ipynb](sae_overlap.ipynb).

Although the aligment of the SAEs with less than 32k latents is fast, the aligment of the other sizes takes a long time, so we provide the average aligment and the indices in the [alignment](alignment) folder.

All trained SAEs can be found in [HuggingFace](https://huggingface.co/EleutherAI/sae_overlap/tree/main).

# License

Copyright 2024 the EleutherAI Institute

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
