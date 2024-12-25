## About

**A modified version of the GetX package 4.6.6, designed to enhance the original functionalities
while maintaining the core principles.**

## CLI

- Use only **[get_mad_cli](https://pub.dev/packages/get_mad_cli)**.
- [get_cli](https://pub.dev/packages/get_cli) won't work with this package.

## Why mad

* Of-course if you are using an unofficial version of [get_cli](https://pub.dev/packages/get_cli)
  from unknown developer would indicates you are mad.
* So, here package is not mad, the person who is willing to take risk is mad and this package is
  just for them.

## Documentation

- **GetView** widget can carry custom tags to be used with individual multiple instance GetX
  controllers.
- Removed unnecessary features like **GetConnector** to improve performance.
- Added Android native transition animation.
- Modified the default transition duration.
- Modified GetView and Bindings to make unique routing possible using **[get_mad_cli](https://pub.dev/packages/get_mad_cli)**.
- Added **RxMad** for reactive programming.
    - to use it do:
      `final RxMad observerForList = RxMad();`

    - and in the widget do:
      `constroller.observerForList.value;`

    - to rebuild widget do:
      `observerForList.refresh();`

- For more comprehensive information, refer to
  the [original GetX documentation](https://pub.dev/packages/get/).