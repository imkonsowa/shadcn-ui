<script setup lang="ts">
    import SidebarProvider from "~/components/ui/sidebar/SidebarProvider.vue";
    import Sidebar from "~/components/ui/sidebar/Sidebar.vue";

</script>

<template>
    <SidebarProvider>
        <div class="sidebar">
            <Sidebar>
                <SidebarHeader>
                    Some content in the header
                </SidebarHeader>

                <SidebarContent>
                    Some content in the content
                </SidebarContent>

                <SidebarFooter>
                    Some content in the footer
                </SidebarFooter>
            </Sidebar>
        </div>
    </SidebarProvider>
</template>

<style scoped>

</style>