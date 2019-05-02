1.什么是vue热重载？
  答：页面的每次改动，不需要手动去刷新，可自动刷新。
2：什么是预编译头？
  答：预编译头（precompiled header）是程序设计时把头文件编译为中间格式（如目标文件），以节约在开发过程中编译器反复编译该头文件的开销。 C语言、C++语言、Objective C语言等都有类似的技术。
3：组件基础
  答: ① 组件是可复用的 Vue 实例，且带有一个名字。
      ② 一个组件的 data 选项必须是一个函数，因此每个实例可以维护一份被返回对象的独立的拷贝。
      ③ 全局注册和局部注册 
        组件都只是通过 Vue.component 全局注册的

模板字面量 是允许嵌入表达式的字符串字面量。你可以使用多行字符串和字符串插值功能。它们在ES2015规范的先前版本中被称为“模板字符串”。

缩写
v- 前缀作为一种视觉提示，用来识别模板中 Vue 特定的特性。当你在使用 Vue.js 为现有标签添加动态行为 (dynamic behavior) 时，v- 前缀很有帮助，然而，对于一些频繁用到的指令来说，就会感到使用繁琐。同时，在构建由 Vue 管理所有模板的单页面应用程序 (SPA - single page application) 时，v- 前缀也变得没那么重要了。因此，Vue 为 v-bind 和 v-on 这两个最常用的指令，提供了特定简写：

v-bind 缩写
<!-- 完整语法 -->
<a v-bind:href="url">...</a>

<!-- 缩写 -->
<a :href="url">...</a>
…

v-on 缩写
<!-- 完整语法 -->
<a v-on:click="doSomething">...</a>

<!-- 缩写 -->
<a @click="doSomething">...</a>
…

它们看起来可能与普通的 HTML 略有不同，但 : 与 @ 对于特性名来说都是合法字符，在所有支持 Vue 的浏览器都能被正确地解析。而且，它们不会出现在最终渲染的标记中。缩写语法是完全可选的，但随着你更深入地了解它们的作用，你会庆幸拥有它们。




全局配置 
silent optionMergeStrategies devtools errorHandler warnHandler ignoredElements keyCodes performance productionTip
全局 API
Vue.extend
Vue.nextTick
Vue.set
Vue.delete
Vue.directive
Vue.filter
Vue.component
Vue.use
Vue.mixin
Vue.compile
Vue.observable
Vue.version

选项 / 数据
data
props
propsData
computed
methods
watch

选项 / DOM
el
template
render
renderError

选项 / 生命周期钩子
beforeCreate
created
beforeMount
mounted
beforeUpdate
updated
activated
deactivated
beforeDestroy
destroyed
errorCaptured

选项 / 资源
directives
filters
components

选项 / 组合
parent
mixins
extends
provide / inject
选项 / 其它

name
delimiters
functional
model
inheritAttrs
comments

实例属性
vm.$data
vm.$props
vm.$el
vm.$options
vm.$parent
vm.$root
vm.$children
vm.$slots
vm.$scopedSlots
vm.$refs
vm.$isServer
vm.$attrs
vm.$listeners

实例方法 / 数据
vm.$watch
vm.$set
vm.$delete

实例方法 / 事件
vm.$on
vm.$once
vm.$off
vm.$emit

实例方法 / 生命周期
vm.$mount
vm.$forceUpdate
vm.$nextTick
vm.$destroy

指令
v-text
v-html
v-show
v-if
v-else
v-else-if
v-for
v-on
v-bind
v-model
v-slot
v-pre
v-cloak
v-once

特殊特性
key
ref
is
slot
slot-scope
scope

内置的组件
component
transition
transition-group
keep-alive
slot

VNode 接口
服务端渲染

ctrl+D   