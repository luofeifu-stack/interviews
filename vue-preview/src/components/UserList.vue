<template>
  <div>
    <ul>
      <li v-for="(user, index) in users" :key="index">{{ user.name }} - {{ user.age }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'UserList',
  data() {
    return {
      users: [
        { name: 'John', age: 28 },
        { name: 'Jane', age: 34 },
      ],
    };
  },
};
</script>
