# esx_ambulancejob

## Requisitos

* Modo automático
   - [esx_skin](https://github.com/ESX-Brasil/esx_skin)
   - [esx_vehicleshop](https://github.com/ESX-Brasil/esx_vehicleshop)

* Gerenciamento de jogadores (ações de chefe)
   - [esx_society](https://github.com/ESX-Brasil/esx_society)

## Download e Instalação

### Usando [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx esx-brasil/esx_ambulancejob
```

### Usando Git
```
cd resources
git clone https://github.com/ESX-Brasil/esx_ambulancejob [esx]/esx_ambulancejob
```

### Manualmente
- Download https://github.com/ESX-Brasil/esx_ambulancejob/archive/master.zip
- Coloque no diretório `[esx]`

## Instalação
- Importar `esx_ambulancejob.sql` para seu banco de dados
- Se você quiser um jogador como chefe aqui `Config.EnablePlayerManagement` de `false` para `true` em `config.lua`
- Adicione isto ao seu `server.cfg`:

```
start esx_ambulancejob
```
# Discord

[![Join ESX Brasil](https://discordapp.com/api/guilds/693468263161659402/embed.png?style=banner2)](https://discord.gg/ZGXTsdN)

# Legal
### License
esx_ambulancejob - esx_ambulancejob for ESX

Copyright (C) 2015-2020 ESX-Brasil

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
