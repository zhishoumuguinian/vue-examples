<template>
  <div>
    <h1>Vue实例</h1>
    <ul>
      <li>
        <router-link to="/example01">HelloWorld</router-link>
      </li>
      <li>
        <router-link to="/example02">数据驱动</router-link>
      </li>
      <li>
        <router-link to="/example03">生命周期回调函数</router-link>
      </li>
      <li>
        <router-link to="/example04">计算属性</router-link>
      </li>
      <li>
        路由传参
        <ul>
          <li>
            <router-link to="/example05/students/42/homeworks/21"
              >基于RESTful的地址栏传参路由，sid:42; hid:21</router-link
            >
          </li>
          <li>
            <router-link to="/example05/students/75/homeworks/17"
              >基于RESTful的地址栏传参路由，sid:75; hid:17</router-link
            >
          </li>
        </ul>
      </li>
      <li>
        基本指令
        <ul>
          <li>
            <router-link to="/example06-01">v-text v-if v-show</router-link>
          </li>
          <li>
            <router-link to="/example06-02">v-bind</router-link>
          </li>
          <li>
            <router-link to="/example06-03">v-for</router-link>
          </li>
        </ul>
      </li>
      <li>
        双向绑定
        <ul>
          <li>
            <router-link to="/example07-01">v-module双向绑定</router-link>
          </li>
          <li>
            <router-link to="/example07-02">基于执行方法</router-link>
          </li>
          <li>
            <router-link to="/example07-03">基于属性监听</router-link>
          </li>
        </ul>
      </li>
      <li>
        <router-link to="/example08">props属性向子组件传值</router-link>
      </li>
      <li>
        <router-link to="/example09">基于Bus事件总线</router-link>
      </li>
      <li>
        <router-link to="/example10">基本axios请求</router-link>
      </li>
      <li>
        <router-link to="/example11">向服务器发送请求</router-link>
      </li>
    </ul>
  </div>
</template>

<style scoped>
div {
  width: 300px;
  border: 2px solid red;
  display: inline-block;
}
</style>
