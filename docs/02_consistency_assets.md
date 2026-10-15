# 角色一致性资产包

## 目的

后续无论使用生图、图生视频还是参考视频生成，都需要尽量保持同一个角色的体型、颜色、脸部、轮廓和步态。

## 最低配置资产

1. 正面标准图
2. 完整侧面标准图
3. 3/4 视图
4. 背面参考图
5. 标准颜色卡
6. 轮廓 / silhouette 参考
7. 标准比例说明
8. 一套侧视 walking cycle 关键帧

## Walking Cycle 建议

第一版先做 8 帧循环：

1. Contact A
2. Down A
3. Passing A
4. Up A
5. Contact B
6. Down B
7. Passing B
8. Up B

所有风格都尽量以这套相位作为动作锚点。

## 需要固定的变量

- 朝向：向右
- 角色高度占画面比例
- 脚底所在基准线
- 身体重心上下起伏幅度
- 单步时长
- 单步水平位移感
- 头部和身体比例
- 主要配色

## 生成实验记录

每次抽卡都保存：

- 使用平台 / 模型
- Prompt
- Negative Prompt / 限制条件
- 参考图
- Seed（若可用）
- 生成参数
- 最终结果
- 成功点
- 漂移问题

## 资产目录建议

```text
assets/
  character/
    front/
    side/
    three_quarter/
    back/
    palette/
    silhouette/
    walk_cycle/
  references/
  music/
```
