<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://macx.ws/uploads/posts/2016-09/1474284106_parallels-desktop-12.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">MacBook Extend Parallels Trial</h3>
</div>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1 - Go to your Shortcuts Panel

<div align="center">
  <img width="500" alt="Captura de ecrã 2022-10-05, às 09 40 19" src="https://user-images.githubusercontent.com/36825211/194018477-b19b47b4-d917-4d69-82d0-16510f4a31c4.png">
</div>

<br>

2 - Create First Shortcut - "Start Parallels"

   ```sh
   Click on the Plus Sign, give your Shortcut a name and Select "Terminal > Execute Shell Script"
   ```
   
2.1 - Copy and paste this code - This will alter your system time and date, therefore extending the trial.

   ```sh
   sudo -S date -u 1101175721 
   ```
 
2.2 - Go to "Shortcut Details" 

   ```sh
   Enable Fix on the Menu Bar
   ```
   
3 - Create Second Shortcut - "Stop Parallels"

   ```sh
   Click on the Plus Sign, give your Shortcut a name and Select "Terminal > Execute Shell Script"
   ```
   
3.1 - Copy and paste this code

   ```sh
   sudo systemsetup -setusingnetworktime Off
   sudo systemsetup -setusingnetworktime On
   ```
   
   3.2 Go to "Shortcut Details" 

   ```sh
   Enable Fix on the Menu Bar
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/Goldenroot/MacBook-Extend-Parallels-Trial/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/Goldenroot/MacBook-Extend-Parallels-Trial/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Goldenroot/MacBook-Extend-Parallels-Trial/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Goldenroot/MacBook-Extend-Parallels-Trial/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/miguel2k1

