# Slider

<script setup>
import { ref } from "vue"; 

const value = ref(0)
const valueTwo = ref(0)
</script>

<DemoContainer>
  <Slider v-model="value" :min="1000" :max="10000" :step="50" :snapPoints="[2500,5000,7500]"/>
  <Slider v-model="valueTwo" :min="1000" :max="10000" :step="50" :disabled="true" :snapPoints="[2500,5000,7500]"/>
</DemoContainer>

```vue
<script setup>
import { ref } from "vue";

const value = ref(0)
</script>

<Slider v-model="value" :min="1000" :max="10000" :step="50" :snapPoints="[2500,5000,7500]"/>
```
