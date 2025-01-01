local RDHub = {}
function RDHub.EquiparArma(arma)
    print("Equipando a arma: " .. arma)
end

function RDHub.AtivarHabilidade(habilidade)

    print("Ativando habilidade: " .. habilidade)
end
function RDHub.PegarItem(nomeItem)
    print("Pegando item: " .. nomeItem)
function RDHub.ClicarEmBotao(botao)
    print("Clicando no botão: " .. botao)
end
function RDHub.IniciarHub()
    print("RD Hub iniciado!")    RDHub.EquiparArma("Espada Lendária")
    RDHub.AtivarHabilidade("Raio")
    RDHub.PegarItem("Fruta Mágica")
end

RDHub.IniciarHub()

return RDHub
