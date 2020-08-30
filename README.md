# Three Word Descriptions
Describe about your content creators in 3 words. Just 3 words.

## Getting Started

1. Find your content creator [here](library/index.md). Can't see yours? You can add yours to the list and your some 3-word-descriptions stuff as an PR.
2. Click your content creator and you'll presented the web editor. At the last line, add your some 3-words-descriptions stuff stuff. Remember, **one entry PER line**.
3. Create a new pull request. Don't worry, we'll link your entries to your PR once we're merged it.

## Using the npm package

Install the package with `npm i @recaptime/three-word-descriptions`. For Yarn users, use `yarn add @recaptime/three-word-descriptions` instead.

**To require an file through an constant**: Require the package first, then call an submodule.

```js
const ThreeWordDescriptors = require('@recaptime/three-word-descriptions');

console.log(ThreeWordDescriptors.gildedguy);

// Also we can try this:
const ShockThreapist = require('@recaptime/three-word-descriptions').oxob;

console.log(ShockThreapist);
```

**To directly require an JSON file**: Require BOTH the package name and path-to-file.

```js
const describeBogIn3Words = require('@recaptime/three-word-descriptions/library/bog.json');

console.log(describeBogIn3Words);
```

## License

MIT License
