# Landing page Bruna Rebello Advocacia (prévia)

- Página estática única (index.html, CSS e JS embutidos); foto em assets/bruna-rebello.jpg.
- Publicada em https://performaticosoficial.com.br/rebelloadvocacia/ (Hostinger, conta u639656644, site performaticosoficial.com.br, pasta "rebelloadvocacia").
- Fluxo de atualização: editar → commit → push em `main` → chamar `hosting_git_deploy-website-repository`
  (username u639656644, domain performaticosoficial.com.br, repository_url https://github.com/performaticosoficial/rebelloadvocacia-site.git, branch main, directory rebelloadvocacia) para a Hostinger puxar.
- Prévia: meta `noindex, nofollow`, cabeçalho X-Robots-Tag no .htaccess e robots.txt bloqueando. Na versão final no domínio da cliente, trocar para `index, follow` e refazer robots.txt.
- Identidade: preto #0A0A0A e dourado (#B8892F → #EED28A), Cinzel nos títulos, Montserrat no texto.
- WhatsApp da cliente: 5547999123962. Pendente: número da OAB/SC no rodapé.
- Status: DESATIVADA desde 26/11/2026 a pedido do Euler. Em `main`, index.html é só um aviso "indisponível" e a foto foi removida; a página completa está guardada na branch `versao-ativa` (commit 93da270). Para reativar: restaurar em `main` index.html e assets/ da `versao-ativa`, tirar o bloco "PÁGINA DESATIVADA" do .htaccess, publicar e limpar o cache (CDN ligado).
