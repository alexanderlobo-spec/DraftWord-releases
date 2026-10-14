<p align="center"><img src="logo.png" width="160" alt="DraftWord"></p>

# DraftWord — downloads

*[English version](README.en.md)*

DraftWord é um processador de texto para macOS e Windows, feito como hobby.
**É gratuito e não aceita pagamento de nenhum tipo**: sem venda, assinatura, anúncios ou doações.
Não é uma oferta comercial e não está em nenhuma loja.

Baseado no [WordCraft](https://github.com/storytold/wordcraft) (MIT OR Apache-2.0), com interface,
ícones e temas próprios. Os avisos de licença e as atribuições vão dentro de cada pacote.

## Downloads

| Sistema | Arquivo | Observações |
|---|---|---|
| macOS 11+ (Intel e Apple Silicon) | [`macOS/`](macOS/) — `.dmg` universal | Assinado com Developer ID e notarizado pela Apple: abre sem avisos. Arraste o DraftWord para Aplicativos. |
| Windows 10/11 (x64) | [`windows/`](windows/) — `.msi` ou `.zip` portátil | Sem certificado de assinatura: na primeira abertura o SmartScreen pode avisar; escolha "Mais informações › Executar assim mesmo". |

Cada arquivo tem um `.sha256` ao lado para conferência.

## Como instalar

### macOS

1. Entre na pasta [`macOS/`](macOS/), clique no arquivo `.dmg` e depois no botão **Download**.
2. Abra o arquivo baixado. Aparece uma janela com o ícone do DraftWord e a pasta Aplicativos.
3. Arraste o DraftWord para Aplicativos.
4. Abra o DraftWord pelo Launchpad ou pela pasta Aplicativos. Não há aviso: o app é notarizado pela Apple.
5. Pode ejetar o disco "DraftWord" e apagar o `.dmg`.

### Windows

1. Entre na pasta [`windows/`](windows/), clique no arquivo `.msi` e depois no botão **Download**.
2. Dê dois cliques no arquivo baixado.
3. Se aparecer a tela azul "O Windows protegeu o computador", clique em **Mais informações** e depois em **Executar assim mesmo**. O botão só aparece depois de "Mais informações". É o SmartScreen avisando que o app não tem certificado pago; acontece só na primeira vez.
4. Siga o instalador: aceitar a licença, Instalar, Concluir. Ele pode pedir a senha de administrador.
5. O DraftWord fica no menu Iniciar.

**Sem permissão para instalar programas?** Baixe o `.zip` portátil, descompacte numa pasta sua (Documentos, por exemplo) e abra o `DraftWord.exe` de dentro dela. Nada é instalado.

### Atualizar

Baixe o arquivo da versão nova e instale por cima. Os documentos ficam onde você salvou; a instalação não mexe neles.

## Versão atual

0.6.1-draftword.16 (14/out/2026).

Novidades: o salvamento automático liga assim que um `.docx` é aberto, e uma cópia de recuperação é guardada enquanto você escreve; se o app fechar sem salvar, a abertura seguinte oferece o documento de volta.

## Código-fonte

O código do DraftWord fica em um repositório privado. Este repositório guarda só os instaladores.
