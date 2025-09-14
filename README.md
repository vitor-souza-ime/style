# 🎨 Transferência de Estilo Neural com TensorFlow

Este projeto demonstra uma implementação prática de **transferência de estilo neural** utilizando [TensorFlow](https://www.tensorflow.org/) e [TensorFlow Hub](https://www.tensorflow.org/hub).  
A técnica permite combinar o **conteúdo** de uma imagem (ex.: fotografia) com o **estilo** de outra (ex.: pintura de Van Gogh), gerando uma síntese artística automatizada.  

Repositório: [style](https://github.com/vitor-souza-ime/style)  

---

## 📂 Estrutura do Projeto

- `main.py` → Código principal que:
  - Faz download das imagens (conteúdo e estilo).
  - Pré-processa as imagens.
  - Aplica a transferência de estilo com o modelo do **Google Magenta**.
  - Exibe o resultado final.

---

## 🚀 Como Executar

### 1. Clonar o repositório
```bash
git clone https://github.com/vitor-souza-ime/style.git
cd style
````

### 2. Criar ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

### 3. Instalar dependências

```bash
pip install -r requirements.txt
```

Caso não tenha o arquivo `requirements.txt`, instale manualmente:

```bash
pip install tensorflow tensorflow_hub matplotlib pillow
```

### 4. Executar o script

```bash
python main.py
```

---

## 🖼️ Exemplo de Saída

O script utiliza por padrão:

* **Imagem de conteúdo:** detalhe de *A Criação de Adão*, de Michelangelo.
* **Imagem de estilo:** autorretrato de *Vincent van Gogh*.

O resultado será uma imagem que preserva a estrutura da obra de Michelangelo enquanto incorpora o estilo vibrante de Van Gogh.

---

## 📚 Referências

* [TensorFlow Hub: Arbitrary Image Stylization](https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2)
* Gatys, L. A., Ecker, A. S., & Bethge, M. (2016). *Image Style Transfer Using Convolutional Neural Networks*. CVPR.
* [Google Magenta Project](https://magenta.tensorflow.org/)

---

## 📜 Licença

Este projeto é distribuído sob a licença MIT.
As imagens utilizadas são de **domínio público**.


Quer que eu já monte também o arquivo **requirements.txt** para acompanhar o `README.md`?
```
