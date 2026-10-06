# Acerte os Verbos — Vercel

Jogo estático pronto para publicar. Não requer banco de dados, variáveis de ambiente, instalação de dependências ou compilação.

## Publicar pelo GitHub
1. Extraia este ZIP em uma pasta.
2. Crie um repositório no GitHub e envie os arquivos extraídos para a raiz dele (não envie o ZIP).
3. Na Vercel, crie um projeto e importe esse repositório.
4. Use Framework Preset: Other e Root Directory: a raiz do repositório.
5. O arquivo vercel.json já define Build Command e Install Command vazios, e Output Directory como ponto (.).
6. Clique em Deploy.

## Alternativa pelo terminal
Com Node.js instalado, abra o terminal na pasta que contém index.html e vercel.json e execute:

```sh
npx vercel --prod
```

Faça login e siga as perguntas para criar ou conectar seu projeto.

## Usar offline
Abra index.html no navegador e mantenha os demais arquivos na mesma pasta.

## Conteúdo preservado
Três modos de jogo, três dificuldades, 76 cartões, 60 questões, pausa, som opcional, vidas, combos e revisão. Recordes ficam no navegador de cada jogador. Ao mudar de domínio, os recordes do endereço antigo não são transferidos.

## Verificação do pacote
Arquivos do jogo preservados a partir do pacote original. Referências locais e configuração JSON verificadas, sintaxe JavaScript conferida. Publicação na conta Vercel não realizada nesta preparação.

Documentação: https://vercel.com/docs/builds/configure-a-build
Configuração: https://vercel.com/docs/project-configuration/vercel-json
