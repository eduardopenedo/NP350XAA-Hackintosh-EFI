# NP350XAA-Hackintosh-EFI

Requisitos
1. Imagem Vanilla do macOS - [Download](https://www.olarila.com/topic/6278-olarila-vanilla-images-macos-installer/)
2. Balena Etcher - [Download](https://etcher.balena.io/)
3. MiniTool Partition Wizard - [Download](https://www.partitionwizard.com/)
4. Explorer++ - [Download](https://explorerplusplus.com/download)
5. Python

Instalação
1. Fazer Pen-drive bootável com Balena Etcher
2. Gerar SMBIOS
   2.1 Ir na pasta Utils\GenSMBIOS e executar "GenSMBIOS.bat"
   2.2 Selecionar opção "2. Select config.plist" e arrastar EFI/OC/config.plist ao terminal
   2.3 Selecionar opção "3. Generate SMBIOS"
   2.4 Preencher ProductName que consta em config.plist ("MacBookPro14,1")
   2.5 Selecionar opção "Q. Quit"
3. Atribuir letra à partição EFI do PenDrive
4. Copiar EFI pronta para partição montada pelo Explorer++ (Executando como Administrador)
5. Desatribuir letra à partição EFI do PenDrive
