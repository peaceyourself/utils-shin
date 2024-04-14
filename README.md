# Utils-Shin

该项目是一个 JavaScript 工具库，提供了一些常用的格式化和校验功能，包括金额格式化、手机号、身份证号和邮箱的校验等功能。

## 安装

```bash
npm install utils-shin
```

## 使用方法

### 导入模块

```javascript
import { Format, Validate } from 'utils-shin';
```

### 格式化功能(Format)

#### 格式化金额展示

```javascript
Format.formatMoney(money, symbol, decimals);
```

参数：
- `money` (number): 要格式化的金额
- `symbol` (string): 货币符号，默认为空字符串
- `decimals` (number): 保留的小数位数，默认为 2

返回格式化后的金额字符串。

### 校验功能(Validate)

#### 手机号校验

```javascript
Validate.mobileCheck(value);
```

#### 身份证校验

```javascript
Validate.IDCardCheck(value);
```

#### 邮箱校验

```javascript
Validate.emailCheck(value);
```


## 许可证

[MIT](LICENSE)

