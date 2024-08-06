<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
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
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- 
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80"> 
  </a>
  -->

  <h3 align="center">Dark - Light mode Switcher</h3>

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
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![image](https://github.com/user-attachments/assets/5ef736fa-6df8-44b8-856f-7a94fbdf0b28)


This code creates a basic React application with a dark mode feature.

### Description:

#### Import necessary components:

* useState: Hook for managing state (dark mode in this case).
* Navbar: Component for the navigation bar.
* Main: Component for the main content area.

#### Define the App component:

Uses useState to manage the darkMode state, initially set to true.

Defines a toggleDarkMode function to invert the darkMode state.

#### Render the app:

* Creates a container div.
* Renders the Navbar component, passing darkMode and toggleDarkMode as props.
* Renders the Main component, passing darkMode as a prop.
#### Key Functionality:
* Dark Mode Management: The darkMode state and toggleDarkMode function control the application's theme.
* Component Structure: The Navbar and Main components likely handle the visual appearance based on the darkMode prop.
* Prop Passing: Information about the current dark mode state is passed to child components for customization.
* In essence, this code provides a foundation for a React application that can switch between light and dark mode based on user preference.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Vite][Vitejs]][Vite-url]
* [![React][React.js]][React-url]



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

* Check if Node.js is installed
  ```sh
  node -v
  ```
If it is not installed, [download](https://nodejs.org/en) and install it.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/lalomax/switchmodes.git
   ```
1. Open directory
   ```sh
   cd switchmodes
   ```
   
3. Install NPM packages
   ```sh
   npm install
   ```
4. Run in development mode
   ```js
   npm run dev
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [ ] Multi-language Support
    - [ ] Spanish

See the [open issues](https://github.com/lalomax/switchmodes/issues) for a full list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


<!-- CONTACT -->
## Contact

Your Name - [https://x.com/OrlandoFloresH](https://x.com/OrlandoFloresH) - createc.bo@gmail.com

Project Link: [https://github.com/lalomax/switchmodes](https://github.com/lalomax/switchmodes)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/lalomax/switchmodes.svg?style=for-the-badge
[contributors-url]: https://github.com/lalomax/switchmodes/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/lalomax/switchmodes.svg?style=for-the-badge
[forks-url]: https://github.com/lalomax/switchmodes/network/members
[stars-shield]: https://img.shields.io/github/stars/lalomax/switchmodes.svg?style=for-the-badge
[stars-url]: https://github.com/lalomax/switchmodes/stargazers
[issues-shield]: https://img.shields.io/github/issues/lalomax/switchmodes.svg?style=for-the-badge
[issues-url]: https://github.com/lalomax/switchmodes/issues
[license-shield]: https://img.shields.io/github/license/lalomax/switchmodes.svg?style=for-the-badge
[license-url]: https://github.com/lalomax/switchmodes/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/orlando-flores365/
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[Vitejs]: https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white
[vite-url]: https://vitejs.dev/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
