rubymotion_i18n
===================

i18n by using [sugarcube-localized](https://github.com/rubymotion/sugarcube#localized)

- make Localizable.strings file for each lang

```
resources
├── en.lproj
│   └── Localizable.strings
└── ja.lproj
    └── Localizable.strings
```

- Use SugarCube's 'string._ method

```
puts 'ようこそ'._
```
