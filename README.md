[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/VeritasDL/SADX-Trainer">
  </a>

  <h3 align="center">SADX 2004 PC Trainer</h3>

  <p align="center">
    <br />
    <a href="https://github.com/VeritasDL/SADX-Trainer/issues">Report Bug</a>
    ·
    <a href="https://github.com/VeritasDL/SADX-Trainer/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This Project started back in 2015 as something I never planned to Publicly Release due to the amount of cheating that could be done with it.
I've decided to remove all of that stuff and make a public release for the Community to use.

### Built With

* [Process Memory](https://github.com/MainMemory/ProcessMemory)
* [Metro Framework](http://thielj.github.io/MetroFramework/)



<!-- GETTING STARTED -->
## Getting Started

This program is a Trainer for the 2004 PC Disc Version of Sonic Adventure DX.   
Download the [Latest Release Here](https://github.com/VeritasDL/SADX-Trainer/releases)

## Tasks & Workers Tab 
* First, Next, Prev - These are for exploring the list of Task workers, you must select a Pointer # before you can use any of the buttons.
* Move - This will move the selected Task's Position to yours.
* Custom - This is where you would put your own custom TaskWork Pointers to explore.
* Move Task To Me - Once Checked Pressing D-Pad Down on the Controller will move the selected Task to you.

* SetObjData Pointers - First, Next, Back - these are for exploring the list of SETObjData TaskWorkers,   
* First - This gets the first SETObjData TaskWorker.   
* Next - This get the next SETObjData TaskWorker.   
* Back - This goes to the Previous SETObjData TaskWorker.   
* Follow - This Follows the current SETObjData TaskWorker.   
* Prev - This goes to the Previous SETObjData TaskWorker.   

## Research Tab 
* This Tab Shows info on the current Held Objects TaskWorker.   
* Move Task To Me - Once this is enabled, Pressing D-Pad Down on the Controller will teleport what ever "Object" The game thinks you are holding. *Note: This Requires setting up SRM to function properly.*
* Lock Held Object - Once enabled it will lock the Held Object Task, making it so you can set up a cheated verion of SRM *Note: Enable once Holding a Object, then throw the object away, and change acts to enable SRM*
* Record - Once Enabled it will log all of the Main Subroutine Pointers to the TextBox, usefull for checking what object your referencing, *Note: Need IDA and the SADX IDA DB or Ghidra for cross referencing.*  

## Physics And Position Tab
* This Tab Shows info about the player.
* Set Selected Task Pos - This Will Set the Postion of what ever Task you have selected under the Tasks And Workers.
* Save & Load Position - Once Enabled Pressing, L1 + D-Pad Right Will Save your Current Location, and Pressing L1 + D-Pad Left Will Load your Saved Location.    

## Memes Tab
* This tab has some mods that are mostly Memes

## ACE Tab
* This tab is a W.I.P and can really mess up your Chao Save proceed with caution.
* Lock Held Task - Once enabled it will lock the Held Object Task, making it so you can set up a cheated verion of SRM *Note: Enable once Holding a Object, then throw the object away, and change acts to enable SRM*
* Set Chao Name To Lil Debuggies - This will change the name of the selected chao to x86 code that if called sets the players Movement Debug On.
* SSS Flag Ace - This will change the name of the selected chao and 2 other chaos to x86 code that if called sets the Flag for Super Sonic Story to be unlocked.
* MR Flag Ace - This will change the name of the selected chao and 2 other chaos to x86 code that if called sets the Flag for the Mystic Ruins Cart to be unlocked.
* Run Arbitrary Code - This Requires you to have either a Object Held, or SRM set up prior. once Clicked it changes the Task's Main Subroutine Pointer to the Selected Chaos name.
* Disable - This restores the original Main Subroutine Pointer to the Held Object/SRM

## SpeedRun Save Tab
* This Tab is A W.I.P
* PLEASE enable only ONE of the checkboxs.
* If a checkbox is checked and the player is in the Main Menu, it will write the "clean" save file for the selected Character.
* This Does Require you to ALT-F2 in order for the save file to be loaded correctly.  
* USING THIS MAY MAKE YOUR SPEEDRUNS INVALID!!!!!


<!-- CONTRIBUTING -->
## Contributing

### Editing The Program

1. Clone the repo
   ```sh
   git clone https://github.com/VeritasDL/SADX-Trainer.git
   ```
   
2. Open SADX Trainer.sln with Visual Studio 2019
3. Do your edits
4. Build and run EXE found in SADX Trainer\SADX Trainer\bin\Release

See the [open issues](https://github.com/VeritasDL/SADX-Trainer/issues) for a list of proposed features (and known issues).

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See [License](https://github.com/VeritasDL/SADX-Trainer/issues) for more information.



<!-- CONTACT -->
## Contact

James (Veritas) - [@VeritasDL](https://twitter.com/veritasdl)

Project Link: [https://github.com/VeritasDL/SADX-Trainer](https://github.com/VeritasDL/SADX-Trainer)




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/VeritasDL/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/VeritasDL/SADX-Trainer/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/VeritasDL/repo.svg?style=for-the-badge
[forks-url]: https://github.com/VeritasDL/SADX-Trainer/network/members
[stars-shield]: https://img.shields.io/github/stars/VeritasDL/repo.svg?style=for-the-badge
[stars-url]: https://github.com/VeritasDL/SADX-Trainer/stargazers
[issues-shield]: https://img.shields.io/github/issues/VeritasDL/repo.svg?style=for-the-badge
[issues-url]: https://github.com/VeritasDL/SADX-Trainer/issues
[license-shield]: https://img.shields.io/github/license/VeritasDL/repo.svg?style=for-the-badge
[license-url]: https://github.com/VeritasDL/SADX-Trainer/blob/master/LICENSE 
