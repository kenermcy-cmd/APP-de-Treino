# MEU TREINO TRINCA AF

Aplicativo web gratuito para organizar a rotina de treinos A–F e acompanhar os registros localmente no navegador.

## Recursos disponíveis
- Tela inicial com indicação do próximo treino.
- Treinos A–F com sugestões de exercícios, séries, repetições e orientações textuais de execução para os blocos musculares A–F.
- Dois modelos de divisão muscular e ciclo de 8 semanas.
- Registro de sessões com data, séries, repetições, cargas e observações.
- Histórico de treinos e exclusão de registros.
- Perfil com objetivo principal.
- Exportação de histórico em CSV e backup completo em JSON; importação de backup JSON.
- Manifesto PWA e service worker para suporte básico à instalação/cache.

## Executar localmente
Para testar no computador, abra `index.html` no navegador. Para testar os recursos de PWA/service worker, use HTTPS ou um servidor local:

```bash
python -m http.server 8000
```

Depois abra http://localhost:8000.

## Publicar gratuitamente com GitHub Pages
1. Abra **Settings** no repositório.
2. Acesse **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/(root)`, depois salve.
5. Abra a URL que o GitHub Pages apresentar. Para usar no celular, abra pelo navegador e escolha a opção de adicionar à tela inicial.

## Limitações desta versão
- Ainda não há GIFs animados de demonstração incorporados; a biblioteca apresenta orientações textuais.
- Os dados são guardados no armazenamento local do navegador e não sincronizam entre aparelhos.
- Limpar os dados do navegador pode apagar os registros. Exporte backups regularmente.
- O conteúdo de treino é um modelo inicial; adapte os exercícios e cargas com orientação de profissional de educação física.

Não coloque senhas, tokens ou outras credenciais no repositório.
