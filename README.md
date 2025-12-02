https://tel36214287-star.github.io/Terminal-proprio/


Terminal Python em HTML (Pyodide)
Execução de código Python 100% local, direto no navegador

Este projeto implementa um terminal Python totalmente funcional escrito apenas com HTML, CSS e JavaScript, utilizando Pyodide — uma versão do Python compilada para WebAssembly, capaz de rodar inteiramente dentro do navegador, sem servidores e sem backend.

Ideal para:

Estudos de Python

Execução offline

Ambientes restritos sem instalação de Python

Prototipagem

Ensino e demonstrações rápidas

🚀 Funcionalidades
✔ Execução local

O código Python é executado diretamente no navegador através do Pyodide.
Nenhum dado é enviado para terceiros.

✔ Terminal integrado

Captura de stdout (print)

Captura de erros (stderr)

Saída formatada em tempo real

✔ Editor com recursos úteis

Atalho Ctrl+Enter para executar

Tema escuro/claro

Interface responsiva

Layout profissional com dois painéis

✔ Histórico local

Armazena automaticamente até 30 scripts

Seleção rápida no dropdown

Botão para limpar histórico

✔ Importação e exportação

Salvar código como .py

Carregar arquivos .py diretamente

✔ Exemplos rápidos

Botão para preencher automaticamente o editor com testes iniciais.

✔ Acesso opcional ao online-python.com

Botão que abre o site oficial em nova aba (caso o usuário queira um ambiente externo).

📦 Tecnologias utilizadas

HTML5

CSS3

JavaScript vanilla

Pyodide 0.23.4 (WebAssembly)

Interface criada sem dependências externas (leve e funcional)

📁 Estrutura do Projeto
/
│ index.html      -> Terminal Python completo
│ README.md       -> Este arquivo


(Se você quiser, posso criar uma versão modular separando CSS/JS.)

🖥️ Como executar
1. Baixe ou clone o repositório:
git clone https://github.com/SEU-USUARIO/SEU-REPO.git

2. Abra o arquivo no navegador

Basta clicar duas vezes em:

index.html


Não é necessário servidor local.

🧪 Exemplo de teste
print("=== TESTE: Loop + matemática ===")

for i in range(1, 6):
    print(f"Número {i} → quadrado = {i*i}")

import math
print("Seno de 1 rad =", math.sin(1))

⚠ Limitações conhecidas

input() não é interativo por padrão (Pyodide limita entrada).

Alguns pacotes Python externos podem não estar disponíveis.

Execução depende da performance do navegador.

Posso implementar:
✔ simulação de input
✔ suporte a micropip (instalar libs Python)
✔ painel avançado de arquivos
✔ console estilo Linux real

É só pedir!

📜 Licença

MIT — livre para uso pessoal, educativo ou comercial.
