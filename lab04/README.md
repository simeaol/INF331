
# **Tarefa 4**

**Serviço 1**
> **Breve descrição**

API de busca de informação de tipo de Pokemon existentes, suas características, habilidades e etc. A busca poderá ser feita usando o nome
alguma caracteristica peculiar como habilidade, index, e diversos filtros que podem ser combinadas para melhorar o resultado da busca.

A consulta realiza neste exemplo foi uma simples consulta pelo pokemon ditto

> **Cabeçalho HTTP da requisição**
```
GET /api/v2/pokemon/ditto HTTP/2
Host: pokeapi.co
user-agent: insomnia/2020.4.0
accept: */*
```

> **Cabeçalho HTTP da resposta**

```
HTTP/2 200 
 date: Sat, 19 Sep 2020 05:58:36 GMT
 content-type: application/json; charset=utf-8
 set-cookie: __cfduid=d18789d0bf3ec56c988bfd55680fe63bf1600495116; expires=Mon, 19-Oct-20 05:58:36 GMT; path=/; domain=.pokeapi.co; HttpOnly; SameSite=Lax; Secure
 access-control-allow-origin: *
 cache-control: public, max-age=86400, s-maxage=86400
 etag: W/"500b-wLWc/rhmpjBa2dDxFxiKmyy0uI4"
 function-execution-id: j2u29djjy3ia
 x-cloud-trace-context: 696dc32bab965dd7092d907d37f55d64;o=1
 x-country-code: US
 x-orig-accept-language: es,es-ES;q=0.9
 x-powered-by: Express
 x-served-by: cache-mia17647-MIA
 x-cache: HIT
 x-cache-hits: 1
 x-timer: S1598332095.275207,VS0,VE1
 vary: Accept-Encoding,cookie,need-authorization, x-fh-requested-host, accept-encoding
 cf-cache-status: HIT
 age: 50852
 cf-request-id: 05468a7a470000ef263d087200000001
 expect-ct: max-age=604800, report-uri="https://report-uri.cloudflare.com/cdn-cgi/beacon/expect-ct"
 server: cloudflare
 cf-ray: 5d5113707f05ef26-MIA
```

> **Conteúdo da resposta**

```
{
  "abilities": [
    {
      "ability": {
        "name": "limber",
        "url": "https://pokeapi.co/api/v2/ability/7/"
      },
      "is_hidden": false,
      "slot": 1
    },
    {
      "ability": {
        "name": "imposter",
        "url": "https://pokeapi.co/api/v2/ability/150/"
      },
      "is_hidden": true,
      "slot": 3
    }
  ],
  "base_experience": 101,
  "forms": [
    {
      "name": "ditto",
      "url": "https://pokeapi.co/api/v2/pokemon-form/132/"
    }
  ],
  "game_indices": [
    {
      "game_index": 76,
      "version": {
        "name": "red",
        "url": "https://pokeapi.co/api/v2/version/1/"
      }
    },
    {
      "game_index": 76,
      "version": {
        "name": "blue",
        "url": "https://pokeapi.co/api/v2/version/2/"
      }
    },
    {
      "game_index": 76,
      "version": {
        "name": "yellow",
        "url": "https://pokeapi.co/api/v2/version/3/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "gold",
        "url": "https://pokeapi.co/api/v2/version/4/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "silver",
        "url": "https://pokeapi.co/api/v2/version/5/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "crystal",
        "url": "https://pokeapi.co/api/v2/version/6/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "ruby",
        "url": "https://pokeapi.co/api/v2/version/7/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "sapphire",
        "url": "https://pokeapi.co/api/v2/version/8/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "emerald",
        "url": "https://pokeapi.co/api/v2/version/9/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "firered",
        "url": "https://pokeapi.co/api/v2/version/10/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "leafgreen",
        "url": "https://pokeapi.co/api/v2/version/11/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "diamond",
        "url": "https://pokeapi.co/api/v2/version/12/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "pearl",
        "url": "https://pokeapi.co/api/v2/version/13/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "platinum",
        "url": "https://pokeapi.co/api/v2/version/14/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "heartgold",
        "url": "https://pokeapi.co/api/v2/version/15/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "soulsilver",
        "url": "https://pokeapi.co/api/v2/version/16/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "black",
        "url": "https://pokeapi.co/api/v2/version/17/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "white",
        "url": "https://pokeapi.co/api/v2/version/18/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "black-2",
        "url": "https://pokeapi.co/api/v2/version/21/"
      }
    },
    {
      "game_index": 132,
      "version": {
        "name": "white-2",
        "url": "https://pokeapi.co/api/v2/version/22/"
      }
    }
  ],
  "height": 3,
  "held_items": [
    {
      "item": {
        "name": "metal-powder",
        "url": "https://pokeapi.co/api/v2/item/234/"
      },
      "version_details": [
        {
          "rarity": 5,
          "version": {
            "name": "ruby",
            "url": "https://pokeapi.co/api/v2/version/7/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "sapphire",
            "url": "https://pokeapi.co/api/v2/version/8/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "emerald",
            "url": "https://pokeapi.co/api/v2/version/9/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "firered",
            "url": "https://pokeapi.co/api/v2/version/10/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "leafgreen",
            "url": "https://pokeapi.co/api/v2/version/11/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "diamond",
            "url": "https://pokeapi.co/api/v2/version/12/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "pearl",
            "url": "https://pokeapi.co/api/v2/version/13/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "platinum",
            "url": "https://pokeapi.co/api/v2/version/14/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "heartgold",
            "url": "https://pokeapi.co/api/v2/version/15/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "soulsilver",
            "url": "https://pokeapi.co/api/v2/version/16/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "black",
            "url": "https://pokeapi.co/api/v2/version/17/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "white",
            "url": "https://pokeapi.co/api/v2/version/18/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "black-2",
            "url": "https://pokeapi.co/api/v2/version/21/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "white-2",
            "url": "https://pokeapi.co/api/v2/version/22/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "x",
            "url": "https://pokeapi.co/api/v2/version/23/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "y",
            "url": "https://pokeapi.co/api/v2/version/24/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "omega-ruby",
            "url": "https://pokeapi.co/api/v2/version/25/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "alpha-sapphire",
            "url": "https://pokeapi.co/api/v2/version/26/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "sun",
            "url": "https://pokeapi.co/api/v2/version/27/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "moon",
            "url": "https://pokeapi.co/api/v2/version/28/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "ultra-sun",
            "url": "https://pokeapi.co/api/v2/version/29/"
          }
        },
        {
          "rarity": 5,
          "version": {
            "name": "ultra-moon",
            "url": "https://pokeapi.co/api/v2/version/30/"
          }
        }
      ]
    },
    {
      "item": {
        "name": "quick-powder",
        "url": "https://pokeapi.co/api/v2/item/251/"
      },
      "version_details": [
        {
          "rarity": 50,
          "version": {
            "name": "diamond",
            "url": "https://pokeapi.co/api/v2/version/12/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "pearl",
            "url": "https://pokeapi.co/api/v2/version/13/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "platinum",
            "url": "https://pokeapi.co/api/v2/version/14/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "heartgold",
            "url": "https://pokeapi.co/api/v2/version/15/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "soulsilver",
            "url": "https://pokeapi.co/api/v2/version/16/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "black",
            "url": "https://pokeapi.co/api/v2/version/17/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "white",
            "url": "https://pokeapi.co/api/v2/version/18/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "black-2",
            "url": "https://pokeapi.co/api/v2/version/21/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "white-2",
            "url": "https://pokeapi.co/api/v2/version/22/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "x",
            "url": "https://pokeapi.co/api/v2/version/23/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "y",
            "url": "https://pokeapi.co/api/v2/version/24/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "omega-ruby",
            "url": "https://pokeapi.co/api/v2/version/25/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "alpha-sapphire",
            "url": "https://pokeapi.co/api/v2/version/26/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "sun",
            "url": "https://pokeapi.co/api/v2/version/27/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "moon",
            "url": "https://pokeapi.co/api/v2/version/28/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "ultra-sun",
            "url": "https://pokeapi.co/api/v2/version/29/"
          }
        },
        {
          "rarity": 50,
          "version": {
            "name": "ultra-moon",
            "url": "https://pokeapi.co/api/v2/version/30/"
          }
        }
      ]
    }
  ],
  "id": 132,
  "is_default": true,
  "location_area_encounters": "https://pokeapi.co/api/v2/pokemon/132/encounters",
  "moves": [
    {
      "move": {
        "name": "transform",
        "url": "https://pokeapi.co/api/v2/move/144/"
      },
      "version_group_details": [
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "red-blue",
            "url": "https://pokeapi.co/api/v2/version-group/1/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "yellow",
            "url": "https://pokeapi.co/api/v2/version-group/2/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "gold-silver",
            "url": "https://pokeapi.co/api/v2/version-group/3/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "crystal",
            "url": "https://pokeapi.co/api/v2/version-group/4/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "ruby-sapphire",
            "url": "https://pokeapi.co/api/v2/version-group/5/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "emerald",
            "url": "https://pokeapi.co/api/v2/version-group/6/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "firered-leafgreen",
            "url": "https://pokeapi.co/api/v2/version-group/7/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "diamond-pearl",
            "url": "https://pokeapi.co/api/v2/version-group/8/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "platinum",
            "url": "https://pokeapi.co/api/v2/version-group/9/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "heartgold-soulsilver",
            "url": "https://pokeapi.co/api/v2/version-group/10/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "black-white",
            "url": "https://pokeapi.co/api/v2/version-group/11/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "colosseum",
            "url": "https://pokeapi.co/api/v2/version-group/12/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "xd",
            "url": "https://pokeapi.co/api/v2/version-group/13/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "black-2-white-2",
            "url": "https://pokeapi.co/api/v2/version-group/14/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "x-y",
            "url": "https://pokeapi.co/api/v2/version-group/15/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "omega-ruby-alpha-sapphire",
            "url": "https://pokeapi.co/api/v2/version-group/16/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "sun-moon",
            "url": "https://pokeapi.co/api/v2/version-group/17/"
          }
        },
        {
          "level_learned_at": 1,
          "move_learn_method": {
            "name": "level-up",
            "url": "https://pokeapi.co/api/v2/move-learn-method/1/"
          },
          "version_group": {
            "name": "ultra-sun-ultra-moon",
            "url": "https://pokeapi.co/api/v2/version-group/18/"
          }
        }
      ]
    }
  ],
  "name": "ditto",
  "order": 203,
  "species": {
    "name": "ditto",
    "url": "https://pokeapi.co/api/v2/pokemon-species/132/"
  },
  "sprites": {
    "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/back/132.png",
    "back_female": null,
    "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/back/shiny/132.png",
    "back_shiny_female": null,
    "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/132.png",
    "front_female": null,
    "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/shiny/132.png",
    "front_shiny_female": null,
    "other": {
      "dream_world": {
        "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/132.svg",
        "front_female": null
      },
      "official-artwork": {
        "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/132.png"
      }
    },
    "versions": {
      "generation-i": {
        "red-blue": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-i/red-blue/back/132.png",
          "back_gray": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-i/red-blue/back/gray/132.png",
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-i/red-blue/132.png",
          "front_gray": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-i/red-blue/gray/132.png"
        },
        "yellow": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-i/yellow/back/132.png",
          "back_gray": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-i/yellow/back/gray/132.png",
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-i/yellow/132.png",
          "front_gray": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-i/yellow/gray/132.png"
        }
      },
      "generation-ii": {
        "crystal": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/crystal/back/132.png",
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/crystal/back/shiny/132.png",
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/crystal/132.png",
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/crystal/shiny/132.png"
        },
        "gold": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/gold/back/132.png",
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/gold/back/shiny/132.png",
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/gold/132.png",
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/gold/shiny/132.png"
        },
        "silver": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/silver/back/132.png",
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/silver/back/shiny/132.png",
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/silver/132.png",
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-ii/silver/shiny/132.png"
        }
      },
      "generation-iii": {
        "emerald": {
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/emerald/132.png",
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/emerald/shiny/132.png"
        },
        "firered-leafgreen": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/firered-leafgreen/back/132.png",
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/firered-leafgreen/back/shiny/132.png",
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/firered-leafgreen/132.png",
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/firered-leafgreen/shiny/132.png"
        },
        "ruby-sapphire": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/ruby-sapphire/back/132.png",
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/ruby-sapphire/back/shiny/132.png",
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/ruby-sapphire/132.png",
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iii/ruby-sapphire/shiny/132.png"
        }
      },
      "generation-iv": {
        "diamond-pearl": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/diamond-pearl/back/132.png",
          "back_female": null,
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/diamond-pearl/back/shiny/132.png",
          "back_shiny_female": null,
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/diamond-pearl/132.png",
          "front_female": null,
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/diamond-pearl/shiny/132.png",
          "front_shiny_female": null
        },
        "heartgold-soulsilver": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/heartgold-soulsilver/back/132.png",
          "back_female": null,
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/heartgold-soulsilver/back/shiny/132.png",
          "back_shiny_female": null,
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/heartgold-soulsilver/132.png",
          "front_female": null,
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/heartgold-soulsilver/shiny/132.png",
          "front_shiny_female": null
        },
        "platinum": {
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/platinum/back/132.png",
          "back_female": null,
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/platinum/back/shiny/132.png",
          "back_shiny_female": null,
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/platinum/132.png",
          "front_female": null,
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-iv/platinum/shiny/132.png",
          "front_shiny_female": null
        }
      },
      "generation-v": {
        "black-white": {
          "animated": {
            "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/back/132.gif",
            "back_female": null,
            "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/back/shiny/132.gif",
            "back_shiny_female": null,
            "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/132.gif",
            "front_female": null,
            "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/shiny/132.gif",
            "front_shiny_female": null
          },
          "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/back/132.png",
          "back_female": null,
          "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/back/shiny/132.png",
          "back_shiny_female": null,
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/132.png",
          "front_female": null,
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/shiny/132.png",
          "front_shiny_female": null
        }
      },
      "generation-vi": {
        "omegaruby-alphasapphire": {
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-vi/omegaruby-alphasapphire/132.png",
          "front_female": null,
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-vi/omegaruby-alphasapphire/shiny/132.png",
          "front_shiny_female": null
        },
        "x-y": {
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-vi/x-y/132.png",
          "front_female": null,
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-vi/x-y/shiny/132.png",
          "front_shiny_female": null
        }
      },
      "generation-vii": {
        "icons": {
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-vii/icons/132.png",
          "front_female": null
        },
        "ultra-sun-ultra-moon": {
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-vii/ultra-sun-ultra-moon/132.png",
          "front_female": null,
          "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-vii/ultra-sun-ultra-moon/shiny/132.png",
          "front_shiny_female": null
        }
      },
      "generation-viii": {
        "icons": {
          "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-viii/icons/132.png",
          "front_female": null
        }
      }
    }
  },
  "stats": [
    {
      "base_stat": 48,
      "effort": 1,
      "stat": {
        "name": "hp",
        "url": "https://pokeapi.co/api/v2/stat/1/"
      }
    },
    {
      "base_stat": 48,
      "effort": 0,
      "stat": {
        "name": "attack",
        "url": "https://pokeapi.co/api/v2/stat/2/"
      }
    },
    {
      "base_stat": 48,
      "effort": 0,
      "stat": {
        "name": "defense",
        "url": "https://pokeapi.co/api/v2/stat/3/"
      }
    },
    {
      "base_stat": 48,
      "effort": 0,
      "stat": {
        "name": "special-attack",
        "url": "https://pokeapi.co/api/v2/stat/4/"
      }
    },
    {
      "base_stat": 48,
      "effort": 0,
      "stat": {
        "name": "special-defense",
        "url": "https://pokeapi.co/api/v2/stat/5/"
      }
    },
    {
      "base_stat": 48,
      "effort": 0,
      "stat": {
        "name": "speed",
        "url": "https://pokeapi.co/api/v2/stat/6/"
      }
    }
  ],
  "types": [
    {
      "slot": 1,
      "type": {
        "name": "normal",
        "url": "https://pokeapi.co/api/v2/type/1/"
      }
    }
  ],
  "weight": 40
}
```




**Serviço 2 - StackOverflow**
> **Breve descrição**

Stackoverflow é o site mais famoso entre os desenlvedores de software no mundo. Através dele é possível consultar, postar ou fornercer respostas as perguntas que estão
disponíveis na plataforma de forma simples e prática. Ele é ecessado milhões de vezes por dia e apenas de ser um sistema monolítico ele consegue aguentar a demanda e além
disso a plataforma faz pesquisas com os desenvolvedores para entender as tendências futuras ou desejadas.

Nesse exemplo, foi feita uma consulta simples no sistema das perguntas que possuem mais votos no site ordenados por ordem decrescente.

> URL: http://api.stackexchange.com/2.2/questions?order=desc&sort=votes&site=pt.stackoverflow

> **Cabeçalho HTTP da requisição**
```
GET /2.2/questions?order=desc&sort=votes&site=pt.stackoverflow HTTP/1.1
Host: api.stackexchange.com
User-Agent: insomnia/2020.4.0
Accept: */*
```

> **Cabeçalho HTTP da resposta**

```
HTTP/1.1 301 Moved Permanently
HTTP/1.1 200 OK
 cache-control: private
 content-length: 4831
 content-type: application/json; charset=utf-8
 content-encoding: gzip
 server: Microsoft-IIS/10.0
 strict-transport-security: max-age=2592000
 x-route-name: Questions/GetAll
 access-control-allow-origin: *
 access-control-allow-methods: GET, POST
 access-control-allow-credentials: false
 x-content-type-options: nosniff
 x-sql-count: 3
 x-sql-duration-ms: 83
 x-redis-count: 70
 x-redis-duration-ms: 5
 x-flags: AA
 x-aspnet-duration-ms: 97
 x-request-guid: 5bef9ff7-8103-43aa-82ed-c0b1248ac8df
 x-is-crawler: 1
 x-providence-cookie: b895a2ff-5e00-4736-b059-2bec286b3e76
 date: Sat, 19 Sep 2020 06:18:13 GMT
```

> **Conteúdo da resposta**

```
{
  "items": [
    {
      "tags": [
        "hash",
        "seguran&#231;a",
        "senhas",
        "criptografia"
      ],
      "owner": {
        "reputation": 414410,
        "user_id": 101,
        "user_type": "moderator",
        "accept_rate": 89,
        "profile_image": "https://i.stack.imgur.com/23y8L.png?s=128&g=1",
        "display_name": "Maniero",
        "link": "https://pt.stackoverflow.com/users/101/maniero"
      },
      "is_answered": true,
      "view_count": 27732,
      "protected_date": 1515955620,
      "accepted_answer_id": 2405,
      "answer_count": 9,
      "score": 379,
      "last_activity_date": 1579561042,
      "creation_date": 1390593128,
      "last_edit_date": 1490626537,
      "question_id": 2402,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/2402/como-fazer-hash-de-senhas-de-forma-segura",
      "title": "Como fazer hash de senhas de forma segura?"
    },
    {
      "tags": [
        "sql",
        "join"
      ],
      "owner": {
        "reputation": 3565,
        "user_id": 5503,
        "user_type": "registered",
        "profile_image": "https://i.stack.imgur.com/c9GtL.jpg?s=128&g=1",
        "display_name": "sigmus",
        "link": "https://pt.stackoverflow.com/users/5503/sigmus"
      },
      "is_answered": true,
      "view_count": 210154,
      "protected_date": 1506683584,
      "accepted_answer_id": 6448,
      "answer_count": 4,
      "score": 313,
      "last_activity_date": 1506683282,
      "creation_date": 1392777130,
      "last_edit_date": 1447262003,
      "question_id": 6441,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/6441/qual-%c3%a9-a-diferen%c3%a7a-entre-inner-join-e-outer-join",
      "title": "Qual &#233; a diferen&#231;a entre INNER JOIN e OUTER JOIN?"
    },
    {
      "tags": [
        "php",
        "mysql"
      ],
      "owner": {
        "reputation": 8365,
        "user_id": 36,
        "user_type": "registered",
        "accept_rate": 50,
        "profile_image": "https://i.stack.imgur.com/dT97L.jpg?s=128&g=1",
        "display_name": "Guerra",
        "link": "https://pt.stackoverflow.com/users/36/guerra"
      },
      "is_answered": true,
      "view_count": 11528,
      "protected_date": 1452600183,
      "accepted_answer_id": 4675,
      "answer_count": 6,
      "score": 242,
      "last_activity_date": 1532456594,
      "creation_date": 1387366072,
      "last_edit_date": 1439499471,
      "question_id": 579,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/579/por-que-n%c3%a3o-devemos-usar-fun%c3%a7%c3%b5es-do-tipo-mysql",
      "title": "Por que n&#227;o devemos usar fun&#231;&#245;es do tipo mysql_*?"
    },
    {
      "tags": [
        "aplica&#231;&#227;o-web",
        "gui",
        "console",
        "ux"
      ],
      "owner": {
        "reputation": 414410,
        "user_id": 101,
        "user_type": "moderator",
        "accept_rate": 89,
        "profile_image": "https://i.stack.imgur.com/23y8L.png?s=128&g=1",
        "display_name": "Maniero",
        "link": "https://pt.stackoverflow.com/users/101/maniero"
      },
      "is_answered": true,
      "view_count": 6107,
      "protected_date": 1521404194,
      "accepted_answer_id": 2709,
      "answer_count": 5,
      "score": 226,
      "last_activity_date": 1480599473,
      "creation_date": 1390952933,
      "last_edit_date": 1480599473,
      "question_id": 2539,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/2539/as-mensagens-de-erro-devem-se-desculpar",
      "title": "As mensagens de erro devem se desculpar?"
    },
    {
      "tags": [
        "api",
        "framework",
        "terminologia",
        "biblioteca"
      ],
      "owner": {
        "reputation": 29493,
        "user_id": 3117,
        "user_type": "moderator",
        "accept_rate": 93,
        "profile_image": "https://i.stack.imgur.com/zxdhf.png?s=128&g=1",
        "display_name": "Math",
        "link": "https://pt.stackoverflow.com/users/3117/math"
      },
      "is_answered": true,
      "view_count": 60784,
      "protected_date": 1523456986,
      "accepted_answer_id": 17552,
      "answer_count": 6,
      "score": 217,
      "last_activity_date": 1599148946,
      "creation_date": 1401363191,
      "last_edit_date": 1417535059,
      "question_id": 17501,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/17501/qual-%c3%a9-a-diferen%c3%a7a-de-api-biblioteca-e-framework",
      "title": "Qual &#233; a diferen&#231;a de API, biblioteca e Framework?"
    },
    {
      "tags": [
        "mem&#243;ria",
        "gerenciamento-de-mem&#243;ria",
        "stack",
        "heap"
      ],
      "owner": {
        "reputation": 414410,
        "user_id": 101,
        "user_type": "moderator",
        "accept_rate": 89,
        "profile_image": "https://i.stack.imgur.com/23y8L.png?s=128&g=1",
        "display_name": "Maniero",
        "link": "https://pt.stackoverflow.com/users/101/maniero"
      },
      "is_answered": true,
      "view_count": 33395,
      "protected_date": 1535999962,
      "accepted_answer_id": 15698,
      "answer_count": 4,
      "score": 207,
      "last_activity_date": 1599060521,
      "creation_date": 1391368778,
      "last_edit_date": 1589825679,
      "question_id": 3797,
      "content_license": "CC BY-SA 4.0",
      "link": "https://pt.stackoverflow.com/questions/3797/o-que-s%c3%a3o-e-onde-est%c3%a3o-a-stack-e-heap",
      "title": "O que s&#227;o e onde est&#227;o a &quot;stack&quot; e &quot;heap&quot;?"
    },
    {
      "tags": [
        "php",
        "mysql",
        "sql",
        "sql-injection"
      ],
      "owner": {
        "reputation": 29493,
        "user_id": 3117,
        "user_type": "moderator",
        "accept_rate": 93,
        "profile_image": "https://i.stack.imgur.com/zxdhf.png?s=128&g=1",
        "display_name": "Math",
        "link": "https://pt.stackoverflow.com/users/3117/math"
      },
      "is_answered": true,
      "view_count": 11554,
      "accepted_answer_id": 3869,
      "answer_count": 9,
      "score": 194,
      "last_activity_date": 1565827597,
      "creation_date": 1391431069,
      "last_edit_date": 1511290894,
      "question_id": 3864,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/3864/como-prevenir-inje%c3%a7%c3%a3o-de-c%c3%b3digo-sql-no-meu-c%c3%b3digo-php",
      "title": "Como prevenir inje&#231;&#227;o de c&#243;digo SQL no meu c&#243;digo PHP?"
    },
    {
      "tags": [
        "api",
        "rest",
        "http",
        "arquitetura-de-software",
        "restful"
      ],
      "owner": {
        "reputation": 6592,
        "user_id": 15336,
        "user_type": "registered",
        "accept_rate": 63,
        "profile_image": "https://i.stack.imgur.com/86Duh.jpg?s=128&g=1",
        "display_name": "ropbla9",
        "link": "https://pt.stackoverflow.com/users/15336/ropbla9"
      },
      "is_answered": true,
      "view_count": 142907,
      "protected_date": 1492785801,
      "accepted_answer_id": 45787,
      "answer_count": 3,
      "score": 190,
      "last_activity_date": 1580420752,
      "creation_date": 1420344086,
      "last_edit_date": 1503659710,
      "question_id": 45783,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/45783/o-que-%c3%a9-rest-e-restful",
      "title": "O que &#233; REST e RESTful?"
    },
    {
      "tags": [
        "javascript",
        "terminologia",
        "callback"
      ],
      "owner": {
        "reputation": 9174,
        "user_id": 5686,
        "user_type": "registered",
        "accept_rate": 72,
        "profile_image": "https://i.stack.imgur.com/5Z3VB.jpg?s=128&g=1",
        "display_name": "Rod",
        "link": "https://pt.stackoverflow.com/users/5686/rod"
      },
      "is_answered": true,
      "view_count": 64115,
      "accepted_answer_id": 27182,
      "answer_count": 4,
      "score": 173,
      "last_activity_date": 1556842598,
      "creation_date": 1406758485,
      "last_edit_date": 1530548015,
      "question_id": 27177,
      "content_license": "CC BY-SA 4.0",
      "link": "https://pt.stackoverflow.com/questions/27177/o-que-%c3%a9-callback",
      "title": "O que &#233; callback?"
    },
    {
      "tags": [
        "javascript",
        "matem&#225;tica",
        "n&#250;meros-aleat&#243;rios",
        "random"
      ],
      "owner": {
        "reputation": 8238,
        "user_id": 5082,
        "user_type": "registered",
        "accept_rate": 83,
        "profile_image": "https://i.stack.imgur.com/2DPRD.jpg?s=128&g=1",
        "display_name": "Silvio Andorinha",
        "link": "https://pt.stackoverflow.com/users/5082/silvio-andorinha"
      },
      "is_answered": true,
      "view_count": 5113,
      "accepted_answer_id": 9030,
      "answer_count": 6,
      "score": 170,
      "last_activity_date": 1491338927,
      "creation_date": 1394632101,
      "last_edit_date": 1429714160,
      "question_id": 9026,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/9026/como-%c3%a9-gerada-a-randomiza%c3%a7%c3%a3o-pelo-computador",
      "title": "Como &#233; gerada a randomiza&#231;&#227;o pelo computador?"
    },
    {
      "tags": [
        "java",
        "android",
        "seguran&#231;a",
        "descompila&#231;&#227;o",
        "ofusca&#231;&#227;o"
      ],
      "owner": {
        "reputation": 29493,
        "user_id": 3117,
        "user_type": "moderator",
        "accept_rate": 93,
        "profile_image": "https://i.stack.imgur.com/zxdhf.png?s=128&g=1",
        "display_name": "Math",
        "link": "https://pt.stackoverflow.com/users/3117/math"
      },
      "is_answered": true,
      "view_count": 18360,
      "accepted_answer_id": 7271,
      "answer_count": 7,
      "score": 153,
      "last_activity_date": 1535992513,
      "creation_date": 1393340864,
      "last_edit_date": 1508843522,
      "question_id": 7257,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/7257/como-proteger-o-c%c3%b3digo-fonte",
      "title": "Como proteger o c&#243;digo fonte?"
    },
    {
      "tags": [
        "fun&#231;&#245;es",
        "estilo-de-codifica&#231;&#227;o",
        "return"
      ],
      "owner": {
        "reputation": 414410,
        "user_id": 101,
        "user_type": "moderator",
        "accept_rate": 89,
        "profile_image": "https://i.stack.imgur.com/23y8L.png?s=128&g=1",
        "display_name": "Maniero",
        "link": "https://pt.stackoverflow.com/users/101/maniero"
      },
      "is_answered": true,
      "view_count": 5956,
      "accepted_answer_id": 2478,
      "answer_count": 4,
      "score": 148,
      "last_activity_date": 1598988047,
      "creation_date": 1390866229,
      "last_edit_date": 1591886734,
      "question_id": 2477,
      "content_license": "CC BY-SA 4.0",
      "link": "https://pt.stackoverflow.com/questions/2477/por-que-devo-usar-apenas-um-return-em-cada-fun%c3%a7%c3%a3o",
      "title": "Por que devo usar apenas um &quot;return&quot; em cada fun&#231;&#227;o?"
    },
    {
      "tags": [
        "javascript"
      ],
      "owner": {
        "reputation": 9712,
        "user_id": 1344,
        "user_type": "registered",
        "accept_rate": 88,
        "profile_image": "https://i.stack.imgur.com/Ni57b.png?s=128&g=1",
        "display_name": "Paulo",
        "link": "https://pt.stackoverflow.com/users/1344/paulo"
      },
      "is_answered": true,
      "view_count": 5540,
      "accepted_answer_id": 13365,
      "answer_count": 5,
      "score": 146,
      "last_activity_date": 1557804134,
      "creation_date": 1397774144,
      "last_edit_date": 1397786043,
      "question_id": 13364,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/13364/qual-a-diferen%c3%a7a-entre-as-fun%c3%a7%c3%b5es-var-name-function-e-function-name",
      "title": "Qual a diferen&#231;a entre as fun&#231;&#245;es var name = function() e function name()?"
    },
    {
      "tags": [
        "par&#226;metros",
        "terminologia",
        "argumento"
      ],
      "owner": {
        "reputation": 78261,
        "user_id": 215,
        "user_type": "registered",
        "accept_rate": 77,
        "profile_image": "https://www.gravatar.com/avatar/414aae1257ee9e58014bd81bf438a662?s=128&d=identicon&r=PG",
        "display_name": "mgibsonbr",
        "link": "https://pt.stackoverflow.com/users/215/mgibsonbr"
      },
      "is_answered": true,
      "view_count": 19674,
      "accepted_answer_id": 32450,
      "answer_count": 5,
      "score": 142,
      "last_activity_date": 1599595936,
      "creation_date": 1410644456,
      "last_edit_date": 1445596606,
      "question_id": 32448,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/32448/qual-a-diferen%c3%a7a-entre-par%c3%a2metro-e-argumento",
      "title": "Qual a diferen&#231;a entre par&#226;metro e argumento?"
    },
    {
      "tags": [
        "git",
        "versionamento",
        "svn"
      ],
      "owner": {
        "reputation": 21554,
        "user_id": 3999,
        "user_type": "registered",
        "accept_rate": 100,
        "profile_image": "https://i.stack.imgur.com/CXgNf.png?s=128&g=1",
        "display_name": "Laerte",
        "link": "https://pt.stackoverflow.com/users/3999/laerte"
      },
      "is_answered": true,
      "view_count": 22494,
      "accepted_answer_id": 8322,
      "answer_count": 3,
      "score": 141,
      "last_activity_date": 1544455272,
      "creation_date": 1394128886,
      "last_edit_date": 1508861781,
      "question_id": 8315,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/8315/quais-as-diferen%c3%a7as-entre-git-svn-e-cvs",
      "title": "Quais as diferen&#231;as entre Git, SVN e CVS?"
    },
    {
      "tags": [
        "javascript",
        "operadores"
      ],
      "owner": {
        "user_type": "does_not_exist",
        "display_name": "user59"
      },
      "is_answered": true,
      "view_count": 24720,
      "protected_date": 1587942260,
      "accepted_answer_id": 9,
      "answer_count": 10,
      "score": 136,
      "last_activity_date": 1587509191,
      "creation_date": 1386777483,
      "last_edit_date": 1556046527,
      "question_id": 7,
      "content_license": "CC BY-SA 4.0",
      "link": "https://pt.stackoverflow.com/questions/7/qual-a-diferen%c3%a7a-entre-os-operadores-e-em-javascript",
      "title": "Qual a diferen&#231;a entre os operadores == e === em JavaScript?"
    },
    {
      "tags": [
        "web-service"
      ],
      "owner": {
        "reputation": 21554,
        "user_id": 3999,
        "user_type": "registered",
        "accept_rate": 100,
        "profile_image": "https://i.stack.imgur.com/CXgNf.png?s=128&g=1",
        "display_name": "Laerte",
        "link": "https://pt.stackoverflow.com/users/3999/laerte"
      },
      "is_answered": true,
      "view_count": 96843,
      "protected_date": 1567021920,
      "accepted_answer_id": 11186,
      "answer_count": 3,
      "score": 136,
      "last_activity_date": 1567021776,
      "creation_date": 1396296942,
      "last_edit_date": 1521466244,
      "question_id": 11183,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/11183/quais-as-principais-diferen%c3%a7as-entre-soap-rest",
      "title": "Quais as principais diferen&#231;as entre SOAP, REST?"
    },
    {
      "tags": [
        "terminologia",
        "ide",
        "independente-de-linguagem",
        "compiladores",
        "ci&#234;ncia-da-computa&#231;&#227;o"
      ],
      "owner": {
        "reputation": 64853,
        "user_id": 18246,
        "user_type": "registered",
        "accept_rate": 97,
        "profile_image": "https://i.stack.imgur.com/W6dDA.jpg?s=128&g=1",
        "display_name": "LINQ",
        "link": "https://pt.stackoverflow.com/users/18246/linq"
      },
      "is_answered": true,
      "view_count": 39114,
      "accepted_answer_id": 101703,
      "answer_count": 9,
      "score": 131,
      "last_activity_date": 1572615454,
      "creation_date": 1449140090,
      "last_edit_date": 1471126827,
      "question_id": 101691,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/101691/o-que-%c3%a9-linguagem-de-programa%c3%a7%c3%a3o-ide-e-compilador",
      "title": "O que &#233; linguagem de programa&#231;&#227;o, IDE e compilador?"
    },
    {
      "tags": [
        "c#",
        "linq",
        "estilo-de-codifica&#231;&#227;o"
      ],
      "owner": {
        "reputation": 21554,
        "user_id": 3999,
        "user_type": "registered",
        "accept_rate": 100,
        "profile_image": "https://i.stack.imgur.com/CXgNf.png?s=128&g=1",
        "display_name": "Laerte",
        "link": "https://pt.stackoverflow.com/users/3999/laerte"
      },
      "is_answered": true,
      "view_count": 4917,
      "accepted_answer_id": 14275,
      "answer_count": 7,
      "score": 125,
      "last_activity_date": 1492381951,
      "creation_date": 1398361029,
      "last_edit_date": 1486559568,
      "question_id": 13890,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/13890/como-escrever-um-c%c3%b3digo-leg%c3%advel-e-de-f%c3%a1cil-manuten%c3%a7%c3%a3o",
      "title": "Como escrever um c&#243;digo leg&#237;vel e de f&#225;cil manuten&#231;&#227;o?"
    },
    {
      "tags": [
        "html",
        "caracter&#237;stica-linguagem",
        "terminologia"
      ],
      "owner": {
        "reputation": 3790,
        "user_id": 5508,
        "user_type": "registered",
        "accept_rate": 68,
        "profile_image": "https://www.gravatar.com/avatar/0188f678dcffd0b8c4adbb7e70df7614?s=128&d=identicon&r=PG",
        "display_name": "Cold",
        "link": "https://pt.stackoverflow.com/users/5508/cold"
      },
      "is_answered": true,
      "view_count": 30452,
      "protected_date": 1537243082,
      "accepted_answer_id": 35548,
      "answer_count": 4,
      "score": 124,
      "last_activity_date": 1599671535,
      "creation_date": 1412956155,
      "last_edit_date": 1591886734,
      "question_id": 35547,
      "content_license": "CC BY-SA 4.0",
      "link": "https://pt.stackoverflow.com/questions/35547/html-%c3%a9-uma-linguagem-de-programa%c3%a7%c3%a3o",
      "title": "HTML &#233; uma linguagem de programa&#231;&#227;o?"
    },
    {
      "tags": [
        "javascript",
        "closures"
      ],
      "owner": {
        "reputation": 1799,
        "user_id": 1043,
        "user_type": "registered",
        "profile_image": "https://i.stack.imgur.com/UUb8d.png?s=128&g=1",
        "display_name": "Elias Developer",
        "link": "https://pt.stackoverflow.com/users/1043/elias-developer"
      },
      "is_answered": true,
      "view_count": 8706,
      "answer_count": 5,
      "score": 121,
      "last_activity_date": 1531235036,
      "creation_date": 1389404598,
      "last_edit_date": 1482101094,
      "question_id": 1859,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/1859/como-funcionam-closures-em-javascript",
      "title": "Como funcionam Closures em JavaScript?"
    },
    {
      "tags": [
        "javascript",
        "php",
        "jquery",
        "ajax"
      ],
      "owner": {
        "reputation": 2933,
        "user_id": 3511,
        "user_type": "registered",
        "accept_rate": 88,
        "profile_image": "https://i.stack.imgur.com/fQf8W.jpg?s=128&g=1",
        "display_name": "jpklzm",
        "link": "https://pt.stackoverflow.com/users/3511/jpklzm"
      },
      "is_answered": true,
      "view_count": 12292,
      "accepted_answer_id": 6634,
      "answer_count": 10,
      "score": 121,
      "last_activity_date": 1508868390,
      "creation_date": 1392871713,
      "last_edit_date": 1397240417,
      "question_id": 6626,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/6626/como-criar-um-site-sem-recarregar-a-cada-clique-num-link",
      "title": "Como criar um site sem recarregar a cada clique num link?"
    },
    {
      "tags": [
        "concorr&#234;ncia",
        "desempenho",
        "multithreading",
        "paralelismo",
        "otimiza&#231;&#227;o"
      ],
      "owner": {
        "reputation": 414410,
        "user_id": 101,
        "user_type": "moderator",
        "accept_rate": 89,
        "profile_image": "https://i.stack.imgur.com/23y8L.png?s=128&g=1",
        "display_name": "Maniero",
        "link": "https://pt.stackoverflow.com/users/101/maniero"
      },
      "is_answered": true,
      "view_count": 5128,
      "accepted_answer_id": 1957,
      "answer_count": 8,
      "score": 120,
      "last_activity_date": 1598969491,
      "creation_date": 1389702492,
      "last_edit_date": 1389703316,
      "question_id": 1946,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/1946/%c3%89-sempre-garantido-que-uma-aplica%c3%a7%c3%a3o-com-m%c3%baltiplas-threads-rode-mais-r%c3%a1pido-que",
      "title": "&#201; sempre garantido que uma aplica&#231;&#227;o com m&#250;ltiplas threads rode mais r&#225;pido que usando uma &#250;nica thread?"
    },
    {
      "tags": [
        "orienta&#231;&#227;o-a-objetos",
        "modelagem",
        "engenharia-de-software",
        "ddd"
      ],
      "owner": {
        "reputation": 17526,
        "user_id": 1917,
        "user_type": "registered",
        "accept_rate": 58,
        "profile_image": "https://www.gravatar.com/avatar/687d34e2ad24ba9b5530031eb15f7845?s=128&d=identicon&r=PG",
        "display_name": "SomeDeveloper",
        "link": "https://pt.stackoverflow.com/users/1917/somedeveloper"
      },
      "is_answered": true,
      "view_count": 32743,
      "protected_date": 1440627311,
      "accepted_answer_id": 19550,
      "answer_count": 4,
      "score": 119,
      "last_activity_date": 1486985532,
      "creation_date": 1402241630,
      "last_edit_date": 1483707534,
      "question_id": 19548,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/19548/o-que-realmente-%c3%a9-ddd-e-quando-ele-se-aplica",
      "title": "O que realmente &#233; DDD e quando ele se aplica?"
    },
    {
      "tags": [
        "string",
        "algoritmo",
        "portugu&#234;s-do-brasil",
        "soundex",
        "algoritmo-fon&#233;tico"
      ],
      "owner": {
        "reputation": 414410,
        "user_id": 101,
        "user_type": "moderator",
        "accept_rate": 89,
        "profile_image": "https://i.stack.imgur.com/23y8L.png?s=128&g=1",
        "display_name": "Maniero",
        "link": "https://pt.stackoverflow.com/users/101/maniero"
      },
      "is_answered": true,
      "view_count": 16089,
      "accepted_answer_id": 5391,
      "answer_count": 6,
      "score": 118,
      "last_activity_date": 1539867945,
      "creation_date": 1389343337,
      "last_edit_date": 1539867945,
      "question_id": 1828,
      "content_license": "CC BY-SA 4.0",
      "link": "https://pt.stackoverflow.com/questions/1828/como-fazer-um-algoritmo-fon%c3%a9tico-para-o-portugu%c3%aas-brasileiro",
      "title": "Como fazer um algoritmo fon&#233;tico para o portugu&#234;s brasileiro?"
    },
    {
      "tags": [
        "php",
        "data"
      ],
      "owner": {
        "reputation": 28405,
        "user_id": 5749,
        "user_type": "registered",
        "accept_rate": 86,
        "profile_image": "https://i.stack.imgur.com/5SakC.jpg?s=128&g=1",
        "display_name": "Miguel",
        "link": "https://pt.stackoverflow.com/users/5749/miguel"
      },
      "is_answered": true,
      "view_count": 111134,
      "protected_date": 1486854743,
      "accepted_answer_id": 8333,
      "answer_count": 4,
      "score": 117,
      "last_activity_date": 1557924464,
      "creation_date": 1394129822,
      "last_edit_date": 1557924464,
      "question_id": 8317,
      "content_license": "CC BY-SA 4.0",
      "link": "https://pt.stackoverflow.com/questions/8317/como-fazer-a-fun%c3%a7%c3%a3o-date-formatar-uma-data-em-portugu%c3%aas",
      "title": "Como fazer a fun&#231;&#227;o date() formatar uma data em portugu&#234;s?"
    },
    {
      "tags": [
        "php",
        "html",
        "mysql",
        "codifica&#231;&#227;o-de-caracteres"
      ],
      "owner": {
        "reputation": 1181,
        "user_id": 18775,
        "user_type": "unregistered",
        "profile_image": "https://www.gravatar.com/avatar/89f4312a2ac09d32ca0660b6bca140ea?s=128&d=identicon&r=PG",
        "display_name": "Diogo",
        "link": "https://pt.stackoverflow.com/users/18775/diogo"
      },
      "is_answered": true,
      "view_count": 47798,
      "answer_count": 3,
      "score": 116,
      "last_activity_date": 1583957612,
      "creation_date": 1417993063,
      "last_edit_date": 1583957565,
      "question_id": 43193,
      "content_license": "CC BY-SA 4.0",
      "link": "https://pt.stackoverflow.com/questions/43193/d%c3%bavida-com-charset-iso-8859-1-e-utf8",
      "title": "D&#250;vida com charset=iso-8859-1 e utf8"
    },
    {
      "tags": [
        "javascript",
        "if"
      ],
      "owner": {
        "reputation": 2297,
        "user_id": 2129,
        "user_type": "registered",
        "accept_rate": 89,
        "profile_image": "https://www.gravatar.com/avatar/0b583f359f983cc9fd2329d47af9a49a?s=128&d=identicon&r=PG",
        "display_name": "filipelinhares",
        "link": "https://pt.stackoverflow.com/users/2129/filipelinhares"
      },
      "is_answered": true,
      "view_count": 56746,
      "accepted_answer_id": 4916,
      "answer_count": 7,
      "score": 111,
      "last_activity_date": 1537215983,
      "creation_date": 1391879740,
      "last_edit_date": 1449772286,
      "question_id": 4907,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/4907/como-funciona-este-if-else-com-e",
      "title": "Como funciona este if/else com &quot;?&quot; e &quot;:&quot;?"
    },
    {
      "tags": [
        "javascript",
        "ponto-flutuante",
        "valor-monet&#225;rio",
        "tipagem"
      ],
      "owner": {
        "reputation": 78261,
        "user_id": 215,
        "user_type": "registered",
        "accept_rate": 77,
        "profile_image": "https://www.gravatar.com/avatar/414aae1257ee9e58014bd81bf438a662?s=128&d=identicon&r=PG",
        "display_name": "mgibsonbr",
        "link": "https://pt.stackoverflow.com/users/215/mgibsonbr"
      },
      "is_answered": true,
      "view_count": 12708,
      "protected_date": 1579712379,
      "accepted_answer_id": 11267,
      "answer_count": 7,
      "score": 110,
      "last_activity_date": 1579708072,
      "creation_date": 1396124051,
      "last_edit_date": 1396329601,
      "question_id": 11018,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/11018/como-representar-dinheiro-em-javascript",
      "title": "Como representar dinheiro em JavaScript?"
    },
    {
      "tags": [
        "javascript",
        "html",
        "estilo-de-codifica&#231;&#227;o"
      ],
      "owner": {
        "reputation": 6525,
        "user_id": 263,
        "user_type": "registered",
        "accept_rate": 88,
        "profile_image": "https://i.stack.imgur.com/giCRY.jpg?s=128&g=1",
        "display_name": "Zignd",
        "link": "https://pt.stackoverflow.com/users/263/zignd"
      },
      "is_answered": true,
      "view_count": 42862,
      "accepted_answer_id": 1112,
      "answer_count": 4,
      "score": 108,
      "last_activity_date": 1569615257,
      "creation_date": 1388078301,
      "last_edit_date": 1455838357,
      "question_id": 1109,
      "content_license": "CC BY-SA 3.0",
      "link": "https://pt.stackoverflow.com/questions/1109/onde-devo-colocar-um-c%c3%b3digo-javascript-em-um-documento-html",
      "title": "Onde devo colocar um c&#243;digo JavaScript em um documento HTML?"
    }
  ],
  "has_more": true,
  "quota_max": 300,
  "quota_remaining": 297
}
```
