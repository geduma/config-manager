<p align="center">
  <img src="https://user-images.githubusercontent.com/26848451/221998944-4aee6ec9-6621-45b0-acb0-38f82781a647.png" />
</p>

## APP
https://config.geduma.com

## API
https://api.geduma.com/config-manager

Endpoints:

- GET `/all`: returns all configuration variables.
- GET `/owner/:owner`: returns configuration variables filtered by owner.
- GET `/schema/:owner/:schema`: returns configuration variables filtered by owner > schema
- GET `/name/:owner/:schema/:name`: returns configuration variables filtered by owner > schema > name
