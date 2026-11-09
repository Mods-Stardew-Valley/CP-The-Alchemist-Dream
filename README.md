# The Alchemist's Dream - Equivalent Exchange

# Descrição

The dream of everyone who dabbles in alchemy: equivalent exchange.
Modify the properties of elements without any loss.
Freely transform one material into another.
Create matter from dust.

With the alchemist's grimoire and its secrets, you can manipulate everything to your will!

The alchemist's dream is now in your hands!

A collection of recipes ranging from converting stones into coal to creating diamonds.
Convert, multiply, and transform!
Powers never seen before, now in your hands!

Simply find the pages of the alchemist's lost grimoire and master the secrets of alchemy.
There are 20 lost pages, help the wizard of the valley complete his alchemy research.



With the complete grimoire, you will master copper, iron, gold, iridium, and radioactive material.
And perhaps, the Wizard gives you a gift on par with the Philosopher's Stone.


# Recipes 23 in Total (So far, for now)

[spoiler]
- Stone to Coal - Reward for finding the first page
- Break Copper - Rewards fot the second page
- DesTransmute Iron - The third page
- Forge Copper - Fourth page
- Transmute Iron - Fifth
- Break Iron 
- DesTransmute Gold
- Forge Iron
- Transmute Gold
- Break Ouro
- DesTransmute Iridium
- Forge Ouro
- Transmute Iridium
- Break Iridium
- DesTransmute Radioactive
- Forge Iridium
- Transmute Radioactive
- Break Radioactive
- Forge Radioactive
- Coal to Diamond
- Pearl
- Prismatic Shard
- Galaxy Soul - Especial rewards for completing the Grimoire
[/spoiler]

See the images for more details.

# This is an ongoing project, and its development will proceed according to the plan below:

   # Released

      v0.1.0 [CHEATING EDITION]
         *All recipes available without restriction, for testing purposes only.

      v0.1.1 [CHEATING EDITION]
         *Added two new recipes for Pearl and Galaxy Soul.
         *Added a new ingredient to Prismatic Shard.
         *Changed the order of the last few recipes to accommodate the new ones.
         *Added Nexus update key. 


   # Unreleased

      v0.2.0
         *Added GitHub update key. 
         *Modified all the recipes with new learning mode. [Buying at the Adventurers' Guild]
   
      * Test recipe learning using the Content Patcher mail system.
      * Create the "Lost Page" item so it can be found
      * Add it to the game using Content Patcher
      * Give artifact spots a chance to drop the Lost Page
      * Set up a trigger for when the lost page is found to create a flag that sends the letter by mail.
      * Create an in-game quest assigned by the wizard to find the lost pages.
      * Create the entire proposed storyline and combine all the ideas into a single mod.

Many other steps could be part of the process, but that’s the main idea!
Check the project's progress in the changelog session.

[line]

Any suggestions or help with this project are welcome!
I’m always keeping an eye on the comments.

All stable test versions will be available for download.

Download at your own risk, most of them will be CHEATING!

[line]

💬 Feel free to leave comments, suggestions, or emotional support.
Don't forget to ⭐ Endorse ⭐ the mods you like! It costs nothing, takes two seconds, but it significantly boosts visibility. And it makes a modder very happy.
Plus, it motivates me to keep updating and creating more content. 👍🏼
Seriously. Do it. 😄

💖 Want to do more?
Consider buying me a [b][url=https://ko-fi.com/logandoidao][size=4]Ko-Fi[/size][/url][/b] ☕

📦 For more of my mods:
[url=https://www.nexusmods.com/profile/LoganDoidao989][b][size=4]Click Here![/size][/b][/url]

[line]



# Receipes Code 

//trocar default para null assim as receitas vao precisar ser aprendidas por meio das suas receitas proprias 
   {
   "Stone to Coal": "390 9/Field/382/false/null/",
   "Break Copper": "334 1/Field/378 6/false/null/",
   "DesTrans (Fe)": "335 1/Field/334/false/default/",
   "Forge Copper": "378 10/Field/334/false/default/",
   "Trans (Fe)": "334 2/Field/335/false/default/",
   "Break Iron": "335 1/Field/380 6/false/default/",
   "DesTrans (Au)": "336 1/Field/335/false/default/",
   "Forge Iron": "380 10/Field/335/false/default/",
   "Trans (Au)": "335 2/Field/336/false/default/",
   "Break Gold": "336 1/Field/384 6/false/default/",
   "DesTrans (Ir)": "337 1/Field/336/false/default/",
   "Forge Gold": "384 10/Field/336/false/default/",
   "Trans (Ir)": "336 2/Field/337/false/default/",
   "Break Iridium": "337 1/Field/386 6/false/default/",
   "DesTrans (Rad)": "910 1/Field/337/false/default/",
   "Forge Iridium": "386 10/Field/337/false/default/",
   "Trans (Rad)": "337 2/Field/910/false/default/",
   "Break Radioactive": "910 1/Field/909 6/false/default/",
   "Forge Radioactive": "909 10/Field/910/false/default/",
   "Coal to Diamond": "382 99/Field/72/false/default/",
   "Pearl": "372 20 393 10 80 5 382 3/Field/797/false/default/",   
   "Prismatic": "394 1 60 1 62 1 64 1 66 1 68 1 70 1 72 1/Field/74/false/default/",
   "Galaxy Soul": "74 1 910 5 72 5/Field/896/false/default/"
   }

# Changelog

- v0.1.0
    feat: todas as receitas abertas para teste

- v0.1.1
    fix: modificadas as receitas anteriores para exigir outro meio de aprendizado
    feat: adicionados receitas para Pearl e Galaxy Soul por padrão para teste
    fix: modificada receita do fragmento prismatico
    feat: Added Updatekey

# Roadmap

-V0.1.1

*Correções.
*Balanceamento.
*Traduções.

-V0.2.0 — Mail com Content Patcher

*Alterar todas as receitas para aprendidas por carta.
*Fazer cartas de teste.
*Aprender a usar todas as condições de envio do Content Patcher. O modelo suporta diversos gatilhos, como datas, eventos, cartas recebidas, receitas conhecidas e condições do Expanded Preconditions.
*Validar que o aprendizado das receitas funciona corretamente.

-V0.2.1

*Testar receitas compraveis na loja da guilda com Content Patcher
*Compra em cadeia onde a proxima so libera quando tiver a anterior

-V0.3.0 — Páginas Perdidas

*Fazer os objetos das páginas.
*Adicionar aos pontos de artefato.
*Criar as flags de descoberta.
*Fazer cada página disparar sua respectiva carta.

-V0.4.0 — A Quest

*Criar a missão do Mago.
*Fazer as páginas aparecerem apenas após a missão ser iniciada.
*Validar todo o fluxo:
*Receber a missão.
*Encontrar uma página.
*Criar a flag.
*Receber a carta.
*Aprender a receita.
*Repetir até completar o grimório.
*Adicionar receita do fragmento prismatico apenas ao completar a missao das 20 carts perdidas com uma carta do mago agradecendo pela ajuda e mandando a receita da Stone filosofal como uma piada para a receita real do fragmento prismatico que é o que mais se aproxima disso no jogo

-V1.0.0

*Expandir para todas as páginas.
*Adicionar todas as receitas.
*Completar a história.
*Balanceamento final.