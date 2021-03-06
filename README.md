This is a pytorch (>=1.3.0) implementation of https://github.com/PengjieRen/RepeatNet in the paper:

Pengjie Ren, Jing Li, Zhumin Chen, Zhaochun Ren, Jun Ma and Maarten de Rijke (2019). RepeatNet: A Repeat Aware Neural Recommendation Machine for Session-based Recommendation. In Proceedings of The Thirty-Third AAAI Conference on Artificial Intelligence.

This pytorch version supports distributed GPU computing, and has a higher GPU usage.
Run with the following command:

python -m torch.distributed.launch --nproc_per_node=#GPU ./RepeatNet/Run.py --mode='train' or 'infer'

We have additionally released our implementation of NARM in the paper:

Jing Li, Pengjie Ren, Zhumin Chen, Zhaochun Ren, and Jun Ma. Neural Attentive Session-based Recommendation. The 26th ACM Conference on Information and Knowledge Management (CIKM), 2017. (Best Paper Runner-up)

Please refer to https://github.com/lijingsdu/sessionRec_NARM

Please cite our AAAI'19 and CIKM'17 papers if you are using our codes and/or based on our codes.
