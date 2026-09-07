# Mardisa Care+

## Pós-venda inteligente e preventivo

O **Mardisa Care+** é uma proposta de melhoria da jornada de pós-venda da Mardisa, criada para tornar o atendimento mais transparente, ágil e personalizado.

### Objetivo

Oferecer ao cliente acompanhamento do serviço, comunicação clara, evidências do diagnóstico, um resumo visual da saúde do veículo e contato pós-serviço.

### Como funciona

1. A Ordem de Serviço recebe um identificador único.
2. O cliente recebe um link ou QR Code.
3. O cliente acompanha as etapas do atendimento.
4. O consultor pode disponibilizar fotos e vídeos curtos das condições encontradas.
5. Ao final, é apresentado o Check-up Digital Mercedes.
6. Após a entrega, a Mardisa realiza o acompanhamento de satisfação.

### Protótipo

O arquivo `index.html` é um protótipo estático e funciona diretamente no GitHub Pages.

Exemplo:
`https://SEU-USUARIO.github.io/mardisa-care-plus/?os=25874`

O parâmetro `os` altera o número da Ordem de Serviço exibida na tela.

### Estrutura

- `index.html` — página principal do protótipo.
- `README.md` — documentação do projeto.
- `docs/PROJETO.md` — descrição completa da solução.
- `docs/IMPLANTACAO.md` — roteiro de implantação e piloto.
- `data/os-exemplo.json` — exemplo de dados de uma OS.
- `.nojekyll` — evita processamento desnecessário do Jekyll.
- `.github/workflows/pages.yml` — publicação automática via GitHub Actions.

### Importante

Este repositório é um **protótipo**. Não coloque dados reais de clientes, placas, CPF, telefone, documentos, fotos de veículos ou outras informações pessoais enquanto a solução não estiver integrada a um ambiente autorizado e com os controles de segurança e privacidade definidos pela empresa.

### Publicação no GitHub Pages

O GitHub Pages publica arquivos estáticos de um repositório e permite configurar a publicação a partir de uma branch ou por GitHub Actions.

Para uma conta GitHub Free, um repositório público pode ser usado para o Pages.

Após enviar os arquivos:

1. Abra o repositório no GitHub.
2. Acesse **Settings → Pages**.
3. Em **Build and deployment**, selecione a opção de publicação por GitHub Actions ou, alternativamente, pela branch `main`.
4. Aguarde a publicação.
5. Use o endereço exibido pelo GitHub em **Visit site**.

Consulte a documentação oficial:
https://docs.github.com/pt/pages
