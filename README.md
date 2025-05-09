# 📦 Modelo de Pacote Python Simples

Este é um exemplo de **pacote Python simples**, criado com o objetivo de servir como base para projetos futuros. Ele foi desenvolvido para praticar a estruturação de pacotes, a organização do código, a criação de funções reutilizáveis e a escrita de testes unitários.

---

## ✨ Objetivo

- Compreender como criar um pacote Python reutilizável.
- Praticar a separação de responsabilidades em arquivos diferentes.
- Aprender a estruturar um projeto com testes e dependências.
- Treinar o uso de `setup.py` e `requirements.txt` para empacotamento e instalação.

---

## 🚀 Funcionalidades do Pacote

O pacote contém **duas funções principais**:

### ✅ `say_hello(name: str) -> str`

Retorna uma saudação personalizada com o nome fornecido.

**Exemplo de uso:**
```python
from seu_pacote import say_hello

print(say_hello("Siury"))  # Saída: "Hello, Siury!"

➕ add_numbers(a: float, b: float) -> float
Soma dois números e retorna o resultado.

Exemplo de uso:

python
Copiar
Editar
from seu_pacote import add_numbers

print(add_numbers(3, 5))  # Saída: 8

🗂️ Estrutura do Projeto
A estrutura dos arquivos está organizada assim:

kotlin
Copiar
Editar
seu_pacote/
├── __init__.py              # Torna o diretório um módulo Python
├── file1_name.py            # Contém a função say_hello
├── file2_name.py            # Contém a função add_numbers
tests/
├── __init__.py              # Permite rodar os testes como pacote
├── test_file1_name.py       # Testes para a função say_hello
├── test_file2_name.py       # Testes para a função add_numbers
setup.py                     # Script para instalação do pacote
requirements.txt             # Lista de dependências
README.md                    # Explicações do projeto


📌 Requisitos
Python 3.8 ou superior

Nenhuma biblioteca externa obrigatória

📂 Sobre os Arquivos
setup.py
Arquivo de configuração que define os metadados do seu pacote (nome, versão, autor, etc.) e as instruções para instalação.

requirements.txt
Lista bibliotecas que seu pacote precisa para funcionar corretamente (mesmo que esteja vazio neste exemplo).

__init__.py
Permite que o Python trate os diretórios como pacotes. Você pode deixar vazio ou importar as funções principais aqui para facilitar o uso.

🧑‍💻 Autor(a)
Feito com 💻 por Siury — estudante de Análise e Desenvolvimento de Sistemas, buscando crescer como programadora
com base sólida e dedicação.

📄 Licença
Este projeto está licenciado sob os termos da MIT License.

🙏 Finalidade Didática
Este repositório é parte de um exercício de aprendizado sobre como construir pacotes Python de forma organizada,
com boas práticas e foco em reutilização de código. Sinta-se à vontade para reutilizar e melhorar este modelo.













