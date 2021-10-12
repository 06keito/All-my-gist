# __Add submodule example__

- [__Add submodule example__](#add-submodule-example)
  - [__Overview__](#overview)
  - [__Usage__](#usage)
  - [__Reference__](#reference)
  - [__Licence__](#licence)

## __Overview__

A repository to aggregate the Gists you have created.

---

## __Usage__

- __sample__

```shell
git submodule add [Gist_URL] [Any directory name]
```

- __example__

```shell
git submodule add https://gist.github.com/06keito/6af6fb73a45baaabe7f8772b7f8d5e66 ubuntu
```

- __delete__

```shell
git submodule deinit -f [submodule name]
git rm -f [submodule name]
rm -rf .git/modules/[submodule name]
```

- __clone__

```shell
git clone --recurse-submodules https://github.com/06keito/All-my-gist.git
```

---

## __Reference__

>[Github Gist を1個のレポジトリでまとめて管理する ( git submodule を利用 )](https://qiita.com/YumaInaura/items/8088aae8df7ffac482b9)

---

## __Licence__

- [MIT](https://opensource.org/licenses/mit-license.php)
