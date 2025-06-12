<template>
    <v-container class="d-flex justify-center align-center" style="height: 100vh;">
      <v-card width="400" elevation="8" class="pa-4">
        <v-card-title class="text-h5 text-center">Login</v-card-title>
        <v-card-text>
          <v-text-field
            label="CPF"
            type="password"
            prepend-inner-icon="mdi-lock"
            variant="outlined"
            density="comfortable"
            class="mt-4"
          />
          <v-btn color="primary" block class="mt-6" size="large">Entrar</v-btn>
        </v-card-text>
  
        <v-card-actions class="justify-center">
          <v-btn variant="text" size="small" class="mt-2">Esqueceu a senha?</v-btn>
        </v-card-actions>
      </v-card>
    </v-container>
  </template>

<script>
export default {
  name: 'LoginPage'
}
</script>