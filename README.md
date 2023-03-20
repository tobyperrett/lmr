<p style="text-align: center;">
[Toby Perrett](), [Saptarshi Sinha](), [Tilo Burghardt](), [Majid Mirmehdi]() and [Dima Damen]()
</p>

![Image](fig1_200.jpg)

Unlike naturally-collected video datasets and existing long-tail image benchmarks, current video benchmarks fall short on multiple long-tailed properties. Most critically, they lack few-shot classes in their tails. In response, we propose new video benchmarks that better assess long-tail recognition, by sampling subsets from two datasets: SSv2 and VideoLT.


We propose a method, Long-Tail Mixed Reconstruction (LMR), which reduces overfitting to instances from few-shot classes by reconstructing them as weighted combinations of samples from head classes. 


LMR then employs label mixing to learn robust decision boundaries. It achieves state-of-the-art average class accuracy on EPIC-KITCHENS and the proposed SSv2-LT and VideoLT-LT.

## Paper

[ArXiv]()

## Code

[GitHub](github.com/tobyperrett/lmr-release)

## Bibtex

```BibTeX
@inproceedings{perrett2023,
   title={Use Your Head: Improving Long-Tail Video Recognition}, 
   author={Perrett, Toby and Sinha, Saptarshi and Burghardt, Tilo and Mirhemdi, Majid and Damen, Dima},
   year={2023},
   booktitle={Computer Vision and Pattern Recognition},
}
```

## Acknowledgements
