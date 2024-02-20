<template>
    <NuxtLayout>
      <n-notification-provider>
        <n-message-provider>
          <n-dialog-provider>
            <n-loading-bar-provider>
                slot: 
              <slot></slot>
            </n-loading-bar-provider>
          </n-dialog-provider>
        </n-message-provider>
      </n-notification-provider>
    </NuxtLayout>
  </template>
  
  <script setup lang="ts">
  import {NNotificationProvider, NMessageProvider, NDialogProvider, NLoadingBarProvider} from "naive-ui"
  </script>