<h1> Hi there 👋 You can call me James<h5>(if you want)</h5> </h1>
<style>
    body {
      margin: 0;
      padding: 0;
      overflow: hidden;
      background: #f0f0f0;
    }
    .dog {
      position: absolute;
      width: 100px;
      height: auto;
      animation: moveDog 4s linear infinite alternate;
    }
    @keyframes moveDog {
      0% {
        left: 0;
        transform: scaleX(1); /* quay mặt về bên phải */
      }
      100% {
        left: calc(100% - 100px);
        transform: scaleX(-1); /* quay mặt về bên trái */
      }
    }
  </style>
  <img class="dog" src="./idle-pixel.gif" alt="Dog">
<!--
**Tamekhanh/Tamekhanh** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
