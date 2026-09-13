<markdown>
# 颜色

使用颜色字符串快捷设置样式，或使用颜色对象完整定制标签颜色。
</markdown>

<template>
  <n-space>
    <n-tag color="#18a058">
      字符串颜色
    </n-tag>
    <n-tag :color="{ color: '#BBB', textColor: '#555', borderColor: '#555' }">
      告别夜晚 等待天亮
    </n-tag>
  </n-space>
</template>
