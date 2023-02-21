<template>
    <div class="common-layout">
        <el-container style="height: 100vh;">
            <el-header style="background-color: red;">Header</el-header>
            <el-container>
                <el-aside width="200px" style="background-color: green;">Aside</el-aside>
                <el-main>
                    <slot />
                </el-main>
            </el-container>
        </el-container>
    </div>
</template>

<style lang="css" >
body {
    padding: 0;
    margin: 0;
}
</style>
