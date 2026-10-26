# マランゴーニ効果 表面張力流 Canvas

表面張力の不均一によるマランゴーニ流を2Dパーティクルで可視化。

## 機能
- 温度勾配スライダー（ΔT 0〜80K）でΔγ計算（Δγ = -dγ/dT × ΔT）
- パーティクルは高γ(冷側)方向に引き寄せられ循環流を形成
- 石鹸膜の薄膜干渉色グラデーション（50nm〜450nm）をpixel描画
- 速度係数・パーティクル数スライダー
- 一時停止/リセットボタン
- 表面流・戻り流の流れ方向表示

## 技術
- 静的SPA（単一index.html）
- Tailwind CSS CDN
- Canvas + requestAnimationFrame
- createImageData で干渉色ピクセル描画
- localStorage不使用
