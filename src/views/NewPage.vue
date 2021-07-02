<template>
  <div>新增頁面</div>
  <div class="row">
    <div class="col-4">
      <div class="list-group">
        <router-link
          to="/newpage/a"
          class="list-group-item list-group-item-action"
          aria-current="true"
        >
          元件 A
        </router-link>
        <router-link
          to="/newpage/b"
          class="list-group-item list-group-item-action"
          aria-current="true"
        >
          元件 B
        </router-link>
        <router-link
          to="/newpage/namedView/c2a"
          class="list-group-item list-group-item-action"
          aria-current="true"
        >
          命名視圖 c2a
        </router-link>
        <router-link
          to="/newpage/namedView/a2b"
          class="list-group-item list-group-item-action"
          aria-current="true"
        >
          命名視圖 a2b
        </router-link>
        <router-link
          to="/newpage/dynamicRouter/:id"
          class="list-group-item list-group-item-action"
          aria-current="true"
        >
          動態路由($route)
        </router-link>
        <router-link
          to="/newpage/dynamicRouterByProps/:id"
          class="list-group-item list-group-item-action"
          aria-current="true"
        >
          動態路由($props)
        </router-link>
        <router-link
          to="/newpage/routerNavigation"
          class="list-group-item list-group-item-action"
          aria-current="true"
        >
          路由導覽
        </router-link>
      </div>
    </div>
    <div class="col-8">
      <router-view></router-view>
    </div>
  </div>
</template>
