<template>
    <div id="login">
        <el-row>
            <el-button>默认按钮</el-button>
            <el-button type="primary">主要按钮</el-button>
            <el-button type="success">成功按钮</el-button>
            <el-button type="info">信息按钮</el-button>
            <el-button type="warning">警告按钮</el-button>
            <el-button type="danger">危险按钮</el-button>
        </el-row>
        我是登录页6666
    </div>
</template>

<script>
    export default {
        name: "login"
    }
</script>

<style scoped>
#login{
    background-image: linear-gradient(to bottom , skyblue, white);
    height: 100vh;
}    

</style>