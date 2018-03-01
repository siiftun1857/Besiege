# siiftun1857的Besiege github项目
这里是siiftun1857有关Besiege的github项目。
## Besiege xml文件结构描述文件使用
### Besiege dtd
引用兼容所有版本1的bsg工程文件的dtd:
```xml
<!DOCTYPE Machine SYSTEM "https://raw.githubusercontent.com/siiftun1857/Besiege/master/dtd/bsg_v1.dtd">
...
```
引用bsg0.3的bsg工程文件dtd:
```xml
<!DOCTYPE Machine SYSTEM "https://raw.githubusercontent.com/siiftun1857/BesiegeDTD/master/dtd/bsg_0.3.dtd">
...
```
引用bsg0.8的blv关卡文件dtd:
```xml
<!DOCTYPE Level SYSTEM "https://raw.githubusercontent.com/siiftun1857/BesiegeDTD/master/dtd/blv_0.8.dtd">
...
```
### Besiege XSD
引用bsg0.8的bsg工程文件xsd:
```xml
<Machine 
	xmlns="https://github.com/siiftun1857/Besiege"
	xmlns:xsi="https://github.com/siiftun1857/Besiege"
	xsi:schemaLocation="https://raw.githubusercontent.com/siiftun1857/BesiegeDTD/master/xsd/bsg_0.8.xsd">
...
```
来引用bsg0.8的blv关卡文件xsd:
```xml
<Level 
	xmlns="https://github.com/siiftun1857/Besiege"
	xmlns:xsi="https://github.com/siiftun1857/Besiege"
	xsi:schemaLocation="https://raw.githubusercontent.com/siiftun1857/BesiegeDTD/master/xsd/blv_0.8.xsd">
...
```
