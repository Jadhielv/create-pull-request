# create-pull-request

create-pull-request is a CLI that allows you to open the URL to create a pull request pointing to the base branch in Github.

## Installation

Use npm or yarn to install create-pull-request.

```bash
# npm
npm install create-pull-request --global

# yarn
yarn add create-pull-request --global
```

## Usage

```
// in the terminal in your project folder
create-pull-request
```

It will open an URL to create a new pull request pointing to the base branch.

e.g.
if you have the `linux` project and you're working in a cool feature like `my-cool-feature` and the project origin url is `git@github.com:torvalds/linux.git` if you run `create-pull-request` it will open this URL

```bash
https://github.com/torvalds/linux/compare/my-cool-feature?expand=1
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)