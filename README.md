# CineOrbe

**Windows e Android · Downloads oficiais**

Português brasileiro · [English](README.en.md)

CineOrbe é um aplicativo para navegar por um catálogo de filmes e séries e reproduzir conteúdos disponíveis. Este repositório distribui o aplicativo para Windows e o APK para Android; não contém o código-fonte do aplicativo nem ferramentas internas de licenciamento.

## Downloads

| Plataforma | Versão | Download |
| --- | --- | --- |
| Windows x64 — instalador | 1.5.14 | [Baixar setup.exe](https://github.com/IstefaniOrbe/CineOrbe/releases/download/windows-v1.5.14/CineOrbe-1.5.14-setup.exe) |
| Windows x64 — portátil | 1.5.14 | [Baixar portable.exe](https://github.com/IstefaniOrbe/CineOrbe/releases/download/windows-v1.5.14/CineOrbe-1.5.14-portable.exe) |
| Android 8.0+ — APK | 1.5.17 | [Baixar APK](https://github.com/IstefaniOrbe/CineOrbe/releases/download/android-v1.5.17/CineOrbe-Android-1.5.17.apk) |

Todas as versões e os hashes SHA-256 estão na [página de Releases](https://github.com/IstefaniOrbe/CineOrbe/releases). Windows e Android usam numerações de versão independentes.

## Instalação

### Windows

1. Baixe o **instalador** para uma instalação padrão ou o executável **portátil** para executar sem o instalador.
2. Confira o hash SHA-256 no arquivo anexado à versão correspondente.
3. Execute o arquivo baixado.

**Os arquivos de Windows não possuem assinatura digital.** O Windows SmartScreen pode exibir um aviso. Não desative as proteções do Windows; prossiga apenas se confiar na origem e tiver conferido o download.

### Android

1. Utilize Android **8.0 ou superior** e mantenha o **Android System WebView** atualizado.
2. Baixe o APK na release de Android e confira o hash.
3. Se o Android solicitar, permita a instalação pelo navegador ou gerenciador de arquivos utilizado e abra o APK.
4. Depois, remova essa permissão de instalação se não precisar mais dela.

O APK é instalado manualmente; não é um link da Google Play. Faça backup de dados locais importantes antes de atualizar. A compatibilidade de atualização não foi testada novamente nesta publicação.

## Catálogo e apoio opcional

O catálogo não é limitado pelo status de apoiador. O apoio é opcional; uma licença de apoiador válida remove anúncios durante sua validade. A reprodução depende da disponibilidade do conteúdo e da conexão. Acesse apenas conteúdos que você tenha autorização para assistir.

## Verificação dos downloads

Cada release inclui `SHA256SUMS.txt`. No PowerShell do Windows:

```powershell
Get-FileHash .\CineOrbe-1.5.14-setup.exe -Algorithm SHA256
Get-FileHash .\CineOrbe-Android-1.5.17.apk -Algorithm SHA256
```

Compare o resultado com o hash da release correspondente. Um hash igual confirma a integridade do arquivo, não uma assinatura digital ou auditoria de segurança.

## Problemas e sugestões

Relate erros em [Issues](https://github.com/IstefaniOrbe/CineOrbe/issues). Informe plataforma, versão do aplicativo e passos para reproduzir. Não publique chaves de ativação, dados de pagamento, informações pessoais ou credenciais privadas.

## Escopo do repositório

Este é um **repositório de downloads**, não uma publicação de código aberto. Os executáveis ficam nas Releases do GitHub, e não no histórico Git. Chaves de assinatura, geradores de licença, ferramentas internas e configurações de servidor não são publicados aqui. Este repositório não concede uma nova licença de código aberto.
