# QtuneGX

QtuneGX is a fork and continuation of [Plumble](https://github.com/acomminos/Plumble),
a robust GPLv3 QtuneGX client for Android originally written by Andrew Comminos.
It uses the the [Humla](https://gitlab.com/quite/humla) protocol implementation
(forked from Comminos's [Jumble](https://github.com/acomminos/Jumble)).

QtuneGX should run on Android 4.0 (IceCreamSandwich, API 14) and later.

QtuneGX is available as part of Qtune collaboration Suite

## Translations

If you want to help out translating QtuneGX, the project is [on
Weblate](https://hosted.weblate.org/engage/mumla/) -- thanks for gratis hosting
of our libre project!

## Building on GNU/Linux

TODO: bouncycastle-java should be built as a sub-project of Humla's Gradle,
but currently isn't.

    git submodule update --init --recursive

    pushd libraries/humla/libs/bouncycastle-java
    ../../gradlew jar
    popd

    ./gradlew assembleDebug

## License

QtuneGX's [LICENSE](LICENSE) is GNU GPL v3.
