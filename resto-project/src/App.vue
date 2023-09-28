<template>
 <NavBar/>
<SecTion1/>
<SecTion2/>
<SecTion3/>
<SecTion4/>
<SecTion5/>
<SecTion6/>
<SecTion7/>





<PageHead/>
 
</template>

<script>
import PageHead from './components/PageHead.vue'
import NavBar from './components/NavBar.vue'
import SecTion1 from './components/SecTion1.vue'
import SecTion2 from './components/SecTion2.vue'
import SecTion3 from './components/SecTion3.vue'
import SecTion4 from './components/SecTion4.vue'
import SecTion5 from './components/SecTion5.vue'
import SecTion6 from './components/SecTion6.vue'
import SecTion7 from './components/SecTion7.vue'




export default {
  name: 'App',
  components: {
     NavBar,
     SecTion1,
     SecTion2,
     SecTion3,
     SecTion4,
     SecTion5,
     SecTion6,
     SecTion7,




     PageHead
  }
}
</script>

<style>
/* Your styles */
</style>