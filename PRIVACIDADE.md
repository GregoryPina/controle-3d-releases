# Privacidade — Controle 3D Valhalla

Atualizado em 21 de outubro de 2026.

O Controle 3D Valhalla é um aplicativo para Windows e Android que organiza estoque, vendas, compras, contas e eventos de uma pequena loja.

## Dados utilizados

Ao conectar o Google, o aplicativo usa o e-mail verificado da conta para identificar o autor dos lançamentos. Solicita a permissão `drive.file`, limitada aos arquivos que o usuário autoriza para este aplicativo. Não solicita acesso geral a todas as planilhas da conta.

O aplicativo consulta e acrescenta registros na planilha escolhida, incluindo produtos, quantidades, valores, pagamentos, datas e o e-mail do autor. Esses registros ficam na conta Google do proprietário da planilha e são acessíveis às pessoas com quem ele a compartilha. Cada loja pode usar uma planilha separada.

## Armazenamento no aparelho

O aplicativo guarda a identificação da planilha e da conta para reconectar. No Windows, a credencial de renovação do login é guardada usando armazenamento criptografado do sistema. No Android, a autorização é administrada pelos serviços do Google. Tokens de acesso são usados na memória durante a comunicação autenticada.

Lançamentos com confirmação pendente podem ser guardados no armazenamento privado do aplicativo até a sincronização. A demonstração e seus backups ficam no aparelho. Desconectar não apaga a planilha nem os registros pendentes.

## Serviços externos

Google autentica a conta, mostra o seletor de arquivos e armazena os dados da planilha. GitHub distribui atualizações e recebe as solicitações de consulta e download. Esses serviços processam as conexões conforme suas próprias políticas. Dados da loja e credenciais Google não são enviados ao repositório GitHub pelo aplicativo.

O aplicativo não implementa publicidade, venda de dados ou envio automático de registros da loja ao desenvolvedor.

## Controle e exclusão

O proprietário controla o compartilhamento da planilha pelo Google Drive. Cada usuário pode revogar a autorização nas conexões de terceiros da sua conta Google e desconectar a loja no aplicativo. A revogação interrompe novos acessos, mas não apaga os registros já salvos.

Excluir uma compra ou conta pelo aplicativo mantém o histórico da correção na planilha. Para remover definitivamente os dados, o proprietário deve excluir os arquivos correspondentes no Google Drive e esvaziar a lixeira quando desejar. Dados e backups locais devem ser removidos separadamente pelo usuário.

## Contato

Dúvidas sobre o aplicativo ou privacidade podem ser encaminhadas pelo canal de suporte indicado na tela de consentimento Google ou pelas [issues deste repositório](https://github.com/GregoryPina/controle-3d-releases/issues). Não publique dados da loja, senhas ou tokens em issues públicas.
