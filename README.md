# Trans2Vec: Learning embeddings for transactions via frequent itemsets, Word2Vec, and Doc2Vec
This is the implementation of the Trans2Vec method in the paper "Trans2Vec: Learning Transaction Embedding via Items and Frequent Itemsets", PAKDD 2018: [https://link.springer.com/chapter/10.1007/978-3-030-10928-8_34](https://link.springer.com/chapter/10.1007/978-3-319-93040-4_29)

# Installation
1. Microsoft .NET Framework 4.0 (to run C# code to mine sequential patterns)
2. gensim 3.4 (to run Doc2Vec model)

# How to run
## Trans2Vec-Ind
1. Run "FIM_Trans.exe" to mine frequent itemsets. Please make sure to select the option "Write Trans" and set the "Data path" and "Embedding path" correctly.
2. Run "trans2vec_ind_classify.py" to embed the transactions into low-dimensional vectors. Please make sure to change the hyper-parameters in the Python code.

## Trans2Vec-Joi
1. Run "FIM_Trans.exe" to mine frequent itemsets. Please make sure to select the option "Write Items-FIs" and set the "Data path" and "Embedding path" correctly.
2. Run "trans2vec_joi_classify.py" to embed the transactions into low-dimensional vectors. Please make sure to change the hyper-parameters in the Python code.

# Reference
```
@inproceedings{nguyen2018trans2vec,
  title={Trans2vec: learning transaction embedding via items and frequent itemsets},
  author={Nguyen, Dang and Nguyen, Tu Dinh and Luo, Wei and Venkatesh, Svetha},
  booktitle={Advances in Knowledge Discovery and Data Mining: 22nd Pacific-Asia Conference, PAKDD 2018, Melbourne, VIC, Australia, June 3-6, 2018, Proceedings, Part III 22},
  pages={361--372},
  year={2018},
  organization={Springer}
}
```
