# patch'd [TYPO3](https://typo3.org) extension [`frontend`](https://github.com/TYPO3/typo3/tree/main/typo3/sysext/frontend)

This extension covers frontend rendering features, such as TypoScript configuration or caching, and basic frontend plugins, such as page and content element rendering.

## Compatibility

https://github.com/typo3patch/cms-frontend/blob/7b6bcc793b65eaa1000990db0dd7e670b3af7cc8/composer.json#L18

## Installation

```bash
composer config repo.t3p-frontend git https://github.com/typo3patch/cms-frontend
composer req typo3patch/cms-frontend
```

## Patches

+ [x] use `selectFields` @ `numRows`
