
# 切换飞行模式

切换飞行模式

## Example Usage

```java
// Java
driver.toggleAirplaneMode();

```

```python
# Not supported
```

```javascript
// Javascript
// webdriver.io example
driver.toggleAirplaneMode();

// wd example
await driver.toggleAirplaneMode();

```

```ruby
# Ruby
# ruby_lib example
toggle_flight_mode

# ruby_lib_core example
@driver.toggle_flight_mode

```

```php
# PHP
// TODO

```

```csharp
// C#
// TODO

```



## 支持


### Appium 服务端

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/cn/drivers/ios-xcuitest.md) | None | None | None |
|  | [UIAutomation](/docs/cn/drivers/ios-uiautomation.md) | None | None | None |
| Android | [Espresso](/docs/cn/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator2](/docs/cn/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/cn/drivers/android-uiautomator.md) | 4.3+ | All | All |
| Mac | [Mac](/docs/cn/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/cn/drivers/windows.md) | None | None | None |


### Appium 客户端

|Language|Support|Documentation|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [appium.github.io](https://appium.github.io/java-client/io/appium/java_client/android/SupportsNetworkStateManagement.html#toggleAirplaneMode--) |
|[Python](https://github.com/appium/python-client/releases/latest)| None |  |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L2712) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/github/appium/ruby_lib_core/Appium/Core/Device#toggle_flight_mode-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| All | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| All | [github.com](https://github.com/appium/appium-dotnet-driver/) |


## HTTP API 规范


### 路径

`POST /session/:session_id/appium/device/toggle_airplane_mode`


### URL 参数

|名称|描述|
|----|-----------|
|session_id|新建会话(session)后用来标识当前会话(session)的ID|

### JSON 参数

无


### 响应

null


## 参考

* [JSONWP 规范](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L510)
