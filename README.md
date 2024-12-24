# Get Mad

Get Mad is a customized version of the GetX package 4.6.6, designed to enhance the original functionalities while maintaining the core principles.

## Documentation

- `GetView` widget can carry custom tags to be used with individual multiple instance GetX controllers.
- Removed unnecessary features like `GetConnector` to improve performance.
- Added Android native transition animation.
- Modified the default transition duration.
- Added `RxMad` for reactive programming.
  - to use it do:
  `final RxMad observerForList = RxMad();`
  
  - and in the widget do:
    `constroller.observerForList.value;`
  
  - to rebuild widget do:
  `observerForList.refresh();`


For more comprehensive information, refer to the [original GetX documentation](https://pub.dev/packages/get/).