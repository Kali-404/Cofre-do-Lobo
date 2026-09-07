<!-- README DO COFRE DO LOBO • KALI404 -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=210&text=COFRE%20DO%20LOBO&fontAlign=50&fontAlignY=38&fontSize=54&fontColor=ffffff&animation=twinkling&stroke=00d9ff&strokeWidth=1&color=0:090b13,25:3b1b7a,55:00a6d6,78:ff00aa,100:090b13" alt="Cofre do Lobo" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=21&duration=2400&pause=600&color=00E5FF&center=true&vCenter=true&width=800&lines=Seu+cofre+pessoal.+Local.+Criptografado.;Privacidade+e+organiza%C3%A7%C3%A3o%2C+sem+depender+da+nuvem.;Criado+por+Kali404+%F0%9F%87%A7%F0%9F%87%B7" alt="Descrição animada" />

<p>
  <img src="https://img.shields.io/badge/STATUS-OFFLINE%20READY-8b5cf6?style=for-the-badge&labelColor=090b13" alt="Funciona offline" />
  <img src="https://img.shields.io/badge/DADOS-LOCAIS-00e5ff?style=for-the-badge&labelColor=090b13" alt="Dados locais" />
  <img src="https://img.shields.io/badge/CRIPTOGRAFIA-AES--GCM%20256--bit-ff00aa?style=for-the-badge&labelColor=090b13" alt="Criptografia AES-GCM" />
  <a href="LICENSE"><img src="https://img.shields.io/badge/LICEN%C3%87A-MIT-00ff88?style=for-the-badge&labelColor=090b13" alt="Licença MIT" /></a>
</p>

</div>

> **Projeto local e privado:** seus dados permanecem no arquivo do cofre. Nenhum servidor do projeto recebe suas contas, senhas ou serviços cadastrados.

## 🐺 O que é o Cofre do Lobo?

O **Cofre do Lobo** organiza e-mails, senhas e os serviços vinculados a cada conta em uma interface visual, local e protegida por criptografia.

Ele nasceu para substituir planilhas confusas e anotações espalhadas, mantendo o controle dos dados nas mãos de quem usa. O projeto foi criado por **Kali404**, com foco em utilidade, privacidade e organização pessoal.

## ⚡ Recursos

- Uso em um único arquivo HTML, sem precisar instalar nada.
- Cofre protegido por senha mestre.
- Criptografia local com **Web Crypto API**, **AES-GCM de 256 bits** e **PBKDF2/SHA-256**.
- Frase de recuperação opcional.
- Cadastro de múltiplas contas de e-mail.
- Cadastro de serviços vinculados a cada conta.
- Serviços predefinidos e nomes personalizados, como TikTok, Kwai, bilibili ou Krafton.
- Ícones predefinidos ou personalizados para contas e serviços.
- Exportação de um novo HTML criptografado e utilizável offline.
- Layout responsivo para desktop e Android.

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=1700&pause=350&color=FF00AA&center=true&vCenter=true&width=760&lines=%F0%9F%94%90+Seus+dados.+Seu+controle.+Seu+cofre.;%E2%9C%A8+Organiza%C3%A7%C3%A3o+com+privacidade+de+verdade." alt="Mensagem animada" />
</div>

## 🖼️ Galeria

<p align="center">
  <img src="assets/screenshots/tela-inicial.png" alt="Tela inicial do Cofre do Lobo" width="48%" />
  <img src="assets/screenshots/criacao-do-cofre.png" alt="Criação de senha mestre e frase de recuperação" width="48%" />
</p>

<p align="center">
  <img src="assets/screenshots/painel-vazio.png" alt="Painel sem contas cadastradas" width="48%" />
  <img src="assets/screenshots/contas-e-servicos.png" alt="Contas e serviços vinculados" width="48%" />
</p>

<p align="center">
  <img src="assets/screenshots/adicionar-conta.png" alt="Formulário para adicionar uma conta" width="70%" />
</p>

> As imagens demonstram a interface com exemplos de teste. Nunca publique capturas contendo credenciais reais.

## 🎬 Demonstração em vídeo

<div align="center">
  <a href="https://raw.githubusercontent.com/Kali-404/Cofre-do-Lobo/main/cofre-do-lobo-demo.mp4">
    <img src="assets/screenshots/tela-inicial.png" width="640" alt="Clique para assistir à demonstração do Cofre do Lobo" />
  </a>

  <br>

  <sub>▶ Clique na imagem para abrir ou baixar o vídeo completo.</sub>
</div>

## 🚀 Como usar

1. Baixe o arquivo `index.html` deste repositório.
2. Abra-o em um navegador atualizado: Chrome, Edge, Firefox ou Safari.
3. Crie uma senha mestre forte e, se quiser, uma frase de recuperação.
4. Cadastre suas contas e os serviços vinculados.
5. Use **Baixar HTML** para salvar uma cópia atualizada do seu cofre.

> O navegador não envia os dados do cofre para um servidor do projeto. Eles permanecem no arquivo local, criptografados pela sua senha mestre.

## 🛡️ Segurança e transparência

O Cofre do Lobo é código aberto: qualquer pessoa pode inspecionar o HTML e JavaScript antes de usá-lo. Ele não instala programas, não executa arquivos externos e não depende de servidor próprio.

Boas práticas importantes:

- Use uma senha mestre longa e exclusiva.
- Guarde a frase de recuperação em um local seguro.
- Mantenha cópias de segurança do seu cofre em local protegido.
- Nunca publique ou envie seu cofre pessoal para terceiros.
- Não envie ao GitHub um HTML que já tenha suas contas cadastradas, mesmo criptografadas.

### Verificação no VirusTotal

Para aumentar a confiança da comunidade, envie ao [VirusTotal](https://www.virustotal.com/gui/home/upload) apenas a versão **limpa**, antes de cadastrar dados, e publique o link do resultado em uma Release.

<div align="center">
  <img src="assets/virus-total-warning.svg" alt="Atenção: não envie ao VirusTotal seu HTML pessoal exportado com dados cadastrados. Os arquivos enviados podem ser compartilhados com a comunidade de segurança." width="100%" />
</div>

Para conferir a integridade do arquivo no Windows:

```powershell
Get-FileHash .\index.html -Algorithm SHA256
```

Publique o valor retornado junto de cada Release para que outras pessoas possam comparar o arquivo baixado.

## 📊 Projeto no GitHub

<div align="center">
  <a href="https://github.com/Kali-404/Cofre-do-Lobo">
    <img src="https://img.shields.io/badge/ABRIR%20REPOSIT%C3%93RIO-Cofre%20do%20Lobo-00e5ff?style=for-the-badge&logo=github&logoColor=white&labelColor=090b13" alt="Abrir repositório Cofre do Lobo" />
  </a>
</div>

## ⚠️ Limitações conhecidas

- A recuperação depende da senha mestre ou da frase de recuperação configurada. Não há servidor capaz de restaurar uma senha perdida.
- Ícones adicionados por URL podem precisar de conexão para aparecer; prefira enviar uma imagem local para manter o uso totalmente offline.
- Esta é uma ferramenta de organização pessoal e não substitui uma auditoria profissional de segurança.

## 🤝 Contribuições

Sugestões, correções e melhorias são bem-vindas. Leia [CONTRIBUTING.md](CONTRIBUTING.md) antes de abrir uma issue ou pull request.

Para relatar uma possível falha de segurança, siga [SECURITY.md](SECURITY.md).

## 📄 Licença

Este projeto é disponibilizado sob a [Licença MIT](LICENSE).

<div align="center">

<br>

<p><strong>Kali404</strong> · Feito no Brasil 🇧🇷</p>

<a href="https://github.com/Kali-404"><img src="https://img.shields.io/badge/GitHub-Kali--404-181717?style=for-the-badge&logo=github&logoColor=white" alt="Perfil GitHub de Kali404" /></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&section=footer&animation=twinkling&color=0:090b13,30:ff00aa,55:8b5cf6,75:00e5ff,100:090b13" alt="Rodapé animado" />

</div>
