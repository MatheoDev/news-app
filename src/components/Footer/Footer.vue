<template>
    <div class="footer">
        <el-footer>
            <span>
                Site made by News Site - Copyright 2022
            </span>
        </el-footer>
    </div>
</template>


<script>
import {ElFooter} from 'element-plus'

export default {
    name: 'Footer',
    components: {
        "el-footer": ElFooter,
    }
}
</script>

<style scoped>
.footer {
    bottom: 0;
    width: 100%;
}

</style>
