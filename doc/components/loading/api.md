## Loading Props

| 属性          | 类型    | 默认值 | 可选值                                                                        | 必传 | 说明                               |
| ------------- | ------- | ------ | ----------------------------------------------------------------------------- | ---- | ---------------------------------- |
| type          | String  | '1_0'  | -                                                                             | N    | 类型编号。                         |
| height        | String  | '8'    | '2'/'4'/'6'/'8'/'12'/'16'/'20'/'28'/'36'/'48'/'56'/'64'/'72'/'80'/'96'/'full' | N    | 容器高度。                         |
| width         | String  | '8'    | '2'/'4'/'6'/'8'/'12'/'16'/'20'/'28'/'36'/'48'/'56'/'64'/'72'/'80'/'96'/'full' | N    | 容器宽度。                         |
| theme         | Boolean | false  | true/false                                                                    | N    | 是否使用主题色，仅单色生效。       |
| inverse       | Boolean | false  | true/false                                                                    | N    | 是否使用反差色，仅单色与双色生效。 |
| customColor   | Array   | []     | -                                                                             | N    | 自定义颜色数组。                   |
| lazyAnimation | Boolean | true   | true/false                                                                    | N    | 是否开启懒动画。                   |
| speed         | Number  | 1      | -                                                                             | N    | 动画速度，基数为 1。               |
