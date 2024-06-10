# ML Papers and Implementations
## [DiffEdit](https://github.com/ChrisDoh100/MLPapers/blob/main/DiffEdit.ipynb),[DiffEditPaper](https://arxiv.org/pdf/2210.11427) ##
* DiffEdit is a technique used to edit images in place using stable diffusion, it removes the need to create a manual mask by taking the difference from the input image and the image generated from the new prompt/edit, this difference determines which part of
the image should be allowed to be changed and which sections shouldn't. After a mask is generated stable diffusion is run once again but only the parts of the image that are allowed to be changed by our mask will be changed to the new image which, again, is determined by the input
prompt.

