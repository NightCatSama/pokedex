# pokedex
宝可梦中文数据，包含各种类型图片

## pokemon.json 说明

| 字段 | 类型 | 说明 | 示例 |
| - | :-: | - | - |
| id | int | 全国图鉴序号 | 1 |
| id_str | string | 全国图鉴 | 001 |
| name | string | 中文名称 | 妙蛙种子 |
| name_en | string | 英文名称 | Bulbasaur |
| name_jp | string | 日文名称 | フシギダネ |
| height | int | 身高 | 0.7 |
| weight | int | 体重 | 6.9 |
| type1 | string | 第一属性 | 草 |
| type2 | string | 第二属性 | 毒 |
| ability1 | string | 特性一 | 茂盛 |
| ability2 | string | 特性二 | - |
| abilityHide | string | 隐藏特性 | 叶绿素 |
| ability1_desc | string | 特性一描述 | ＨＰ减少的时候，草属性的招式威力会提高。 |
| ability2_desc | string | 特性二描述 | - |
| abilityHide_desc | string | 隐藏特性描述 | 晴朗天气时，速度会提高。 |
| generation | int | 时代 | 1 |
| catchRate | string | 捕捉概率（满HP情况下使用普通球） | 5.9% |
| desc | string | 宝可梦描述 | 会看到它在太阳底下睡午觉的样子。在沐浴了充足的阳光后，它背上的种子就会茁壮成长。 |
| chain | string | 进化链 | 1,2,3 |
| stat | string | 种族值，分别为 HP,攻击,防御,特攻,特防,速度 | 45,49,49,65,65,45 |

## images 说明

| 文件夹 | 说明 | 示例 |
| - | - | - |
| gif | 宝可梦动图 | ![img](https://raw.githubusercontent.com/NightCatSama/pokedex/main/images/gif/1.gif) |
| normal | 宝可梦正常图片 | ![img](https://raw.githubusercontent.com/NightCatSama/pokedex/main/images/normal/1.png) |
| pixel | 宝可梦像素图 | ![img](https://raw.githubusercontent.com/NightCatSama/pokedex/main/images/pixel/1.png) |
| sprite/forward | 宝可梦精灵图 - 正面 | ![img](https://raw.githubusercontent.com/NightCatSama/pokedex/main/images/sprite/forward/1.png) |
| sprite/back | 宝可梦精灵图 - 背面 | ![img](https://raw.githubusercontent.com/NightCatSama/pokedex/main/images/sprite/back/1.png) |
| sprite/shiny-forward | 宝可梦精灵图 - 正面（闪光） | ![img](https://raw.githubusercontent.com/NightCatSama/pokedex/main/images/sprite/shiny-forward/1.png) |
| sprite/shiny-back | 宝可梦精灵图 - 背面（闪光） | ![img](https://raw.githubusercontent.com/NightCatSama/pokedex/main/images/sprite/shiny-back/1.png) |

