# vue-router 

## vue-router的使用方式  

### html中 

1. 使用script 引入 vue-router  

2. 定义组件  

    const login = {template:'<div></div>'}

3. 实例化路由 new VueRouter  

4. 配置路由规则   

5. 挂载路由 

6. 使用router-view渲染路由  


### webpack

1. 使用import 引入vue-router  

2. 使用Vue.use 注册路由

3. 在components文件夹下面以.vue文件定义组件  组件中包含template script style

4. 实例化路由 new VueRouter  

5. 配置路由规则   

6. 在main.js文件中挂载路由 

7. 在APP.vue文件中使用router-view渲染路由  
