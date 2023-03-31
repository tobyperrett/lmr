
<p align="center" style="font-size:25px">
<a href="https://tobyperrett.github.io/">Toby Perrett</a>, <a href="">Saptarshi Sinha</a>, <a href="http://people.cs.bris.ac.uk/~burghard/">Tilo Burghardt</a>, <a href="http://people.cs.bris.ac.uk/~majid/">Majid Mirmehdi</a> and <a href="https://dimadamen.github.io/">Dima Damen</a>
</p>

We begin our long-tail video investivation by defining a set of long-tail properties, which are distribution independent.

<p align="center" width="100%">
    <img width="80%" src="def2_200.jpg">
</p>

We find that, unlike naturally-collected video datasets and existing long-tail image benchmarks, current video benchmarks fall short on multiple long-tailed properties. Most critically, they lack few-shot classes in their tails. In response, we propose new video benchmarks that better assess long-tail recognition, by sampling subsets from two datasets: SSv2 and VideoLT.

![Image](fig1_200.jpg)


We propose a method, Long-Tail Mixed Reconstruction (LMR), which reduces overfitting to instances from few-shot classes by reconstructing them as weighted combinations of samples from head classes. 


<p align="center" width="100%">
    <img width="40%" src="m3_1_200.jpg">
</p>


LMR then employs label mixing to learn robust decision boundaries. It achieves state-of-the-art average class accuracy on EPIC-KITCHENS and the proposed SSv2-LT and VideoLT-LT.

<p align="center" width="100%">
    <img width="40%" src="m3_2_200.jpg">
</p>

## Paper

[PDF](use_your_head.pdf)

## Code

[GitHub](https://github.com/tobyperrett/lmr-release)

<a href="https://github.com/tobyperrett/lmr-release">GitHub</a>

## Bibtex

If you find this helpful, please cite our paper:

```BibTeX
@inproceedings{perrett2023,
   title={Use Your Head: Improving Long-Tail Video Recognition}, 
   author={Perrett, Toby and Sinha, Saptarshi and Burghardt, Tilo and Mirhemdi, Majid and Damen, Dima},
   year={2023},
   booktitle={Computer Vision and Pattern Recognition},
}
```

And also cite the [EPIC](https://epic-kitchens.github.io/), [Something-Something V2](https://developer.qualcomm.com/software/ai-datasets/something-something) and [VideoLT](https://videolt.github.io/) works.
