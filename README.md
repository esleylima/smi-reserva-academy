# Página reserva no endereço da academy

Plano B da Black 2026, para um apagão do servidor inteiro. Num apagão longo, o DNS
de **academy.treinamentosmi.com.br** é apontado para cá (CNAME para
esleylima.github.io), e quem abrir qualquer endereço da academy vê a página reserva.
Quando o servidor volta, o DNS volta para ele.

- `index.html` e `404.html`: a mesma página do repositório smi-reserva.
- `CNAME`: o endereço da academy, já configurado no GitHub Pages.

Nada aqui tem dado de cliente, senha ou chave: o repositório é público para o
GitHub Pages ser gratuito.
