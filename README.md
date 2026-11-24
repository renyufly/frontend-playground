# Frontend Playground

> 一个面向前端开发者的多框架技术实验室、工程实践平台与个人代码知识库。

## 📖 项目介绍

Frontend Playground 是一个用于学习、研究、实践和比较现代前端开发技术的项目，涵盖 HTML、CSS、JavaScript、TypeScript 以及 React、Vue、Angular 等主流前端框架及其技术生态。

本项目通过最小可运行示例（Minimal Runnable Examples）、独立技术实验、UI 组件实现、跨框架对比和综合项目实践，系统性地积累前端开发知识与工程经验。

项目不局限于某一种前端框架，而是关注前端开发中的通用技术原理、设计思想、浏览器机制、工程实践以及不同技术生态下的解决方案。

希望将本项目逐步建设成为一个可以长期维护、持续扩展、快速查阅的个人前端工程知识库。

## 🎯 项目目标

- **技术学习（Learning）**：系统学习前端基础知识、主流框架及相关技术生态。
- **代码参考（Reference）**：建立可运行、可复用、易于查阅的个人代码参考库。
- **技术实验（Experiment）**：通过独立实验验证浏览器机制、框架原理和技术方案。
- **横向对比（Comparison）**：研究不同前端框架解决相同问题的方式。
- **组件积累（Components）**：沉淀常见 UI 组件、交互模式和页面布局。
- **工程实践（Engineering）**：积累真实开发场景中的工程经验与最佳实践。
- **知识沉淀（Documentation）**：记录技术原理、常见问题、踩坑经验和解决方案。
- **综合应用（Application）**：通过小型项目整合不同技术，提升前端工程开发能力。

## 🛠️ 技术栈

以下为项目计划覆盖的技术生态。

### 前端基础

| 技术           | 说明                         |
| -------------- | ---------------------------- |
| HTML5          | 页面结构与语义化             |
| CSS3           | 样式、布局、动画与响应式设计 |
| JavaScript     | 前端核心编程语言             |
| TypeScript     | 静态类型与大型项目开发       |
| Web APIs       | 浏览器原生 API               |
| Web Components | 原生组件化开发               |
| HTTP / HTTPS   | 网络通信基础                 |
| WebSocket      | 双向实时通信                 |
| SSE            | 服务端事件推送               |
| WebAssembly    | 高性能 Web 应用拓展          |

### 主流框架及生态

| 技术领域   | React                   | Vue                     | Angular                       |
| ---------- | ----------------------- | ----------------------- | ----------------------------- |
| 核心框架   | React                   | Vue 3                   | Angular                       |
| 路由       | React Router            | Vue Router              | Angular Router                |
| 状态管理   | Zustand / Redux Toolkit | Pinia                   | NgRx / Signals                |
| 服务端状态 | TanStack Query          | TanStack Vue Query      | RxJS / TanStack Angular Query |
| 表单处理   | React Hook Form         | VeeValidate             | Reactive Forms                |
| UI 组件库  | Ant Design / MUI        | Element Plus / Naive UI | Angular Material / NG-ZORRO   |
| 全栈与 SSR | Next.js                 | Nuxt                    | Angular SSR                   |
| 单元测试   | Vitest / Jest           | Vitest                  | Vitest / Jasmine              |
| 组件测试   | React Testing Library   | Vue Test Utils          | Angular Testing Library       |
| 端到端测试 | Playwright              | Playwright              | Playwright                    |

### 前端工程化

| 技术领域   | 技术选型                        |
| ---------- | ------------------------------- |
| 包管理     | npm / pnpm                      |
| 构建工具   | Vite / Webpack / Angular CLI    |
| 编译工具   | Babel / SWC / TypeScript        |
| 代码检查   | ESLint                          |
| 代码格式化 | Prettier                        |
| CSS 工程化 | Sass / PostCSS / CSS Modules    |
| 原子化 CSS | Tailwind CSS                    |
| Monorepo   | pnpm Workspace / Turborepo / Nx |
| 组件开发   | Storybook                       |
| Mock 服务  | MSW                             |
| API 客户端 | Fetch / Axios                   |
| 自动化测试 | Vitest / Jest / Playwright      |
| 持续集成   | GitHub Actions                  |
| 部署       | Docker / Nginx                  |

## 📂 项目目录结构

以下为项目的参考目录结构，将根据学习进度与实际需求逐步完善。

```text
frontend-playground/
├── README.md
├── LICENSE
├── .gitignore
├── .editorconfig
├── .env.example
├── package.json
├── pnpm-workspace.yaml
├── pnpm-lock.yaml
│
├── html/
│   ├── README.md
│   ├── semantic-elements/
│   ├── forms/
│   ├── tables/
│   ├── multimedia/
│   ├── accessibility/
│   └── seo/
│
├── css/
│   ├── README.md
│   ├── selectors/
│   ├── box-model/
│   ├── positioning/
│   ├── flexbox/
│   ├── grid/
│   ├── responsive-design/
│   ├── media-queries/
│   ├── container-queries/
│   ├── transitions/
│   ├── animations/
│   ├── transforms/
│   ├── custom-properties/
│   ├── sass/
│   ├── tailwindcss/
│   └── layouts/
│
├── javascript/
│   ├── README.md
│   ├── language/
│   ├── scope/
│   ├── closure/
│   ├── prototype/
│   ├── this-binding/
│   ├── modules/
│   ├── collections/
│   ├── functional-programming/
│   ├── asynchronous/
│   ├── promise/
│   ├── async-await/
│   ├── event-loop/
│   ├── error-handling/
│   ├── design-patterns/
│   └── testing/
│
├── typescript/
│   ├── README.md
│   ├── basic-types/
│   ├── interfaces/
│   ├── generics/
│   ├── type-narrowing/
│   ├── utility-types/
│   ├── conditional-types/
│   ├── mapped-types/
│   ├── template-literal-types/
│   ├── decorators/
│   ├── declaration-files/
│   └── type-challenges/
│
├── browser/
│   ├── README.md
│   ├── dom/
│   ├── bom/
│   ├── events/
│   ├── event-delegation/
│   ├── fetch-api/
│   ├── storage/
│   ├── indexeddb/
│   ├── websocket/
│   ├── server-sent-events/
│   ├── web-worker/
│   ├── service-worker/
│   ├── intersection-observer/
│   ├── mutation-observer/
│   ├── resize-observer/
│   ├── canvas/
│   ├── svg/
│   ├── web-components/
│   └── rendering/
│
├── react/
│   ├── README.md
│   ├── fundamentals/
│   ├── components/
│   ├── hooks/
│   ├── context/
│   ├── routing/
│   ├── forms/
│   ├── state-management/
│   │   ├── zustand/
│   │   └── redux-toolkit/
│   ├── data-fetching/
│   ├── tanstack-query/
│   ├── react-hook-form/
│   ├── error-handling/
│   ├── performance/
│   ├── design-patterns/
│   ├── testing/
│   ├── ui-libraries/
│   ├── nextjs/
│   └── mini-projects/
│
├── vue/
│   ├── README.md
│   ├── fundamentals/
│   ├── components/
│   ├── reactivity/
│   ├── composition-api/
│   ├── composables/
│   ├── directives/
│   ├── lifecycle/
│   ├── vue-router/
│   ├── pinia/
│   ├── forms/
│   ├── data-fetching/
│   ├── tanstack-query/
│   ├── error-handling/
│   ├── performance/
│   ├── design-patterns/
│   ├── testing/
│   ├── ui-libraries/
│   ├── nuxt/
│   └── mini-projects/
│
├── angular/
│   ├── README.md
│   ├── fundamentals/
│   ├── components/
│   ├── directives/
│   ├── pipes/
│   ├── services/
│   ├── dependency-injection/
│   ├── lifecycle/
│   ├── signals/
│   ├── rxjs/
│   ├── routing/
│   ├── forms/
│   ├── http-client/
│   ├── interceptors/
│   ├── guards/
│   ├── ngrx/
│   ├── performance/
│   ├── testing/
│   ├── angular-material/
│   ├── ssr/
│   └── mini-projects/
│
├── ui-components/
│   ├── README.md
│   ├── button/
│   ├── input/
│   ├── select/
│   ├── checkbox/
│   ├── dropdown/
│   ├── modal/
│   ├── tooltip/
│   ├── popover/
│   ├── toast/
│   ├── tabs/
│   ├── accordion/
│   ├── carousel/
│   ├── pagination/
│   ├── data-table/
│   ├── tree-view/
│   ├── date-picker/
│   ├── file-upload/
│   ├── drag-and-drop/
│   ├── infinite-scroll/
│   └── virtual-list/
│
├── engineering/
│   ├── README.md
│   ├── package-management/
│   ├── vite/
│   ├── webpack/
│   ├── babel/
│   ├── swc/
│   ├── eslint/
│   ├── prettier/
│   ├── postcss/
│   ├── monorepo/
│   ├── environment-variables/
│   ├── code-splitting/
│   ├── tree-shaking/
│   ├── module-federation/
│   ├── micro-frontends/
│   ├── storybook/
│   └── ci-cd/
│
├── networking/
│   ├── README.md
│   ├── http/
│   ├── rest-api/
│   ├── graphql/
│   ├── axios/
│   ├── request-interceptor/
│   ├── request-cancellation/
│   ├── retry/
│   ├── polling/
│   ├── caching/
│   ├── file-upload/
│   ├── file-download/
│   └── mock-api/
│
├── security/
│   ├── README.md
│   ├── authentication/
│   ├── authorization/
│   ├── jwt/
│   ├── session-cookie/
│   ├── oauth2/
│   ├── cors/
│   ├── xss/
│   ├── csrf/
│   ├── csp/
│   └── secure-storage/
│
├── performance/
│   ├── README.md
│   ├── core-web-vitals/
│   ├── lazy-loading/
│   ├── image-optimization/
│   ├── bundle-optimization/
│   ├── rendering-optimization/
│   ├── debounce/
│   ├── throttle/
│   ├── virtual-scrolling/
│   ├── memory-leak/
│   ├── lighthouse/
│   └── profiling/
│
├── testing/
│   ├── README.md
│   ├── unit-testing/
│   ├── component-testing/
│   ├── integration-testing/
│   ├── e2e-testing/
│   ├── visual-regression/
│   ├── accessibility-testing/
│   ├── vitest/
│   ├── jest/
│   ├── playwright/
│   └── msw/
│
├── architecture/
│   ├── README.md
│   ├── component-design/
│   ├── state-management/
│   ├── feature-based-architecture/
│   ├── design-system/
│   ├── atomic-design/
│   ├── clean-architecture/
│   ├── csr/
│   ├── ssr/
│   ├── ssg/
│   ├── hydration/
│   ├── micro-frontends/
│   └── internationalization/
│
├── comparisons/
│   ├── README.md
│   ├── component-model/
│   ├── reactivity/
│   ├── lifecycle/
│   ├── state-management/
│   ├── routing/
│   ├── forms/
│   ├── data-fetching/
│   ├── rendering/
│   ├── dependency-injection/
│   └── benchmarks/
│
├── projects/
│   ├── README.md
│   ├── todo-app/
│   ├── weather-app/
│   ├── admin-dashboard/
│   ├── ecommerce-frontend/
│   ├── markdown-editor/
│   ├── kanban-board/
│   ├── realtime-chat/
│   ├── file-manager/
│   └── low-code-editor/
│
├── infrastructure/
│   ├── README.md
│   ├── mock-server/
│   ├── docker/
│   └── nginx/
│
├── docs/
│   ├── concepts/
│   ├── architecture/
│   ├── best-practices/
│   ├── troubleshooting/
│   ├── interview/
│   └── resources/
│
├── scripts/
│   ├── setup/
│   ├── testing/
│   └── benchmark/
│
└── .github/
    └── workflows/
        ├── lint.yml
        ├── test.yml
        └── build.yml
```

## 📁 目录说明

| 目录              | 说明                             |
| ----------------- | -------------------------------- |
| `html/`           | HTML 基础、语义化与可访问性      |
| `css/`            | CSS 样式、布局、动画与响应式设计 |
| `javascript/`     | JavaScript 语言特性与核心原理    |
| `typescript/`     | TypeScript 类型系统与高级特性    |
| `browser/`        | 浏览器机制与原生 Web API         |
| `react/`          | React 框架及其技术生态           |
| `vue/`            | Vue 框架及其技术生态             |
| `angular/`        | Angular 框架及其技术生态         |
| `ui-components/`  | 通用 UI 组件与交互模式           |
| `engineering/`    | 前端工程化、构建工具与自动化     |
| `networking/`     | 网络通信与 API 请求              |
| `security/`       | 前端安全与身份认证               |
| `performance/`    | 前端性能分析与优化               |
| `testing/`        | 通用测试工具与测试策略           |
| `architecture/`   | 前端架构与设计思想               |
| `comparisons/`    | 跨框架技术对比实验               |
| `projects/`       | 综合实践项目                     |
| `infrastructure/` | Mock 服务、容器及部署配置        |
| `docs/`           | 技术文档与学习笔记               |
| `scripts/`        | 自动化与辅助脚本                 |
| `.github/`        | GitHub Actions 持续集成配置      |

## 📚 学习内容

### 1. HTML 与 CSS

- HTML 语义化
- 表单与表单验证
- 可访问性（Accessibility）
- 搜索引擎优化（SEO）
- CSS 选择器与优先级
- 盒模型
- BFC 与文档流
- Flexbox 与 Grid
- 响应式布局
- CSS 动画与过渡
- CSS 自定义属性
- Sass 与 Tailwind CSS
- 深色模式与主题切换

### 2. JavaScript 与 TypeScript

- 作用域与闭包
- 原型与原型链
- this 绑定
- 模块化
- 函数式编程
- Promise
- async / await
- Event Loop
- Microtask 与 Macrotask
- 错误处理
- 泛型
- 类型推导
- 类型收窄
- 高级类型
- 类型体操

### 3. 浏览器与 Web API

- DOM 与 BOM
- 事件传播机制
- 事件委托
- 浏览器渲染机制
- 重排与重绘
- LocalStorage 与 SessionStorage
- IndexedDB
- Fetch API
- WebSocket
- Server-Sent Events
- Web Worker
- Service Worker
- Canvas 与 SVG
- Web Components
- Observer APIs

### 4. 前端框架

- 组件化开发
- Props 与组件通信
- 生命周期
- 响应式系统
- Hooks 与 Composables
- 依赖注入
- 路由管理
- 状态管理
- 表单处理
- 服务端状态管理
- 异步数据加载
- 错误处理
- 组件复用
- 框架性能优化

### 5. UI 组件与交互设计

- 基础表单组件
- 弹窗与浮层
- 导航与菜单
- 数据表格
- 树形结构
- 文件上传
- 拖拽交互
- 无限滚动
- 虚拟列表
- 响应式组件
- 键盘交互
- 无障碍组件
- Design Tokens
- Design System

### 6. 网络通信

- HTTP 协议
- RESTful API
- GraphQL
- 请求与响应拦截
- 请求取消
- 请求重试
- 请求去重
- Token 刷新
- 数据缓存
- 乐观更新
- 轮询与实时通信
- 文件上传与下载
- Mock API

### 7. 前端安全

- Authentication & Authorization
- Session & Cookie
- JWT
- OAuth 2.0
- OpenID Connect
- RBAC
- XSS 防护
- CSRF 防护
- CORS
- Content Security Policy
- 敏感数据保护
- 安全依赖管理

前端路由守卫、菜单权限和按钮权限仅用于客户端交互控制，真正的权限校验必须由后端完成。

### 8. 前端工程化

- npm 与 pnpm
- 模块化与依赖管理
- Vite 与 Webpack
- Babel 与 SWC
- ESLint 与 Prettier
- 环境变量管理
- Tree Shaking
- Code Splitting
- Monorepo
- 组件库开发
- Storybook
- Module Federation
- 微前端
- CI/CD
- Docker 与 Nginx

### 9. 性能优化

- Core Web Vitals
- 首屏加载优化
- 资源加载优化
- 图片优化
- 路由懒加载
- 防抖与节流
- 虚拟滚动
- 组件渲染优化
- Bundle Size 优化
- 浏览器缓存
- 内存泄漏排查
- Lighthouse
- Chrome DevTools
- Performance Profiling

### 10. 前端架构

- 组件设计原则
- 组件组合模式
- Feature-based Architecture
- Atomic Design
- Design System
- Headless Components
- Clean Architecture
- Client-side Rendering（CSR）
- Server-side Rendering（SSR）
- Static Site Generation（SSG）
- Hydration
- 微前端架构
- 国际化（i18n）
- 多主题系统

### 11. 测试与质量保障

- 单元测试
- 组件测试
- 集成测试
- 端到端测试
- Mock 与 Stub
- API Mock
- 视觉回归测试
- 可访问性测试
- 性能测试
- 自动化构建与检查

## 🔬 Demo 组织规范

每个 Demo 应尽可能独立、简单、可运行，并围绕一个明确的技术知识点展开。

### 示例：CSS Flexbox

```text
css/flexbox/
├── README.md
├── basic-layout/
│   ├── README.md
│   ├── index.html
│   └── style.css
├── alignment/
├── wrapping/
├── navigation-bar/
└── responsive-layout/
```

### 示例：JavaScript Promise

```text
javascript/promise/
├── README.md
├── basic-usage/
│   ├── README.md
│   └── index.js
├── promise-all/
├── promise-all-settled/
├── promise-race/
├── promise-any/
├── error-handling/
└── custom-promise/
```

### 示例：React Hooks

```text
react/hooks/
├── README.md
├── use-state/
├── use-effect/
├── use-ref/
├── use-memo/
├── use-callback/
├── use-reducer/
├── use-context/
├── use-transition/
└── custom-hooks/
    ├── use-debounce/
    ├── use-local-storage/
    └── use-fetch/
```

一个独立的 React Demo 可以采用以下结构：

```text
react/hooks/use-state/
├── README.md
├── package.json
├── tsconfig.json
├── vite.config.ts
├── index.html
└── src/
    ├── main.tsx
    ├── App.tsx
    ├── App.test.tsx
    └── style.css
```

### 示例：Vue Composition API

```text
vue/composition-api/
├── README.md
├── ref/
├── reactive/
├── computed/
├── watch/
├── watch-effect/
├── provide-inject/
└── lifecycle-hooks/
```

### 示例：Angular Signals

```text
angular/signals/
├── README.md
├── writable-signal/
├── computed-signal/
├── effect/
├── linked-signal/
└── rxjs-interop/
```

Angular Demo 应根据实际复杂度采用 Angular CLI 项目或共享 Angular Workspace，不强制为每个知识点创建完整项目。

### 示例：通用 UI 组件

```text
ui-components/modal/
├── README.md
├── specification.md
├── vanilla/
├── react/
├── vue/
└── angular/
```

同一个组件可以使用原生 JavaScript、React、Vue 和 Angular 分别实现，并比较不同框架的组件设计与交互机制。

简单示例无须引入完整的框架工程，优先采用最小可运行实现。

## 📝 Demo 文档规范

建议每个 Demo 包含独立的 README，并根据实际情况记录以下内容：

| 内容                | 说明               |
| ------------------- | ------------------ |
| Overview            | 功能介绍与实验背景 |
| Learning Objectives | 学习目标           |
| Concepts            | 核心技术原理       |
| Implementation      | 实现思路与关键代码 |
| Prerequisites       | 环境与依赖要求     |
| Quick Start         | 运行方式           |
| Preview             | 页面截图或交互效果 |
| Expected Results    | 预期运行结果       |
| Test Cases          | 测试与验证方式     |
| Edge Cases          | 异常情况与边界条件 |
| Accessibility       | 可访问性注意事项   |
| Use Cases           | 实际业务应用场景   |
| Best Practices      | 工程实践与注意事项 |
| References          | 官方文档及参考资料 |

对于 UI 组件和页面布局，建议提供截图、GIF 或在线演示。

## ⚖️ 跨框架技术对比

本项目不仅关注单一框架的使用方式，也关注不同框架在设计思想、响应式机制、组件模型和工程实践方面的差异。

例如，针对状态管理、表单验证、数据请求、组件通信等通用前端问题，分别使用 React、Vue 和 Angular 进行实现与对比。

```text
comparisons/state-management/
├── README.md
├── specification.md
├── test-cases/
└── benchmark/
```

具体实现优先复用各框架目录下的 Demo，通过文档链接、统一功能需求及测试用例进行关联，避免重复维护相同代码。

对比维度包括：

- 框架设计思想
- 响应式机制
- 组件模型
- 状态更新机制
- 生命周期
- 代码复杂度与可读性
- 类型安全
- 渲染性能
- Bundle Size
- 开发效率
- 测试便利性
- 维护成本
- 实际业务适用场景

性能对比应采用尽可能一致的功能需求、浏览器环境、测试数据和构建配置，并记录框架版本及实验条件。

## 🚀 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/<your-username>/frontend-playground.git

cd frontend-playground
```

请将 `<your-username>` 替换为实际的 GitHub 用户名。

### 2. 准备开发环境

| 环境             | 用途                    |
| ---------------- | ----------------------- |
| Node.js LTS      | JavaScript 运行环境     |
| pnpm             | 包管理与 Workspace 管理 |
| Git              | 版本控制                |
| Chrome / Firefox | 浏览器开发与调试        |
| VS Code          | 代码编辑与开发          |
| Docker           | 可选的容器化环境        |

具体版本要求以各 Demo 的文档及项目配置为准。

### 3. 安装依赖

项目计划使用 pnpm Workspace 统一管理多个独立的前端实验项目。

Workspace 配置完成后，可在根目录安装依赖：

```bash
pnpm install
```

### 4. 运行 Demo

以下命令为对应示例完成后的参考运行方式。

**HTML / CSS**

可以直接打开 `index.html`。涉及 ES Modules、Fetch API 等功能时，应使用本地 HTTP 开发服务器。

**JavaScript**

```bash
node javascript/promise/basic-usage/index.js
```

**React**

```bash
cd react/hooks/use-state
pnpm dev
```

**Vue**

```bash
cd vue/composition-api/ref
pnpm dev
```

**Angular**

```bash
cd angular/signals/writable-signal
pnpm start
```

具体启动方式、端口、环境变量及依赖要求，请参考对应 Demo 的 README。

### 5. 测试与构建

在已配置相应脚本的项目目录中运行：

```bash
pnpm lint
pnpm test
pnpm build
```

端到端测试：

```bash
pnpm exec playwright test
```

## 🏗️ 项目设计原则

### Minimal — 最小化

每个 Demo 聚焦一个明确的技术问题，避免引入不必要的业务逻辑和复杂架构。

### Independent — 独立性

各 Demo 尽可能独立运行，减少不同实验之间的耦合。

### Runnable — 可运行

代码不仅用于阅读，也应能够实际运行并验证技术行为。

### Visual — 可视化

对于 UI 组件、页面布局及交互实验，应尽可能提供直观的页面效果。

### Testable — 可测试

通过测试用例验证功能、用户交互、异常处理和边界条件。

### Accessible — 可访问

关注语义化 HTML、键盘操作、焦点管理、屏幕阅读器支持和颜色对比度。

### Reproducible — 可复现

明确记录依赖版本、运行环境、配置参数和实验步骤。

### Documented — 可查阅

记录技术原理、实现方式、使用场景、常见问题及参考资料。

### Extensible — 可扩展

支持未来加入新的前端框架、组件库、构建工具和技术领域。

### Practical — 实用性

关注实际前端开发中的问题与解决方案，而不仅仅是 API 的简单使用。

## 🔄 学习与实践流程

```text
Learn       学习技术原理
    ↓
Implement   编写最小可运行示例
    ↓
Preview     验证页面与交互效果
    ↓
Experiment  进行技术实验与异常模拟
    ↓
Test        验证功能与边界条件
    ↓
Document    记录知识与工程经验
    ↓
Compare     对比不同框架实现
    ↓
Apply       应用于实际业务项目
    ↓
Refactor    持续改进与完善
```

通过持续实践，将零散的前端技术知识转化为可复用的工程经验。

## 📋 开发与学习路线

以下为初始规划，将根据实际学习进度持续调整。

### Phase 1 — Frontend Fundamentals

- [ ] HTML 与语义化
- [ ] CSS 布局与响应式设计
- [ ] JavaScript 核心原理
- [ ] TypeScript 类型系统
- [ ] DOM 与浏览器事件
- [ ] 异步编程
- [ ] HTTP 与 Fetch API

### Phase 2 — Frontend Frameworks

- [ ] React
- [ ] Vue
- [ ] Angular
- [ ] 组件化开发
- [ ] 路由管理
- [ ] 状态管理
- [ ] 表单处理
- [ ] 服务端数据管理

### Phase 3 — UI Components

- [ ] 基础表单组件
- [ ] 弹窗与浮层组件
- [ ] 数据表格
- [ ] 拖拽交互
- [ ] 虚拟列表
- [ ] 响应式组件
- [ ] 无障碍组件
- [ ] Design System

### Phase 4 — Frontend Engineering

- [ ] Vite 与 Webpack
- [ ] pnpm Workspace
- [ ] ESLint 与 Prettier
- [ ] Storybook
- [ ] 单元测试与组件测试
- [ ] Playwright
- [ ] 性能分析与优化
- [ ] 前端安全
- [ ] CI/CD

### Phase 5 — Advanced Architecture

- [ ] Next.js
- [ ] Nuxt
- [ ] Angular SSR
- [ ] SSR 与 SSG
- [ ] Hydration
- [ ] 微前端
- [ ] Module Federation
- [ ] 国际化
- [ ] 前端架构设计
- [ ] 跨框架技术对比

### Phase 6 — Practical Projects

- [ ] Todo App
- [ ] Weather App
- [ ] Admin Dashboard
- [ ] E-commerce Frontend
- [ ] Markdown Editor
- [ ] Kanban Board
- [ ] Realtime Chat
- [ ] File Manager
- [ ] Low-code Editor

## 📐 代码与提交规范

### 代码规范

- 遵循各编程语言与框架的官方编码规范。
- 新建框架项目优先使用 TypeScript。
- 使用清晰且具有语义的变量、函数、组件和目录名称。
- 优先使用语义化 HTML。
- 关注响应式设计与可访问性。
- 避免过度设计与不必要的抽象。
- 优先保证代码的正确性、可读性和可维护性。
- 使用 ESLint 与 Prettier 保持代码风格一致。
- 不提交密码、Token、API Key 等敏感信息。
- 不在前端代码或构建产物中保存服务端密钥。
- 对关键逻辑、异常场景和技术原理添加必要说明。

### Git 提交规范

推荐使用 Conventional Commits 规范。

```text
feat(html): add semantic form example
feat(css): add responsive grid layout
feat(js): add promise concurrency example
feat(ts): add conditional types example
feat(react): add custom debounce hook
feat(vue): add pinia state management
feat(angular): add signals example
feat(ui): add accessible modal component
fix(react): fix effect cleanup issue
docs(browser): explain event loop
test(vue): add component tests
refactor(angular): simplify dependency injection
perf(ui): optimize virtual list rendering
chore(engineering): update workspace configuration
```

## 📖 参考资料

### 前端基础

- [MDN Web Docs](https://developer.mozilla.org/)
- [JavaScript.info](https://javascript.info/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [web.dev](https://web.dev/)
- [W3C](https://www.w3.org/)
- [WHATWG](https://whatwg.org/)

### 前端框架

- [React](https://react.dev/)
- [Vue](https://vuejs.org/)
- [Angular](https://angular.dev/)
- [Next.js](https://nextjs.org/docs)
- [Nuxt](https://nuxt.com/docs)
- [RxJS](https://rxjs.dev/)

### 状态管理

- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Zustand](https://zustand.docs.pmnd.rs/)
- [Pinia](https://pinia.vuejs.org/)
- [NgRx](https://ngrx.io/)
- [TanStack Query](https://tanstack.com/query/)

### 前端工程化

- [Node.js](https://nodejs.org/docs/latest/api/)
- [pnpm](https://pnpm.io/)
- [Vite](https://vite.dev/)
- [Webpack](https://webpack.js.org/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Storybook](https://storybook.js.org/)
- [Turborepo](https://turborepo.com/)
- [Nx](https://nx.dev/)

### 测试与质量保障

- [Vitest](https://vitest.dev/)
- [Jest](https://jestjs.io/)
- [Testing Library](https://testing-library.com/)
- [Playwright](https://playwright.dev/)
- [Mock Service Worker](https://mswjs.io/)
- [OWASP](https://owasp.org/)
- [WAI-ARIA](https://www.w3.org/WAI/ARIA/apg/)

## 🔗 相关项目

- `backend-playground`：多语言后端技术实验室。
- `devops-playground`：容器化、部署与自动化运维实验室。
- `algorithm-playground`：数据结构与算法实验室。
- `ai-playground`：人工智能与大语言模型技术实验室。

以上为个人技术知识库的配套仓库规划。
