# Projeto de Engenharia de Software

## Sobre o Projeto
Este projeto está sendo desenvolvido para a disciplina de Engenharia de Software, com o objetivo de aprender e aplicar **Métodos Ágeis**, organização de equipes e documentação de sistemas. 

## Objetivo
Desenvolver um sistema que calcule notas.


## 👥 Equipe de Desenvolvimento
- **Ana Carolina Teles** 
- 
- 
- 

## 🛠️ Metodologia Utilizada
Utilizamos a metodologia **Scrum**, organizando as tarefas em **Kanban**, trabalhando em ciclos curtos e sempre mantendo a documentação atualizada neste repositório. 📋⚔️

## 📂 Estrutura do Repositório
- 📁 **/Documentos**: Aqui estão todos os diagramas, relatórios, atas de reunião e desenhos de telas produzidos durante o projeto. 📑
- 📄 **README.md**: Você está aqui! Apresentação geral do trabalho.

## 💻 Tecnologias
Para este projeto estamos utilizando:
- Ferramentas de organização: GitHub, Quadro Kanban.
- Documentação: Ferramentas de desenho de diagramas e texto.

---
Última atualização: [28/05/2026]

# Envie o código para o GitHub
git branch -M main
git push -u origin main
#Código Enviado: Ana
/*Adicionado por Ana*/
#ENTRADRA/definindo variaveis
#notas provas
np1= float(input())
np2= float(input())
np3= float(input())
np4= float(input())
#peso provas
p1p= 1
p2p= 2
p3p= 3
p4p= 4
#processamento/calculos
soma_notas= (np1*p1p)+(np2*p2p)+(np3*p3p)+(np4*p4p)
soma_peso= p1p + p2p + p3p + p4p
media= soma_notas/soma_peso
#condicionais e saida
if media=<4:
    print(f"{media:.2f} Reprovado")
elif media=<7:
    print(f"{media:.2f} Exame")
else:
    print(f"{media:.2f} Aprovado")
#código define a media de notas do aluno 
#tecnologias usadas: Python 

