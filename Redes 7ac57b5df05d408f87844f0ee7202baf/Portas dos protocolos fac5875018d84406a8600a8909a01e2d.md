# Portas dos protocolos

| Porta | Descrição | Status |
| --- | --- | --- |
| 0/TCP,UDP | Reservada. | Fora de Serviço |
| 1/TCP,UDP | TCPMUX (Serviço de porta TCP multiplexador) | Oficial |
| 5/TCP,UDP | RJE (Remote Job Entry - Entrada de trabalho remoto) | Oficial |
| 7/TCP,UDP | ECHO protocol (Serviço Echo) | Oficial |
| 9/TCP,UDP | DISCARD protocol (Serviço zero para teste de conexão) | Oficial |
| 11/TCP,UDP | SYSTAT protocol (Serviço de Estado do Sistema para listar as portas conectadas) | Oficial |
| 13/TCP,UDP | DAYTIME protocol (Envia data e hora para a máquina requerente) | Oficial |
| 17/TCP,UDP | QOTD protocol (Envia a citação do dia para a máquina conectada) | Oficial |
| 18/TCP,UDP | Message Send Protocol (Protocolo de envio de mensagem) | Oficial |
| 19/TCP,UDP | CHARGEN protocol (Character Generator Protocol - Protocolo de geração de caracter) | Oficial |
| 20/TCP | https://pt.wikipedia.org/wiki/File_Transfer_Protocol (File Transfer Protocol - Protocolo de transferência de arquivo) - Porta de dados do FTP | Oficial |
| 21/TCP | https://pt.wikipedia.org/wiki/File_Transfer_Protocol (File Transfer Protocol - Protocolo de transferência de arquivo) - Porta do Protocolo de Transferência de Arquivos | Oficial |
| 22/TCP,UDP | https://pt.wikipedia.org/wiki/Secure_shell (Secure Shell - Shell seguro) - Usada para logins seguros, transferência de arquivos e redirecionamento de porta | Oficial |
| 23/TCP,UDP | https://pt.wikipedia.org/wiki/Telnet protocol - Comunicação de texto sem encriptação | Oficial |
| 25/TCP,UDP | https://pt.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol (Simple Mail Transfer Protocol - Protocolo simples de envio de e-mail) - usada para roteamento de e-mail entre servidores (Atualmente é utilizada a porta 587,conforme https://pt.wikipedia.org/wiki/Comit%C3%AA_Gestor_da_Internet_no_Brasil CGI.br | Oficial |
| 26/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=RSFTP&action=edit&redlink=1 - protocolo similar ao FTP | Não-oficial |
| 35/TCP,UDP | QMS Magicolor 2 printer | Não-oficial |
| 37/TCP,UDP | TIME protocol (Protocolo de Tempo) | Oficial |
| 38/TCP,UDP | Route Access Protocol (Protocolo de Acesso ao roteador) | Oficial |
| 39/TCP,UDP | Resource Location Protocol (Protocolo de localização de recursos) | Oficial |
| 41/TCP,UDP | Graphics (gráficos) | Oficial |
| 42/TCP,UDP | Host Name Server (Servidor do Nome do Host) | Oficial |
| 42/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=WINS&action=edit&redlink=1 http://www.auditmypc.com/port/tcp-port-1512.asp | Não-oficial/Conflito |
| 43/TCP | https://pt.wikipedia.org/wiki/WHOIS (protocolo de consulta de informações de contato e DNSprotocol) | Oficial |
| 49/TCP,UDP | https://pt.wikipedia.org/wiki/TACACS Login Host protocol(Protocolo de Login no Host) | Oficial |
| 53/TCP,UDP | https://pt.wikipedia.org/wiki/Domain_Name_System (Domain Name System - Sistema de nome de domínio) | Oficial |
| 57/TCP | MTP, Mail Transfer Protocol (Protocolo de transferência de e-mail) |  |
| 67/UDP | https://pt.wikipedia.org/wiki/BOOTP (BootStrap Protocol) server; também utilizada por https://pt.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol (Protocolo de configuração dinâmica do Host) | Oficial |
| 68/UDP | https://pt.wikipedia.org/wiki/BOOTP client; também utilizada por https://pt.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol | Oficial |
| 69/UDP | https://pt.wikipedia.org/wiki/Trivial_File_Transfer_Protocol(Trivial File Transfer Protocol) (Protocolo de transferência de arquivo trivial) | Oficial |
| 70/TCP | https://pt.wikipedia.org/wiki/Gopher (Protocolo para indexar repositórios) | Oficial |
| 79/TCP | https://pt.wikipedia.org/wiki/Finger_protocol (Serviço finger para informações de contato do usuário) | Oficial |
| 80/TCP | https://pt.wikipedia.org/wiki/HTTP (HyperText Transfer Protocol - Procolo de transferência de HiperTexto) - usada para transferir páginas WWW | Oficial |
| 80/TCP | HTTP Alternate (HyperText Transfer Protocol - Protocolo de transferência de HiperTexto) | Oficial |
| 81/TCP | https://pt.wikipedia.org/wiki/Skype protocol | Oficial |
| 81/TCP | https://pt.wikipedia.org/w/index.php?title=Torpark&action=edit&redlink=1 - https://pt.wikipedia.org/w/index.php?title=Onion_routing&action=edit&redlink=1 ORport | Não-oficial |
| 82/UDP | https://pt.wikipedia.org/w/index.php?title=Torpark&action=edit&redlink=1 - Control Port | Não-oficial |
| 88/TCP | https://pt.wikipedia.org/w/index.php?title=Kerberos_(protocol)&action=edit&redlink=1 (Protocolo de comunicações individuais seguras e identificadas) - authenticating agent | Oficial |
| 101/TCP | HOSTNAME (Serviços de nomes para máquinas SRI-NIC) |  |
| 102/TCP | ISO-TSAP protocol (Aplicações de rede do Ambiente de Desenvolvimento ISO (ISODE) |  |
| 107/TCP | Remote Telnet Service (Serviço remoto Telnet) |  |
| 109/TCP | POP (Post Office Protocol): Protocolo de Correio Eletrônico, versão 2 |  |
| 110/TCP | https://pt.wikipedia.org/wiki/Post_Office_Protocol (Post Office Protocol version 3): Protocolo de Correio Eletrônico, versão 3 - usada para recebimento de e-mail | Oficial |
| 111/TCP,UDP | sun protocol (Protocolo da Chamada de Procedimento Remoto (RPC) para execução de comandos remotos, usado pelo Sistema de Arquivo de Rede (NFS) | Oficial |
| 113/TCP | https://pt.wikipedia.org/w/index.php?title=Ident&action=edit&redlink=1 - antigo identificador de servidores, ainda usada em servidores https://pt.wikipedia.org/wiki/Internet_Relay_Chat para identificar seus usuários | Oficial |
| 115/TCP | SFTP, (Simple File Transfer Protocol) (Protocolo de simples transferência de arquivo) |  |
| 117/TCP | UUCP-PATH (Serviços da Localidade do Protocolo de Cópia Unix-para-Unix) |  |
| 118/TCP,UDP | https://pt.wikipedia.org/wiki/SQL Services | Oficial |
| 119/TCP | https://pt.wikipedia.org/wiki/NNTP (Network News Transfer Protocol) (Protocolo de transferência de notícias na rede) - usada para recebimento de mensagens de newsgroups | Oficial |
| 123/UDP | https://pt.wikipedia.org/wiki/Network_Time_Protocol (Network Time Protocol) (Protocolo de tempo na rede) - usada para sincronização de horário | Oficial |
| 135/TCP,UDP | EPMAP (End Point Mapper) / Microsoft RPC Locator Service (Microsoft RPC Serviço de localização) | Oficial |
| 137/TCP,UDP | https://pt.wikipedia.org/wiki/NetBIOS NetBIOS Name Service | Oficial |
| 138/TCP,UDP | https://pt.wikipedia.org/wiki/NetBIOS NetBIOS Datagram Service (Serviço de datagrama NetBios) | Oficial |
| 139/TCP,UDP | https://pt.wikipedia.org/wiki/NetBIOS NetBIOS Session Service (Serviço de sessão NetBios) | Oficial |
| 143/TCP,UDP | https://pt.wikipedia.org/wiki/Internet_Message_Access_Protocol (Internet Message Access Protocol 4) (Protocolo de Acesso a mensagens na Internet) - usada para recebimento de e-mail | Oficial |
| 152/TCP,UDP | BFTP, Background File Transfer Program (Protocolo de transferência de arquivo em Background(fundo) |  |
| 153/TCP,UDP | SGMP, https://pt.wikipedia.org/w/index.php?title=Simple_Gateway_Monitoring_Protocol&action=edit&redlink=1 (Protocolo de simples monitoramento do gateway) |  |
| 156/TCP,UDP | SQL Service (Serviço SQL) | Oficial |
| 158/TCP,UDP | DMSP, Distributed Mail Service Protocol (Protocolo de serviço de e-mail distribuído) |  |
| 161/TCP,UDP | https://pt.wikipedia.org/wiki/Simple_Network_Management_Protocol (Simple Network Management Protocol) (Protocolo simples de gerenciamento de rede) | Oficial |
| 162/TCP,UDP | SNMPTRAP | Oficial |
| 170/TCP | Print-srv (Print Server) |  |
| 179/TCP | https://pt.wikipedia.org/wiki/Border_Gateway_Protocol (Border Gateway Protocol)(Protocolo de Gateway de Borda) | Oficial |
| 194/TCP | https://pt.wikipedia.org/wiki/Internet_Relay_Chat (Internet Relay Chat) | Oficial |
| 201/TCP,UDP | AppleTalk Routing Maintenance |  |
| 209/TCP,UDP | The Quick Mail Transfer Protocol (Protocolo de rápida transferência de mail) |  |
| 213/TCP,UDP | https://pt.wikipedia.org/wiki/IPX (Internetwork Packet Exchange) (Troca de pacote na área de trabalho da internet) | Oficial |
| 218/TCP,UDP | MPP, Message Posting Protocol (Protocolo de postagem de mensagem) |  |
| 220/TCP,UDP | IMAP, Interactive Mail Access Protocol, version 3 (Protocolo de acesso interativo ao mail) |  |
| 259/TCP,UDP | ESRO, Efficient Short Remote Operations (Operações remotas de curta eficiência) |  |
| 264/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=Border_Gateway_Multicast_Protocol&action=edit&redlink=1, Border Gateway Multicast Protocol |  |
| 311/TCP | Apple Server-Admin-Tool, Workgroup-Manager-Tool, (Ferramenta de gerenciamento de workgroup) |  |
| 318/TCP,UDP | TSP, https://pt.wikipedia.org/w/index.php?title=Time_Stamp_Protocol&action=edit&redlink=1 |  |
| 323/TCP,UDP | IMMP, Internet Message Mapping Protocol (Protocolo de mapeamento de mensagem da internet) |  |
| 383/TCP,UDP | HP OpenView HTTPs Operations Agent |  |
| 366/TCP,UDP | SMTP, Simple Mail Transfer Protocol (Protocolo de simples transferência de mail). ODMR, On-Demand Mail Relay |  |
| 369/TCP,UDP | Rpc2portmap | Oficial |
| 371/TCP,UDP | ClearCase albd | Oficial |
| 384/TCP,UDP | A Remote Network Server System (Sistema servidor de rede remota) |  |
| 387/TCP,UDP | AURP, AppleTalk Update-based Routing Protocol |  |
| 389/TCP,UDP | https://pt.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol (Lightweight Directory Access Protocol)(Protocolo de acesso a diretório lightweight) | Oficial |
| 401/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=Uninterruptible_power_supply&action=edit&redlink=1 Uninterruptible Power Supply (Suprimento de potência Ininterruptível) | Oficial |
| 411/TCP | https://pt.wikipedia.org/w/index.php?title=Direct_Connect_network&action=edit&redlink=1 (Rede de conexão direta, Conexão direta) Hub port | Não-oficial |
| 412/TCP | https://pt.wikipedia.org/w/index.php?title=Direct_Connect_network&action=edit&redlink=1 Client-To-Client port | Não-oficial |
| 427/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=Service_Location_Protocol&action=edit&redlink=1 (Service Location Protocol) (Protocolo de serviço de localização) | Não-oficial |
| 443/TCP | https://pt.wikipedia.org/wiki/HTTPS - https://pt.wikipedia.org/wiki/HTTP Protocol over TLS/https://pt.wikipedia.org/wiki/Transport_Layer_Security (transmissão segura)(Camada de transporte seguro) | Oficial |
| 444/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=Simple_Network_Paging_Protocol&action=edit&redlink=1, Simple Network Paging Protocol (Protocolo simples de paging de rede) |  |
| 445/TCP | Microsoft-DS (https://pt.wikipedia.org/wiki/Active_Directory, Windows shares, https://pt.wikipedia.org/wiki/Sasser (vírus), Agobot, Zobotworm | Oficial |
| 445/UDP | Microsoft-DS https://pt.wikipedia.org/wiki/Server_Message_Block (Bloco de mensagem de servidor) file sharing | Oficial |
| 464/TCP,UDP | Kerberos Change/Set password | Oficial |
| 465/TCP | https://pt.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol over https://pt.wikipedia.org/wiki/Transport_Layer_Security - Conflito registrado com protocolo Cisco | Conflito |
| 500/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=ISAKMP&action=edit&redlink=1, IKE-Internet Key Exchange | Oficial |
| 502/TCP,UDP | https://pt.wikipedia.org/wiki/Modbus, Protocol |  |
| 512/TCP | exec, Remote Process Execution (Processo de execução remota) |  |
| 512/UDP | comsat, together with biff: notifica usuários acerca de novos e-mail's não lidos |  |
| 513/TCP | Login |  |
| 513/UDP | Who |  |
| 514/TCP | https://pt.wikipedia.org/w/index.php?title=Rsh&action=edit&redlink=1 protocol(protocolo de shell remoto) - usado para executar linha de comando não interativa em sistema remoto e visualizar a tela de retorno |  |
| 514/UDP | https://pt.wikipedia.org/wiki/Syslog protocol - usado para log do sistema | Oficial |
| 515/TCP | https://pt.wikipedia.org/wiki/Line_Printer_Daemon_protocol - usada em servidores de impressão LPD |  |
| 517/UDP | Talk |  |
| 518/UDP | NTalk |  |
| 520/TCP | efs |  |
| 520/UDP | Routing - https://pt.wikipedia.org/wiki/Routing_Information_Protocol (Protocolo de informação do roteador) | Oficial |
| 513/UDP | Router |  |
| 524/TCP,UDP | NetWare Core Protocol (NCP) (Protocolo de core do NetWare) | Oficial |
| 525/UDP | Timed, Timeserver |  |
| 530/TCP,UDP | https://pt.wikipedia.org/wiki/Remote_procedure_call (Procedimento de chamada remota) | Oficial |
| 531/TCP,UDP | AOL Instant Messenger, IRC Mensageiro instantâneo AOL | Não-oficial |
| 532/TCP | netnews |  |
| 533/UDP | netwall, For Emergency Broadcasts |  |
| 540/TCP | https://pt.wikipedia.org/wiki/UUCP (Unix-to-Unix Copy Protocol) | Oficial |
| 542/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=Commerce&action=edit&redlink=1 (Commerce Applications) | Oficial |
| 543/TCP | klogin, Kerberos login |  |
| 544/TCP | kshell, Kerberos Remote shell |  |
| 546/TCP,UDP | DHCPv6 client |  |
| 547/TCP,UDP | DHCPv6 server |  |
| 548/TCP | AFP (https://pt.wikipedia.org/wiki/Apple_Filing_Protocol) (Protocolo de arquivamento da Apple) |  |
| 550/UDP | new-rwho, new-who |  |
| 554/TCP,UDP | https://pt.wikipedia.org/wiki/RTSP (Real Time Streaming Protocol) (Protocolo de streaming em tempo real) | Oficial |
| 556/TCP | Remotefs, rfs, rfs_server |  |
| 560/UDP | rmonitor, Remote Monitor (Monitor remoto) |  |
| 561/UDP | monitor |  |
| 563/TCP,UDP | https://pt.wikipedia.org/wiki/NNTP protocol over TLS/SSL (NNTPS) | Oficial |
| 587/TCP | email message submission (https://pt.wikipedia.org/wiki/SMTP) (https://tools.ietf.org/html/rfc2476) | Oficial |
| 591/TCP | https://pt.wikipedia.org/wiki/FileMaker 6.0 Web Sharing (alternativa ao HTTP) | Oficial |
| 593/TCP,UDP | HTTP RPC Ep Map | Oficial |
| 604/TCP | TUNNEL |  |
| 631/TCP,UDP | https://pt.wikipedia.org/w/index.php?title=Internet_Printing_Protocol&action=edit&redlink=1, (Internet Printing Protocol) (Protocolo de impressão na internet) |  |
| 636/TCP,UDP | https://pt.wikipedia.org/wiki/LDAP sobre https://pt.wikipedia.org/wiki/SSL | Oficial |
| 639/TCP,UDP | MSDP, Multicast Source Discovery Protocol (Protocolo de descoberta de fonte multicast) |  |
| 646/TCP | LDP, Label Distribution Protocol (Protocolo de distribuição de rótulo) |  |
| 647/TCP | DHCP Failover Protocol |  |
| 648/TCP | RRP, Registry Registrar Protocol (Protocolo de registro) |  |
| 652/TCP | DTCP, Dynamic Tunnel Configuration Protocol (Protocolo de configuração dinâmica de túnel) |  |
| 654/TCP | AODV, Ad hoc On-Demand Distance Vector |  |
| 665/TCP | sun-dr, Remote Dynamic Reconfiguration (Reconfiguração remota dinâmica) | Não-oficial |
| 666/UDP | https://pt.wikipedia.org/wiki/Doom_(jogo_eletr%C3%B4nico_de_1993), First online https://pt.wikipedia.org/wiki/First-person_shooter |  |
| 674/TCP | ACAP, Application Configuration Access Protocol (Protocolo de acesso a configuração da aplicação) |  |
| 691/TCP | MS Exchange Routing | Oficial |
| 692/TCP | Hyperwave-ISP |  |
| 694/UDP | Linux-HA High availability Heartbeat port | Não-oficial |
| 695/TCP | IEEE-MMS-SSL |  |
| 698/TCP | OLSR, Optimized Link State Routing |  |
| 699/TCP | Access Network |  |
| 700/TCP | EPP, Extensible Provisioning Protocol (Protocolo de provisionamento extensível) |  |
| 701/TCP | LMP, Link Management Protocol (Protoloco de gerenciamento de link) |  |
| 702/TCP | IRIS over BEEP |  |
| 706/TCP | SILC, Secure Internet Live Conferencing (Conferência ao vivo da seguraça da internet) |  |
| 711/TCP | TDP, Tag Distribution Protocol (Protocolo de distribuição de marcadores) |  |
| 712/TCP | TBRPF, Topology Broadcast based on Reverse-Path Forwarding |  |
| 720/TCP | SMQP, Simple Message Queue Protocol (Protocolo de simples mensagem em fila) |  |
| 749/TCP, UDP | kerberos-adm, Kerberos administration |  |
| 750/UDP | Kerberos version IV |  |
| 782/TCP | https://pt.wikipedia.org/w/index.php?title=Conserver&action=edit&redlink=1 serial-console management server |  |
| 829/TCP | CMP (Certificate Management Protocol) |  |
| 860/TCP | https://pt.wikipedia.org/wiki/ISCSI |  |
| 873/TCP | https://pt.wikipedia.org/wiki/Rsync File synchronisation protocol | Oficial |
| 901/TCP | https://pt.wikipedia.org/w/index.php?title=Samba_software&action=edit&redlink=1 Web Administration Tool (SWAT) | Não-oficial |
| 902 | https://pt.wikipedia.org/wiki/VMware Server Consolehttps://pt.wikipedia.org/wiki/Lista_de_portas_dos_protocolos_TCP_e_UDP#cite_note-1 | Não-oficial |
| 904 | https://pt.wikipedia.org/wiki/VMware Server Alternate (se a porta 902 estiver em uso - ex: SUSE linux) | Não-oficial |
| 911/TCP | https://pt.wikipedia.org/w/index.php?title=Network_Console_on_Acid&action=edit&redlink=1 (NCA) - local https://pt.wikipedia.org/wiki/Tty redirection over https://pt.wikipedia.org/wiki/OpenSSH |  |
| 981/TCP | https://pt.wikipedia.org/w/index.php?title=SofaWare_Technologies&action=edit&redlink=1 Remote HTTPS management for firewall devices running embedded https://pt.wikipedia.org/w/index.php?title=Checkpoint_Firewall-1&action=edit&redlink=1 software | Não-oficial |
| 989/TCP,UDP | https://pt.wikipedia.org/wiki/FTP Protocol (data) over TLS/SSL | Oficial |
| 990/TCP,UDP | FTP Protocol (control) over TLS/SSL | Oficial |
| 991/TCP,UDP | NAS (Netnews Admin System) |  |
| 992/TCP,UDP | Telnet protocol over TLS/SSL | Oficial |
| 993/TCP | https://pt.wikipedia.org/wiki/Internet_Message_Access_Protocol sobre https://pt.wikipedia.org/wiki/SSL (transmissão segura) | Oficial |
| 995/TCP | https://pt.wikipedia.org/wiki/Post_Office_Protocol sobre https://pt.wikipedia.org/wiki/SSL (transmissão segura) | Oficial |