# BrigsProjectz
Arquivo Secreto pra Databricks - SPARK
----------------------------------------
Olá, Eu do futuro que vai precisar dos codigos do passado e por isso veio aqui.

Aquela Pesquisada basica pra encontrar o mount/path dos arquivos
____
%fs
ls
____
# Import padrão de tudo que iremos usar em um tratamento dos dados!

from pyspark.sql.functions import *
import pandas as pd
from pyspark.sql import SparkSession
from pyspark.sql import functions as F
import json
import requests
from pyspark.sql.functions import explode
