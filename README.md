<!-- ======================================================= -->
<!--                        HEADER                           -->
<!-- ======================================================= -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:031224,100:00599C&height=220&section=header&text=Arkar%20Chan%20Myae&fontSize=48&fontColor=F5B041&fontAlignY=38&desc=Embedded%20Systems%20%7C%20IoT%20%7C%20Low-Level%20C&descSize=18&descColor=FFFFFF&descAlignY=58&animation=fadeIn" alt="header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=F5B041&center=true&vCenter=true&width=650&lines=Hi,+I'm+Arkar+Chan+Myae+👋;Aspiring+Embedded+Systems+Engineer;IoT+and+Hardware+Enthusiast;Building+with+STM32,+ESP32+and+LoRa;Writing+C+close+to+the+metal" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Arkarchanmyae123&label=Profile+Views&color=F5B041&style=for-the-badge&labelColor=031224" alt="views" />
<img src="https://img.shields.io/github/followers/Arkarchanmyae123?label=Followers&style=for-the-badge&color=00599C&labelColor=031224&logo=github&logoColor=F5B041" alt="followers" />
<img src="https://img.shields.io/badge/Location-Thailand%20%F0%9F%87%B9%F0%9F%87%AD-00599C?style=for-the-badge&labelColor=031224" alt="location" />

</div>

<br/>

<!-- ======================================================= -->
<!--                        ABOUT                            -->
<!-- ======================================================= -->
## 👨‍💻 About Me

I'm an aspiring Embedded Systems Engineer who loves hardware, microcontrollers, and low-level programming.I learn by building: reading datasheets, wiring up boards, and debugging at the register level.Ultimately, my goal is to build robust, low-power firmware that solves real-world problems especially in IoT and disaster prevention.

<table>
<tr>
<td>

🔭 **Currently building**<br/>
FLash Flood Warning System (STM32 + LoRa SX126x)(LoRa mesh hop network)

🌱 **Currently learning**<br/>
Embedded system architecture, FreeRTOS, and register-level hardware debugging

</td>
<td>

🎯 **Goals**<br/>
Mastering embedded system architectures to design robust, real-time IoT solutions for critical real-world challenges.

💬 **Ask me about**<br/>
STM32, ESP32, IoT, STM32-HAL, STM32-LL, 42 curriculum

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png">

<!-- ======================================================= -->
<!--                        SKILLS                           -->
<!-- ======================================================= -->
## 🛠️ Skills & Technologies

**Languages**<br/>
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Ada](https://img.shields.io/badge/Ada-000000?style=for-the-badge)

**Hardware / Microcontrollers**<br/>
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

**Protocols & Interfaces**<br/>
![LoRa](https://img.shields.io/badge/LoRa-F5B041?style=for-the-badge&labelColor=031224)
![SPI](https://img.shields.io/badge/SPI-00599C?style=for-the-badge&labelColor=031224)
![I2C](https://img.shields.io/badge/I2C-00599C?style=for-the-badge&labelColor=031224)
![UART / USART](https://img.shields.io/badge/UART%20%2F%20USART-00599C?style=for-the-badge&labelColor=031224)
![DMA](https://img.shields.io/badge/DMA-03234B?style=for-the-badge&labelColor=031224)


**Tools & Platforms**<br/>
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5B041?style=for-the-badge&logo=platformio&logoColor=031224)
![STM32CubeMX](https://img.shields.io/badge/STM32CubeMX-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00599C?style=for-the-badge&logo=freertos&logoColor=white)
![Make](https://img.shields.io/badge/Make-031224?style=for-the-badge&logo=gnu&logoColor=white)
<br/><br/>
<img src="https://skillicons.dev/icons?i=git,github,linux,vim&theme=dark" alt="tools" />


<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png">



<!-- ======================================================= -->
<!--                      PROJECTS                           -->
<!-- ======================================================= -->
## 🚀 My Projects

| Status | Project | Tech |
|:---:|---|---|
| ✅ Completed | **IoT Hydroponic System**: automates watering, nutrients and monitoring for plants | ESP32, Sensors, IoT |
| 🔧 In Progress | **Flood Disaster Warning System**: long-range, low-power flood alerts | STM32, LoRa (SX126x), SPI |
| 🔍 Always | Hardware-software integration and exploring new MCU architectures | C, HAL, Datasheets |

<details>
<summary><b>📡 Flood Disaster Warning System: how it works (click to expand)</b></summary>

<br/>

A remote sensor node measures water level and sends it over **LoRa** to a gateway, which raises an alert when a threshold is crossed. LoRa makes it possible to cover rural river areas with no Wi-Fi or cellular coverage, using very little power.

```mermaid
flowchart LR
    A[Water Level Sensor] --> B[STM32 Node]
    B -- SPI --> C[LoRa SX126x]
    C -. LoRa RF .-> D[LoRa Gateway]
    D --> E[Alert: SMS / Buzzer / Cloud]
```

**What I'm working on**
- SX126x driver in C on STM32 HAL (SetStandby, SetPacketParams, SetTx, IRQ handling on DIO1)
- Reliable TX/RX with BUSY-pin handling and timeouts
- Low-power sleep between measurements

</details>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png">

<!-- ======================================================= -->
<!--                      42 SCHOOL                          -->
<!-- ======================================================= -->
## <img src="https://upload.wikimedia.org/wikipedia/commons/8/8d/42_Logo.svg" width="26" height="26" /> 42 School Projects

*Learning low-level C programming, system architecture, and manual memory management through the 42 curriculum.*

<div align="center">
<table>
<tr>
<td align="center">
  <a href="https://github.com/Arkarchanmyae123/LIBFT_42">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Arkarchanmyae123&repo=LIBFT_42&hide_border=true&bg_color=031224&title_color=F5B041&icon_color=F5B041&text_color=FFFFFF" alt="Libft" />
  </a>
</td>
<td align="center">
  <a href="https://github.com/Arkarchanmyae123/42_ft_Printf">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Arkarchanmyae123&repo=42_ft_Printf&hide_border=true&bg_color=031224&title_color=F5B041&icon_color=F5B041&text_color=FFFFFF" alt="ft_printf" />
  </a>
</td>
</tr>
<tr>
<td align="center">
  <a href="https://github.com/Arkarchanmyae123/42_fract_ol">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Arkarchanmyae123&repo=42_fract_ol&hide_border=true&bg_color=031224&title_color=F5B041&icon_color=F5B041&text_color=FFFFFF" alt="fract_ol" />
  </a>
</td>
<td align="center">
  <a href="https://github.com/Arkarchanmyae123/42_push_swap">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Arkarchanmyae123&repo=42_push_swap&hide_border=true&bg_color=031224&title_color=F5B041&icon_color=F5B041&text_color=FFFFFF" alt="push_swap" />
  </a>
</td>
</tr>
</table>

<a href="https://github.com/Arkarchanmyae123/LIBFT_42"><img src="https://img.shields.io/badge/LIBFT-00599C?style=for-the-badge&logo=42&logoColor=F5B041&labelColor=031224" alt="Libft"/></a>
<a href="https://github.com/Arkarchanmyae123/42_ft_Printf"><img src="https://img.shields.io/badge/FT_PRINTF-00599C?style=for-the-badge&logo=42&logoColor=F5B041&labelColor=031224" alt="ft_printf"/></a>
<a href="https://github.com/Arkarchanmyae123/42_fract_ol"><img src="https://img.shields.io/badge/FRACT__OL-00599C?style=for-the-badge&logo=42&logoColor=F5B041&labelColor=031224" alt="fract_ol"/></a>
<a href="https://github.com/Arkarchanmyae123/42_push_swap"><img src="https://img.shields.io/badge/PUSH__SWAP-00599C?style=for-the-badge&logo=42&logoColor=F5B041&labelColor=031224" alt="push_swap"/></a>
</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png">

<!-- ======================================================= -->
<!--                  LEADERSHIP & COMMUNITY                 -->
<!-- ======================================================= -->
## 🌟 Leadership & Community

- 🎓 **Founder, [Impact Education](https://impactedu.impacteducation650.workers.dev/)**: an initiative dedicated to making learning accessible to everyone.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png">

<!-- ======================================================= -->
<!--                        STATS                            -->
<!-- ======================================================= -->
## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Arkarchanmyae123&show_icons=true&hide_border=true&bg_color=031224&title_color=F5B041&icon_color=F5B041&text_color=FFFFFF&ring_color=00599C" alt="stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Arkarchanmyae123&layout=compact&hide_border=true&bg_color=031224&title_color=F5B041&text_color=FFFFFF" alt="top langs" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Arkarchanmyae123&theme=dark&background=031224&ring=F5B041&fire=F5B041&currStreakNum=FFFFFF&currStreakLabel=F5B041&stroke=00599C&hide_border=true" alt="streak" />

</div>

<!-- SNAKE ANIMATION: .github/workflows/snake.yml ကို run ပြီးမှ ပေါ်ပါမယ် -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arkarchanmyae123/Arkarchanmyae123/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Arkarchanmyae123/Arkarchanmyae123/output/github-snake.svg" />
    <img alt="snake animation" src="https://raw.githubusercontent.com/Arkarchanmyae123/Arkarchanmyae123/output/github-snake-dark.svg" />
  </picture>
</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png">

<!-- ======================================================= -->
<!--                        CONTACT                          -->
<!-- ======================================================= -->
## 📫 Let's Connect

I'm open to **collaborations, mentorship, and learning opportunities** in embedded systems and IoT. Feel free to reach out.

<div align="center">

<a href="mailto:ark307471@gmail.com">
  <img src="https://img.shields.io/badge/Email-ark307471%40gmail.com-000080?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://www.linkedin.com/in/arkar-chan-myae-2b976a231/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://impactedu.impacteducation650.workers.dev/">
  <img src="https://img.shields.io/badge/Impact%20Education-F5B041?style=for-the-badge" alt="Impact Education" />
</a>

<br/><br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&pause=2000&color=F5B041&center=true&vCenter=true&width=700&lines=Thanks+for+visiting+my+profile+%E2%9D%A4%EF%B8%8F" alt="thanks" />

<br/>
<div align="center">
  <i>"The sun is the same in a relative way but you're older,<br/>Shorter of breath and one day closer to death."</i><br/><br/>
  <a href="https://www.youtube.com/@pinkfloyd" target="_blank">
    <img src="https://img.shields.io/badge/Listen_to_Pink_Floyd-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
</div>
<br/>

<div align="center">
  <img src="prism.svg" width="140" alt="Pink Floyd Prism" />
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00599C,100:031224&height=120&section=footer" alt="footer" />

</div>
