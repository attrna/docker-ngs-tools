# PALMA

We present a novel approach based on large margin learning that combines accurate splice site predictions with common sequence alignment techniques. By solving a convex optimization problem, our algorithm -- called PALMA -- tunes the parameters of the model such that true alignments score higher than other alignments. We study the accuracy of alignments of mRNAs containing artificially generated micro-exons to genomic DNA. In a carefully designed experiment, we show that our algorithm accurately identifies the intron boundaries as well as boundaries of the optimal local alignment. It outperforms all other methods: for 5702 artificially shortened EST sequences from C. elegans and human it correctly identifies the intron boundaries in all except two cases. The best other method is a recently proposed method called exalin which misaligns 37 of the sequences. Our method also demonstrates robustness to mutations, insertions and deletions, retaining accuracy even at high noise levels.