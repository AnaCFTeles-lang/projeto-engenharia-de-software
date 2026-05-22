# projeto-engenharia-de-software
# Inicialize um repositório Git
git init

# Adicione um arquivo README
echo "# Meu Projeto" > README.md

# Adicione os arquivos ao Git
git add .

# Faça o primeiro commit
git commit -m "Initial commit"

# Adicione o repositório remoto (copie a URL do seu novo repositório no GitHub)
git remote add origin https://github.com/seu-usuario/seu-repositorio.git

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
#peso provas
p1p= 1
p2p= 2
p3p= 3
#processamento/calculos
soma_notas= (np1*p1p)+(np2*p2p)+(np3*p3p)
soma_peso= p1p + p2p + p3p
media= soma_notas/soma_peso
#condicionais e saida
if media<4:
    print(f"{media:.2f} Reprovado")
elif media<7:
    print(f"{media:.2f} Exame")
else:
    print(f"{media:.2f} Aprovado")
