# react.ts.template
![](https://github.com/gowda/data-entry.react/workflows/lint-and-tests/badge.svg)
![](https://github.com/gowda/data-entry.react/workflows/features/badge.svg)

Sample forms from around the web implemented in react

## Usage
#### Install dependencies
```bash
$ npm install
```

#### Run development server
```
$ npm run start
```

Development server listens at [http://localhost:3000](http://localhost:3000).
Can be changed by updating [webpack.development.ts](webpack.development.ts#L12).

#### Run linter
```bash
$ npm run lint
```

[TSLint](https://palantir.github.io/tslint/) is configured to extend from
[tslint:recommended](https://github.com/palantir/tslint/blob/master/src/configs/recommended.ts)

Configuration is in [tslint.json](tslint.json)

#### Run unit tests
```bash
$ npm run test
```

#### Run cucumber tests
```bash
$ npm run features
```

Server running at [http://localhost:3000](http://localhost:3000) is required
for cucumber tests. Run `webpack-dev-server` using:
```bash
$ npm run server
```

## License

> "THE BEER-WARE LICENSE" (Revision 42):
> [Gowda](https://github.com/gowda) wrote this file.  As long as you retain
> this notice you can do whatever you want with this stuff. If we meet
> some day, and you think this stuff is worth it, you can buy me a beer in return.
