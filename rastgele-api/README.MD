# Rastgele API End Points

> API is still under development

### All Content

__*Base Url:*__ [https://rastgele-api.glitch.me/api](https://rastgele-api.glitch.me/api)

- GET **[/ip](https://rastgele-api.glitch.me/api/ip)**: Kendi ipniz.
- GET **[/coolsay](https://rastgele-api.glitch.me/api/havaliyaz)**: Ａｙｎｅｎ  ｂｕ  ｓｅｋｉｌｄｅ  ｙａｚｍａｎｉｚｉ  ｓａｇｌａｒ．(Ve Daha Fazla Şekilde)
- GET **[/urban](https://rastgele-api.glitch.me/api/urban)**: Urban Dictionary'de birşeyler aratmanızı sağlar.
- GET **[/mc/java/name-history](https://rastgele-api.glitch.me/api/mc/java/name-history)**: Minecraft oyuncularının isim geçmişi.
- GET **[/nsfw/video](http://rastgele-api.glitch.me/api/nsfw/video)** - P()rn() videoları (`xvideos, sex.com, pornhub.com, redtube`)
- GET **[/nsfw/gif](http://rastgele-api.glitch.me/api/nsfw/gif)** - P()rn() Gifleri (`sex.com, pornhub.com`)


---

# Usages

#### Urban Dictionary

GET `https://rastgele-api.glitch.me/api/urban?q=Minecraft`

Parameter | Info
------|------
q     | Any Word

<details>
  <summary>Response</summary>
  
  ```json
 {
  "status": "ok",
  "response": {
    "total": 10,
    "results": [
      {
        "word": "Minecraft",
        "owner": "SibunaS",
        "definition": "[What is this] 'Physics' you speak of, [is it] [magic]?",
        "example": "Person 1: How is that castle being help up by a 20 foot tall stick?\r\nPerson 2: Minecraft\r\nPerson 1: But it's not physically possible!\r\nPerson 2: [What is this] 'Physics' you speak of, is it magic?\r\nPerson 1: It's the [governing] law [o-]\r\nPerson 2: MINECRAFT!(Bitch slaps person 1)",
        "additional": {
          "vote": {
            "like": 746,
            "dislike": 120
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/6730949",
            "id": 6730949
          },
          "date": "2012-08-26T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "Logdotzip",
        "definition": "Cheap and [legal] alternative to drugs. [This shit] will [sap] your life away.",
        "example": "A: Hey Tony, you wanna go to a party? There's booze and chicks an-\n\nB: FUCK OFF I'M BUILDING A [CASTLE] AND [MOAT] ON [MINECRAFT].",
        "additional": {
          "vote": {
            "like": 5233,
            "dislike": 1333
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/5345893",
            "id": 5345893
          },
          "date": "2010-11-10T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "xXChibitaliaXx",
        "definition": "A [virtual] drug that will probably take over your [childhood] and [teenage years].",
        "example": "Guy 1 - Hey, Do you wanna go to my house and watch the game?\r\nGuy 2 - FUCK YEAH! I JUST KILLED A [CREEPER]!\r\nMother [down stairs] - What's going on up there?!\r\nGuy 2 - He's on [minecraft] again...",
        "additional": {
          "vote": {
            "like": 221,
            "dislike": 48
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/6483983",
            "id": 6483983
          },
          "date": "2012-03-06T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "Seelad",
        "definition": "A [kick ass] game that is being built slowly. [The creator] is [notch], and he programs the game.",
        "example": "Person1: [Hey].\r\nPerson2: [Shut the fuck up]! I'm [playing Minecraft]!",
        "additional": {
          "vote": {
            "like": 6636,
            "dislike": 1920
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/5024805",
            "id": 5024805
          },
          "date": "2010-06-09T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "Mikeandike123456789",
        "definition": "Minecraft is a game where when you play it once, u will never go outside or get [excersize] again. It is like a cheap drug in which you build and remove [blocks] to make [awe inspiring] structures.",
        "example": "Friend: Hey dude lets go to a party. Lots of [hot chicks] there.\n\nYou: What server is it on?\n\nFriend: What? Server?\n\nYou: Minecraft [party's] have to [b on] servers!",
        "additional": {
          "vote": {
            "like": 1368,
            "dislike": 484
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/5431335",
            "id": 5431335
          },
          "date": "2010-12-12T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "Minecrafterererererer",
        "definition": "A suitable [alternative] to some [illegal] [substance].",
        "example": "Person 1: Wanna come round me and do come [crack]?\r\nPerson 2: I [kicked] that for Minecraft.\r\nPerson 1: What the fuck is that?\r\nPerson 2: Just a ga- FUCK A [CREEPER]!",
        "additional": {
          "vote": {
            "like": 1509,
            "dislike": 551
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/5723632",
            "id": 5723632
          },
          "date": "2011-04-05T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "Idekwia",
        "definition": "Minecraft is a sandbox video game created and designed by Swedish game designer Markus \"Notch\" [Persson], and later fully developed and published by [Mojang]. Wikipedia\r\nInitial release date: [May 17], 2009\r\nPlatforms: PlayStation 4, PlayStation Vita, Wii U, Nintendo Switch, Android, PlayStation 3, Xbox One, MORE\r\nDid you know: \"Minecraft\" is the best-selling PC game (26 million copies sold). wikipedia.org",
        "example": "\"[I Love] [Playing Minecraft]!\"",
        "additional": {
          "vote": {
            "like": 14,
            "dislike": 2
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/11995426",
            "id": 11995426
          },
          "date": "2017-09-25T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "Kitty Carvis",
        "definition": "The single most [addicting] game in the world, [side effects] are anti-sociality, fear of light, explodingpenisphobia, a fear of [the Creeper], occasional dreams only in blocks and thinking Minecraft is real.",
        "example": "person1: I punched my [refrigerator] to get milk.\n\nperson2: You dumbass you know you need a bucket for milk\n\nperson3: Minecraft is [not real] you need a fucking cup for milk [dumbasses]!\n\nperson1,2: Um, We knew that",
        "additional": {
          "vote": {
            "like": 108,
            "dislike": 35
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/6064603",
            "id": 6064603
          },
          "date": "2011-09-07T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "davidjl123",
        "definition": "Minecraft is a game written in Java created by [Mojang] AB in 2009. Minecraft has two current variants - Classic (which is free) and Beta (which you have to pay for).\r\n[In Beta], the main goal is to survive. At night, monsters spawn (but not in Peaceful mode) and attack you so you need to craft items and tools to help you survive. You also need to eat regularly.\n\nMinecraft has gone through many development stages:\n\nClassic - the oldest version. It is still playable and has multiplayer. In Classic, you have an infinite amount of blocks, no health, and no [mobs].\n\nSurvival Test - Part of Classic, very basic compared to the Survival we play and know today.\n\n[Indev] - Added a number of new features, including [crafting], torches, and tools.\n\nInfdev - Added the ability to have an infinite playing surface.\n\nAlpha - Added [biomes], [nether], sneaking, and much more.\n\nBeta - The current version of Minecraft. Added beds (which can skip the night), more mobs such as [endermen] and wolves (which can be tamed with bones and attack monsters), and many more.\n\nMultiplayer is in both Classic and Beta, which allows, well, multiplayer, duhhhh",
        "example": "Girlfriend: Why aren't you spending much time with me, [Greg]?\r\nGreg: SHUT UP AND [GO AWAY], I'M [PLAYING MINECRAFT]",
        "additional": {
          "vote": {
            "like": 86,
            "dislike": 30
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/6142427",
            "id": 6142427
          },
          "date": "2011-10-16T00:00:00.000Z"
        }
      },
      {
        "word": "Minecraft",
        "owner": "DrPooptickler",
        "definition": "The meeting place of all annoying 10-12 year olds. [Nobody knows] what they are talking about because they are speaking in a very [broken English] that scientists suspect are from the child being hit in the head so hard that his head [slammed] into the keyboard.",
        "example": "Jim: Tim, do you play minecraft?\r\nTim: [yersh] i em tho [gud] it [ti]",
        "additional": {
          "vote": {
            "like": 201,
            "dislike": 80
          },
          "cennections": {
            "url": "http://minecraft.urbanup.com/8027644",
            "id": 8027644
          },
          "date": "2014-12-30T00:00:00.000Z"
        }
      }
    ]
  }
}
  ```
</details>

---

#### Minecraft Java Edition Preminum Account Name History

GET `https://rastgele-api.glitch.me/api/mc/java/name-history?qtype=username&q=Armagann`

Parameter | Info
------|------
q     | Minecraft Preaminum Account UUID or Username
qtype | Query Type `username` or `uuid`

<details>
  <summary>Response</summary>
  
  ```json
  {
  "status": "ok",
  "response": [
    "HDNameHD",
    "ArmaganDCS",
    "Armagann"
  ]
}
  ```
</details>

---

#### Coolsay

GET `http://rastgele-api.glitch.me/api/coolsay?font=DOUBLE&input=REALY%20COOL`

Parameter | Info
------|------
input | Text Input
font  | Text Style (`WIDE & DOUBLE & SNOOPDOGG`)
COOL  | ℝ𝔼𝔸𝕃𝕐 ℂ𝕆𝕆𝕃


<details>
  <summary>Response</summary>
  
```json
 {
  "status": "ok",
  "response": {
    "font": "DOUBLE",
    "input": "REALY COOL",
    "output": "ℝ𝔼𝔸𝕃𝕐 ℂ𝕆𝕆𝕃"
  }
} 

```
</details>

---

#### [NSFW] `Adult Gifs`

GET `http://rastgele-api.glitch.me/api/nsfw/gif?p=50&q=ass&source=pornhub`

Parameter | Info
------|------
q     | Search Query
p     | Page Number `(Default 1)`
source| Query Source (`sex & pornhub`)

<details>
 <summary>Response</summary>

```json
{
  "status": "ok",
  "response": {
    "total": 34,
    "page": "1",
    "results": [
      {
        "title": "asses",
        "media": {
          "gif": "https://dl.phncdn.com/gif/5990271.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/005/990/271/5990271a.webm"
        }
      },
      {
        "title": "#ass #big ass #twerk",
        "media": {
          "gif": "https://dl.phncdn.com/gif/13401142.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/013/401/142/13401142a.webm"
        }
      },
      {
        "title": "Amazing ass riding",
        "media": {
          "gif": "https://dl.phncdn.com/gif/2753881.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/002/753/881/2753881a.webm"
        }
      },
      {
        "title": "ASS",
        "media": {
          "gif": "https://dl.phncdn.com/gif/15490662.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/015/490/662/15490662a.webm"
        }
      },
      {
        "title": "Ass, Ass, Ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/12056021.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/012/056/021/12056021a.webm"
        }
      },
      {
        "title": "Ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/1418511.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/001/418/511/1418511a.webm"
        }
      },
      {
        "title": "#big-ass #perfect-ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/1078541.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/001/078/541/1078541a.webm"
        }
      },
      {
        "title": "#ass #cum",
        "media": {
          "gif": "https://dl.phncdn.com/gif/810421.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/000/810/421/810421a.webm"
        }
      },
      {
        "title": "#ass #big-ass-jada-stevens",
        "media": {
          "gif": "https://dl.phncdn.com/gif/873821.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/000/873/821/873821a.webm"
        }
      },
      {
        "title": "#big-ass #big-ass-white-girls",
        "media": {
          "gif": "https://dl.phncdn.com/gif/3306541.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/003/306/541/3306541a.webm"
        }
      },
      {
        "title": "Ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/19546281.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/019/546/281/19546281a.webm"
        }
      },
      {
        "title": "#ass #elles",
        "media": {
          "gif": "https://dl.phncdn.com/gif/20611131.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/020/611/131/20611131a.webm"
        }
      },
      {
        "title": "#ass #asses",
        "media": {
          "gif": "https://dl.phncdn.com/gif/3791941.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/003/791/941/3791941a.webm"
        }
      },
      {
        "title": "ASS",
        "media": {
          "gif": "https://dl.phncdn.com/gif/17520931.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/017/520/931/17520931a.webm"
        }
      },
      {
        "title": "ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/592452.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/000/592/452/592452a.webm"
        }
      },
      {
        "title": "#ass #booty",
        "media": {
          "gif": "https://dl.phncdn.com/gif/8383431.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/008/383/431/8383431a.webm"
        }
      },
      {
        "title": "#big-ass #big-dick",
        "media": {
          "gif": "https://dl.phncdn.com/gif/2675431.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/002/675/431/2675431a.webm"
        }
      },
      {
        "title": "Asses",
        "media": {
          "gif": "https://dl.phncdn.com/gif/3503931.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/003/503/931/3503931a.webm"
        }
      },
      {
        "title": "Milf Ass Is The Best Kind Of Ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/4249411.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/004/249/411/4249411a.webm"
        }
      },
      {
        "title": "#big-ass #big-ass-white-girls #fat-ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/2036481.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/002/036/481/2036481a.webm"
        }
      },
      {
        "title": "Sexy ass babe",
        "media": {
          "gif": "https://dl.phncdn.com/gif/20096211.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/020/096/211/20096211a.webm"
        }
      },
      {
        "title": "ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/425511.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/000/425/511/425511a.webm"
        }
      },
      {
        "title": "spread ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/13829792.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/013/829/792/13829792a.webm"
        }
      },
      {
        "title": "#ass #spread",
        "media": {
          "gif": "https://dl.phncdn.com/gif/5164471.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/005/164/471/5164471a.webm"
        }
      },
      {
        "title": "Ass fucked",
        "media": {
          "gif": "https://dl.phncdn.com/gif/5176591.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/005/176/591/5176591a.webm"
        }
      },
      {
        "title": "Amazing ass ride",
        "media": {
          "gif": "https://dl.phncdn.com/gif/2753861.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/002/753/861/2753861a.webm"
        }
      },
      {
        "title": "cum on ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/2122111.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/002/122/111/2122111a.webm"
        }
      },
      {
        "title": "ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/814231.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/000/814/231/814231a.webm"
        }
      },
      {
        "title": "sexy ass babe",
        "media": {
          "gif": "https://dl.phncdn.com/gif/19439781.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/019/439/781/19439781a.webm"
        }
      },
      {
        "title": "ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/4979041.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/004/979/041/4979041a.webm"
        }
      },
      {
        "title": "#ass #cum",
        "media": {
          "gif": "https://dl.phncdn.com/gif/5010401.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/005/010/401/5010401a.webm"
        }
      },
      {
        "title": "#ass #ass-licking #jada-stevens",
        "media": {
          "gif": "https://dl.phncdn.com/gif/2064451.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/002/064/451/2064451a.webm"
        }
      },
      {
        "title": "#ride #sweet-ass",
        "media": {
          "gif": "https://dl.phncdn.com/gif/814361.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/000/814/361/814361a.webm"
        }
      },
      {
        "title": "#ass #sexy",
        "media": {
          "gif": "https://dl.phncdn.com/gif/18313141.gif",
          "webm": "https://dl.phncdn.com/pics/gifs/018/313/141/18313141a.webm"
        }
      }
    ]
  }
}
```
</details>

---

#### [NSFW] `Adult Videos`

GET `http://rastgele-api.glitch.me/api/nsfw/video?p=1&q=ass&source=redtube`

Paramater | Info
----------|------
q | Search Query
p | Page Number `(Default 1)`
souce | Query Source (`sex & pornhub & xvideos & redtube`)

<details>
<summary>Response</summary>

```json
{
  "status": "ok",
  "response": {
    "total": 20,
    "page": "1",
    "results": [
      {
        "title": "Delicious ebony ghetto fuck under the trees",
        "media": {
          "gif": "https://www.redtube.com/167220",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201203/30/167220/original/5.jpg",
          "duration": "14:36"
        }
      },
      {
        "title": "Ebony just wants to suck his dick",
        "media": {
          "gif": "https://www.redtube.com/120599",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201201/09/120599/original/14.jpg",
          "duration": "11:29"
        }
      },
      {
        "title": "Lil Ass got nailed outdoor",
        "media": {
          "gif": "https://www.redtube.com/90913",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201111/04/90913/original/15.jpg",
          "duration": "13:43"
        }
      },
      {
        "title": "Big tits babe fucked on sofa",
        "media": {
          "gif": "https://www.redtube.com/45464",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201105/09/45464/original/14.jpg",
          "duration": "12:53"
        }
      },
      {
        "title": "Hot big ass gets some cum ",
        "media": {
          "gif": "https://www.redtube.com/32507",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201002/10/32507/original/16.jpg",
          "duration": "18:16"
        }
      },
      {
        "title": "Big ass ebony gets nailed ",
        "media": {
          "gif": "https://www.redtube.com/334746",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201212/29/334746/original/10.jpg",
          "duration": "32:43"
        }
      },
      {
        "title": "Big Booty Fantasies - Cherokee D Ass ",
        "media": {
          "gif": "https://www.redtube.com/873782",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201408/30/873782/original/15.jpg",
          "duration": "8:07"
        }
      },
      {
        "title": "Massive Ass Ebony BBW fucks a big black cock",
        "media": {
          "gif": "https://www.redtube.com/203784",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201205/27/203784/original/6.jpg",
          "duration": "24:05"
        }
      },
      {
        "title": "Cherry gets that big booty pounded",
        "media": {
          "gif": "https://www.redtube.com/493668",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201307/09/493668/original/6.jpg",
          "duration": "6:58"
        }
      },
      {
        "title": "cherohee d' ass on cam",
        "media": {
          "gif": "https://www.redtube.com/383954",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201302/27/383954/original/15.jpg",
          "duration": "10:18"
        }
      },
      {
        "title": "Cherokee D'Ass DVD Box Covers",
        "media": {
          "gif": "https://www.redtube.com/946148",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201411/05/946148/original/15.jpg",
          "duration": "4:19"
        }
      },
      {
        "title": "Cherokee D'Ass: My Friend Wit' The Big Booty ",
        "media": {
          "gif": "https://www.redtube.com/786705",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201406/13/786705/original/15.jpg",
          "duration": "6:20"
        }
      },
      {
        "title": "Alexis &amp; Cherokee: My Friends Wit' Big Booty",
        "media": {
          "gif": "https://www.redtube.com/772825",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201405/31/772825/original/15.jpg",
          "duration": "5:13"
        }
      },
      {
        "title": "pinky squirts on cam",
        "media": {
          "gif": "https://www.redtube.com/385201",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201303/01/385201/original/2.jpg",
          "duration": "16:39"
        }
      },
      {
        "title": "Cherokee &amp; Pinky: My Friends Wit' Big Booty's",
        "media": {
          "gif": "https://www.redtube.com/953021",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201411/11/953021/original/13.jpg",
          "duration": "6:13"
        }
      },
      {
        "title": "GTA: SA - The Porno Shop (Pinky DVDs)",
        "media": {
          "gif": "https://www.redtube.com/890442",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201409/12/890442/original/15.jpg",
          "duration": "9:00"
        }
      },
      {
        "title": "GTA:SA - Pinky, Cherokee &amp; BodyXXX Billboards",
        "media": {
          "gif": "https://www.redtube.com/895338",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201409/17/895338/original/15.jpg",
          "duration": "6:05"
        }
      },
      {
        "title": "Hot model nice ass bikini",
        "media": {
          "gif": "https://www.redtube.com/4655821",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201802/23/4655821/original/12.jpg",
          "duration": "0:17"
        }
      },
      {
        "title": "Thick Milf Sara Jay Fucked & Smothered By Ebony Cherokee D'Ass!",
        "media": {
          "gif": "https://www.redtube.com/13548511",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201902/13/13548511/original/12.jpg",
          "duration": "11:00"
        }
      },
      {
        "title": "Cherokee &amp; Beauty Dior Get Pipped Down",
        "media": {
          "gif": "https://www.redtube.com/1068625",
          "thumb": "https://ei.rdtcdn.com/m=e0YH8f/media/videos/201503/14/1068625/original/15.jpg",
          "duration": "30:13"
        }
      }
    ]
  }
}
```
</details>

