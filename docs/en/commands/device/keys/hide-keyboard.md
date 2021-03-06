[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/hide-keyboard.yml)

# Hide Keyboard

Hide soft keyboard
## Example Usage

```java
// Java
driver.hideKeyboard();

```

```python
# Python
self.driver.hide_keyboard()

```

```javascript
// Javascript
// webdriver.io example
driver.hideDeviceKeyboard();



// wd example
await driver.hideDeviceKeyboard();

```

```ruby
# Ruby
@driver.hide_keyboard

```

```php
# PHP
$driver->hideKeyboard();
$driver->hideKeyboard(array(
      'keyName' => 'Done'
));

```

```csharp
// C#
// TODO C# sample

```



## Support

### Appium Server

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | 9.3+ | 1.6.0+ | All |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | 8.0 to 9.3 | All | All |
| Android | [Espresso](/docs/en/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.2+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/en/drivers/windows.md) | 10+ | 1.6.0+ | All |

### Appium Clients

|Language|Support|Documentation|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [appium.github.io](https://appium.github.io/java-client/io/appium/java_client/HidesKeyboard.html#hideKeyboard--) |
|[Python](https://github.com/appium/python-client/releases/latest)| All | [github.com](https://github.com/appium/python-client/blob/master/appium/webdriver/webdriver.py#L378) |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L2609) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/github/appium/ruby_lib_core/Appium/Core/Device#hide_keyboard-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| All | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| All | [github.com](https://github.com/appium/appium-dotnet-driver/) |

## HTTP API Specifications

### Endpoint

`POST /wd/hub/session/:session_id/appium/device/hide_keyboard`

### URL Parameters

|name|description|
|----|-----------|
|session_id|ID of the session to route the command to|

### JSON Parameters

|name|type|description|
|----|----|-----------|
| strategy | `string` | Hide keyboard strategy (optional, UIAutomation only). Available strategies - 'press', 'pressKey', 'swipeDown', 'tapOut', 'tapOutside', 'default'. |
| key | `string` | Key (optional) |
| keyCode | `string` | Key code (optional) |
| keyName | `string` | Key name (optional) |

### Response

null

## See Also

* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L470)
