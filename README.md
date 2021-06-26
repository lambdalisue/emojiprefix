# 🎨 emojiprefix

Emoji prefix guide for git commit message.
This guide try to make small definition by

1.  Use only short and single word emoji
2.  Do not subdivide categories too much

## Usage

Create `.gitmessage` on your git repository root with the following content.

```


# Guide (v1.0)
#
# 👍  :+1:      Apply changes.
#
# 🌿  :herb:    Add or update things for tests.
# ☕  :coffee:  Add or update things for developments.
# 📦  :package: Add or update dependencies.
# 📝  :memo:    Add or update documentations.
#
# 🐛  :bug:     Bugfixes.
# 💋  :kiss:    Critical hotfixes.
# 🚿  :shower:  Remove features, codes, or files.
#
# 🚀  :rocket:  Improve performance.
# 💪  :muscle:  Refactor codes.
# 💥  :boom:    Breaking changes.
# 💩  :poop:    Bad codes needs to be improved.
#
# How to use:
#   git config commit.template .gitmessage
#
# Reference:
#   https://github.com/lambdalisue/emojiprefix
```

Then install it on the repository by the following command:

```
git config commit.template .gitmessage
```

## License

These codes are licensed under CC0.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed)

## See also

- [gitmoji](https://gitmoji.dev/)
- [Git Commit message Emoji](https://gist.github.com/parmentf/035de27d6ed1dce0b36a)
- [Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)
