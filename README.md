# TriTan:An efficient triple non-negative matrix factorisation method for integrative analysis of single cell multi-omics data

1. install from PyPI：

   pip install TriTan

2. See tutorials in ./tutorial/

3. Related data could be found in Figshare with DOI:10.48420/23283998 and DOI:10.48420/23289797

4. Default : TriTan.TriTan(
                n_modalities=2,
                n_clusters = 100,
                resolution=10,
                epoch =30,
                res_size=60,
                complexity=5,
                precomputed = False,
                svd_rna= None,
                svd_atac = None,
                sparse = False,
                n_component= [20,50,20,50])
