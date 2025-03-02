unction fly(player)
    player:SetGravity(0) -- Define a gravidade para 0 para permitir o voo
    player:BindKey("W", function()
        player:MoveForward(1) -- Move o jogador para frente
    end)
    player:BindKey("S", function()
        player:MoveBackward(1) -- Move o jogador para trás
    end)
end

-- Função para ficar invisível
function becomeInvisible(player)
    player:SetVisible(false) -- Torna o jogador invisível
end

-- Função para gerar objetos
function spawnObject(player, objectName, position)
    local newObject = CreateObject(objectName) -- Cria um novo objeto
    newObject:SetPosition(position) -- Define a posição do novo objeto
end

-- Exemplo de uso:
local player = GetPlayer() -- Obtém o jogador atual
fly(player) -- Permite que o jogador voe
becomeInvisible(player) -- Torna o jogador invisível
spawnObject(player, "ExemploObjeto", {x = 0, y = 0, z = 0}) -- Gera um objeto na posição (0, 0, 0)
