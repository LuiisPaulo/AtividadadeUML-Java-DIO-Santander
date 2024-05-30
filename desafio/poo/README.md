classDiagram
IPHONE : 
IPHONE 
IPHONE : ReprodutoMusical()
IPHONE : AparelhoTelefonico()
IPHONE : NavegadorInternet()

IPHONE --|> ReprodutoMusical
ReprodutoMusical : + musica String
ReprodutoMusical : + tocar()
ReprodutoMusical : + pausar()
ReprodutoMusical : + selecionarMusica(String musica)

IPHONE --|> AparelhoTelefonico
AparelhoTelefonico : numero String
AparelhoTelefonico : + ligar(String numero)
AparelhoTelefonico : + atender()
AparelhoTelefonico : + iniciarCorreioVoz()

IPHONE --|> NavegadorInternet
NavegadorInternet : Url String
NavegadorInternet : + exibirPagina(String Url)
NavegadorInternet : + adicionarNovaAba()
NavegadorInternet : + atualizarPagina()


