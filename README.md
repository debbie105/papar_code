###檔案說明

***0_data_preprocessing***

step 1.該檔案內含有資料集整合
即為整理並析出資料集WOS_patent之keyword欄位，並進行存檔，檔案名為processed_keywordsnew.csv，後再以此建立辭典

step.2 進行資料預處理，除去Abstract欄位中的空值與重複值，再利用spacy與N-gram建立corpus和dictonary

step 3. 建立PMI與TF-IDF，以及PMI+TF-IDF三種加權方法


***2_bertopic_both***

使用兩種加權方法的檔案

檔案名含roberta的檔案是使用嵌入模型：all-roberta-large-v1
檔案名含all的檔案是使用嵌入模型：all-MiniLM
檔案名含有dot的檔案是使用嵌入模型：msmarco-bert-base-dot-v5


***2_bertopic_orignal***

檔案名含roberta的檔案是使用嵌入模型：all-roberta-large-v1
檔案名含all的檔案是使用嵌入模型：all-MiniLM
檔案名含有dot的檔案是使用嵌入模型：msmarco-bert-base-dot-v5


***2_bertopic_tfidf***

檔案名含roberta的檔案是使用嵌入模型：all-roberta-large-v1
檔案名含all的檔案是使用嵌入模型：all-MiniLM
檔案名含有dot的檔案是使用嵌入模型：msmarco-bert-base-dot-v5


***2_bertopic_pmi***

檔案名含roberta的檔案是使用嵌入模型：all-roberta-large-v1
檔案名含all的檔案是使用嵌入模型：all-MiniLM
檔案名含有dot的檔案是使用嵌入模型：msmarco-bert-base-dot-v5

