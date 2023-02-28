# Find_motif_in_dataset
Write software that finds motifs in a dataset (generate your own data). See an example of an existing application https://meme-suite.org/meme/tools/meme 


## De novo sequencing motif finding
目标： 在input data中寻找 （文件中）富集的common sequence pattern（相对于背景基因组）  
### Position weight  matrix update
* data driven approach, use data to refine(提炼) motif
* 两种计算approaches：EM，Gibbs sampling. 两者的statistical model 相同，但是update的方式不同
* Motif score 和 markov background
