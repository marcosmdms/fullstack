# CLI E ANBIENTE DE DESENVOLVIMENTO - (CLI - COMMAND LINE INTERFACE)

* INTERFACE GRAFICA VS AMBIENTE DE LINHA DE COMENDO

* terminal e shell (definição)
* tipos de shell
 - powershell
 - bash
 - zsh

 * Prompts
 - comando (o que eu quero executar)
 - argumentos (contra quem eu quero executar)
 - opção (como eu quero executar)

* lista de comandos 
ls      → Get-ChildItem - lista
dir     → Get-ChildItem - 
--------------------------------------------------------------
cd pasta     → entra na pasta
cd ..        → volta 1 nível
cd ../..     → volta 2 níveis
cd \         → vai para a raiz do drive atual
cd ~         → vai para a pasta do usuário
cd -         → volta para a localização anterior
cd C:\       → vai para C:\ 
D:           → muda para o drive D:
cd D:\       → vai para a raiz do drive D:
--------------------------------------------------------------
mkdir pasta       → cria uma pasta
mkdir pasta1,pasta2 → cria várias
mkdir pasta1\pasta2 → cria pasta e subpasta
mkdir "Meu Projeto" → cria pasta com espaços
------------------------------------------------------------
pwd     → Get-Location - localização atual
cls     → Clear-Host - limpar (clear)
cat     → Get-Content - 
cp      → Copy-Item - 
mv      → Move-Item - 
rm      → Remove-Item - 
--------------------------------

rmdir → Remove-Item
ren   → renomeia arquivo
ni    → Cria arquivo
mkdir → criar diretório
ren   → renomear arquivo/diretório
mv    → mover arquivo/diretório
cp    → copiar
rm    → remover