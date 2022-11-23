#盒模型
CSS盒模型定义了盒的每个部分包含 margin, border, padding, content 。根据盒子大小的计算方式不同盒模型分成了两种，标准盒模型和怪异盒模型。
标准模型，给盒设置 `width` 和 `height`，实际设置的是 content box。`padding` 和 `border `再加上设置的宽高一起决定整个盒子的大小。
怪异盒模型，给盒设置 `width` 和 `height`，包含了`padding`和`border `，设置的 `width` 和 `height`就是盒子实际的大小。默认情况下，盒模型都是标准盒模型。
设置标准盒模型：`box-sizing:content-box`；
设置怪异盒模型：`box-sizing:border-box`