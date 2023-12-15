<!--
 * @Author: wy
 * @Date: 2023-12-13 15:08:05
 * @LastEditors: wy
 * @LastEditTime: 2023-12-14 10:18:21
 * @FilePath: /笔记/webgl-three/readme.md
 * @Description:
-->

## three.js

### three 要素

#### 场景(scene)

#### 相机(camera)

- 透视相机
  遵循近大远小规则，可视范围是一个圆锥的范围

- 正交相机
  只要在可视范围内，不管远近，物体的大小不变，可视范围是一个立方体的范围。

`lookAt`可以改变摄像机的朝向，模拟实现，人眼望向的目标点。

#### 渲染器(renderer)

### 几何图形(geometry)
