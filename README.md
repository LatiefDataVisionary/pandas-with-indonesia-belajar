# pandas-with-indonesia-belajar

Saya menyimpan hasil belajar saya disini dari channel youtube Indonesia Belajar pada serie belajar Python Pandas

df_titanic = pd.read_csv('https://raw.githubusercontent.com/LatiefDataVisionary/pandas-with-indonesia-belajar/master/datasets/titanicfull.csv')

df_iris = pd.read_csv('https://raw.githubusercontent.com/LatiefDataVisionary/pandas-with-indonesia-belajar/master/datasets/Iris.csv')



n_rows = 10
n_cols = 5
cols = tuple('ABCDE')

df = pd.DataFrame(np.random.randint(1, 10, size=(n_rows, n_cols)),
                  columns=cols)
df



data = 'https://raw.githubusercontent.com/LatiefDataVisionary/pandas-with-indonesia-belajar/master/datasets/Iris_error.csv'


df_titanic = pd.read_csv('https://raw.githubusercontent.com/boedybios/kaggle_explorations/master/belajar_matplotlib_dasar/data/titanicfull.csv')
df_titanic.head()

url = 'https://raw.githubusercontent.com/boedybios/kaggle_explorations/master/Iris_Data_Classification_and_EDA/dataset/iris/Iris.csv'
df = pd.read_csv(url)
df
