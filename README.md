# fixtsconfig

A tsconfig.json file scrubber for the truly insane.

It will re-write your tsconfig.json file as follows:

- compilerOptions
- extends
- files
- include
- exclude
- compileOnSave
- all other keys in alphabetical order
- compilerOptions sorted alphabetically
- newline at the end of the file

Fix all indenting to 2 spaces.

Oh, and it will tolerate improperly quoted and comma'd JSON thanks to [ALCE](https://npmjs.org/package/alce).

## Usage

1. install it globally

```
npm i -g fixtsconfig
```

2. run it in the same directory as your tsconfig.json, that's it.

```
fixtsconfig
```

## What you might do if you're clever

```
npm i cool_package --save && fixtsconfig
```

## Credits

This repo is forked from [https://github.com/HenrikJoreteg/fixpack](https://github.com/HenrikJoreteg/fixpack) .
The most important idea and code is his great work.

## License

MIT
