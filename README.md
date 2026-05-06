# ZIP1
import gzip
import shutil

with open('','rb') as f_input:
    with gzip.open(' .gz','wb') as f_output:
        shutil.copyfileobj(f_input,f_output)
