# Installation and testing

The repository currently contains an educational example script. Always test on a development server before deploying changes to a public server.

## Preparation

1. Set up a compatible Paper or Spigot server.
2. Install a matching Skript plugin release according to its official documentation.
3. Start the server once so Skript can create its folders.
4. Back up your server and existing scripts.

## Install the example

1. Copy `examples/cooldown-demo.sk` to `plugins/Skript/scripts/cooldown-demo.sk`.
2. Run `/sk reload cooldown-demo` using the server console or an appropriately authorized account.
3. Review the output for syntax or compatibility errors.
4. Use `/toolkitboost` in game and test that the cooldown activates.

## Troubleshooting

- Verify that your Minecraft, Paper/Spigot, and Skript versions are compatible.
- Check for conflicting commands provided by other plugins.
- Open a GitHub issue and include your environment and a redacted error log.

The demo script is a starting example, not a validated release for every supported configuration.
