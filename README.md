# Vladislav Volf

<p align="center"><sub><em>
High school student from Samara, Russia.<br />
I like turning everyday problems into small, reliable tools, solving olympiad problems,<br />
and I plan to study Computer Science in the US.
</em></sub></p>

---

## Now

school<br>
﹂**Samara International Aerospace Lyceum**, class of 2027<br>
&nbsp;&nbsp;&nbsp;&nbsp;﹂planning to study Computer Science in the US<br>

building<br>
﹂**[couple-habit](https://github.com/itvladis/couple-habit)**: a Telegram bot and Mini App for keeping habits together with friends<br>
&nbsp;&nbsp;&nbsp;&nbsp;﹂runs on Yandex Cloud, with a Cloudflare relay because Telegram is blocked from Russian data centers<br>
﹂**freelance web developer**: websites for small businesses<br>

competitive programming<br>
﹂**191 problems** solved on acmp.ru · [solutions](https://github.com/itvladis/ACMP-solutions)<br>
﹂**Codeforces**: 26th place in Round 1131 (Div. 3)<br>
﹂**USACO**: 2026–27 season<br>

research<br>
﹂working on research papers in computer science · [ORCID](https://orcid.org/0009-0004-4619-4653)<br>

---

## Featured: couple-habit

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/itvladis/couple-habit"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itvladis/couple-habit/main/docs/screenshots/home-dark.png"><img width="100%" src="https://raw.githubusercontent.com/itvladis/couple-habit/main/docs/screenshots/home-light.png" alt="couple-habit home screen" /></picture></a>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/itvladis/couple-habit"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itvladis/couple-habit/main/docs/screenshots/habit-dark.png"><img width="100%" src="https://raw.githubusercontent.com/itvladis/couple-habit/main/docs/screenshots/habit-light.png" alt="couple-habit habit screen with a heatmap" /></picture></a>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/itvladis/couple-habit"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itvladis/couple-habit/main/docs/screenshots/feed-dark.png"><img width="100%" src="https://raw.githubusercontent.com/itvladis/couple-habit/main/docs/screenshots/feed-light.png" alt="couple-habit friends feed" /></picture></a>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Shared habits</b><br />streaks and quick check-ins</td>
    <td align="center"><b>Habit page</b><br />stats and a half-year heatmap</td>
    <td align="center"><b>Feed</b><br />what friends checked today</td>
  </tr>
</table>

A habit tracker that lives inside Telegram, designed in Figma and built from scratch: React Mini App, bot, REST API and a one-command deploy.

- Telegram and Russian data centers can't reach each other, so only the bot's traffic goes through a small Cloudflare Worker. The app and the data stay in Yandex Cloud, close to the users.
- All data is one JSON file saved with conditional writes, so two people checking in at the same moment never overwrite each other.
- 260+ tests, including one that caught a bundling bug which silently broke every message the bot sent.

---

## Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/itvladis/couple-habit"><b>couple-habit</b></a><br />
      <sub>Telegram bot + Mini App for tracking habits together with friends</sub><br />
      <img src="https://img.shields.io/static/v1?style=for-the-badge&label=focus&message=telegram%20%7C%20mini%20app&labelColor=f97362&color=111827" alt="focus telegram mini app" /><br />
      <img src="https://img.shields.io/static/v1?style=flat-square&label=built%20with&message=TypeScript%20%C2%B7%20React%20%C2%B7%20Yandex%20Cloud&color=3178c6" alt="built with TypeScript, React, Yandex Cloud" />
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/itvladis/plenka-pics"><b>plenka-pics</b></a><br />
      <sub>Share photos and videos with friends by link, no accounts · live at <a href="https://plenka-pics.ru">plenka-pics.ru</a></sub><br />
      <img src="https://img.shields.io/static/v1?style=for-the-badge&label=focus&message=web%20%7C%20media%20sharing&labelColor=a855f7&color=111827" alt="focus web media sharing" /><br />
      <img src="https://img.shields.io/static/v1?style=flat-square&label=built%20with&message=Django%20%C2%B7%20PostgreSQL%20%C2%B7%20S3&color=0c4b33" alt="built with Django, PostgreSQL, S3" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/itvladis/uptime-monitor"><b>uptime-monitor</b></a><br />
      <sub>Watches my clients' websites and sends a Telegram alert when one goes down</sub><br />
      <img src="https://img.shields.io/static/v1?style=for-the-badge&label=focus&message=monitoring%20%7C%20async&labelColor=22c55e&color=111827" alt="focus monitoring async" /><br />
      <img src="https://img.shields.io/static/v1?style=flat-square&label=built%20with&message=Python%20%C2%B7%20asyncio%20%C2%B7%20Docker&color=3776ab" alt="built with Python, asyncio, Docker" />
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/itvladis/ACMP-solutions"><b>ACMP-solutions</b></a><br />
      <sub>My solutions to olympiad problems from acmp.ru, one folder per problem</sub><br />
      <img src="https://img.shields.io/static/v1?style=for-the-badge&label=focus&message=algorithms%20%7C%20olympiad&labelColor=f59e0b&color=111827" alt="focus algorithms olympiad" /><br />
      <img src="https://img.shields.io/static/v1?style=flat-square&label=solved&message=191%20problems&color=f59e0b" alt="191 problems solved" />
    </td>
  </tr>
</table>

---

## Highlights

| Highlight | Detail |
|---|---|
| **Shipped a Telegram app end to end** | [couple-habit](https://github.com/itvladis/couple-habit): Figma design, React Mini App, bot, API and deploy on Yandex Cloud |
| **A site people use** | [plenka-pics.ru](https://plenka-pics.ru): photo and video sharing without sign-up, EXIF stripped, videos converted to play everywhere |
| **Tools for my freelance work** | [uptime-monitor](https://github.com/itvladis/uptime-monitor): checks client sites concurrently and alerts once per incident, with CI and Docker |
| **Competitive programming** | 191 problems on acmp.ru · 26th in Codeforces Round 1131 (Div. 3) · USACO 2026–27 |

---

## Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=flat-square&logo=css&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## Contact

[vvolf4709@gmail.com](mailto:vvolf4709@gmail.com) · [ORCID 0009-0004-4619-4653](https://orcid.org/0009-0004-4619-4653)
