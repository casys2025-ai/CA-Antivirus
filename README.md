# CA Antivírus

Instalador oficial do CA Antivírus para Windows 10 e 11 (64 bits). Baixe **CA-Antivirus-Setup.exe** na página [Releases](https://github.com/casys2025-ai/CA-Antivirus/releases).

## O que o aplicativo faz

- Usa o Microsoft Defender para a verificação rápida e para a proteção em tempo real do Windows. O Defender aplica as ações e administra a própria quarentena.
- Consulta detecções novas do Defender enquanto o CA está aberto e mostra um aviso visual e sonoro.
- Inclui o ClamAV como verificador adicional sob demanda. Atualize as assinaturas neste computador antes de analisar pastas.
- Mantém uma quarentena reversível própria para os resultados do scanner adicional.
- A limpeza temporária ignora arquivos em uso. Ela pede autorização do Windows antes de limpar as pastas do sistema.
- Envia somente contagens agregadas de aberturas, instalações únicas e atividade diária ao Painel CA Sys. Não envia nomes, IDs do computador, caminhos, arquivos ou resultados de verificação; o serviço de contagem recebe os dados normais da conexão de rede.

## Limites

O CA Antivírus não instala driver de interceptação e não bloqueia ameaças sozinho em tempo real. Para proteção contínua, deixe ativa a proteção em tempo real do Microsoft Defender ou de outro antivírus. Um resultado sem detecções não garante que todos os arquivos estejam limpos.

## Componentes de terceiros

Este instalador inclui os binários oficiais do ClamAV 1.5.4 para Windows. O ClamAV é licenciado sob GPLv2. Consulte o [código-fonte oficial da versão 1.5.4](https://github.com/Cisco-Talos/clamav/releases/tag/clamav-1.5.4) e a [documentação/licença do ClamAV](https://docs.clamav.net/).

© CA Sys, 2025–2026. Este repositório distribui o instalador oficial. O código-fonte do aplicativo CA não é publicado aqui. Não revenda nem distribua cópias modificadas como se fossem oficiais da CA Sys.
