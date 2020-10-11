# Proyecto_1


# Para configurar tu Git localmente

git config --global user.email [email]
git config --global user.name [name]


# Puedes ver tus configuraciones de Git en el archivo

cat ~/.gitconfig

# Comando para generar tu llave SSH

ssh-keygen -t rsa -b 4096 -C [email] 

# Para evaluar que hay un agente corriendo

eval "$(ssh-agent -s)"

# Copiar ID SSH al agente

ssh-copy-id [email]

# Copiar llave publica

cd ~/.ssh 
cat id_rsa.pub

