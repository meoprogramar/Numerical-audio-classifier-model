## Classificação de números através de áudios

O algorimo tem como objetivo desenvolver um modelo que consiga classificar números através de entrada de áudio, para isso foi usado o dataset [**MNIST**](https://www.kaggle.com/datasets/sripaadsrinivasan/audio-mnist). Basicamente o dataset contém **30000 áudios** com o som dos números de 0 até 9 falados por 60 diferentes pessoas.

Para a resolução do problema foi escolhido o uso de **Redes Neurais Artificiais**, ao final do processo será possível entrar com um áudio e o modelo classificará e informará qual o número dito.

### Estrutura do projeto

<ul>
  <li>📂 <strong>dataset</strong>
    <ul>
      <li>📂 <strong>audios</strong>: Pasta com os áudios do dataset, extraia os áudios para essa pasta.</li>
      <li>📂 <strong>audios_extras</strong>: Pasta com os áudios extras, gravados manualmente por mim para testar o modelo.</li>
      <li>📂 <strong>audios_processed</strong>: Pasta com os áudios processados em csv caso você não queira baixar o dataset, também já está separado em dados de treino e teste.</li>
    </ul>
  </li>
  <li>.gitignore</li>
  <li>audio_processing.ipynb</li>
</ul>

**OBS: O dataset não está incluso no repositório devido a limites do github, faça o download do dataset [**aqui**](https://www.kaggle.com/datasets/sripaadsrinivasan/audio-mnist). Em seguida extraia os áudios para a pasta "/dataset/audios/..." ficando como mostrado abaixo:**

<ul>
  <li>📂 <strong>dataset</strong>
    <ul>
      <li>📂 <strong>audios</strong>
      <ul>
        <li>📂 <strong>01</strong></li>
        <li>📂 <strong>02</strong></li>
        <li>📂 <strong>03</strong></li>
        <li>📂 <strong>...</strong></li>
      </ul>
    </li>
    </ul>
  </li>
</ul>
