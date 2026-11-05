# MyTutor

Tutor pessoal com IA para aprender qualquer assunto: trilhas de estudo, diagnóstico, conversa com o tutor e cartões de revisão.

**Abrir o app:** https://eneas-ena.github.io/mytutor/

## Como funciona

- App feito em página web; abre direto no navegador e pode ser instalado na tela inicial do celular ou do iPad.
- Entra com e-mail e senha (login do Supabase).
- Os dados ficam no Supabase, no schema `mytutor`, por isso aparecem iguais em todos os aparelhos.
- A inteligência artificial passa pelo Worker `mytutor-ia` no Cloudflare, que só responde a quem está logado; a chave secreta fica guardada lá, nunca neste código.
- Mostra o número da versão na tela, tem modo claro e escuro (sol/lua) e botão para atualizar.

## Como publicar uma nova versão

1. Nesta página do repositório, clique em **Add file → Upload files**.
2. Arraste os arquivos novos, com os mesmos nomes dos antigos.
3. Clique em **Commit changes**.

Em um ou dois minutos a nova versão está no ar no mesmo endereço. No app, o aviso **"Atualizar agora"** aparece sozinho quando há versão nova.

---
Desenvolvido por Bispo Enéas Araújo.
