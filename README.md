<!-- BACK TO TOP ANCHOR -->
<a id="readme-top"></a>

<!-- LOGO -->
<div align="center">
  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/oriente">
    <img src="assets/logo/Logo%20Oriente%20JPEG.jpg" alt="Logo" height="140" />
  </a>

  <h1 align="center">Oriente Limpeza, Conservação e Dedetização</h1>

  <p align="center">A Joomla-built corporate site for Grupo Oriente, a Brazilian facilities-services company, showcasing cleaning, conservation, and pest-control offerings alongside lead-capture and recruitment portals.</p>

  <p align="center">// facilities services · cleaning, conservation & pest control</p>

  <br />

  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/oriente"
    ><strong>View it live »</strong></a>
</div>

<br />

<!-- SHIELDS -->
<div align="center">

[![Creator Website][website-shield]][website-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Released][year-shield]][year-url]

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Screenshot][product-screenshot]](https://leonardo-vasconcellos.vercel.app/portfolio/oriente)

<!-- PROJECT INTRO: 260 chars max -->

Corporate site for Grupo Oriente, a Brazilian facilities-services company, built on Joomla to turn cleaning, conservation, and pest-control marketing into an active lead-generation and recruitment channel rather than a static brochure.

<!-- END INTRO -->

Founded in May 2005, Grupo Oriente is a Brazilian facilities-services company built on developing people to deliver conservation, maintenance, cleaning, sanitization, pest control, and temporary staffing/recruitment services. The site was built on Joomla 1.5 with a custom theme and serves as the company's primary commercial touchpoint: prospective clients request quotes ("Faça um orçamento") and site visits directly through the homepage, job candidates apply through a dedicated Recrutamento e Seleção flow, and existing clients self-serve compliance certificates (FGTS, INSS, state tax clearance) without contacting the back office. The "Vantagens" page makes the outsourcing pitch explicit — eliminating labor-law risk, severance costs, equipment/uniform procurement, and absence coverage by delegating those operational burdens to Oriente. This repository preserves that original 2005-era build, running on a Dockerized PHP 5.6/MySQL 5.6 stack matching the original Joomla 1.5.18 deployment.

**Key features:**

<!-- KEY FEATURES -->
### Key Features

- **Lead-generation forms** — quote, recruitment, and visit-request forms wired directly into the company's sales and HR workflows, turning the site into an active lead-generation channel instead of a static brochure
- **Self-service compliance documents** — downloadable client due-diligence paperwork (FGTS, INSS, state tax certificates) on the Certidões and Clientes pages, cutting manual back-office requests for compliance documents
- **Containerized legacy stack** — the original Joomla 1.5 / PHP 5.6 / MySQL 5.6 stack packaged with Docker so a 2010-era CMS can still be reliably run and demoed today, preserving the site and its workflows for archival reference

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SCREENSHOTS -->

## Screenshots

<div align="center" style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;">
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Candidatos.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Candidatos.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Certid%C3%B5es.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Certid%C3%B5es.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Clientes.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Clientes.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Contato.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Contato.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Desinsetiza%C3%A7%C3%A3o.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Desinsetiza%C3%A7%C3%A3o.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Disk%20Servi%C3%A7os.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Disk%20Servi%C3%A7os.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Fa%C3%A7a%20um%20or%C3%A7amento.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Fa%C3%A7a%20um%20or%C3%A7amento.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Limpeza%20e%20Conserva%C3%A7%C3%A3o.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Limpeza%20e%20Conserva%C3%A7%C3%A3o.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Localiza%C3%A7%C3%A3o.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Localiza%C3%A7%C3%A3o.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Miss%C3%A3o%2C%20Vis%C3%A3o%20e%20Valores.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Miss%C3%A3o%2C%20Vis%C3%A3o%20e%20Valores.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Perfil.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Perfil.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Recrutamento%20e%20Sele%C3%A7%C3%A3o.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Recrutamento%20e%20Sele%C3%A7%C3%A3o.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Solicite%20uma%20visita.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Solicite%20uma%20visita.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Tempor%C3%A1rio%20%20%20Estagi%C3%A1rio.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Tempor%C3%A1rio%20%20%20Estagi%C3%A1rio.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Terceirizados.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Terceirizados.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Vantagens.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Vantagens.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o.png"><img src="screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->

## Built With

<!-- LANGUAGES -->

**Languages**

|                                                                                                                | Language | Version |
| ---------------------------------------------------------------------------------------------------------------- | -------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="20" />               | PHP      | 5.6     |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" />            | HTML     | 5       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" />              | CSS      | 3       |

<!-- FRAMEWORKS & LIBRARIES -->

**Frameworks & Libraries**

|                                                                                                                  | Framework | Version |
| ---------------------------------------------------------------------------------------------------------------- | --------- | ------- |
| <img src="https://devicons.io/devicons/icons/joomla.svg" width="20" />                                          | Joomla!   | 1.5.18  |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="20" />            | MySQL     | 5.6     |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="20" />          | Docker    | —       |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

This project repository is for archive purposes only. No new features or issues are being tracked.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->

## Contributors

<a href="https://github.com/llvasconcellos2/oriente/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=llvasconcellos2/oriente" alt="Contributors" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

[Leonardo Vasconcellos - Website](https://leonardo-vasconcellos.vercel.app/) — [LinkedIn](https://www.linkedin.com/in/llvasconcellos)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[website-shield]: https://img.shields.io/badge/Creator_Website-%E2%86%97-2eba7a?style=for-the-badge
[website-url]: https://leonardo-vasconcellos.vercel.app/
[contributors-shield]: https://img.shields.io/github/contributors/llvasconcellos2/oriente.svg?style=for-the-badge
[contributors-url]: https://github.com/llvasconcellos2/oriente/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/llvasconcellos2/oriente.svg?style=for-the-badge
[forks-url]: https://github.com/llvasconcellos2/oriente/network/members
[issues-shield]: https://img.shields.io/github/issues/llvasconcellos2/oriente.svg?style=for-the-badge
[issues-url]: https://github.com/llvasconcellos2/oriente/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/llvasconcellos
[year-shield]: https://img.shields.io/badge/Released-2005-gray?style=for-the-badge
[year-url]: #
[product-screenshot]: screenshots/Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o%20-%20Oriente%20Limpeza%20e%20Dedetiza%C3%A7%C3%A3o.png
