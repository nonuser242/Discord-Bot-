# 🌟 Sky Discord Bot (App)
<div align="center">
  <h1>🤖 Sky ⭐ #6110</h1>
  <p><i>Bot-ka maamulka server-ka (Moderation), Amniga (Lock & Anti-link), iyo Madadaalada (Fun Commands)</i></p>
  <!-- Badges -->
  <img src="https://img.shields.io/badge/Discord.js-v14-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord.js" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Bot_Status-Active-339933?style=for-the-badge" alt="Status" />
</div>
---
## 🛠️ Sifooyinka Ugu Muhiimsan (Features)
* **🔒 Channel Lock & Unlock:** Amarrada `/lock` iyo `/unlock` oo si degdeg ah loogu xiro ama looga furo channel-ada xilliga dhibaatadu ka dhacdo server-ka.
* **🛡️ Advanced Anti-Link Protection:** 
  * 1-2 Jeer: Tirtirid fariinta + Digniin (Warning).
  * 3-aad: **30 Seconds Timeout** otomaatig ah.
  * In ka badan 3 jeer: Mute/Communication Disabled + Admin Unmute Button.
* **👋 Fun Commands (`/slap`):** Amarrada madadaalada sida tilaabida/oranta (`/slap`) xubnaha kale oo leh GIF iyo fariimo xioso badan.
* **📚 Search /Help System:** Autocomplete Search Menu leh qeybta **Another Problem** oo toos batoon ugu geynaya Profile-ka Admin-ka (`1483111151469465722`).
* **🚚 Advanced Moderation:**
  * `/move` - U rar user kasta channel-ka aad rabto.
  * `/writemsg` - Fariin ka dir magaca bot-ka.
  * `/add-role` & `/remove-role` - Maaree roles-ka xubnaha.
  * `/autorole` - Si otomaatig ah uga sii role xubnaha cusub.
---
## 📜 Amarrada Bot-ka (Slash Commands)
### 🔒 Amniga & Moderation (Security & Mod)

| Amarka | Qeexidda (Description) | Mod Permission |
| :--- | :--- | :--- |
| `/lock` | Ku xir channel-ka si aan fariimo loo dirin | `Manage Channels` |
| `/unlock` | Ka fur xirnaanta channel-ka | `Manage Channels` |
| `/antilink` | Ka shid ama ka dami xakamaynta links-ka (`on`/`off`) | `Administrator` |
| `/move` | U rar user channel kasta (Voice ama Text) | `Move Members` |
| `/add-role` | Sii user role gaar ah | `Manage Roles` |
| `/remove-role` | Ka qaad user role uu leeyahay | `Manage Roles` |
| `/autorole` | Set-up garee role-ka xubnaha cusub | `Administrator` |

### 🎭 Madadaalada & Caawinaada (Fun & Utility)

| Amarka | Qeexidda (Description) |
| :--- | :--- |
| `/slap` | U dir slap (sampabal/dharbaaxo) user kale adoo isticmaalaya GIF |
| `/help` | Search help center (setup, warning, another problem, etc.) |
| `/writemsg` | Ku amr bot-ka inuu fariin gaar ah ka diro channel-ka |
| `/feedback` | Dhiibo fikrad iyo qiimayn (1-10 stars) |
| `/id` | Soo saar ID-ga User-ka ama Role-ka |

---
## 💻 Sida loo kiciyo Bot-ka (Setup)
1. **Install Dependencies:**
   ```bash
   npm install discord.js
