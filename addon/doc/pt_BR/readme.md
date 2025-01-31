# Sound Splitter #

* Autores: Joseph Lee, Luke Davis e colaboradores
* Download [versão estável][1]
* Compatibilidade com NVDA: 2022.4 e posterior

Esse complemento, parcialmente baseado no Tony's Enhancements de Tony
Malykh, adiciona a capacidade de dividir o áudio do NVDA e outros sons em
canais de áudio separados.

Nota: este complemento não se destina a ser usado em telas seguras.

## Comandos:

* Alt+NVDA+S: alterna o divisor de som entre ativado com NVDA no canal
  direito, NVDA no canal esquerdo ou desativado.

## Configurações do divisor de som

Você pode definir as configurações do complemento no menu
NVDA/Preferências/Configurações/Categoria Sound Splitter.

* Dividir o som do NVDA e os sons dos aplicativos em canais esquerdo e
  direito: marque essa caixa de seleção para ativar o recurso de divisão de
  som.
* Alternar esquerda e direita durante a divisão de som: por padrão, o NVDA
  será ouvido pelo canal direito se a divisão de som estiver ativada. Em vez
  disso, você pode ouvir o NVDA pelo canal esquerdo marcando essa caixa de
  seleção.

## Versão 23.02

* É necessário o NVDA 2022.4 ou posterior.
* É necessário o Windows 10 21H2 (atualização/compilação 19044 de novembro
  de 2021) ou posterior.

## Versão 23.01

* É necessário o NVDA 2022.3 ou posterior.
* É necessário ter o Windows 10 ou posterior, pois o Windows 7, 8 e 8.1 não
  serão mais suportados pela Microsoft a partir de janeiro de 2023.
* Atualização da dependência do psutil para a versão 5.9.4.

## Versão 22.03

* É necessário o NVDA 2021.3 ou posterior.
* Segurança aprimorada ao não carregar o complemento quando o NVDA estiver
  sendo executado no modo seguro.
* Atualização da dependência do psutil para a versão 5.9.0.
* Alteração do comando de alternância do divisor de som (Alt+NVDA+S) para
  alternar entre NVDA no canal direito, no canal esquerdo ou divisor de som
  desativado.

## Versão 22.02.1

* Corrigido o fato de o NVDA e o áudio do aplicativo não serem restaurados
  para ambos os canais de áudio depois que o complemento é desativado ou
  desinstalado.

## Versão 22.02

* Versão inicial baseada no complemento Tony's Enhancements de Tony Malykh.

[[!tag dev stable]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=soundSplitter
