# Primeiro-mini-homelab
a primeira experiencia com home lab, simples e prático.


# 🧪 Meu Primeiro Mini Home Lab

Este repositório documenta meu primeiro mini home lab, feito com uma máquina virtual rodando um servidor Apache simples. O objetivo foi entender como hospedar um arquivo HTML em uma VM e acessá-lo pelo navegador do meu PC.

---

## ⚙️ Tecnologias e Ferramentas
- VMware Workstation
- Ubuntu Server
- Apache2
- Rede Bridge (acesso via IP local)

---

## 🧩 Estrutura do Projeto
- `/setup`: configuração da VM e rede
- `/webserver`: arquivos e setup do servidor web
- `/notes`: anotações e aprendizados

---

## 🚀 Passos realizados
1. Criei uma máquina virtual no VMware com Ubuntu Server
2. Instalei o Apache2 (`sudo apt install apache2`)
3. Testei acessando o IP da VM no navegador (`http://192.168.x.x`)
4. Editei o arquivo `index.html` e confirmei que o texto aparecia no navegador

---

## 📸 Prints do processo
(wake-up,-neo.png)

---

## 💡 Aprendizados
- Entendi como funciona o servidor HTTP básico
- Aprendi a configurar rede Bridge no VMware
- Comecei a praticar documentação técnica

---

## 🔮 Próximos passos
- Adicionar DNS local (com `bind9`)
- Criar mais de uma VM (client + server)
- Automatizar instalação com script
