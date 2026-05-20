# Offline Payments module

[![Tests](https://github.com/LibreAkaunto/module-offline-payments/workflows/Tests/badge.svg?label=tests)](https://github.com/LibreAkaunto/module-offline-payments/actions)

## Tests

The workflow runs both the host application and module test suites. They're configured to run once per week and triggered manually. Therefore, **before** publishing a new release, run the workflow [manually](https://github.com/LibreAkaunto/module-offline-payments/actions?query=workflow%3ATests) and make sure it passes.

## Translations

Crowdin is the home of translators and it's synced (download & upload) with GitHub. The workflow is configured to run once per week and triggered manually. Therefore, **before** publishing a new release, run the workflow [manually](https://github.com/LibreAkaunto/module-offline-payments/actions?query=workflow%3ATranslations) and merge the automatically created PR, if available. Finally, all language files must be listed in the [config](https://github.com/LibreAkaunto/module-offline-payments/blob/master/crowdin.yml) file.
