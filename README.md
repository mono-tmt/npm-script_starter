# Web 制作テンプレート

## 使用ツールの概要

- Pug
- Sass(SCSS)
- SCSS, JavaScript のコード整形
- 画像の圧縮
- Git Hook

## 使用準備

```
$ git clone https://github.com/mono-tmt/npm-script_starter.git {project_name}
$ cd {project_name}
$ npm ci
$ npx simple-git-hooks
```

## 使用時

- Web 制作

```
$ npm run watch:all
```

- コード整形

```
$ npm run format:all
```

- dist ファイルの削除

```
$ npm run delete:dist
```

- 公開

```
$ npm run prepare:all
```
