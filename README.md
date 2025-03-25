# Want mark!

Localization resources for mobile app "Want mark!"

# App Downloads

To try the app you can download it from your favorite app store:
* [Google Play](https://play.google.com/store/apps/details?id=by.ds.markcalc)
* [Apple App Store](https://apps.apple.com/app/id1630664059)

Or you can try it on the web at https://f69.github.io/wantmark.app/

# Project structure

```
├── data
│   ├── subject_<lang1>.json
│   ...
│   └── subject_<langN>.json
├── help
│   ├── <lang1>
│   │   ├── archive.html
│   │   ├── calc.html
│   │   ├── subject.html
│   │   └── subjects.html
│   ...
└── strings
    ├── app_<lang1>.arb
    ...
    └── app_<langN>.arb
```

* `subject_<lang>.json` files in `data` folder contain list of subject names, 
which appear in suggestions, when you enter name of a new subject
* `.html` files in `help/<lang>` folders contain text for appropriate help 
screens
* `app_<lang>.arb` files in `strings` folder contain strings used in the app 
user interface

# Contributing

If you want to corrent existing or add new translation please create pull 
request.
