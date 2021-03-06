The tip supplements tip of 23-07-2017.

To push git commits along **with** corresponding tags, use:

```bash
git push --follow-tags
```

In the most common case (create npm version + git tag and push it to the remote) this command is equal to:

```bash
git push && git push --tags
```

---
Special credits to [@nexidan](https://github.com/NeXidan) for asking a good question which led to this tip.

---
As noted by [@vlyahovich](https://github.com/vlyahovich) `git push origin <branch-name> --tags` pushes commits and tags as well. The key here is the `<branch-name>` parameter.
