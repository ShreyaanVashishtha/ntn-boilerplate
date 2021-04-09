const router = new VueRouter({
  routes: [
    { path: '/blog', component: Blog, alias: '/blog' },
    { path: '/yt', component: YouTube },
    { path: '/blog', redirect: to => {
      return 'https://www.shreyaan.tech';
    }}
  ]
});
