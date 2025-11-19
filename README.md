# atividadeIA
Script para localizar arquivos através de palavras-chave. 

# Integrantes
Gabriel Quirino
Higor Rocha
Julio Cesar
Matheus Fermino
Mateo Rodriguez
Nicolas Medina

# problema
  - Dificuldade na localização de arquivos, dentro de uma grande base de dados
    
# solução
HuggingFace (para gerar embeddings)
  - Transformamos nomes de arquivos em vetores numéricos que representam o significado do texto.,

FAISS (Vector Database)
  - Criamos um índice vetorial para fazer busca rápida por similaridade.,

Python + Loop interativo

O usuário pode:
digitar o que procura
o modelo gera embeddings
o FAISS encontra o arquivo mais semântico
o sistema pergunta se ele quer continuar
