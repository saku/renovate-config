# renovate-config

## When you want to use

```
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>saku/renovate-config"
  ]
}
```

## When you want to select automerge strategy

By default, your automerge setting is conservative.
But you want to merge automatically more, you can choise aggressive settings.

```
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>saku/renovate-config",
    "github>saku/renovate-config:automerge/aggressive"
  ],
  "ignorePresets": [
    "github>saku/renovate-config:automerge/default"
  ]
}
```
