# 组件 API 和 Demo 设计规范

1. 命名方式用中划线风格：组件的参数名和事件名统一使用中划线格式。
2. 组件名称前缀：组件的命名统一使用D前缀。
3. 针对需要双向绑定的参数，需要直接用v-model，避免增加额外参数，例如v-model:xxx。
4. 原生支持的属性尽量不再用API去单独声明，直接通过attrs透传即可，比如placeholder。