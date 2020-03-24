
## Default Variables

### cyberduck_started

Start in background after install

#### Default value

```yaml
cyberduck_started: true
```

### cyberduck_user

User to run user-specific commands

#### Default value

```yaml
cyberduck_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
