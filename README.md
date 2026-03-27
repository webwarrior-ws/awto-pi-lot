# awto-pi-lot

awto-pi-lot is an extension for [pi-coding-agent](https://www.npmjs.com/package/@mariozechner/pi-coding-agent) that adds support for [PPQ.ai](https://ppq.ai/) & its [AutoClaw](https://ppq.ai/blog/using-autoclaw-with-payperq) model.

Install it with:

```
./pi/pi install npm:awto-pi-lot
```

And authenticate with an [auth.json](https://github.com/badlogic/pi-mono/blob/main/packages/coding-agent/docs/providers.md#auth-file) file to hook your key, e.g.:

```
{ "ppq": { "type": "api_key", "key": "sk-..." } }
```

Which you can extract from your [PPQ.ai account page](https://ppq.ai/account-activity), and place in `~/.pi/agent/auth.json`.

Using env var PPQ_API_KEY is also supported but not recommended, because sandboxing tools like [pi-less-yolo](https://github.com/cjermain/pi-less-yolo) would not work OOTB.

---

## License

MIT
