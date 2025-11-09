# Tydli Documentation

This repository contains the customer-facing documentation for Tydli, hosted on Mintlify.

## 🔄 Automated Sync

Documentation is automatically synced from the [main Tydli repository](https://github.com/MaxWillEj/tydliio). Do not edit documentation files directly in this repository - they will be overwritten.

## 📝 Content Updates

To update documentation:
1. Make changes in the `MaxWillEj/tydliio` repository
2. Push changes to the `main` branch
3. GitHub Actions will automatically create a PR in this repository
4. Review and merge the PR

## 🚀 Local Development

```bash
# Install Mintlify CLI
npm install -g mintlify

# Preview documentation locally
mintlify dev

# Check for broken links
mintlify broken-links
```

## 📚 Documentation Structure

- `/guides` - User guides and tutorials
- `/support` - Troubleshooting and FAQ
- `/api-reference` - API and technical reference
- `/developers` - Developer documentation
- `/operations` - Operations and security
- `/resources` - Changelog and resources

## 🔗 Links

- **Live Docs**: https://docs.tydli.io (or your Mintlify URL)
- **Main Repo**: https://github.com/MaxWillEj/tydliio
- **Dashboard**: https://tydli.io

## 📄 License

Same as main Tydli repository.
