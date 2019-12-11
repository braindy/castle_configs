# castle_configs


resources_config.json

DefaultResourcesCount – кол-во ресов на старте

MinesAutoProductionDurations – длительность одного цикла выработки

MinesProductionsByLevel – кол-во реса за 1 цикл выработки для каждой шахты

MinesUpgradePrice – цены апгрейдов каждой из шахт

	"currencies": ["coins", "res2"] – ресы, которые нужны для апгрейда
	
	[1000, 1], – кол-во реса номер 1 и реса номер 2 для апгрейда
	
	(если цена из одного ресурса, то можно без квадратных скобок цену указывать)
	
MinesManagerUpgradePrice – цены апгрейдов менеджера для каждой из шахт

MineManagerOfflineReward – сколько ресурса менеджер каждой шахты приносит в оффлайне

<br>

units_config.json

BarrackAutoProductionDurations – длительность одного цикла выработки

BarrackInteractionForce – на сколько сек интерактив ускоряет выработку

BarracksProductionsByLevel – кол-во юнитов за 1 цикл выработки для каждой казармы

BarracksUpgradePrice – цены апгрейдов для каждой из казарм, по аналогии с шахтами

BarracksManagerUpgradePrice – цены апгрейдов менеджера для каждой из казарм

BarrackManagerPowerMult – во сколько раз возрастает мощь юнита (относительно базовой) при апгрейде менеджера казармы
