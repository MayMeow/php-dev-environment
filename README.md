# PHP dev environment

My dev environment

## Requirements

- Docker
- VSCode
- PHPStorm

## How to use in VS code?

- Install extension `ms-vscode-remote.vscode-remote-extensionpack` 
- Clone and open this repository
- `Control` + `Shift` + `P` and then find `Reopen folder in container`

## How to use in PHPStorm ?

- Clone this repository
- Go to settings
- Click on PHP
- In the window click on `...` right near **Cli Interpreter**
- Click on `+` and select **From Docker, Vargrant ...**
- Check **Docker Compose** 
- Select **Configuration files** Click on `+` and select `docker-compose.dev.yml` from this repository.
- Select service `php8`
- Click `OK`
- Click `OK`
- Cli interpreter will now show you `php8:some version of php`
- Click `Apply` then `OK`
- You are now ready to go.