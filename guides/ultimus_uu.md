# Ultimus Ultimate Umbra Guide
*a.k.a. Prestige Push using Ultimate Charm*

*This is an advance guide for Valour Rift area. For the general guide of this area, refer to [Valour Rift Guide](valour_rift.md)*

**Table of Contents**
- [Ultimus Ultimate Umbra Guide](#ultimus-ultimate-umbra-guide)
  - [0. What is this all about again?](#0-what-is-this-all-about-again)
  - [1. Know what to expect](#1-know-what-to-expect)
  - [2. Requirements](#2-requirements)
  - [3. Popular plan](#3-popular-plan)
  - [4. Using the simulators](#4-using-the-simulators)
    - [4.1. Simulators](#41-simulators)
    - [4.2. Comparing run performance](#42-comparing-run-performance)
  - [5. Considerations](#5-considerations)
  - [6. References](#6-references)
  - [Extension: Retreat strategy](#extension-retreat-strategy)

[Extension: Retreat strategy](#extension-retreat-strategy)

## 0. What is this all about again?
Valour Rift is the place where you can earn the greatest piece of equipment in the game: [Prestige Base](https://www.mousehuntgame.com/item.php?item_type=valour_rift_prestige_base). It is the [Base](https://www.mousehuntgame.com/inventory.php?tab=traps&sub_tab=base) with upgradable stats. By the time this guide is written, the most successful hunter has boosted his Prestige Base to 3,450 power and 41 luck. Additionally, because it is a Rift-type Base, your setup can enjoy up to 40% power bonus and 10 luck on top of whatever stats you have. Awesome, isn't it?

To boost the stats of this Base, you need to climb the tower in hard mode, which is called **Ultimate Umbra** in the game. Catches let you advance, while misses push you back. So, to climb as high as you can, you want your catch rate to be as high as possible. To the crazy hunters out there, the catch rate of 100% is what they seek, and certainly [Ultimate Charm](https://www.mousehuntgame.com/item.php?item_type=ultimate_trinket) is needed to achieve that.

For that very reason, this is an ***"Everything you need to know about doing Prestige Push with Ultimate Charm"*** guidebook for this quest. Believe me, this guide will provide you the absolute knowledge, just like your catch rate ;)

Now, let's not delay any further. Here I present to you: The **Ultimus Ultimate Umbra Guide**:

## 1. Know what to expect
- How high can I climb with all UC?
- How good the result is compared to other options?
- How much time and resources do I need to pour in to make it happen?
- Do I really want to do this?

These are the frequently asked questions when one starts thinking about an UUU run. You need to think through before committing your time and resources to do this kind of stretch goal, right?

The first two questions can be answered by using the chart below, while you can refer to UC Farming Guide in [References](#6-references) section for the third question. The last question can only be answered by yourself.

![Prestige push expectation](https://cdn.discordapp.com/attachments/869153158335713300/1032513218159067216/MH_VRift_Push_viz_final.png)

## 2. Requirements
- Before the run:
    - 1000 [Tower Sigils](https://www.mousehuntgame.com/item.php?item_type=rift_gaunt_upgrade_a_stat_item)
    - 75 [Fragments of the Eclipse](https://www.mousehuntgame.com/item.php?item_type=shade_eclipse_resource_stat_item)
    - 1500 [Tower Secrets](https://www.mousehuntgame.com/item.php?item_type=rift_gaunt_upgrade_b_stat_item)
- During the run:
    - 1000 [Gauntlet String Cheese](https://www.mousehuntgame.com/item.php?item_type=gauntlet_string_cheese)
    - 500 [Ultimate Charm](https://www.mousehuntgame.com/item.php?item_type=ultimate_trinket)
    - 1000 [Champion's Fire](https://www.mousehuntgame.com/item.php?item_type=rift_gauntlet_fuel_stat_item) (the run itself will refund 500+ CF from poking [Unstable Rift Cores](https://www.mousehuntgame.com/item.php?item_type=unstable_core_convertible), so only 500 CF spent)

Average UC needed: **475** [Ultimate Charm](https://www.mousehuntgame.com/item.php?item_type=ultimate_trinket)

## 3. Popular plan
- Step 1: Utilize Halloween event:
  - Farm [Ultimate Potion](https://www.mousehuntgame.com/item.php?item_type=ultimate_potion)
  - Spam Spooky Shuffle (Upgraded Baron-Duke boards) for [Plumepearl Herbs] and [Lunaria Petal]
- Step 2: Be a golem master during Great Winter Hunt:
  - Send Scarved Golem to Zokor for direct UC
  - Send Scarved Golem to Lost City for [Plumepearl Herbs](https://www.mousehuntgame.com/item.php?item_type=plumepearl_herbs_crafting_item)
  - Send Scarved Golem to Sand Dunes for [Lunaria Petal](https://www.mousehuntgame.com/item.php?item_type=lunaria_petal_crafting_item)
- Step 3: Farm [Twisted Carmine](https://www.mousehuntgame.com/adversaries.php?mouse=twisted_carmine) for essence to brew Ultimate Potion after Great Winter Hunt (can farm during Lunar New Year as well, not recommended though)
- Step 4: Push with [Ultimate Charm](https://www.mousehuntgame.com/item.php?item_type=ultimate_trinket)

*(check [6. References](#6-references) for UC farming guide with details on Step 1, 2, and 3)*

## 4. Using the simulators
### 4.1. Simulators
- [Aaron's sim](https://tinyurl.com/VRift): for checing the median run
- [Re's sim (modified)](https://bit.ly/MH_Re_Vrift_sim_mod): for checking probability to reach a certain TE
### 4.2. Comparing run performance
(in other words, *how am I doing?*)
- Change that question to: ***What is the probability to reach <that_position> (floor/step) with <that_number_of_hunts> or less?***
- Tool: [Re's sim (modified)](https://bit.ly/MH_Re_Vrift_sim_mod)
- Checking current progress at a certain TE:
    - On `Sim` sheet, input `Step` = 0, `Sync` = <number_of_hunts_done>, `Siphon` = 0 *(for example, I reached TE2 in 20 hunts so I put 0/20/0 there)*
    - Check `At least` column of that TE *(9.9% for me here)*
- Checking current progress at the start of a customed floor:
    - Same as above, except that you should check `At least` column of that particular floor
- Usage: planning retreat (or making the break point of *I will retreat if I can't reach TEx by y hunts*)
    - On `Sim` sheet, input `Step` = 0 and `Siphon` = 0
    - Track the change of `At least` value at your make-it-or-break-it TEx (x can be any number between 2 and 6)
    - Decide the threshold you're comfortable with *(mine is 10%)* and check the target hunt count *(mine is 20 hunts to TE2 (9.9%) or 38 hunts to TE3 (8.6%))*
    - Stick to the plan

## 5. Considerations
- You can do your climb in parts, since no aura/event boost needed for the actual climb. Even without having enough UC, starting to get your PB stats higher helps speeding up the UC farming process (i.e. minluck Twisted Carmine with lesser charm and fewer auras)
- 300-400 UC is a good point to start. It takes about 600 hunts to reach TE14 and about 850 hunts to reach TE17, and those 2 are the checkpoints that helps minlucking TC easier. You can always farm more UC later.
- [Retreat strategy](#extension-retreat-strategy) is something you can consider doing at the beginning of your push.
- Saving CF without costing more hunts\
![Saving CF](https://cdn.discordapp.com/attachments/930851824234274816/1035864389665968168/unknown.png)

## 6. References
- [UC Farming Guide](uc_farming.md)

## Extension: Retreat strategy

While the climb can be simple as "arm your best setup, turn CF on, and widget hunt for 10 days straight", some of us want to have the best start (when TA AR is still as high as 18.3%) instead of relying on that 8% AR on final laps. That is why this strategy exists.
This can be done with either UC or your best non-UC setup. The choice of this will affect other parts of the decision making process a lot.

Before starting, check the tables to get yourself familiar with the expectations of cost of time and resources of doing retreat.\
![Retreat threshold](https://cdn.discordapp.com/attachments/869153158335713300/1037538395133575188/unknown.png)

Then you can do the steps below.

***Step 1:*** Based on the charts, ***choose a certain aim*** you're comfortable with the expected resource burned.
- Note the expected usage of charm, CF, Fragments, and Secrets. You should be well aware of the amount of time and resource pouring to doing this strategy and thus see the big picture before making the decision.\
*(If you're still not aware yet, then I'll tell you again: Retreat strategy is the next-level whaling, like 1.5x UC push, and it may not even work for you. Think carefully before you start. But if you do decide to do it, I'm here cheering and praying for you.)*

***Step 2: Farm Fragments and Secrets***
- For retreating with UC, you can farm enough Fragments and Secrets for **1** climb then start testing the water.
- For retreating with non-UC setups, it's recommended to farm enough Fragments and Secrets for multiple climbs and fit those climbs to a certain aura span. Common span is 7 days (1 Cursed Skull worth of Spooky Aura), which can hold as many as 20 climbs depending on your chosen aim. Also consider the expected number of retreat for this step. For example, if you expect to do 20 climbs and are willing use use 4 Cursed Skull then it's fine to farm Fragments and Secrets for 5-7 climbs then start climbing.

***Step 3: Climb!***
- Start the climb with **Super Siphon** + **Ultimate Umbra** + **String Stepping** augmentations. All other augmentations are optional, except for **Elixir Rain** which should not be activate, to save Secrets.
- Retreat if the chance of reaching the ***aim*** drops to ***0%***.
- In case you have more than 1 checkpoints *(like me, I believe in second chances)*, retreat if the chance of all the aims drop to 0%.
- If you achieve the ***aim***, turn off your brain and commit to the run. 😉