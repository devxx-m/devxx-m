<img width="1200" height="320" alt="banner" src="https://github.com/user-attachments/assets/1e9834d4-db0b-475b-8ed0-522704f5d802" />
[README (2).md](https://github.com/user-attachments/files/34979934/README.2.md)
<p align="center">
  <img src="./banner.svg" alt="Animated banner"<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="1200" height="320" role="img" aria-label="Animated IoT network banner" xmlns:c2pa="http://c2pa.org/manifest">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#060a14"/>
      <stop offset="1" stop-color="#101c3a"/>
    </linearGradient>

    <linearGradient id="accent" x1="0" y1="0" x2="0.5" y2="0" spreadMethod="reflect">
      <stop offset="0" stop-color="#00e5ff"/>
      <stop offset="0.5" stop-color="#7c4dff"/>
      <stop offset="1" stop-color="#ff3d9a"/>
      <animateTransform attributeName="gradientTransform" type="translate"
        values="-0.5 0; 0.5 0; -0.5 0" dur="7s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="sweep" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="0.5" stop-color="#ffffff" stop-opacity="0.07"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>

    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" fill="none" stroke="#1b2a4e" stroke-width="1"/>
    </pattern>

    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <clipPath id="card"><rect width="1200" height="320" rx="18"/></clipPath>

    <clipPath id="type">
      <rect x="60" y="222" height="34" width="0">
        <animate attributeName="width" values="0;520;520;0" keyTimes="0;0.4;0.9;1"
          dur="9s" repeatCount="indefinite"/>
      </rect>
    </clipPath>
  </defs>

  <g clip-path="url(#card)">
    <rect width="1200" height="320" fill="url(#bg)"/>
    <rect width="1200" height="320" fill="url(#grid)" opacity="0.55"/>

    <!-- network links -->
    <g stroke="#2d5bd1" stroke-width="1.6" fill="none" stroke-dasharray="6 8" opacity="0.8">
      <path d="M760 70 L890 190"><animate attributeName="stroke-dashoffset" from="0" to="-28" dur="1.2s" repeatCount="indefinite"/></path>
      <path d="M890 190 L1020 80"><animate attributeName="stroke-dashoffset" from="0" to="-28" dur="1.2s" repeatCount="indefinite"/></path>
      <path d="M1020 80 L1120 215"><animate attributeName="stroke-dashoffset" from="0" to="-28" dur="1.2s" repeatCount="indefinite"/></path>
      <path d="M890 190 L940 285"><animate attributeName="stroke-dashoffset" from="0" to="-28" dur="1.2s" repeatCount="indefinite"/></path>
      <path d="M940 285 L1120 215"><animate attributeName="stroke-dashoffset" from="0" to="-28" dur="1.2s" repeatCount="indefinite"/></path>
    </g>

    <!-- data packets -->
    <g filter="url(#glow)">
      <circle r="4.5" fill="#00e5ff"><animateMotion dur="2.6s" repeatCount="indefinite" path="M760 70 L890 190"/></circle>
      <circle r="4.5" fill="#7c4dff"><animateMotion dur="2.2s" begin="0.8s" repeatCount="indefinite" path="M890 190 L1020 80"/></circle>
      <circle r="4.5" fill="#ff3d9a"><animateMotion dur="2.4s" begin="1.3s" repeatCount="indefinite" path="M1020 80 L1120 215"/></circle>
      <circle r="4.5" fill="#00e5ff"><animateMotion dur="2.0s" begin="0.4s" repeatCount="indefinite" path="M890 190 L940 285"/></circle>
      <circle r="4.5" fill="#7c4dff"><animateMotion dur="2.8s" begin="1.0s" repeatCount="indefinite" path="M940 285 L1120 215"/></circle>
    </g>

    <!-- nodes with pulse rings -->
    <g fill="none" stroke="#00e5ff">
      <circle cx="760" cy="70" r="9"><animate attributeName="r" values="9;28" dur="2.4s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.8;0" dur="2.4s" repeatCount="indefinite"/></circle>
      <circle cx="890" cy="190" r="9"><animate attributeName="r" values="9;28" dur="2.4s" begin="0.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.8;0" dur="2.4s" begin="0.5s" repeatCount="indefinite"/></circle>
      <circle cx="1020" cy="80" r="9"><animate attributeName="r" values="9;28" dur="2.4s" begin="1.0s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.8;0" dur="2.4s" begin="1.0s" repeatCount="indefinite"/></circle>
      <circle cx="1120" cy="215" r="9"><animate attributeName="r" values="9;28" dur="2.4s" begin="1.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.8;0" dur="2.4s" begin="1.5s" repeatCount="indefinite"/></circle>
      <circle cx="940" cy="285" r="9"><animate attributeName="r" values="9;28" dur="2.4s" begin="2.0s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.8;0" dur="2.4s" begin="2.0s" repeatCount="indefinite"/></circle>
    </g>
    <g fill="#0a1226" stroke="url(#accent)" stroke-width="2.5" filter="url(#glow)">
      <circle cx="760" cy="70" r="9"/>
      <circle cx="890" cy="190" r="11"/>
      <circle cx="1020" cy="80" r="9"/>
      <circle cx="1120" cy="215" r="9"/>
      <circle cx="940" cy="285" r="9"/>
    </g>

    <!-- text -->
    <text x="60" y="150" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="66" font-weight="800" letter-spacing="1" fill="url(#accent)">YOUR NAME</text>
    <text x="62" y="196" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="24" fill="#a9bbe0" letter-spacing="2">IoT ENGINEERING STUDENT  ·  ISTCOM</text>
    <g clip-path="url(#type)">
      <text x="62" y="246" font-family="'Courier New', Consolas, monospace" font-size="19" fill="#00e5ff">&gt; sensors. firmware. connected things.</text>
    </g>

    <!-- light sweep -->
    <rect x="-300" y="0" width="300" height="320" fill="url(#sweep)">
      <animateTransform attributeName="transform" type="translate" values="0 0; 1500 0" dur="7s" repeatCount="indefinite"/>
    </rect>
  </g>

  <rect x="1" y="1" width="1198" height="318" rx="17" fill="none" stroke="url(#accent)" stroke-width="1.5" opacity="0.55"/>
<metadata><c2pa:manifest>AAAWgmp1bWIAAAAeanVtZGMycGEAEQAQgAAAqgA4m3EDYzJwYQAAABZcanVtYgAAAEdqdW1kYzJtYQARABCAAACqADibcQN1cm46YzJwYToyOTljNzIxNS0zODFhLTRlODctYTdjNC0xZmY4ZDVkMGJhMTYAAAADl2p1bWIAAAApanVtZGMyYXMAEQAQgAAAqgA4m3EDYzJwYS5hc3NlcnRpb25zAAAAALxqdW1iAAAARGp1bWRjYm9yABEAEIAAAKoAOJtxE2MycGEuaW5ncmVkaWVudC52MwAAAAAYYzJzaI/aXI8aWD4zS9tDznSPL34AAABwY2JvcqNpZGM6Zm9ybWF0bWltYWdlL3N2Zyt4bWxqaW5zdGFuY2VJRHgseG1wOmlpZDo1MDg2ZjE5Yi02MTM0LTQyNWEtYjNiNi00MjMzOWJiZjQwZDRscmVsYXRpb25zaGlwaHBhcmVudE9mAAAB4mp1bWIAAABBanVtZGNib3IAEQAQgAAAqgA4m3ETYzJwYS5hY3Rpb25zLnYyAAAAABhjMnNoQ9SpFdPtFWJmhq0tdL+vcQAAAZljYm9yomdhY3Rpb25zgqJmYWN0aW9ua2MycGEub3BlbmVkanBhcmFtZXRlcnOha2luZ3JlZGllbnRzgaJjdXJseC1zZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmluZ3JlZGllbnQudjNkaGFzaFggid2qzMYwTMKeLZsyKklsxqbwtStv2dAZ+g0bO56bIGOkZmFjdGlvbngdY29tLmFudGhyb3BpYy5jbGF1ZGUucHJvdmlkZWRqcGFyYW1ldGVyc6F4H2NvbS5hbnRocm9waWMub3JpZ2luLWNvbmZpZGVuY2VndW5rbm93bmtkZXNjcmlwdGlvbnhmQ2xhdWRlIHByb3ZpZGVkIHRoaXMgZmlsZSBhdCB0aGUgcmVxdWVzdCBvZiBhIHVzZXIgYW5kIG1heSBoYXZlIGNyZWF0ZWQgb3IgbW9kaWZpZWQgdGhlIGZpbGUgY29udGVudHMubXNvZnR3YXJlQWdlbnShZG5hbWVmQ2xhdWRlcmFsbEFjdGlvbnNJbmNsdWRlZPUAAADIanVtYgAAAEBqdW1kY2JvcgARABCAAACqADibcRNjMnBhLmhhc2guZGF0YQAAAAAYYzJzaHz47BEmcRuVkMIe6SU7PlgAAACAY2JvcqVjYWxnZnNoYTI1NmNwYWRMAAAAAAAAAAAAAAAAZGhhc2hYIO/ZIL5w6LydwyYwtI+3AXJnKULzrfGP8PmkKy1vKyXZZG5hbWVuanVtYmYgbWFuaWZlc3RqZXhjbHVzaW9uc4GiZXN0YXJ0GRc5Zmxlbmd0aBkeBAAAAj5qdW1iAAAAJ2p1bWRjMmNsABEAEIAAAKoAOJtxA2MycGEuY2xhaW0udjIAAAACD2Nib3KlY2FsZ2ZzaGEyNTZpc2lnbmF0dXJleE1zZWxmI2p1bWJmPS9jMnBhL3VybjpjMnBhOjI5OWM3MjE1LTM4MWEtNGU4Ny1hN2M0LTFmZjhkNWQwYmExNi9jMnBhLnNpZ25hdHVyZWppbnN0YW5jZUlEeCx4bXA6aWlkOjgwN2MzNWYwLWZlMWMtNDE3MS1iOTk1LWMwYTllZGJlMjA1M3JjcmVhdGVkX2Fzc2VydGlvbnODomN1cmx4LXNlbGYjanVtYmY9YzJwYS5hc3NlcnRpb25zL2MycGEuaW5ncmVkaWVudC52M2RoYXNoWCCJ3arMxjBMwp4tmzIqSWzGpvC1K2/Z0Bn6DRs7npsgY6JjdXJseCpzZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmFjdGlvbnMudjJkaGFzaFgg63MT6qJl7c8bi5kcw7ru8u0+xLOjtivnay40GXThmZOiY3VybHgpc2VsZiNqdW1iZj1jMnBhLmFzc2VydGlvbnMvYzJwYS5oYXNoLmRhdGFkaGFzaFggNVj0kUpRgXrRU8JmpJqrO0cp1ETAqHp58U8eHjwitIp0Y2xhaW1fZ2VuZXJhdG9yX2luZm+jZG5hbWVvQW50aHJvcGljIEZpbGVzZ3ZlcnNpb25lMS4wLjBrc3BlY1ZlcnNpb25lMi40LjAAABA4anVtYgAAAChqdW1kYzJjcwARABCAAACqADibcQNjMnBhLnNpZ25hdHVyZQAAABAIY2JvctKEWQISogEmGCFZAgowggIGMIIBjaADAgECAhRA5aAK7sI50L64g/oGQgU9Z1UTADAKBggqhkjOPQQDAzBJMRcwFQYDVQQKEw5BbnRocm9waWMsIFBCQzEuMCwGA1UEAxMlQW50aHJvcGljIENvbnRlbnQgQ3JlZGVudGlhbHMgUm9vdCBDQTAeFw0yNjA4MDcxODQzNTZaFw0yODA4MDYxOTQzNTZaMEQxFzAVBgNVBAoTDkFudGhyb3BpYywgUEJDMSkwJwYDVQQDEyBBbnRocm9waWMgQ2xhdWRlIENvbnRlbnQgU2lnbmluZzBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABJh6CmvLUBgFFNU0vUKlOVtE6djd17L5SuwX0LemFisBM3dkd/3cyjxFA3Qo5S46fX0/ihY0VZ7mfb9KF703t5OjWDBWMA4GA1UdDwEB/wQEAwIHgDAVBgNVHSUEDjAMBgorBgEEAYPoXgIBMAwGA1UdEwEB/wQCMAAwHwYDVR0jBBgwFoAUzlHiBIFOZFsj+OPEz5o+nMHXXMIwCgYIKoZIzj0EAwMDZwAwZAIwMXMdFJ4BetLLVY7ORuE9noqbbAZOZn/aArXyTwFAZfKrPzxF2vPoJNf1+UCdg1XGAjBwX1zd9WGqYkqmL5SFqw1QySjr1zJfpJM9+1rdDwSPLMOPOjKuiXjoU/pUUeG9RwmhY3BhZFkNngAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPZYQCACXm1zl4Oq+CKSWG15PMu8sAQCoSoSa281+Xma22TecNdt9n2bUGbqQ1+BJ1cYaVDCeR5CdxLAfJ0lc1R459k=</c2pa:manifest></metadata></svg>
 width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1200&color=00E5FF&center=true&vCenter=true&width=720&lines=Building+the+bridge+between+hardware+and+software;Embedded+C+%C2%B7+Sensors+%C2%B7+Connectivity;Open+to+internships+and+collaboration" alt="Typing animation"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Embedded%20%26%20IoT-00E5FF?style=flat-square&labelColor=0a1226"/>
  <img src="https://img.shields.io/badge/Language-C-7C4DFF?style=flat-square&labelColor=0a1226"/>
  <img src="https://img.shields.io/badge/School-ISTCOM-FF3D9A?style=flat-square&labelColor=0a1226"/>
  <img src="https://img.shields.io/badge/Location-Tunisia-1f6feb?style=flat-square&labelColor=0a1226"/>
</p>

---

## ⚡ Profile

```c
typedef struct {
    const char *name;
    const char *role;
    const char *school;
    const char *focus[3];
    const char *looking_for;
} Engineer;

Engineer me = {
    .name        = "[Your Full Name]",
    .role        = "IoT Engineering Student",
    .school      = "ISTCOM, Tunisia",
    .focus       = { "Embedded systems", "Sensor networks", "Connected devices" },
    .looking_for = "[Summer 2027 internship in IoT / embedded]"
};
```

---

## 🧰 Stack

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
  <img src="https://img.shields.io/badge/Espressif-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white"/>
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

> Edit this row to match your CV: keep only what you can actually discuss in an interview.

---

## 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>[Project 1 name]</h3>
      <p>[One line: what it does and why it matters.]</p>
      <p><b>Stack:</b> [hardware · language · protocol]<br/>
         <b>My role:</b> [what you built]<br/>
         <b>Result:</b> [outcome / demo]</p>
      <a href="#">View repository →</a>
    </td>
    <td width="50%" valign="top">
      <h3>[Project 2 name]</h3>
      <p>[One line: what it does and why it matters.]</p>
      <p><b>Stack:</b> [hardware · language · protocol]<br/>
         <b>My role:</b> [what you built]<br/>
         <b>Result:</b> [outcome / demo]</p>
      <a href="#">View repository →</a>
    </td>
  </tr>
</table>

---

## 🎓 Education & experience

| Period | What | Where |
|---|---|---|
| [20XX – present] | [Degree / program] | ISTCOM, Tunisia |
| [Dates] | [Internship / role] | [Organization] |

---

## 🛣️ Roadmap

- [ ] Master C fundamentals (strings, pointers, structs, files)
- [ ] Ship a terminal project: Hangman, then a sensor data logger
- [ ] Build a first hardware project on Arduino / ESP32
- [ ] Add MQTT and send sensor data to a dashboard
- [ ] Land a summer 2027 internship

---

## 📡 Let's connect

<p>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer" width="100%"/>
