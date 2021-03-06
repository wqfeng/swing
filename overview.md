# 概述

Swing API 是一组方便开发者使用 Java 开发前端/GUI 应用的可扩展组件。它构建于 AWT API 之上，并且几乎涵盖了 AWT 的所有功能，顺理成章地取而代之。Swing 组件遵循模型-视图-控制架构，以达成如下三条准则：

- 一个 API 支持多种外观。
- API 由模型驱动，最高级别的 API 不需要持有数据。
- API 使用 Java Bean 模型，构建工具和 IDE能为开发者提供更好的支持。

## MVC 架构

Swing API 基于一种松散的 MVC 架构，具体如下：

- 模型代表组件数据。
- 视图是组件数据的视觉展示。
- 控制器接收用户来自视图的输入，并且反映组件数据的变化。
- Swing 组件将模型作为单独的元素，将视图和控制器混在一起作为用户界面元素。这样，Swing 就有了可插拔的外观架构。

## Swing 的功能

- **轻量级**——Swing 组件独立于本地操作系统 API，Swing API 控件几乎都由纯 Java 代码渲染，而不需调用底层操作系统。
- **丰富的控件**——Swing 提供了丰富的高级控件，比如树、选项卡、滑动条、颜色选择器和表格。
- **高度定制化**——Swing 控件的外表和内部表示独立，因此可以轻松定制。
- **可插拔的外观**——基于 Swing 的 GUI 应用的外观能在运行期根据提供的值动态改变。