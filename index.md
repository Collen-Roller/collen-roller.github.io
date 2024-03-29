Hello, thanks for swinging by!

### a bit on me

<p>
  <div id="animation" style="color: green">
  </div>
  <script type="text/javascript">
    const movingString = "Collen"
    const distance = 20
    let spaces = 0
    let step = 1
    const animationElement = document.getElementById("animation")
    setInterval(() => {
      animationElement.innerHTML = "[" + "&nbsp;".repeat(spaces) + movingString + "&nbsp;".repeat(distance - spaces - movingString.length) + "]"
      spaces += step
      if (spaces === 0 || (spaces + movingString.length) === distance) {
        step = -step
      }
    }, 50)
  </script>
</p>

If you're here it's likely to checkout my portfolio of things I've worked on. If you want to see my papers, head to the bottom, I normally update it when I can. 

### current interests

- Conversational AI
- Dialogue State Tracking
- Natural Language Understanding
- Moderizing DoD DevSecOps

### code

I like to code - Moral of the story like most engineers - I love solving puzzles in my free time. I'm a full stack developer, that means I do everything from requirement gathering and design to development, transition, and sustainment. Here's my primary languages and tools I use.

Languages: Python, Java, Javascript, C++, Swift, Bash

Tools: Docker, AWS / GovCloud, Git, Express, Postgres, Apache Solr, MongoDB, Keycloak, iOS, Android, Kubernetes, Atlassian Tool Suite, Sketch, Figma

Here's some of the open projects I've created.

#### flydenity - [Checkout the Code](https://github.com/Collen-Roller/flydenity)

Flydenity is a callsign identification library to help match tail numbers or callsigns to origin nations. The library is a python wrapper on top of a curated dataset containing a set of regular expressions generated from the International Telecommunications Union (ITU) International Call Sign prefixes. The registration codes in this dataset are separated by country post The Paris Convention in 1929. The database also contains a description of each codeset with 2 and 3 letter ISO country codes following the ISO-3166 standard.

#### rasa denerator - [Checkout the Code](https://github.com/Collen-Roller/Rasa-Denerator)

A simple way of generating a domain.yml file for the Rasa conversational AI framework

#### anc control - iOS iPad television control application used by The Standard Athens hotels. I developed the full-stack application and published it in mid-2020

![Checkout the app](/docs/assets/anc.png)

#### shameless plug

I enjoy full-stack mobile and web development so if you're looking for a developer for an application or website, please feel free to reachout.

### websites

In 2019 I started a Government Software Factory for the United States Air Force called Dark Saber that aims to help airmen learn to build applications by providing mentorship, training, and hosting. 

[Dark Saber Home](https://devilops.dso.mil)

[Force Development Road Map Training Management System](https://fdrm.devilops.dso.mil) - Training Management System for the United States Air Force

### tunes 

In my spare time, I like writing and producing music. I enjoy creating videos and more recently I've been posting covers to YouTube. 

[The Gear Stop](https://www.youtube.com/channel/UCeEBY1M93NGi7BdPho9Z8IQ)

I've been playing guitar, keys, and a variety of other instruments for the better part of 15 years now. I'm in two bands currently and I have some music I produced with friends back in high-school that people still enjoy.

  - Isaac French Duo (2020-Current): [Facebook](https://www.facebook.com/TheIsaacFrench), [Spotify](https://open.spotify.com/artist/3neONBJ0J1PMTCoTp84zi5)
  - Second Breakfast (2022-Current): [Facebook](https://www.facebook.com/SecondBreakfastRomeNY)
  - Work Related (2016-2020): [Facebook](https://www.facebook.com/WorkRelatedCNY)
  - Uncle Charlie and the Meatballs (UCMB) (2017-2020): [Facebook](https://www.facebook.com/UncleCharlieandtheMeatballs/)
  - Slanted Home (2010-2014): [Lonely Triangle World EP (2013)](https://slantedhome.bandcamp.com/)

I love collaborating with musicians on covers, if you're interested send me an email sometime

If you're here for custom pedalboards, send me an email and please provide a long description of exactly what you're looking for :)

### media

- [Linkedin](https://www.linkedin.com/in/collen-roller-7b871682)
- [Github](https://github.com/Collen-Roller)
- [Twitter](https://twitter.com/C_Rollah)

### patents

Segment Vectors (Patent Pending) - [Link to USPTO](https://uspto.report/patent/app/20200184016)

### contact

You can reach me at my email: collen.roller @ gmail dot com 
