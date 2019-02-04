# puppeteer-canavas-login

## Description 
This can be added to any canvas automating program so that the login is already automated

## How to Install

Standard Install

1. Clone this repository:
    ```bash
    git clone https://github.com/byuitechops/puppeteer-canavas-login.git
    ```
1. Step into the folder that was just created 
    ```bash
    cd ./puppeteer-canvas-login.git
    ```
1. To install dependancies, run:
    ```bash
    npm i
    ```
    &/or
    ```bash
    npm i save
    ```

<!--- TODO: Add Additional Installation/Set Up Instructions, then delete this comment  --->

## How to Use
In your code you need to require:
```bash
require('../puppeteer-canvas-login/puppeteerLogin.js');
```
Depending on where you clone the file you may need to modify the path to be able to require
the file.

One you have the file required in your program, you will need to set your Canvas API token in
cmd using:

```bash
set CANVAS_API_TOKEN=
```
Once you have done this, and you run the file you will be prompted for your username and password.

TADA you now are logged into canvas.
<!--- TODO: Add Additional Information on How to use the tool/module, then delete this comment  --->

