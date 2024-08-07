------------------ ssh
1.  git --version

2. git config --global user.name ''Emanuele”
3.  git config --global user.email "emanuelevpries5252@gmail.com"

4.  git config --list 

5.  ls -al ~/.ssh → verifica se a chave existe

6. ssh-keygen -t ed25519 -C "Meu email" → **criando a chave**

7. eval "$(ssh-agent -s)" → **Inicializar o agente**

8.  ssh-add ~/.ssh/id_ed25519 → **Adicionar a chave ao agente**

9.  clip < ~/.ssh/id_ed25519.pub → **copia a chave do ssh para o github**

10.  ssh -T git@github.comF


----------------------

git rm --cached exemplo.md → isso tira eles do estágio de commit

nano exemplo2.md → Nano quer dizer que vai abrir o arquivo, dai você pode editar

----------------------

**Git status** → status

**Gid add <filename ou .>** → Vai adicionar um arquivo para ser commitado

**Git Restore - -staged <filename ou .>** → remover esse arquivo para ele não ser commitado

**Git branch** <branchname> → criar uma nova branch

**Git checkout** <branchname> → vai trocar de branch

**Git checkout** -b <branchname> → vai criar uma nova e trocar

**Git commit -m “<description>”** → vai fazer o commit

**Git merge** <branchname> → vai mesclar as branches

**Git branch -D <branchname>** → deletar a branch

Para limpar o terminal, cntrl L ou clear