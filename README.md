# PowerBI-API-Helper
With the introduction of the new Power BI API for custom visuals ([https://github.com/Microsoft/PowerBI-visuals](https://github.com/Microsoft/PowerBI-visuals))
not all features/functions/... are migrated from the old version to the new version.

With this package I try to include as many of these 'missing' features to help migrating to the new API.

Most code (99%) is copied directly from the Power BI core visuals repository ([https://github.com/Microsoft/PowerBI-visuals-core](https://github.com/Microsoft/PowerBI-visuals-core)).
Only small minor changes are allowed, like removing `reference` links

# Main goal
An empty package as all missing features are included in the new API :-)

# Usage
Via NPM
```
npn install powerbi-api-helper
```

Add reference to Power BI Custom Visual *tsconfig.json* in the section *files* 
```
"node_modules/powerbi-api-helper/index.d.ts"
```

# Requirements
Install typings via npm
```
npm install typings -g
```

And after install typings for jquery, d3 and lodash:
```
typings install --save --global dt~jquery
typings install --save --global dt~d3
typings install --save --global dt~lodash
```

# Missing feature?
If you have a missing feature? Please either submit an issue or fork and create a PR. 