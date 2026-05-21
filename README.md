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
