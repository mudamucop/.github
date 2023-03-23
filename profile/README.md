<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/mudamucop">
    <img src="https://user-images.githubusercontent.com/44289776/227314664-3b61fa2d-3f41-4a86-b728-89bae820c078.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">muDamu</h3>

  <p align="center">
    University project org. for a AI powered health software. Made in 2022 by <a href="https://github.com/AitorAstorga">Aitor Astorga Saez de Vicuña</a>, <a href="https://github.com/danmazkih">Danel Mazkiaran Hernandez</a>, <a href="https://github.com/aitororuna">Aitor Oruna Rodriguez</a> and <a href="https://github.com/IbaiRodriguez">Ibai Rodriguez Ruiz</a>
    <br />
    <a href="https://github.com/mudamucop"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://gitlab.com/m11137/mudamu">Original repo in GitLab</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

University proyect with AI about a communication system that allows the symptoms of patients to doctors and predicts possible diseases. All the documentation from the project is available in spanish:

* [Memoria muDamu.pdf](https://drive.google.com/file/d/1IAM3pRX99bEuWPrrH0svgL1GBIQnF2Qc/view?usp=sharing)
* [Anexo I. Análisis de riesgos empresariales.pdf](https://drive.google.com/file/d/1ONU_C--75qDSqa_IN2f-REEnxsd66hBA/view?usp=sharing)
* [Anexo II. Análisis de riesgos.pdf](https://drive.google.com/file/d/1fVRszTYaFhQLtcLVLCQy_mkIPo56qvoV/view?usp=sharing)
* [Anexo III. Análisis de riesgos residuales.pdf](https://drive.google.com/file/d/1S9fq542mSczzD9C4r6Pwd_c9pf_Adcmf/view?usp=sharing)
* [Anexo IV. Plan de viabilidad.pdf](https://drive.google.com/file/d/1OCuG1VxyuEvM2-WMdM2wFSK2tQCkMdtz/view?usp=sharing)
* [Anexo IX. Análisis estático y mejoras.pdf](https://drive.google.com/file/d/1BIX-B85s2VpV9MZSkupipj4JI8i3H6cW/view?usp=sharing)
* [Anexo V. Porfolio de servicios.pdf](https://drive.google.com/file/d/1sGxU4mSglLubvHxuyPFb859pkpcVNa_z/view?usp=sharing)
* [Anexo VI. SLA.pdf](https://drive.google.com/file/d/1EdnxmUTMJEE95iYth0IQglY1XKdSLVMu/view?usp=sharing)
* [Anexo VII. Proactivanet.pdf](https://drive.google.com/file/d/1IMUSMCqTnvMyAsefOV2RyJFTOHUfZzQ0/view?usp=sharing)
* [Anexo VIII. Paralelización de CSV.pdf](https://drive.google.com/file/d/1nMooPUee8zT5qmJm8z9BsB3PUGQmfqHi/view?usp=sharing)
* [Anexo X. Test de seguridad TLS.pdf](https://drive.google.com/file/d/1nMooPUee8zT5qmJm8z9BsB3PUGQmfqHi/view?usp=sharing)
* [Anexo XI.Factura.xlxs](https://docs.google.com/spreadsheets/d/1SuE7a3ppquz_tZZ2iZScp8I7NUMjNv1-/edit?usp=sharing&ouid=106300472442980693433&rtpof=true&sd=true)

There are 5 different repositories:

(this project is being migrated from GitLab, find the original project in [https://gitlab.com/m11137/mudamu](https://gitlab.com/m11137/mudamu))
* mudamu_pacientes: It is the functional version of the patients web page. The Jenkins service detects changes to it and automatically deploys them as a patient web service.
* RabbitMQ Workers: Used to manage RabbitMQ test versions for workers. The final version is integrated into web services.
* mudamu_workers: It is the functional version of the workers web page, the branch that Jenkins listens to deploy as a workers web service.
* PatientRabbit: It is used to manage test versions of RabbitMQ for patients. The final version is integrated into web services.
* mudamu_mysql: It is the functional version of the database API. Jenkins listens for updates in it to deploy it as a web service when it receives them.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

Major frameworks/libraries used:

* ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
* ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
* ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
* ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
* ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
* ![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black)
* ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
* ![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
* ![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Aitor Astorga Saez de Vicuña - a.astorga.sdv@gmail.com
* [![LinkedIn][linkedin-shield]][linkedin-url-aitor]

Danel Mazkiaran Hernandez - danel.mazkiaran@gmail.com
* [![LinkedIn][linkedin-shield]][linkedin-url-danel]

Aitor Oruna Rodriguez

Ibai Rodriguez Ruiz

Project Link: [https://github.com/mudamucop](https://github.com/mudamucop)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [markdown-badges](https://github.com/Ileriayo/markdown-badges#table-of-contents)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/.svg?style=for-the-badge
[contributors-url]: https://github.com/
[forks-shield]: https://img.shields.io/github/forks/
[forks-url]: https://github.com/
[stars-shield]: https://img.shields.io/github/stars/
[stars-url]: https://github.com/
[issues-shield]: https://img.shields.io/github/issues/
[issues-url]: https://github.com/
[license-shield]: https://img.shields.io/github/license/mudamucop/.github.svg?style=for-the-badge
[license-url]: https://github.com/mudamucop/.github/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url-aitor]: https://linkedin.com/in/aitor-astorga-saez-de-vicuña
[linkedin-url-danel]: https://linkedin.com/in/danel-mazkiaran-hernandez-67a970248
