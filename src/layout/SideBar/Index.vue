<template>
    <div>
        <div class="bg-base-200 w-56 h-screen">
            <slot name="header">
                <div class="navbar bg-base-200">
                    <div class="flex-1 bg-base-100">
                        <a class="btn btn-ghost normal-case text-xl">daisyUI</a>
                    </div>
                </div>
            </slot>
            <ul class="menu bg-base-200 w-56 h-screen">
                <li><a>布局</a></li>
                <li><a>组件</a></li>
                <li><a>配置</a></li>
            </ul>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
</style>