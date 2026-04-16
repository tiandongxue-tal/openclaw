# Figma 设计稿 - 完整 AI 解析文档

## 📊 项目概览

| 属性 | 值 |
|------|-----|
| **页面名称** | 密友详情 |
| **节点 ID** | 15556-19842 |
| **文件名称** | NEXT-英语天天练UI交付文件2026（上半年） |
| **页面尺寸** | 812 × 375 px |
| **总元素数** | 6,054 个 |
| **最大层级** | 16 层 |
| **文本元素** | 31 个 |
| **矩形元素** | 793 个 |
| **框架元素** | 21 个 |
| **编组元素** | 144 个 |
| **渐变效果** | 1,157 处 |
| **图片资源** | 95 个 |

---

## 🎨 完整设计令牌 (Design Tokens)

### 颜色系统 (Colors)

```css
:root {
  /* ========== 主色调 ========== */
  --color-primary-900: #011829;    /* 最深蓝 */
  --color-primary-800: #023153;    /* 深蓝 - 主背景 */
  --color-primary-700: #034a7d;    /* 中深蓝 */
  --color-primary-600: #0463a7;    /* 蓝色 */
  --color-primary-500: #0078e9;    /* 亮蓝 - 强调/按钮 */
  --color-primary-400: #3aaee4;    /* 天蓝 - 渐变 */
  --color-primary-300: #22c6e1;    /* 青色 - 辅助 */
  --color-primary-200: #81e3f0;    /* 浅青 */
  --color-primary-100: #c0f1f8;    /* 最浅青 */

  /* ========== 中性色 ========== */
  --color-neutral-900: #000000;    /* 纯黑 */
  --color-neutral-800: #232435;    /* 深灰黑 - 主文字 */
  --color-neutral-700: #333333;    /* 深灰 - 次要文字 */
  --color-neutral-600: #666666;    /* 中灰 - 辅助文字 */
  --color-neutral-500: #999999;    /* 浅灰 - 禁用 */
  --color-neutral-400: #b3b3b3;    /* 更浅灰 */
  --color-neutral-300: #cccccc;    /* 浅灰 */
  --color-neutral-200: #e6e6e6;    /* 更浅 */
  --color-neutral-100: #f5f5f5;    /* 背景灰 */
  --color-neutral-50: #ffffff;     /* 纯白 */

  /* ========== 功能色 ========== */
  --color-accent-pink: #E559E5;           /* 关系标签 */
  --color-accent-pink-light: #F0A3F0;     /* 浅粉 */
  --color-accent-brown: #A75E0F;          /* 角色名 */
  --color-accent-brown-light: #C67B23;    /* 浅棕 */
  --color-accent-orange: #622E00;         /* Tab选中 */
  --color-accent-gold: #FFD700;           /* VIP标识 */
  --color-accent-purple: #7B3FD5;         /* 渐变色1 */
  --color-accent-cyan: #4ADEDE;           /* 渐变色2 */

  /* ========== 渐变定义 ========== */
  --gradient-page-bg: linear-gradient(180deg, #023153 0%, #0d4a7c 50%, #1a5c99 100%);
  --gradient-header: linear-gradient(135deg, #023153 0%, #0078e9 100%);
  --gradient-card: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --gradient-button: linear-gradient(90deg, #0078e9 0%, #22c6e1 100%);
  --gradient-vip: linear-gradient(135deg, #FFD700 0%, #FFA500 100%);
  --gradient-svip: linear-gradient(135deg, #E559E5 0%, #FF6B9D 100%);
}
```

### 字体系统 (Typography)

```css
:root {
  /* ========== 字体族 ========== */
  --font-family-display: 'FZLanTingYuanS-B-GB', 'PingFang SC', 'Microsoft YaHei', sans-serif;
  --font-family-title: 'FZLanTingYuanS-DB-GB', 'PingFang SC', 'Microsoft YaHei', sans-serif;
  --font-family-body: 'PingFang SC', 'FZLanTingYuanS-R-GB', 'Microsoft YaHei', sans-serif;
  --font-family-tag: 'FZLTTHK--GBK1-0', 'Arial', sans-serif;
  --font-family-mono: 'SF Mono', 'Consolas', monospace;

  /* ========== 字体大小 (基于 4px 基准) ========== */
  --font-size-2xs: 6px;     /* 极小标签 */
  --font-size-xs: 8px;      /* 标签/徽章 */
  --font-size-sm: 10px;     /* 小字说明 */
  --font-size-base: 12px;   /* 正文 */
  --font-size-lg: 14px;     /* 次要标题 */
  --font-size-xl: 16px;     /* 标题 */
  --font-size-2xl: 18px;    /* 大标题 */
  --font-size-3xl: 20px;    /* 更大标题 */
  --font-size-4xl: 24px;    /* 页面标题 */
  --font-size-5xl: 32px;    /* 超大标题 */

  /* ========== 行高 ========== */
  --line-height-tight: 1.2;
  --line-height-normal: 1.4;
  --line-height-relaxed: 1.6;
  --line-height-loose: 1.8;

  /* ========== 字重 ========== */
  --font-weight-light: 300;
  --font-weight-normal: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* ========== 字间距 ========== */
  --letter-spacing-tight: -0.02em;
  --letter-spacing-normal: 0;
  --letter-spacing-wide: 0.02em;
}
```

### 间距系统 (Spacing)

```css
:root {
  /* ========== 基础间距 (4px 基准) ========== */
  --space-0: 0;
  --space-1: 4px;
  --space-2: 8px;
  --space-3: 12px;
  --space-4: 16px;
  --space-5: 20px;
  --space-6: 24px;
  --space-7: 28px;
  --space-8: 32px;
  --space-9: 36px;
  --space-10: 40px;
  --space-12: 48px;
  --space-14: 56px;
  --space-16: 64px;
  --space-20: 80px;
  --space-24: 96px;
  --space-28: 112px;
  --space-32: 128px;

  /* ========== 组件间距 ========== */
  --gap-xs: var(--space-1);
  --gap-sm: var(--space-2);
  --gap-md: var(--space-3);
  --gap-lg: var(--space-4);
  --gap-xl: var(--space-6);

  /* ========== 内边距 ========== */
  --padding-xs: var(--space-1);
  --padding-sm: var(--space-2);
  --padding-md: var(--space-3);
  --padding-lg: var(--space-4);
  --padding-xl: var(--space-6);

  /* ========== 外边距 ========== */
  --margin-xs: var(--space-1);
  --margin-sm: var(--space-2);
  --margin-md: var(--space-3);
  --margin-lg: var(--space-4);
  --margin-xl: var(--space-6);
}
```

### 圆角系统 (Border Radius)

```css
:root {
  --radius-none: 0;
  --radius-xs: 2px;
  --radius-sm: 4px;
  --radius-md: 6px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 20px;
  --radius-4xl: 24px;
  --radius-full: 9999px;
}
```

### 阴影系统 (Shadows)

```css
:root {
  --shadow-none: none;
  
  /* 小阴影 */
  --shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.05);
  --shadow-sm-colored: 0 1px 2px rgba(2, 49, 83, 0.1);
  
  /* 中阴影 */
  --shadow-md: 0 2px 4px rgba(0, 0, 0, 0.1);
  --shadow-md-colored: 0 2px 8px rgba(2, 49, 83, 0.15);
  
  /* 大阴影 */
  --shadow-lg: 0 4px 8px rgba(0, 0, 0, 0.15);
  --shadow-lg-colored: 0 4px 12px rgba(2, 49, 83, 0.2);
  
  /* 超大阴影 */
  --shadow-xl: 0 8px 16px rgba(0, 0, 0, 0.2);
  --shadow-xl-colored: 0 8px 24px rgba(2, 49, 83, 0.25);
  
  /* 卡片阴影 */
  --shadow-card: 0 2px 8px rgba(0, 0, 0, 0.1);
  --shadow-card-hover: 0 4px 16px rgba(0, 0, 0, 0.15);
  --shadow-card-elevated: 0 20px 60px rgba(0, 0, 0, 0.3);
  
  /* 内阴影 */
  --shadow-inner: inset 0 2px 4px rgba(0, 0, 0, 0.05);
  --shadow-inner-colored: inset 0 2px 4px rgba(2, 49, 83, 0.1);
}
```

### 动画系统 (Animations)

```css
:root {
  /* 过渡时间 */
  --duration-instant: 0ms;
  --duration-fast: 100ms;
  --duration-normal: 200ms;
  --duration-slow: 300ms;
  --duration-slower: 500ms;

  /* 缓动函数 */
  --ease-linear: linear;
  --ease-in: cubic-bezier(0.4, 0, 1, 1);
  --ease-out: cubic-bezier(0, 0, 0.2, 1);
  --ease-in-out: cubic-bezier(0.4, 0, 0.2, 1);
  --ease-bounce: cubic-bezier(0.68, -0.55, 0.265, 1.55);
  --ease-spring: cubic-bezier(0.175, 0.885, 0.32, 1.275);
}
```

---

## 📐 完整页面结构

### 层级结构图

```
密友详情 [FRAME] - 根容器 (812 x 375px, 位置: 415,533)
├── 天天学_bg [GROUP] - 背景层
│   ├── Mask group [GROUP]
│   │   ├── Rectangle 34624920 [RECTANGLE] - 蒙版矩形
│   │   ├── Rectangle 34624921 [RECTANGLE] - 渐变背景
│   │   └── Mask group [GROUP]
│   │       └── ... (更多渐变层)
│   └── ... (更多背景装饰)
│
├── bg [FRAME] - 内容容器
│   ├── bg [GROUP] - 背景装饰
│   │   ├── Rectangle 1329131339 [RECTANGLE] - 装饰矩形
│   │   ├── image 16609 [RECTANGLE] - 装饰图片
│   │   ├── image 16610 [RECTANGLE] - 装饰图片
│   │   ├── Vector 8493 [VECTOR] - 矢量图形
│   │   └── Group 2090061646 [GROUP] - 装饰组
│   │
│   ├── 返回 [GROUP] - 返回按钮
│   │   └── 返回 [TEXT] - "返回" 文字
│   │
│   ├── 园丁pose1 1 [RECTANGLE] - 角色图片
│   ├── 唐影pose 1 [RECTANGLE] - 角色图片
│   │
│   ├── Group 2085669007 [GROUP] - 装饰组
│   ├── Group 2090061719 [GROUP] - 装饰组
│   │
│   ├── 姐妹 [GROUP] - 关系标签区
│   │   ├── 12 [TEXT] - 亲密度数值
│   │   ├── 姐妹 [TEXT] - 关系标签
│   │   └── Sister [TEXT] - 英文标签
│   │
│   ├── 角色名区 [GROUP]
│   │   ├── 贝吉塔王子 [TEXT]
│   │   └── 松鼠的大尾巴... [TEXT]
│   │
│   ├── Tab区 [GROUP]
│   │   ├── 密友关系 [TEXT] - 选中
│   │   └── 密友记录 [TEXT] - 未选中
│   │
│   └── 任务列表 [GROUP]
│       ├── 说明文字 [TEXT] - "通过以下途径提升亲密度"
│       ├── 任务1 [GROUP]
│       │   ├── 发送学习鼓励 [TEXT]
│       │   └── 去完成 [TEXT]
│       └── 更多任务...
│
└── ... (其他装饰元素)
```

---

## 🧩 组件详细规格

### 组件 1: 页面容器 (PageContainer)

```typescript
interface PageContainerProps {
  width: 812;
  height: 375;
  background: 'linear-gradient(180deg, #023153 0%, #0d4a7c 50%, #1a5c99 100%)';
  overflow: 'hidden';
  position: 'relative';
}

const pageContainerStyle = {
  width: '812px',
  height: '375px',
  background: 'linear-gradient(180deg, #023153 0%, #0d4a7c 50%, #1a5c99 100%)',
  borderRadius: '20px',
  overflow: 'hidden',
  position: 'relative' as const,
  boxShadow: '0 10px 40px rgba(0,0,0,0.5)'
};
```

### 组件 2: 返回按钮 (BackButton)

```typescript
interface BackButtonProps {
  position: { x: 445; y: 550 };
  size: { width: 78; height: 28 };
  text: '返回';
  icon: 'arrow-left';
}

const backButtonStyle = {
  position: 'absolute' as const,
  left: '30px',  // 445 - 415 (父容器偏移)
  top: '17px',   // 550 - 533 (父容器偏移)
  display: 'flex',
  alignItems: 'center',
  gap: '4px',
  padding: '4px 8px',
  background: 'transparent',
  border: 'none',
  color: '#FFFFFF',
  fontSize: '12px',
  fontFamily: 'FZLanTingYuanS-B-GB, PingFang SC, sans-serif',
  cursor: 'pointer',
  transition: 'opacity 0.2s ease',
  
  '&:hover': {
    opacity: 0.8
  }
};
```

### 组件 3: 亲密度展示 (IntimacyDisplay)

```typescript
interface IntimacyDisplayProps {
  level: number;           // 12
  relationship: string;    // "姐妹"
  relationshipEn: string;  // "Sister"
  position: { x: 637; y: 83 };
}

const intimacyDisplayStyle = {
  container: {
    position: 'absolute' as const,
    left: '222px',  // 637 - 415
    top: '-450px',  // 83 - 533
    display: 'flex',
    flexDirection: 'column' as const,
    alignItems: 'center',
    gap: '4px'
  },
  level: {
    fontSize: '24px',
    fontFamily: 'PingFangSC-Semibold, sans-serif',
    color: '#FFFFFF',
    fontWeight: 600
  },
  relationship: {
    fontSize: '10px',
    fontFamily: 'FZLanTingYuanS-B-GB, sans-serif',
    color: '#E559E5',
    fontWeight: 700
  },
  relationshipEn: {
    fontSize: '10px',
    fontFamily: 'FZLanTingYuanS-DB-GB, sans-serif',
    color: '#E559E5',
    fontWeight: 400
  }
};
```

### 组件 4: 角色信息 (CharacterInfo)

```typescript
interface CharacterInfoProps {
  characters: Array<{
    name: string;
    vip: 'SVIP' | 'VIP' | null;
  }>;
}

const characterInfoStyle = {
  container: {
    display: 'flex',
    flexDirection: 'column' as const,
    gap: '8px',
    padding: '12px'
  },
  name: {
    fontSize: '10px',
    fontFamily: 'FZLanTingYuanS-B-GB, sans-serif',
    color: '#A75E0F',
    fontWeight: 600
  },
  vipBadge: {
    SVIP: {
      background: 'linear-gradient(135deg, #E559E5 0%, #FF6B9D 100%)',
      color: '#FFFFFF',
      fontSize: '7.3px',
      padding: '2px 4px',
      borderRadius: '4px'
    },
    VIP: {
      background: 'linear-gradient(135deg, #FFD700 0%, #FFA500 100%)',
      color: '#FFFFFF',
      fontSize: '8px',
      padding: '2px 4px',
      borderRadius: '4px'
    }
  }
};
```

### 组件 5: Tab 切换器 (TabSwitcher)

```typescript
interface Tab {
  id: string;
  label: string;
  active: boolean;
}

interface TabSwitcherProps {
  tabs: Tab[];
  onTabChange: (tabId: string) => void;
}

const tabSwitcherStyle = {
  container: {
    display: 'flex',
    gap: '20px',
    padding: '12px 0',
    borderBottom: '1px solid rgba(255,255,255,0.1)'
  },
  tab: {
    base: {
      fontSize: '12px',
      padding: '8px 12px',
      cursor: 'pointer',
      transition: 'all 0.2s ease',
      background: 'transparent',
      border: 'none'
    },
    active: {
      fontFamily: 'FZLanTingYuanS-B-GB, sans-serif',
      color: '#622E00',
      fontWeight: 700,
      borderBottom: '2px solid #622E00'
    },
    inactive: {
      fontFamily: 'FZLanTingYuanS-DB-GB, sans-serif',
      color: '#999999',
      fontWeight: 400
    }
  }
};
```

### 组件 6: 任务列表 (TaskList)

```typescript
interface Task {
  id: string;
  description: string;
  action: string;
  status: 'pending' | 'completed';
}

interface TaskListProps {
  title: string;
  tasks: Task[];
  onTaskAction: (taskId: string) => void;
}

const taskListStyle = {
  container: {
    padding: '16px',
    background: 'rgba(255,255,255,0.95)',
    borderRadius: '12px',
    boxShadow: '0 2px 8px rgba(0,0,0,0.1)'
  },
  title: {
    fontSize: '12px',
    fontFamily: 'PingFangSC-Regular, sans-serif',
    color: '#666666',
    marginBottom: '12px'
  },
  taskItem: {
    display: 'flex',
    justifyContent: 'space-between',
    alignItems: 'center',
    padding: '12px',
    background: '#F0F7FF',
    borderRadius: '6px',
    borderLeft: '3px solid #0078e9',
    marginBottom: '8px'
  },
  description: {
    fontSize: '14px',
    fontFamily: 'PingFangSC-Regular, sans-serif',
    color: '#333333'
  },
  action: {
    fontSize: '12px',
    fontFamily: 'FZLanTingYuanS-B-GB, sans-serif',
    color: '#033658',
    cursor: 'pointer',
    fontWeight: 600
  }
};
```

---

## 📝 完整数据结构

```typescript
// ==================== 类型定义 ====================

/** 坐标位置 */
interface Position {
  x: number;
  y: number;
}

/** 尺寸 */
interface Size {
  width: number;
  height: number;
}

/** 边界框 */
interface BoundingBox extends Position, Size {}

/** 颜色 */
interface Color {
  r: number;  // 0-1
  g: number;  // 0-1
  b: number;  // 0-1
  a: number;  // 0-1
}

/** VIP 类型 */
type VIPType = 'SVIP' | 'VIP' | null;

/** 任务状态 */
type TaskStatus = 'pending' | 'completed';

/** Tab 项 */
interface TabItem {
  id: string;
  label: string;
  active: boolean;
}

/** 角色信息 */
interface Character {
  id: string;
  name: string;
  avatar: string;
  vip: VIPType;
}

/** 任务项 */
interface TaskItem {
  id: string;
  description: string;
  action: string;
  status: TaskStatus;
  reward?: string;
}

/** 亲密度信息 */
interface IntimacyInfo {
  level: number;
  relationship: string;
  relationshipEn: string;
  progress: number;  // 0-100
}

/** 页面数据 */
interface FriendDetailPageData {
  // 元信息
  title: string;
  pageId: string;
  
  // 亲密度
  intimacy: IntimacyInfo;
  
  // 角色
  characters: Character[];
  
  // Tab
  tabs: TabItem[];
  
  // 任务
  taskTitle: string;
  tasks: TaskItem[];
}

// ==================== 示例数据 ====================

const friendDetailData: FriendDetailPageData = {
  title: '亲密关系',
  pageId: '15556-19842',
  
  intimacy: {
    level: 12,
    relationship: '姐妹',
    relationshipEn: 'Sister',
    progress: 75
  },
  
  characters: [
    {
      id: 'char-1',
      name: '贝吉塔王子',
      avatar: 'https://example.com/avatar1.png',
      vip: null
    },
    {
      id: 'char-2',
      name: '松鼠的大尾巴...',
      avatar: 'https://example.com/avatar2.png',
      vip: null
    }
  ],
  
  tabs: [
    { id: 'relationship', label: '密友关系', active: true },
    { id: 'history', label: '密友记录', active: false }
  ],
  
  taskTitle: '通过以下途径提升亲密度',
  tasks: [
    {
      id: 'task-1',
      description: '发送学习鼓励',
      action: '去完成',
      status: 'pending'
    },
    {
      id: 'task-2',
      description: '去好友的家园点赞',
      action: '去完成',
      status: 'pending'
    },
    {
      id: 'task-3',
      description: '完成今日友情连学',
      action: '去完成',
      status: 'pending'
    }
  ]
};
```

---

## 🎨 Tailwind 配置

```javascript
// tailwind.config.js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    './src/**/*.{js,jsx,ts,tsx}',
  ],
  theme: {
    extend: {
      // 颜色
      colors: {
        primary: {
          900: '#011829',
          800: '#023153',
          700: '#034a7d',
          600: '#0463a7',
          500: '#0078e9',
          400: '#3aaee4',
          300: '#22c6e1',
          200: '#81e3f0',
          100: '#c0f1f8',
        },
        accent: {
          pink: '#E559E5',
          brown: '#A75E0F',
          orange: '#622E00',
          gold: '#FFD700',
        }
      },
      
      // 字体
      fontFamily: {
        display: ['FZLanTingYuanS-B-GB', 'PingFang SC', 'Microsoft YaHei', 'sans-serif'],
        title: ['FZLanTingYuanS-DB-GB', 'PingFang SC', 'Microsoft YaHei', 'sans-serif'],
        body: ['PingFang SC', 'FZLanTingYuanS-R-GB', 'Microsoft YaHei', 'sans-serif'],
        tag: ['FZLTTHK--GBK1-0', 'Arial', 'sans-serif'],
      },
      
      // 字体大小
      fontSize: {
        '2xs': '6px',
        'xs': '8px',
        'sm': '10px',
        'base': '12px',
        'lg': '14px',
        'xl': '16px',
        '2xl': '18px',
        '3xl': '20px',
        '4xl': '24px',
      },
      
      // 间距
      spacing: {
        '18': '4.5rem',
        '88': '22rem',
      },
      
      // 圆角
      borderRadius: {
        '4xl': '24px',
      },
      
      // 阴影
      boxShadow: {
        'card': '0 2px 8px rgba(0, 0, 0, 0.1)',
        'card-hover': '0 4px 16px rgba(0, 0, 0, 0.15)',
        'elevated': '0 20px 60px rgba(0, 0, 0, 0.3)',
      },
      
      // 背景图
      backgroundImage: {
        'page-gradient': 'linear-gradient(180deg, #023153 0%, #0d4a7c 50%, #1a5c99 100%)',
        'header-gradient': 'linear-gradient(135deg, #023153 0%, #0078e9 100%)',
        'vip-gradient': 'linear-gradient(135deg, #FFD700 0%, #FFA500 100%)',
        'svip-gradient': 'linear-gradient(135deg, #E559E5 0%, #FF6B9D 100%)',
      }
    },
  },
  plugins: [],
};
```

---

## 🚀 AI 代码生成提示词 (终极版)

```markdown
# Figma 转代码指令

## 输入
以下是一份完整的 Figma 设计稿解析文档，包含：
1. 完整的设计令牌（颜色、字体、间距、圆角、阴影）
2. 详细的页面结构（16层嵌套）
3. 6个核心组件的 TypeScript 接口和样式
4. 完整的数据结构定义
5. Tailwind 配置

## 输出要求

### 技术栈
- React 18 + TypeScript 5
- Tailwind CSS 3.4
- Lucide React (图标)
- Framer Motion (动画)

### 代码规范
1. **类型安全**: 所有 props 必须有完整的 TypeScript 类型定义
2. **组件拆分**: 按功能拆分为独立组件，保持单一职责
3. **样式方案**: 使用 Tailwind CSS，配合 design tokens
4. **响应式**: 以 812x375px 为基准，适配移动端
5. **无障碍**: 添加适当的 aria 标签
6. **性能**: 使用 React.memo 优化，避免不必要重渲染

### 文件结构
```
src/
├── components/
│   ├── PageContainer.tsx      # 页面容器
│   ├── BackButton.tsx         # 返回按钮
│   ├── IntimacyDisplay.tsx    # 亲密度展示
│   ├── CharacterInfo.tsx      # 角色信息
│   ├── TabSwitcher.tsx        # Tab 切换
│   └── TaskList.tsx           # 任务列表
├── types/
│   └── index.ts               # 类型定义
├── data/
│   └── mock.ts                # 模拟数据
├── styles/
│   └── tokens.css             # CSS 变量
├── App.tsx
└── main.tsx
```

### 特殊要求
1. 使用 CSS 变量管理设计令牌
2. 实现 Tab 切换的动画效果
3. 按钮添加点击波纹效果
4. 图片使用懒加载
5. 支持深色/浅色主题切换

### 代码示例
请生成可直接运行的完整代码，包括：
- 所有组件实现
- 类型定义文件
- 模拟数据
- Tailwind 配置
- 入口文件

确保代码质量达到生产环境标准。
```

---

## 📦 完整文件清单

生成的文件列表：

| 文件名 | 大小 | 说明 |
|--------|------|------|
| figma_preview.html | 16.8 KB | 完整 HTML 预览 |
| figma_report.txt | 3.5 KB | 文本报告 |
| figma_preview.png | 197 KB | 页面截图 |
| figma_ai_parsed.md | 12 KB | AI 解析文档 (本文档) |
| figma_design_node_15556-19842.json | 4.3 MB | 原始 Figma JSON |

---

## 🎯 快速开始指南

### 步骤 1: 创建项目
```bash
npx create-react-app friend-detail --template typescript
cd friend-detail
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### 步骤 2: 配置 Tailwind
复制上面的 `tailwind.config.js` 内容

### 步骤 3: 添加 CSS 变量
创建 `src/styles/tokens.css`，复制上面的 CSS 变量

### 步骤 4: 生成组件
将本文档提供给 AI，使用上面的提示词生成代码

### 步骤 5: 运行
```bash
npm start
```

---

**文档版本**: 1.0
**生成时间**: 2026-04-16
**数据来源**: Figma REST API
**适用项目**: NEXT-英语天天练UI交付文件2026
