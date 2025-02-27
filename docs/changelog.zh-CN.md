---
order: 5
title: 更新日志
toc: false
timeline: true
---

`ng-zorro-antd-mobile` 严格遵循 [Semantic Versioning 2.0.0](https://semver.org/lang/zh-CN/) 语义化版本规范。

#### 发布周期

- 修订版本号：每周末会进行日常 bugfix 更新。（如果有紧急的 bugfix，则任何时候都可发布）
- 次版本号：每月发布一个带有新特性的向下兼容的版本。
- 主版本号：含有破坏性更新和新特性，不在发布周期内。

## 1.0.2(2019-12-04)

### Bug Fixes

* **accordion:** 修复快速点击 accordion 展开时错误([#614](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/614)) ([567ff59](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/567ff59))
* **calendar:** 从 cell 而非 row 中获取 extra cell class 名([#620](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/620)) ([0a11514](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0a11514))
* **carousel:** 修复 resize 时 carousel slide 展示错误 ([#615](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/615)) ([3ff1894](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3ff1894))
* **checkbox:** 修复 disabled 状态为 true 时已点击的初始状态([#598](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/598)) ([85511ca](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/85511ca))
* **datepicker:** 修复中文提示文案错误 ([#616](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/616)) ([71576bb](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/71576bb))
* **list:** 修复 inputitem demo ([#606](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/606)) ([0a50951](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0a50951))
* **list&range:** 删除 console.log ([#610](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/610)) ([762f200](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/762f200))
* **pagination:** 修复设置 locale 不生效错误 ([#611](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/611)) ([756f5be](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/756f5be))
* **searchbar:** 修复用户提交时键盘未收起的问题 ([#596](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/596)) ([5e20a54](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5e20a54))
* **steps:** 修复 step import async 错误 ([#617](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/617)) ([ef4153c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/ef4153c))
* **tabs:** 让 popup类组件在Tabs和TabBar里正常的面板里弹出 ([#621](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/621)) ([89bd218](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/89bd218))

## 1.0.1(2019-09-24)

### Bug Fixes

* **picker:** 去除对 lodash isEqual 的引用 ([#592](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/592)) ([ee6f4b6](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/ee6f4b6))

## 1.0.0(2019-09-23)

### Bug Fixes

* **date-picker:** 修复快速滑动时显示NAN的错误 ([#589](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/589)) ([3e63d20](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3e63d20))

* **picker:** 修复 data input 为一个函数时引发的选择错误 ([#586](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/586)) ([26a07d7](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/26a07d7))

## 1.0.0-rc.0(2019-09-16)

### Bug Fixes

* **carousel:** 当设置为左右滑动方向时忽略垂直方向的事件 ([#581](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/581)) ([abb3a0a](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/abb3a0a))

* **carousel:** 修复走马灯样式错误 ([#582](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/582)) ([004e4e0](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/004e4e0))

* **toast:** 修复 toast z-index ([#580](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/580)) ([7350600](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/7350600))

* **steps:** 修复 steps 状态icon错误 ([#577](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/577)) ([fef7568](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/fef7568))

* **accordion:** 修复 accordion 无法自动展开错误 ([#575](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/575)) ([19b90da](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/19b90da))

* **pull-to-refresh:** 修复 pull-to-refresh direction属性为空时的运行错误 ([#573](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/573)) ([6df7d7c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/6df7d7c))

* **textarea-item:** 修复 textarea-item 自动高度错误 ([#571](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/571)) ([5aa3149](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5aa3149))

* **swipe-action:** 修复 swipe-action 在 ionic 中无法正常运行错误 ([#569](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/569)) ([f2d1600](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/f2d1600))

## 1.0.0-beta.2(2019-09-05)

### Bug Fixes

* **list:** 修复 typescript 格式导致的编译报错 ([#565](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/565)) ([46e66f2](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/46e66f2))

* **website:** 修复官网 version 映射 ([#562](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/562)) ([3744833](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3744833))

* **codebox:** 修复 stackblitz package 依赖展示错误 ([#561](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/561)) ([61dcc28](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/61dcc28))

* **codebox:** 修复复制代码为对象的错误 ([#560](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/560)) ([630f63c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/630f63c))

* **codebox:** 修复 rawCode 转换错误 ([#558](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/558)) ([ddb89cb](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/ddb89cb))

* **website:** 修复官网运行错误 ([#557](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/557)) ([b44a095](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b44a095))

## 1.0.0-beta.1(2019-09-03)

### Bug Fixes

* **stepper:** 修复用户输入时按钮状态错误 ([#554](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/544)) ([0739e2c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0739e2c))

* **modal:** 修复函数调用错误 ([#543](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/543)) ([53cde92](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/53cde92))

### Features
* **All:** 支持 Angular 8.0 ([#553](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/pull/553)) ([c2fd82d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/c2fd82d))

## 1.0.0-beta.0(2019-08-21)

### BreakChange

* **toast:** toast 重构 ([454b55c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/454b55c))

* **picker & modal & action-sheet:** popup 相关重构
([62c4d60](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/62c4d60))

* **input-item:** 增加 label content API  ([#527](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/527)) ([109dbd6](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/109dbd6))

### Bug Fixes

* **modal:** 修复 visable 默认值为false ([#535](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/535)) ([1f6391e](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/1f6391e))
* **radio:** 删除重复API ([#508](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/508)) ([2fc7350](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/2fc7350))
* **textarea-item:** 修复自动高度错误([#501](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/501)) ([#502](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/502)) ([50ade9b](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/50ade9b))
* **picker:** 修复 okText & dismissText API ([#499](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/499)) ([0c9bc52](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0c9bc52))


### Features

* **action-sheet:** 增加单元测试 ([#515](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/515)) ([b74db68](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b74db68))
* **carousel:** 增加单元测试 ([#511](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/511)) ([7f80c13](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/7f80c13))
* **input-item:** 增加 label content API  ([#527](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/527)) ([109dbd6](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/109dbd6))
* **input-item:** 修复 input-item cursor bug ([#500](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/500)) ([9f9f579](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/9f9f579))
* **README:** 增加 CodeFactor&Twitter 标签 ([#490](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/490)) ([6fe3caf](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/6fe3caf))

## 0.12.5(2019-06-25)

### Bug Fixes

* **carousel:** 修复只包含一个元素时的宽度错误 ([#482](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/482)) ([7ab3cba](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/7ab3cba))

## 0.12.4 (2019-06-24)

### Bug Fixes

* **carousel:** 修复竖直模式时宽度错误 ([#477](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/477)) ([b0ca5ba](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b0ca5ba))
* **date-picker:** 增加 minuteStep 支持 ([#479](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/479)) ([246c222](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/246c222))

### Features

* **calendar:** 增加单测覆盖范围 ([#474](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/474)) ([7dd77ba](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/7dd77ba))
* **input-item:** 修复 clear 时出现的值错误 ([#472](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/472)) ([51772f7](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/51772f7))

## 0.12.3 (2019-06-05)

### Bug Fixes

* **date-picker:** 修复时间计算错误 ([#456](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/456)) ([413178d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/413178d))
* **date-picker:** 修复在safari中日期初始化可能出现无效日期 ([#454](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/454)) ([87c62a3](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/87c62a3))
* **radio-item-group:** 修复可选项在运行时变更时导致选中状态出错 ([#458](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/458)) ([#463](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/463)) ([0e3ca04](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0e3ca04))
* **stackblitz:** 为 @angular/compiler 设置正确的版本 ([#466](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/466)) ([3bc4053](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3bc4053))
* **picker:** 修复返回结果错误 ([#462](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/462)) ([eeabc11](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/eeabc11))

## 0.12.2 (2019-05-21)

### Bug Fixes

* **popupservice:** 在相关组件的providers里添加 popupservice ([#449](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/449)) ([a14ea6b](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/a14ea6b))


### Features

* **toast:** 支持 top 和 bottom 两种位置 ([#450](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/450)) ([77c326a](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/77c326a))

## 0.12.1 (2019-05-20)

### Bug Fixes

* **calendar:** 修复 calendar timepicker 显示标题错误 ([#444](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/444)) ([7ad01ba](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/7ad01ba))
* **mobile site:** 修复无线站点中的组件名称格式错误 ([#415](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/415)) ([f106942](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/f106942))
* **picker:** 修复 picker 样式错误 ([#434](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/434)) ([c09b85e](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/c09b85e))
* **badge:** 修复文案从空到非空时 badge 错误 ([#441](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/441)) ([fab7312](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/fab7312))
* **carousel:** 修复横竖屏切换时未动态调整的错误 ([#411](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/411)) ([4ff06d9](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/4ff06d9))


### Features

* **imagepicker:** 增加 capture&disableDelete API ([#410](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/410)) ([cfd733e](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/cfd733e))
* **swipe-action:** 增加 className api ([#436](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/436)) ([3a976c5](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3a976c5))
* **toast:** 提供一种新的API方案自注入 ([#426](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/426)) ([ad31989](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/ad31989))

## 0.12.0 (2019-04-30)

### BreakChange

* **tabbar:** 使用TabBarItem 替代 TabPane和TabBarTab, 使用上更加简单
* **grid:** 将 OnClick 修改为 onClick

### Bug Fixes

* **grid:** 将 OnClick 修改为 onClick ([#394](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/394)) ([bf3039a](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/bf3039a))
* **schematics:** 将 url 从 https 切换到 http ([#393](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/393)) ([0c3ad0f](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0c3ad0f))
* **stepper:** 修复 stepper 不可用的问题 ([#405](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/405)) ([acb2a95](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/acb2a95))

### Features

* **all:** 公开导出组件库 API ([#389](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/389)) ([dd9af23](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/dd9af23))
* **checkboxitem&radioitem:** 支持 wrap API ([#406](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/406)) ([db8a6c8](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/db8a6c8))
* **checkboxItem&radioItem:** API 与 listItem 同步 ([#408](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/408)) ([6cf232f](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/6cf232f))
* **dependencies:** 更新三方依赖 ([#401](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/401)) ([dcf4a61](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/dcf4a61))
* **docs:** 更新 README.md ([#398](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/398)) ([80bd1b5](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/80bd1b5))
* **styles:** 与 ant design mobile of react 样式同步 ([#403](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/403)) ([5c77b8c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5c77b8c))
* **tabs&tabbar:** tabs&tabbar 重构，支持动态增加面板、预加载以及自定义设置标签页尺寸，提升整体性能 ([#399](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/399)) ([f82ceab](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/f82ceab))

### Performance Improvements

* **code-box:** 优化stackblitz中demo参数. ([#404](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/404)) ([9c39051](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/9c39051))
* **site:** 更新首页 ([#397](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/397)) ([92ae470](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/92ae470))
* **tabs&tabbar:** 默认将 prerenderingSiblingsNumber设置为-1，预加载逻辑与React版本能保持一致 ([#407](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/407)) ([1db49eb](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/1db49eb))

## 0.11.9 (2019-04-18)

### Bug Fixes

* **calendar:** 修复样式更新后出现的样式问题 ([#385](//github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/385)) ([cee534a](//github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/cee534a))
* **datepickerview:** 修复日选择无法选中31号的问题 ([#383](//github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/383)) ([aac65b6](//github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/aac65b6))
* **inputitem:** 修复样式更新后出现的样式问题 ([#377](//github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/377)) ([97bf63e](//github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/97bf63e))
* **picker:** 修复样式更新后出现的样式问题 ([#387](//github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/387)) ([d5128af](//github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/d5128af))
* **carousel:** 修复走马灯不在视图内且页面没重新渲染的情况下会停止轮播的问题 ([#382](//github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/382)) ([362245f](//github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/362245f))

### Features

* **styles:** 与React版本进行样式同步 ([#376](//github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/376)) ([0c4b966](//github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0c4b966))
* **textarea:** 更改样式 ([#379](//github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/379)) ([bcd5d1f](//github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/bcd5d1f))


### Performance Improvements

* **site:** 资源链接默认使用https ([#373](//github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/373)) ([cc693e5](//github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/cc693e5))

## 0.11.8 (2019-04-04)

### Bug Fixes

* **tabbar:** 修复 tabbar 设置 activeTab 错误并修改 demo ([#345](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/345)) ([3f8becd](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3f8becd))
* **accordion:** 修复 accordion 支持异步加载 accordionPanel ([#355](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/355)) ([924bcc2](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/924bcc2))
* **carousel:** 修复 carousel vertical 模式异常 ([#344](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/344)) ([e9ae898](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/e9ae898))
* **inputitem:** 修复 inputitem extra 模板支持 ([#353](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/353)) ([aeb3cbe](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/aeb3cbe))
* **inputitem:** 修复 inputitem label 样式初始化问题 ([#364](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/364)) ([bd11c54](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/bd11c54))
* **picker:** 修复 异步 picker 需要更新选中数据 ([#346](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/346)) ([fbcc0cf](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/fbcc0cf))
* **picker:** 修复 picker wrap z-index 与 mask保持一致 ([#362](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/362)) ([3f2a83c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3f2a83c))

### Features

* **carousel:** carousel 支持拖拽 ([#350](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/350)) ([5dc49a4](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5dc49a4))

### Performance Improvements

* **modal:** modal 引入 coremodule ([#348](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/348)) ([a3b9014](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/a3b9014))

## 0.11.7 (2019-03-12)

### Bug Fixes

* **assets:** 修复 logo 名称 ([#319](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/319)) ([475eb14](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/475eb14))
* **grid:** 修复 contentType 返回错误 ([#320](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/320)) ([dd88a52](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/dd88a52))
* **input-item:** 修复 custom keyboard input 值 ([#330](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/330)) ([a73a7e8](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/a73a7e8))
* **popupservice:** 修复 popupservice 获取 component 名称时 运行时报错 ([#333](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/333)) ([b69ee5a](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b69ee5a))
* **textarea-item:** 修复 textarea-item 值保护 ([#331](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/331)) ([ffe4f8d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/ffe4f8d))

## 0.11.6 (2019-03-04)

### Bug Fixes

* **accordion:** 修复 accordion template 支持 ([#307](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/307)) ([15f90a6](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/15f90a6))
* **carousel:** 修复 carousel 检测高度变化 ([#290](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/290)) ([86be97d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/86be97d))
* **carousel:** 修复设置selecedindex值超出当前最大值的问题 ([#315](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/315)) ([193a4d6](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/193a4d6))
* **drawer:** 更新文档 ([#311](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/311)) ([1d53a15](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/1d53a15))
* **inputitem:** 修复输入中文时 onChange 不响应的问题 ([#299](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/299)) ([e7a925d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/e7a925d))
* **PopupService:** 修复多 PopupService 运行错误 ([#292](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/292)) ([3717db7](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3717db7))
* **swipe-action:** 修复无法响应滚动事件问题([#300](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/300)) ([98bd525](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/98bd525))
* **tabs:** 禁止 descendants ([#296](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/296)) ([5ed613e](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5ed613e))
* **date-picker:** 修复当 ngmodel 为 null 时选择出错的问题 ([#310](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/310)) ([58e88ca](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/58e88ca))


### Features

* **list:** renderHeader 和 renderFooter 支持 String和 Template 输入 ([#313](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/313)) ([546b38d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/546b38d))


### Performance Improvements

* **logo:** 更换全新的logo ([#314](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/314)) ([a66be30](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/a66be30))

## 0.11.5 (2019-02-21)

### Bug Fixes

* **actionsheet:** 将模板中 title 改成 message ([#283](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/283)) ([f850e1a](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/f850e1a))
* **date-picker-view:** 修复 input 不生效的问题 ([#287](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/287)) ([7d74e54](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/7d74e54))
* **stepper:** 修复 float 计算bug ([#280](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/280)) ([5cd1f6c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5cd1f6c))
* **swipe-action:** 修复 autoclose 不生效bug ([#282](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/282)) ([acb180e](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/acb180e))


### Performance Improvements

* **tabbar:** 扩大 tabbartab 点击区域 ([#286](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/286)) ([5830cd6](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5830cd6))

## 0.11.4 (2019-02-14)

### Bug Fixes

* **carousel:** 修复设置 Carousel 选中序列失败的问题 ([#269](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/269)) ([55ae6d2](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/55ae6d2))
* **input-item:** 修复 iOS9 中文字符输入问题 ([#249](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/249)) ([f421746](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/f421746))
* **notice-bar:** 修复 notice-bar-card 颜色问题 ([#274](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/274)) ([53f5b45](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/53f5b45))
* **searchbar:** 修复 iOS9 中文字符输入问题 ([#250](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/250)) ([3e7efd4](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3e7efd4))
* **date-picker:** 修复不使用onOK导致的下一次显示失败问题 ([#258](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/258)) ([2f5fc79](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/2f5fc79))
* **date-picker:** 修复设置最大最小日期后打开 Picker 显示错误 ([#256](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/256)) ([41f20f5](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/41f20f5))
* **date-picker:** 修复选择最早最晚时间时的 interval ([#267](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/267)) ([3fa56dc](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3fa56dc))
* **date-picker:** 修复设置minDate错误 ([#243](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/243)) ([8fdbe8f](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/8fdbe8f))
* **pulltorefresh:** 修复上划然后下划时导致的 refresh 信号错误 ([#248](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/248)) ([5fd57d7](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5fd57d7))


### Features

* **button:** 增加 dashed 样式 ([#273](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/273)) ([8759db0](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/8759db0))
* **grid:** Grid 中支持动态的 ng-content ([#268](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/268)) ([2a579a2](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/2a579a2))
* **grid:** 支持 自定义 icon 和本地静态资源 ([#257](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/257)) ([eafe8ec](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/eafe8ec))


### Performance Improvements

* **picker:** 删除成员默认值 ([#272](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/272)) ([ec748c3](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/ec748c3))

## 0.11.2 (2019-01-11)

### Bug Fixes

* **actionsheet:** 修复 Actionsheet 没有销毁 locale 订阅问题 ([#236](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/236)) ([d719496](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/d719496))
* **carousel:** 修复 Carousel 选中序列初始化失败问题 ([#230](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/230)) ([5482cb2](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5482cb2))
* **pulltorefresh:** 修复没有使用 NgModel 出现的错误 ([#229](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/229)) ([5a3ba5d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5a3ba5d))

### Features

* **actionsheet:** 支持 locale 国际化 ([#232](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/232)) ([39870da](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/39870da))
* **carousel:** 仅有1个元素时禁止drag ([#239](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/239)) ([799ce51](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/799ce51))
* **datepicker:** 增加disabled 属性 ([#233](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/233)) ([8f772a9](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/8f772a9))
* **picker:** 增加 disabled 属性 ([#231](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/231)) ([02733b4](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/02733b4))
* **switch:** 根据选中状态在子元素设置类名 ([#238](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/238)) ([1117c7c](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/1117c7c))
* **showcase:** 在 kitchen-sink 中设置 "user-select: none" ([#234](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/234)) ([65ad469](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/65ad469))


### Performance Improvements

* **actionsheet:** 使用 cdk 优化实现([#228](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/228)) ([9a9988a](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/9a9988a))

## 0.11.1 (2019-01-08)

### Bug Fixes

* **calendar:** 修复 timepicker 选择报错([#216](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/216)) ([03ffa9e](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/03ffa9e))
* **codebox:** 升级ng-zorro-antd-mobile的版本号 ([#218](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/218)) ([3fb41f1](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3fb41f1))
* **modal:** 修复无 actions 报错. ([#222](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/222)) ([25b7aec](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/25b7aec))
* **package.json:** 升级ng-zorro-antd依赖 ([#213](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/213)) ([b53ff31](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b53ff31))
* **showcase:** 修复文档官网 icon 显示问题 ([#214](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/214)) ([bfe2b3d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/bfe2b3d))

### Performance Improvements

* **modal:** 优化 modal service 的使用 ([#220](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/220)) ([4fca40a](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/4fca40a))

## 0.11.0 (2018-12-29)

### Bug Fixes

* **ActionSheet:** 修复当无标题或消息时头部不为空的问题 ([#192](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/192)) ([b0f41b7](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b0f41b7))
* **checkbox:** 修复初始值为选中时checkbox状态不对的问题 ([#193](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/193)) ([0293e85](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0293e85))
* **input-item:** 修复 input 值不能为空字符串或0的问题 ([#185](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/185)) ([59e0ea8](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/59e0ea8))
* **input-item:** 修复 inputitem 值保护问题 ([#196](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/196)) ([883c2ba](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/883c2ba))
* **package.json:** 修复 Invalid Host/Origin header 导致的循环问题 ([#199](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/199)) ([450c66a](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/450c66a))
* **picker:** 修复当使用服务并点击 OK 按钮抛错的问题 ([#176](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/176)) ([40a8fee](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/40a8fee))
* **picker:** 修复点击取消无响应的问题 ([#205](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/205)) ([bee4fc4](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/bee4fc4))
* **textarea-item:** 修复 textarea 值不能为空字符串或0的问题 ([#186](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/186)) ([0759f65](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0759f65))
* **textarea-item:** 修复 textarea-item 值保护问题 ([#197](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/197)) ([e2c0157](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/e2c0157))


### Features

* **Framework:** 支持 Angular 7.0
* **date-picker:** date-picker 支持 ngmodel ([#207](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/207)) ([c1e6d11](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/c1e6d11))
* **picker-view:** picker-view 支持 ngModel ([#180](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/180)) ([500c893](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/500c893))
* **pulltorefresh:** 支持 scrollendrefresh 和 上、下两个方向滑动刷新 ([#204](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/204)) ([149c461](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/149c461))
* **range:** range 支持 ngmodel ([#208](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/208)) ([26d019d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/26d019d))
* **searchbar:** searchbar 支持 ngModel ([#179](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/179)) ([8bd39d7](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/8bd39d7))
* **slider:** slider 支持 ngModel ([#202](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/202)) ([3db39ae](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/3db39ae))
* **stepper:** stepper 支持 ngModel ([#181](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/181)) ([23f36c1](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/23f36c1))
* **modal:** 增加 modal closable 和 maskClosable 演示样例 ([#195](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/195)) ([d3d3478](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/d3d3478))


### Performance Improvements

* **picker-view:** perf docs and demo ([#189](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/189)) ([fc9627d](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/fc9627d))

## 0.10.1 (2018-12-20)

### Bug Fixes

* **checkbox:** disabled 状态为 true 时 checked 状态应该锁定 ([#170](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/170)) ([5fe311f](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/5fe311f))
* **step and slider-marks:** 修复AOT build 错误 ([#157](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/157)) ([94cb387](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/94cb387))
* **button:** 修复 loading input 只在第一次启动时生效的问题. ([#161](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/161)) ([b54bd04](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b54bd04))

### Features

* **calendar:** ngModel 支持 ([#164](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/164)) ([327d33b](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/327d33b))
* **checkbox&radio:** ngModel&Onpush 支持 ([#167](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/167)) ([b1b4807](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b1b4807))
* **inputitem:** 增加 fontColor input ([#156](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/156)) ([0ef2620](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/0ef2620))
* **picker:** ngModel 支持 ([#165](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/165)) ([b4af7c7](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/b4af7c7))
* **progress:** nzm-progress 支持 大于100%的进度 ([#152](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/152)) ([021f7d8](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/021f7d8))
* **switch:** ngModel 支持 ([#145](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/145)) ([6998e40](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/6998e40))
* **textarea-item:** ngModel 支持 ([#162](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/162)) ([6b60cca](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/6b60cca))

## 0.9.10 (2018-12-06)

### Bug Fixes

* **calendar:** 引入 LocalProvider Module ([#134](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/134)) ([37f20ae](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/37f20ae))
* **checkbox&radio:** 修复回调状态错误([#122](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/122)) ([e709b86](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/e709b86))
* **popover:** 修复 Visable Input 除初始化外无效 ([#127](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/127)) ([05313a4](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/05313a4))
* **Searchbar:** 修复 LocaleProviderService 依赖问题 ([#133](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/133)) ([1ac6008](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/1ac6008))
* **TabBar:** 移除对 TabsModule 的依赖([#135](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/135)) ([eab449b](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/eab449b))

### Features

* **badge:** 在 text 文案外层增加 span 标签 ([#125](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/125)) ([e362320](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/e362320))
* **popover:** 增加自定义样式支持 ([#129](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/129)) ([26bbe53](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/26bbe53)), closes [#120](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/120)
* **PickerView:** 引入 PickerModule 和 LocaleProviderModule
([#141](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/141)) ([52ebaeb](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/52ebaeb))
* **popover:** 增加是否使用组件内部的点击自动关闭 opover
([#130](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/130)) ([71ea780](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/commit/71ea780))

## 0.9.9 (2018-11-27)

### Bug Fixes

* **locale-provider:** 让 locale-provider 跨模块生效; ([#113](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/113)) ([e09f0a3](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/e09f0a3))
* **picker:** 引入 OverlayModule ([#111](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/111)) ([722ee27](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/722ee27))
* **grid:** 修复item数超过数量会出错的bug ([#119](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/119)) ([34e1dd7](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/34e1dd7))


### Features

* **locale:** 增加丹麦语 locale ([5361536](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/5361536))


## 0.9.7 (2018-11-14)

### Bug Fixes

* **action-sheet:** 修复点击item事件会响应背景点击事件 ([#98](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/98)) ([b24bcbc](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/b24bcbc))
* **action-sheet:** 修复遗漏点击item事件 ([#99](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/99)) ([1697cda](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/1697cda))
* **badge:** 修复 badge 单测错误 ([#83](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/83)) ([43eb155](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/43eb155))
* **carousel:** 修复只有一个 item 时宽度不对的问题 ([#86](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/86)) ([bb59fe7](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/bb59fe7))
* **date-picker:** 修复没有 locale 输入时报错 ([#103](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/103)) ([2aa43aa](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/2aa43aa))
* **input-item:** 使用 ngzone.run set value ([#101](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/101)) ([ed2b243](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/ed2b243))
* **LocaleProvider:** 导出 LOCAL_PROVIDER_TOKEN ([#96](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/96)) ([16922a2](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/16922a2))
* **tabs:** 修复 MacOS Safari及 iOS 9.3以下版本的显示问题 ([#106](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/106)) ([ba9e43b](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/ba9e43b))
* **Toast:** 修复 toast 在 init 初始化时报错 ([#93](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/93)) ([49d52be](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/49d52be))
* **showcase:** 更改展开代码 icon ([#97](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/97)) ([8bcfda5](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/8bcfda5))

### Features

* **date-picker-view:** 增加indicatorStyle参数 ([#104](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/104)) ([e97acbd](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/e97acbd))
* **picker:** 增加动态初始化方式 ([#105](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/105)) ([90866df](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/90866df))

## 0.9.6 (2018-10-24)

### Bug Fixes

* **carousel:** 触摸响应时禁止冒泡传递([#61](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/61)) ([c44ba59](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/c44ba59))
* **carousel:** 当vertical:false时修复走马灯无宽度问题([#67](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/67)) ([8dd703f](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/8dd703f))
* **carousel:** 只有2页幻灯片时修复 mousemove 问题 ([#56](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/56)) ([bc02951](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/bc02951))
* **icon:** 修复 icon 的 line-height ([#46](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/46)) ([#47](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/47)) ([28d76f2](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/28d76f2))
* **pulltorefresh:** 修复 drag up touch 问题 ([#51](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/51)) ([8b905cc](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/8b905cc))
* **textarea:** 修复 textarea-item test case 错误 ([#50](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/50)) ([f2bbdfb](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/f2bbdfb))
* **showcase:** 替换正确的钉钉QR码 ([#74](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/74)) ([b4e7483](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/b4e7483))

---
## 0.9.5 （2018-10-15）

### Bug Fixes

* **codebox:** 修复英文网站中弹出代码框显示中文“返回“bug ([#35](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/35)) ([0720fdc](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/0720fdc))
* **codebox:** 修复StackBliz中的问题 ([#41](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/41)) ([8adcbb0](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/8adcbb0))
* **package.json:** 取消Package Json的版本号 ([#27](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/27)) ([fc3cf65](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/fc3cf65))
* **popover:** 为 PopoverOptions 加入providers ([#30](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/30)) ([8f9e1d3](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/8f9e1d3))
* **textarea:** 修复textarea test case错误 ([#36](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/36)) ([97639fc](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/97639fc))
* **package.json:** 修复npm run start在windows中无法运行的错误 ([#42](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/42)) ([68a0453](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/68a0453))
* **tabs:** 修复swipeable为false时useOnPan依然生效的问题 ([#43](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/43)) ([2d63730](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/2d63730))

### Features

* **nav-bar:** 增加 icon string类型支持 ([#38](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/38)) ([4a89b0c](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/4a89b0c))

### Docs

* **README:** 在README中增加更多的状态指示 ([#44](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/44)) ([a59797e](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/a59797e))

---
## 0.9.4 (2018-10-10)


### Bug Fixes

* **button:** 修复Button带自定义icon显示问题([a3c6150](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/a3c6150))
* **ci:** 修复ci node版本号 ([312fce6](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/312fce6))
* **components:** 改变Subject引用方式 ([88864ab](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/88864ab))
* **date-picker:** 修复iOS上无效日期问题 ([6620635](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/6620635))
* **demo:** 修复展开代码不可见问题 ([6d65ebb](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/6d65ebb))
* **pulltorefresh:** 修复下拉刷新的Demo ([8725c4b](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/8725c4b))
* **input-item:** 修复custom-keyboard无法隐藏问题 ([#21](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/21)) ([9b8f3da](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/9b8f3da))
* **carousel:** 修复走马灯最后一页偶现白屏问题 ([2c5cd92](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/2c5cd92))
* **tabs:** 修复TabBar与Tabs混用导致第一次加载时Tabs高亮下划线无法正常渲染问题 ([#7](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/7)) ([6502082](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/6502082))
* **steps:** 更新setTimeout时间 ([6da37ab](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/6da37ab))


### Features

* **ci:** 更新ci的配置 ([0b178c4](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/0b178c4))
* **list-item:** 移除className依赖 ([#20](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/20)) ([e0850f6](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/e0850f6))
* **modal:** 增加Modal测试 ([#18](https://github.com/NG-ZORRO/ng-zorro-antd-mobile/issues/18)) ([7c59b61](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/7c59b61))
* **template:** 增加issue和PR模板 ([bc59939](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/bc59939))

## 0.9.0（2018-09-29）

**NG-ZORRO** 组件库从设计初期就包含了桌面端与无线端两套。

从 2016 年下半年开始，**阿里巴巴集团数据技术及产品部**无线团队就开始基于 **Ant Design Mobile** 设计规范进行 **Angular** 2 代及以上的无线组件研发，并应用在了数据无线业务中。

在 2017 年下半年，**Ant Design Mobile** React 版本开始进行 2.x 重构。为了保持与 React 版本同步，**NG-ZORRO-MOBILE** 中止了对标 **Ant Design Mobile 1.x** 的工作，开始整体组件重构对标 **React 2.x** 版本。

现在 **NG-ZORRO-MOBILE** 已完成了与 **Ant Design Mobile 2.x** 45 个组件的同步工作，基于最新的 **Angular ^6.0.0** 与 **RxJS ^6.0.0** 构建，与 **@angular/cli** 进行了深度整合。同时我们与 **NG-ZORRO DESKTOP** 组件库共享文档和官网构建系统，保持风格统一。
