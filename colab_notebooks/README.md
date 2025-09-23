# ANALISE_ACURACIA_BASES_COM_FALHA
O notebook ANALISE_ACURACIA_BASES_COM_FALHA, desenvolvido no Google Colab, realiza testes de acurácia utilizando os modelos YOLOv8, MTCNN e RetinaFace.

A base de dados empregada é composta por 20.000 imagens, resultantes da junção de 5.000 amostras aleatórias de cada um dos seguintes datasets: WIDERFace, UTKFace, LFW e CelebA.

Durante a execução:
Cada imagem é processada pelos modelos, que avaliam a detecção de faces.
Ao final, são gerados percentuais e quantitativos de acerto.
As imagens em que não foi possível detectar rostos são separadas em um diretório específico para análise posterior.

---

# COLAB_tirar_amostras_bases
O notebook COLAB_tirar_amostras_bases, também desenvolvido no Google Colab, tem como objetivo pré-processar os datasets utilizados no projeto.

Principais funcionalidades:
Extração de arquivos compactados (ZIP) dos datasets WIDERFace, UTKFace, LFW e CelebA, tanto a partir do Google Drive quanto via upload direto do computador.
Listagem automática dos diretórios extraídos, facilitando a navegação.
Seleção de 5.000 amostras aleatórias de cada dataset.
Disponibilização das amostras geradas em formato compactado para download direto.
