# Publishing new versions

Run these commands to publish a new version after you've made changes:

```bash
circleci orb publish orb.yml happo/happo@<version>
```

Where `version` is something like
- `dev:test1` for publishing a dev package
- `1.0.1` for publishing a production version

