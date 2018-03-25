# Input *输入框*

<example />

## API

| 属性 | 类型 | 默认值 | 说明 |
| --- | --- | --- | --- |
| defaultValue | string \| number | | 默认值 |
| delay | number | 400 | 用户输入触发 onChange 和校验间隔时间，单位 毫秒。|
| name | string | 无 | Form 存取数据的名称 |
| onChange | function(d) | | 值改变回调函数 |
| placeholder | string | | 同原生 input 标签的 placeholder |
| popover | string | | 信息弹出位置，可选值为 \['top-left', 'top', 'top-right', 'bottom-left', 'bottom', 'bottom-right'] |
| size | string | 'default' | 可选值 \['large', 'default', 'small'] |
| style | object | 无 | 最外层扩展样式 |
| tip | string \| ReactElement | | 提示信息 |
| type | string | | 同原生 input 标签的 type |
| value | string \| number | | defaultValue 和 value 可以同时设置，defaultValue 会被value覆盖<br />在Form中，value会被表单接管，value无效 |