# INR-st
## Controllable Style Transfer via Test-time Training of Implicit Neural Representation
This is the implementation of the paper "Controllable Style Transfer via Test-time Training of Implicit Neural Representatione" by Sunwoo Kim, Youngjo Min, Younghun Jung and Seungryong Kim.


For more information, check out the paper and project page on [[arXiv](https://arxiv.org/abs/2210.07762), [project page](https://ku-cvlab.github.io/INR-st/)].


Overall code will be updated in this week...

![alt text](/images/INR-st_teaser.png)

# Overall Architecture

Our model "Controllable Style Transfer via Test-time Training of Implicit Neural Representation" is illustrated below:
![alt text](/images/structure.png)



# Environment Settings
```
git clone https://github.com/KU-CVLAB/INR-st.git 
cd INR-st

conda env create -f environment.yaml
conda activate INR-st
```


# Results

## Super Resolution
![alt text](/images/resolution_comp.png)
![alt text](/images/res.png)

## Gradation
![alt text](/images/gradation.png)

## Region-wise stylization
![alt text](/images/mask.png)

### BibTeX
If you find this research useful, please consider citing:
````BibTeX
@article{kim2022inrst,
  title = {Controllable Style Transfer via Test-time Training of Implicit Neural Representation},
  author = {Kim, sunwoo and Youngjo, Min and Younghun, Jung and Kim, Seungryong},
  journal = {arXiv preprint arXiv:2210.07762},
  year = {2022},
}
````


