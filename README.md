# Sistema-de-Streaming-de-Musica-Java
#  StreamMusic

Sistema de playlists no terminal feito em Java. Cria playlists públicas ou privadas, adiciona e remove músicas e reproduz suas playlists. Projeto criado para praticar os pilares de POO.

##  Como rodar

bash
javac *.java
java Main


##  Funcionalidades

- Criar playlists públicas ou privadas
- Adicionar e remover músicas
- Playlists privadas têm senha e bloqueiam após 3 tentativas erradas
- Reproduzir e listar músicas de cada playlist

##  Estrutura


Playlist (abstract)
├── PlaylistPublica  → qualquer um pode reproduzir
└── PlaylistPrivada  → protegida por senha com limite de tentativas

Musica → representa uma faixa com título, artista, gênero e duração
Main   → menu e execução do programa


## 📌 Exemplo


=== StreamMusic ===

1. Criar playlist
Nome da playlist: Favoritas
Tipo: 1. Pública  2. Privada
Escolha: 2
Crie uma senha: 1234
Playlist "Favoritas" criada!

6. Reproduzir playlist
  1. [Pri] Favoritas | 2 música(s)
Senha: 1234
▶  Favoritas [Privada]
   1. Bohemian Rhapsody - Queen
   2. Stairway to Heaven - Led Zeppelin
