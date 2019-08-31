<template>
  <div id="user-list">
    <ul>
      <li v-for="user in users" v-bind:key="user.account">
        <div>{{user.account}}</div>
        <div>{{user.name}}</div>
        <div>{{user.email}}</div>
      </li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
.user-list {
  height: 100%;
}
</style>