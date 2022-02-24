<template>
  <div class="container">
    <CThemeProvider>
      <CColorModeProvider>
        <CBox font-family="body" as="main">
          <CReset />
          <Nuxt />
        </CBox>
      </CColorModeProvider>
    </CThemeProvider>
  </div>
</template>
<script>
import {
  CThemeProvider,
  CColorModeProvider,
  CReset,
  CBox,
} from "@chakra-ui/vue";

export default {
  name: "Master",
  components: {
    CThemeProvider,
    CColorModeProvider,
    CReset,
    CBox,
  },
};
</script>
