### Hi there 👋

<div id="imgratio">
    <img
        id="animatedImage"
        style="border-radius: 50%;"
        src="https://cdn4.cdn-telegram.org/file/YHPAWvKzQXOsXklfM4-w2pVy4vXSVpJaMAaTdMzoJc47udpvWhHvjv9dohgRoMH5QKnPYhS4SNDl1C_tfepi4wuxmfP-Cqwr5VVKP8BLTe3vLrWscYCKAWQJ_14mYoIAtDVSx9l5taBLMiqzphcQFNl62sStJk7Q7Sr6szXLbNfvNKdiwXJspGoW0nTup8Ls3nS9bCLsbEQBUPG4vFozNAndgsjbuFbugQeO53Kx3Z69sqHcm1IvjcaTVhDBUtmoHLFhlblxvlcnWmAG2Ge-RAk1iN8gXEWxUeu1CjmgTfn6ZNQ5b3Wrvr3FwI7em5VMwo2myN0pYixMY5USwaWdQw.jpg"></div>

    <script>
        const image = document.getElementById('animatedImage');

        let rotation = 0;
        const rotateImage = () => {
            rotation = (rotation + 1) % 360;
            image.style.transform = `rotate(${rotation}deg)`;
            requestAnimationFrame(rotateImage);
        };
        rotateImage();
    </script>

<!--
**StoneZol/StoneZol** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
