三维内容的表达：

+ mesh

+ Point Cload

+ Occupancy Filed

+ Signed Distance Field

外观表达：

+ material texture map（unwrap） + environmental lighting

+ Radiance field（材质光照结合，易解 ）

渲染过程：

+ 必须fully differentiable





NeRF的geometry并不好

easy for differetiable rendering

rendering is more expensive

editing is hard





NeRF无边界场景问题

NeRF++

区分inward-facing和outward-facing capture

outward-facing capture：合成bounded unit cube
