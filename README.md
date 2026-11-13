# Liquid Morph

A reusable `LiquidMorphPanel` control that captures its content and morphs between states with a liquid effect drawn with SkiaSharp. The page switches between two states to show the transition.

## Built with

- Uno Platform single project, `Uno.Sdk` 6.5.31 (pinned in `global.json`).
- Targets: Desktop (net10.0).
- Material theme, Uno Toolkit, Skia renderer.

## Run it

You need the .NET 10 SDK. Run `uno-check` first on a fresh machine.

```bash
dotnet run --project LiquidMorph/LiquidMorph.csproj -f net10.0-desktop
```

## License

MIT. See [LICENSE](LICENSE).
