<template>
  <div class="portfolio">
    <div class="card">
      <div class="photo">
        <img src="https://media.licdn.com/dms/image/D4D03AQGa3Oa8-92X5g/profile-displayphoto-shrink_400_400/0/1673660575017?e=1689206400&v=beta&t=DHYt8JsIwNtAFwLofPIFMhaHsKCK72saVEw7qkhoj1U" alt="Foto">
          <h2>Guilherme Santos</h2>
          <h4 class="destak">Desenvolvedor Backend</h4>
            <div class="icons">
              <a href="https://github.com/guilherme-se" target="_blank"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                <rect width="40" height="40" fill="url(#pattern6)"/>
                <defs>
                <pattern id="pattern6" patternContentUnits="objectBoundingBox" width="1" height="1">
                <use xlink:href="#image0_1_43" transform="scale(0.01)"/>
                </pattern>
                <image id="image0_1_43" width="100" height="100" xlink:href="data:image/png;base64,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"/>
                </defs>
                </svg></a>

                <a href="https://www.linkedin.com/in/guilherme-santos-espindula/" target="_blank"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                <rect width="40" height="40" fill="url(#pattern7)"/>
                <defs>
                <pattern id="pattern7" patternContentUnits="objectBoundingBox" width="1" height="1">
                <use xlink:href="#image0_1_45" transform="scale(0.01)"/>
                </pattern>
                <image id="image0_1_45" width="100" height="100" xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAABkCAYAAABw4pVUAAAAAXNSR0IArs4c6QAABHVJREFUeJztnU2IXjUUhp9M1UpV1MoUxIJ/VSsulFbQUXChG0XBGXTRjQu3ikWRasVZq7UbQUToQgRBEARn3Cku3AiKPyiUgrRawUFBRUEqpcrM6yJXQZn5bpKb3Mn97nngg1mcnHOSl0ySm9wbMAzDMAzDMAzD6BeXUkjSOcACcD+wB9gJnJcxryHyB7ACfAEsAUvOuT9jnUQLIukB4EXgqtiyI+Mb4IBz7p2YQsGCSNoCHAKejExs7BwGDjrn1kKMz4pwbGKkcQAQ8HSIcVAPaf5Nvd0hKQMWnHNLbUatgjQD+DHg6hxZjZiTwO62gX4mwNECJkYOrsTPSicSIsh891yMhiyC7M2QiOG5uc0gRJBLMyRieC5rMwgZ1JUnFwPAOTexzUN6iNEjJkhlmCCVYYJUhglSGX0Icgx4BLgW2Nb8rgMeA473EH9QlJ72vgo8vtHzG0nnAkeAhzrEGBRt096SgrwH3OOcm1i+2Wf5CLglMc6g2Mx1yAttYgA451aB5wrmMShK9pALnHOnQgwlXQz8mhhnUGxmD9kSYRu0vTkGSgpye4TtXLEsBkZJQRabAXsikmaAZwrmMShKCjIHvCFp20YGkrbip713FMxjUPTx+P0k8DLwfvM3wOXAncB+/IJxNGzmOsRYB9sPGRgmSGWYIJVhglSGCVIZMYeto2ibTfyfjWZzufwAR4EPgA+BE8AvzW87MIs/onMXcDdwY0zMXlEiueJ09LMm6U1Jt0b62C3pdUmrqfXPVZ+2ChYLXMDPV5I67bFIuk3Sd6ltkKM+kypYNHBmP6/J70Z2RtIlkj5JbYeu9VkvoV4CZ/TzkqSkdycn+LxQ0tHUtoipT7FHJ5s4qM+Evj4W6XcX8CUdX24d3aOTEmI0fk8AiyV8/ydOm8HQekhJ5N8m+xq4ItXH6HpISZrjTK8UjdFmMC09RH6jbNU5d6ajn1ngR+LODPzLqHuIpDlJb0n6Df+lhdOSViQdkXRDik/n3M/Ax1kTjaHU9C40Toe8FzV5pX1G0qOJvp/vq13WC95L4JwVkPRwYJprkvYl+H+wVLtM3Rgi6SL8d0a2Bxb5CbjGOfd7RIw9wOcxef3DGMeQfYSLAbCjKRPDSqR9MNMoyL0JZe6LtA86IpvCNAqSspdxU6T96YQYQUyjIDsSyszGGIec6k9lGgXZmlAmy6P6HEyjIIPGBKkME6QyTJDKMEEqwwSpDBOkMkyQyjBBKsMEqQwTpDJMkMowQSrDBKkME6QyTJDKMEEqwwSpDBOkMuxbJz0zxoNyg8YEqQwTpDJCBCl2bHKEtB7oDhHkhwyJGJ7WtgwR5LMMiRieT9sMQgRZzpCI4Xm3zSBkHXI2/oaDXTkyGjHfAtd3vljSOfcX8FSurEaKgCdCrvMOmvY2V1Af7prViDnknGv9dwVx65CD+HvUjXCEv2X72dACKRfcz+N7i40pkzmOv+A+alKU9JWEZqCfx9/tuhfYCZyf4muKOAV8j387dxlYbsZfwzAMwzAMwzCMqvkbesIo6OuoO2QAAAAASUVORK5CYII="/>
                </defs>
                </svg></a>

                <a href="mailto:guilhermesantosespind@gmail.com"><svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                <rect width="40" height="40" fill="url(#pattern8)"/>
                <defs>
                <pattern id="pattern8" patternContentUnits="objectBoundingBox" width="1" height="1">
                <use xlink:href="#image0_1_47" transform="scale(0.01)"/>
                </pattern>
                <image id="image0_1_47" width="100" height="100" xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAABkCAYAAABw4pVUAAAAAXNSR0IArs4c6QAABQNJREFUeJzt29+LVGUcx/H3NyuNxShKCwpSKOgH1UUEFVpum9VCGmhRRD+o7KbUiAT7E5JIxFKiMogyMlQwZYONylWzoLoooi4K2YuChQKjlOyHfbo4s7jKnGeeM+fMzHNmvy/wZuc7zzyez8yccz6u4JxzzjnnnHPOOeecc84555xzzrlmrNWApHnAh8Clnd9OXxsHbjezH0JDp7VaxczGgYXANxVtbDr6HljYKgyICATAzCaARcBnJTc2HX0F3GxmP8UMRwUCYGaHgcVkX18uzhhwq5n9GvuEkwKRtCA0bGZHgaXArra2N73sAu40s99DQ6ce81M/IaslbZKU+8kxs2PAcuCNdnc6DbwD3Ns4Vk1JMknrgdVTf97swD8JvCXpjLzFzOw4sAJY395++9pm4CEz+ydvQNIM4HXgmVMfy/skPADslHRW3qJmJjN7Fniu2H772joze8rM/ssbkDQT2AY81uzx0En9LuADSWeHdmBm64CVQO4mpgEBa8ws+OaUNADsJvvKb6rVVdYtwMeSzg8Nmdkm4BHg3xbr9aPjwBNm9mJoSNK5ZFeoi0NzMZe91wH7JF0cGjKzt4FlQO6JrA/9DdxvZltCQ5IuBPYCN7ZaMPY+5ArggKTLQkNmthsYBv6IXLfOjgJLzGx7aEjSfGA/cE3MotE3hsAlwH5J14aGzGwvMARE3wzV0G9kvdRoaEjSlWRhRPeARQIBuADYK+mm0JCZfUF2/vm54Pp1MAEsMrODoSFJ15PdqV9UZPGigQCcA4xKuiM0ZGbfAQuAH9t4jVSNk/VSX4eGJA0CHwHBi6Fm2gkEYAB4X9I9oaE+a4qjGltJS4ERYHY7L9JuIABnAu9Kejw01CdN8ZdENLaSHgR2ALPafaEygQDMAF6TtCY0VPOmeAwYatXYSloJvAmcXubFygYC2b86viDp+eBQ1hQvIXsH1cUeYDiisV0LvEQFx7OKQCatjWiK/wLuox5N8VZgmZn9mTcwpbENvhmLqDIQ6J+meDPwcLuNbRlVBwL1b4pjG9v3yGlsy+hEIFDPprhoY7usE5voVCBwoimeExpKpCmutLEto5OBQNYUjyXeFBdpbMeIaGzL6HQgkHZTXLSxvbrTG+pGIJBmU3yYDjW2ZXQrEEirKZ4ABiMb230UbGzL6GYgkEZTXLSxPa8De8jV7UCgt01xVxrbMnoRCJxoileEhipuirvW2JbRq0Aga4pf7VJT3NXGtoxeBgLdaYp30+XGtoxeBzKpU03xVmB5txvbMlIJBKpvimMb2y1U3NiWkVIgkDXF2yXlnlCnNMWrgCNNRo4AqyIa21nATuDRknuuVM9OXgFLgRFJd5tZbo1iZi9L2kb2e7JXNX78LbAj4uQ9m+z/bwxWtOfKpBgIZAfqE0nDZvZL3lDjsVeKLNxobEeAG8ptsTNS+8qaKqopLmJKY5tkGJB2IJA1xfsklS72GmscpAuNbRmpBwIwH/hc0nC7C0gaAj5trJW0OgQCWcG3R9IGSXNjnyRprqQNwCgQ/bxeqksgkO31aeCQpI2Sbmv8ssFJJM1sPLYRONR4Tm3+nqleZYUMkN2DrAKOSRoHJq/E5gDz6FExWIU6BjLVLODyxp++UJuP8nThgSTGA0mMB5IYDyQxHkhiPJDEeCCJ8UAS44EkxgNJjAeSGA8kMR5IYjwQ55xzzjnnnHPOOeecc84555xzztXC/x5LBEtitN7TAAAAAElFTkSuQmCC"/>
                </defs>
                </svg></a>
            </div>
      </div>
      <div class="content">
        <h3 class="destak">Sobre</h3>
        <p> 👋 Ola, meu nome é Guilherme Santos Estudante de Ciência da Computação e Desenvolvedor Backend. Experiência em projetos desafiadores com habilidades em Java, SpringBoot, Python e WebScrapy. Foco em soluções eficientes e escaláveis. Motivado, autodidata, analítico e colaborativo. Em busca de oportunidades inovadoras. 👩‍💻</p>
        <br>
        <h3 class="destak">Tecnologias</h3>
          <div class="icons">
            <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <rect width="60" height="60" fill="url(#pattern0)"/>
            <defs>
            <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0_1_41" transform="scale(0.01)"/>
            </pattern>
            <image id="image0_1_41" width="100" height="100" xlink:href="data:image/png;base64,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"/>
            </defs>
            </svg>


            <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <rect width="60" height="60" fill="url(#pattern1)"/>
            <defs>
            <pattern id="pattern1" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0_2_24" transform="scale(0.01)"/>
            </pattern>
            <image id="image0_2_24" width="100" height="100" xlink:href="data:image/png;base64,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"/>
            </defs>
            </svg>

            
            <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <rect width="60" height="60" fill="url(#pattern2)"/>
            <defs>
            <pattern id="pattern2" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0_1_49" transform="scale(0.01)"/>
            </pattern>
            <image id="image0_1_49" width="100" height="100" xlink:href="data:image/png;base64,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"/>
            </defs>
            </svg>


            <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <rect width="60" height="60" fill="url(#pattern3)"/>
            <defs>
            <pattern id="pattern3" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0_1_59" transform="scale(0.01)"/>
            </pattern>
            <image id="image0_1_59" width="100" height="100" xlink:href="data:image/png;base64,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"/>
            </defs>
            </svg>


            <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <rect width="60" height="60" fill="url(#pattern4)"/>
            <defs>
            <pattern id="pattern4" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0_1_61" transform="scale(0.01)"/>
            </pattern>
            <image id="image0_1_61" width="100" height="100" xlink:href="data:image/png;base64,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"/>
            </defs>
            </svg>


            <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <rect width="60" height="60" fill="url(#pattern5)"/>
            <defs>
            <pattern id="pattern5" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0_1_63" transform="scale(0.01)"/>
            </pattern>
            <image id="image0_1_63" width="100" height="100" xlink:href="data:image/png;base64,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"/>
            </defs>
            </svg>
          </div>
      </div>
    </div>
  </div>
</template>

<style>

p{
  font-weight: 500;
}

.portfolio {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 80vh;
}

.card {
  background-color: #4F709C;
  color: #E4DCCF;
  border-radius: 20px;
  width: 820px;
  padding: 20px;
  display: flex;
}

.destak{
  font-weight:bold;
  color: white;
  margin-bottom: 10px;
}

.icons{
  display: flex;
  justify-content:space-evenly;
}

.content{
  /* background-color: green; */
  display: block;
  margin: 0 auto;
  width: 100%;
}

.photo {
  /* background-color: red; */
  width: 250px;
}

.photo img {
  width: 140px;
  height: 140px;
  max-width: 100%;
  border-radius: 100%;
}

.content {
  width: 50%;
}

@media (max-width: 768px) {

  body{
    width: 100%;
    height: 100%;
  }

  .card{
    display: block;
    width: 100%;
    height: 100%;
  }

  .photo{
    display: block;
    margin: 0 auto;
  }

  .portfolio{
    /* background-color: red; */
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
  }

  .content{
    width: 100%;
  }


  }


</style>
