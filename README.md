# Windows 10 upgrade para Windows 11

Baixe o Windows 11

Há três opções abaixo para instalar ou criar a mídia do Windows 11. Confira cada uma delas para determinar a melhor opção para você.

Se você estiver atualizando do Windows 10, recomendamos que aguarde até que seja notificado por meio do Windows Update que a atualização está pronta para o seu computador.

Antes de instalar, consulte o aplicativo de verificação de integridade do PC para confirmar se o dispositivo atende aos requisitos mínimos do sistema para o Windows 11 e verificar o status de informações de versão do Windows sobre problemas conhecidos que possam afetar seu dispositivo.

https://www.microsoft.com/pt-br/software-download/windows11

# Notebooks compativel migrado com sucesso:

Lenovo

https://support.lenovo.com/us/en/solutions/ht512623-lenovo-devices-supported-for-windows-11

Notebook S145-15API

# Habilitar o TPM 2.0 no computador
Publicado em agosto de 2021

fonte: https://support.microsoft.com/pt-br/windows/habilitar-o-tpm-2-0-no-computador-1fd5a332-360d-4f46-a1e7-ae6b0c90645c

Este artigo destina-se a usuários que não são capazes de atualizar para o Windows 11 porque seu computador não está habilitado no momento com o TPM 2.0 ou seu computador é capaz de executar o TPM 2.0, mas não está definido para isso. Se você não estiver familiarizado com esse nível de detalhes técnicos, recomendamos consultar as informações de suporte do fabricante do computador para obter mais instruções específicas para seu dispositivo.

A maioria dos PCs que foram enviados nos últimos 5 anos é capaz de executar o Trusted Platform Module versão 2.0 (TPM 2.0). O TPM 2.0 é necessário para executar Windows 11, como um bloco de construção importante para recursos relacionados à segurança. O TPM 2.0 é usado no Windows 11 para vários recursos, incluindo o Windows Hello para proteção de identidade e o BitLocker para proteção de dados.

Em alguns casos, os PCs que são capazes de executar o TPM 2.0 não são definidos para isso. Se você estiver considerando atualizar para o Windows 11, verifique se o TPM 2.0 está habilitado em seu dispositivo. A maioria das placas-mãe de computador de varejo usadas por pessoas que estão criando seu próprio computador, por exemplo, são fornecidas com o TPM desligado por padrão, mesmo que seja quase alwatys disponíveis para serem habilitados.

# Opção 1: Usar o Segurança do Windows aplicativo

Executar Configurações > Atualização & Segurança > Segurança do Windows > Segurança do Dispositivo

Se você não vir uma seção Processador de segurança nesta tela, seu computador poderá ter um TPM desabilitado. consulte Como habilitar o TPM para obter mais informações ou verificar as informações de suporte do fabricante do computador para obter instruções. para habilitar o TPM. Se você conseguir habilitar um TPM, conclua a próxima etapa para verificar se é um TPM 2.0.

Se você vir uma opção para detalhes do processador de segurança em Processadorde segurança, selecione-o e verifique se sua versão de Especificação é 2.0. Se for menor que 2.0, o dispositivo não atenderá aos requisitos Windows 11.

# Opção 2: Usar o Console de Gerenciamento da Microsoft

Pressione [Windows Tecla] + R ou selecione Iniciar> Executar.

Digite "tpm.msc" (não use aspas) e escolha OK.

Se você vir uma mensagem dizendo que um "TPM compatível não pode ser encontrado", seu computador pode ter um TPM desabilitado. Consulte Como habilitar o TPM para obter mais informações ou verificar as informações de suporte do fabricante do computador para obter instruções para habilitar o TPM. Se você conseguir habilitar o TPM, conclua a próxima etapa para verificar se é um TPM 2.0.

Se você vir uma mensagem confirmando que o TPM está pronto para uso, verifique a Versão de Especificação em Informações do Fabricante do TPM para verificar se ele é 2.0. Se for menor que 2,0, seu dispositivo não atenderá ao requisito Windows 11.

Como habilitar o TPM
Se você precisar habilitar o TPM, essas configurações serão gerenciadas por meio do BIOS UEFI (firmware do computador) e variam com base no dispositivo. Você pode acessar essas configurações escolhendo: Configurações > Atualizar & Segurança > Recuperação > Reiniciar agora.

Na próxima tela, escolha Solucionar problemas>opções avançadas> firmware UEFI Configurações> Reiniciar para fazer as alterações. Essas configurações às vezes estão contidas em um sub-menu no BIOS UEFI rotulado Avançado,Segurançaou Computação Confiável. A opção para habilitar o TPM pode ser rotulada de Dispositivo de Segurança,Suporte a Dispositivo de Segurança,Estado do TPM,Comução FTPM amd,FTPM do PSP AMD,Intel PTTou Tecnologia de Confiança da   Plataforma Intel.

Se você não tiver certeza de como fazer as alterações necessárias nas configurações do TPM, recomendamos verificar as informações de suporte do fabricante do computador ou entrar em contato com a organização de suporte. Abaixo estão links para informações de alguns fabricantes de computadores para ajudá-lo a começar:

Asus

Dell

HP

Lenovo



