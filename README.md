# scraping-com-python

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/scraping-com-python)
![Badge de Atualização](https://img.shields.io/github/last-commit/fab-souza/scraping-com-python)


| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Web Scraping com Python**
| :label: Tecnologias | python
| :rocket: URL         | [Notebook no Kaggle](https://www.kaggle.com/code/fabianadesouza/web-scraping-com-python)
| :fire: Desafio     | Conteúdo do curso [Web Scraping com Python](https://cursos.alura.com.br/course/web-scraping-data-science-python)


![capa](https://user-images.githubusercontent.com/67301805/217316982-41393a7a-ac78-49e2-85a5-f53e314d04d5.jpg)

## Sobre o curso 📚

Este foi o último curso da formação Python para Data Science, ministrado pelo instrutor [Rodrigo Dias](https://www.linkedin.com/in/rodrigo-fernando-dias-118181120/), em que aprendi como extrair dados a partir de uma página web, os principais métodos de pesquisa, navegação e acesso no HTML, com o auxílio do pacote [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/). Neste curso, retiramos os dados a partir de um site fictício de anúncio de carros, extraindo informações do tipo:
- valor;
- marca/modelo;
- categoria (se é novo ou usado);
- informações sobre o motor;
- ano de fabricação e quilometragem;
- local que o veículo se encontra;
- e itens adicionais (por exemplo: câmbio automático, central multimídia, freio ABS, etc).

![alura motors](https://user-images.githubusercontent.com/67301805/218318139-741afc1c-e7b4-4a90-a36c-79d9107ad659.png)

Iniciamos com a retirada individual de cada item, entendendo como acessar cada *tag*, como usar o método *find()* para buscar uma *tag*, específica ou alguma que seja ‘sua irmã’, e como obter os atributos das *tags*. Com essa etapa concluída, automatizamos a coleta de informações para todos os veículos presentes naquela página e criar um dataframe. Após extrair esses dados, ampliamos a coleta de dados para todos os veículos anunciados e recriar o dataframe.

![image](https://user-images.githubusercontent.com/67301805/218325583-5f9edd87-6d16-4287-9973-ac80f95b4a8a.png)


## Minha prática 👩🏻‍💻
Para a prática deste curso, eu decidi retirar informações de uma lista do [Goodreads](https://www.goodreads.com/). A plataforma possui diversas listas de indicação de leitura, por exemplo, há listas por gênero de livro, por ano de lançamento, local em que a história se passa ou característica do(a) personagem principal. 

![pagina_goodreads](https://user-images.githubusercontent.com/67301805/218314254-2cbae394-3426-4afb-aa19-361f10a54dc8.png)

Eu escolhi trabalhar com a lista [Best Books Ever](https://www.goodreads.com/list/show/1.Best_Books_Ever), porque logo nas 20 primeiras posições há tanto livros que já li ou que quero ler, quanto obras que não conheço. Além do título e autor do livro, cada item da lista apresenta: 
- a nota média (*avg rating*);
- a avaliação/classificação (*ratings*);
- uma pontuação (*score*);
- e quantas pessoas votaram na obra.

Das quatro informações adicionais, eu decidi não trazer as avaliações, porque ela não está em ordem decrescente ao longo da lista. Por exemplo, o livro **To Kill a Mockingbird** tem uma classificação maior do que **Pride and Prejudice**, mas está em uma posição inferior do que a obra de Jane Austen.

![lista_best_books_ever](https://user-images.githubusercontent.com/67301805/218316399-d31f859a-a498-4f80-82cd-87cf3d47e97d.png)

Assim como foi feito no curso, iniciei minha prática retirando informações sobre o primeiro item da lista, entendendo como acessar e extrair as informações previamente determinadas, em seguida automatizar a coleta e ampliar para os livros presentes na página. Finalizando com a expansão de coleta de dados para as 100 páginas do site, resultando em um dataframe com 10.000 linhas.

![dataframe](https://user-images.githubusercontent.com/67301805/218326752-b288a574-ff53-4b70-97eb-84938c36e896.png)


## Conclusão 🏁

Fazer esta prática foi uma das que mais me diverti, pois trabalhar com HTML me lembrou de quando comecei a gostar de programação e me livrei da sensação de que programação ‘não era para mim’, e juntar livros com análise de dados foi a ‘cereja do bolo’. Em conjunto com este projeto, também encerro a revisão dos cursos da formação [Python  para Data Science](https://cursos.alura.com.br/formacao-python-data-science-v31955) e darei início a revisão de outra formação.


## Ferramentas utilizadas 🧰 
<p> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
    <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/" target="_blank" rel="noreferrer"> <img src="https://beautiful-soup-4.readthedocs.io/en/latest/_images/6.1.jpg" alt="BeautifulSoup" width="40" height="40"/> </a>
    <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
    </p>
