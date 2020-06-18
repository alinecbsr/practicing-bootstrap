# 💻 Practicing Bootstrap

Development of a responsive website layout using Bootstrap

### 🛠 Setting up your desktop

1. Download [VSCode](https://code.visualstudio.com/). 🔽
2. Install [Node](https://nodejs.org/en/) or [nvm for Unix](https://github.com/nvm-sh/nvm) (MacOS, Linux), [nvm for Windows](https://github.com/coreybutler/nvm-windows) and follow the steps to run Node and npm. Preferred version 12.16.2. 🔽
3. Run the commands below to install the necessary dependencies in the project folder:
    - `npm init` 
    - `npm install bootstrap@4.0.0-beta.2` 
    - `npm install jquery` 
    - `npm install popper.js` 
    - `sudo gem install sass` for MAC, or check [here](https://sass-lang.com/install) the sass installation documentation  

    Create a file naming style.scss in the path node_modules/bootstrap/scss

    - `sass --watch node_modules/bootstrap/scss:node_modules/bootstrap/compiler` check [here](https://sass-lang.com/guide)

    Ensure the import of your style file and the necessary scripts in your html file

    - `Example below:`

    <head>
      <!-- Bootstrap CSS -->
      <link rel="stylesheet" href="node_modules/bootstrap/compiler/bootstrap.css">
      <link rel="stylesheet" href="node_modules/bootstrap/compiler/style.css">
    </head>

    <body>

      <!-- Here will be your code -->

      <!-- jQuery first, then Popper.js, then Bootstrap JS -->
      <script src="node_modules/jquery/dist/jquery.js"></script>
      <script src="node_modules/popper.js/dist/popper.js"></script>
      <script src="node_modules/bootstrap/dist/js/bootstrap.js"></script>
    </body>  


## :purple_heart: Contribution

<table>
  <tr>
    <td align="center" style="border: none;">
      <a href="https://github.com/alinecbsr">
        <img style="border-radius: 50px;" src="https://avatars0.githubusercontent.com/u/48742480?s=460&u=d21eae3038217c687d478969e8bf7b1bee1b9c3e&v=4" width="70px;" alt="Aline Rosa"/>
        <br />
        <sub>
          <b>Aline Rosa</b>
        </sub>
      </a>
      <br />
      <p><scan title="Code">💻</scan>|<scan title="Documentation">🎨</scan>|<scan title="Bugs">🐛</scan></p>
    </td>
  </tr>
</table>
