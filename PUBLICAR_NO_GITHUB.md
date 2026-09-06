# Publicar o Cofre do Lobo no GitHub

## 1. Preparar os arquivos

Este pacote já contém a estrutura inicial. Antes de publicar:

1. Confirme que `index.html` está limpo, sem contas, e-mails ou serviços pessoais.
2. Se quiser mostrar imagens no README, coloque-as em `assets/screenshots/` e descomente a galeria no `README.md`.
3. Leia a seção **Verificação no VirusTotal** do README.

## 2. Criar o repositório

No GitHub, crie um repositório público chamado, por exemplo, `cofre-do-lobo`.

Ao criar o repositório, não marque a opção de adicionar README, `.gitignore` ou licença: eles já estão neste pacote.

## 3. Publicar pelo GitHub Desktop — caminho mais simples

1. Instale e abra o GitHub Desktop.
2. Escolha **File > Add local repository** e selecione a pasta `Cofre-do-Lobo-GitHub`.
3. Faça o primeiro commit com a mensagem `Primeira versão pública do Cofre do Lobo`.
4. Clique em **Publish repository**.
5. Defina o nome `cofre-do-lobo`, mantenha o repositório público e confirme a publicação.

## 4. Publicar pelo Git — alternativa

Abra o Git Bash ou PowerShell dentro da pasta do projeto e execute:

```bash
git init
git add .
git commit -m "Primeira versão pública do Cofre do Lobo"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/cofre-do-lobo.git
git push -u origin main
```

Troque `SEU-USUARIO` pelo seu nome de usuário do GitHub.

## 5. Criar uma Release confiável

Depois do primeiro envio:

1. No repositório, abra **Releases** e crie uma nova release, por exemplo `v1.0.0`.
2. Anexe o arquivo `index.html` limpo.
3. Gere e informe o hash SHA-256 do arquivo.
4. Envie a mesma cópia limpa ao VirusTotal e adicione o link do resultado nas notas da release.
5. Explique que usuários nunca devem enviar seus cofres pessoais ao VirusTotal.

## Checklist final

- [ ] `index.html` está limpo, sem dados pessoais.
- [ ] README revisado e galeria preenchida, se houver imagens.
- [ ] Licença e política de segurança presentes.
- [ ] Hash SHA-256 calculado.
- [ ] Arquivo limpo analisado no VirusTotal.
- [ ] Release criada com notas claras.
