<template>
    <div class="page-success">
        <div class="columns is-multiline">
            <div class="column is-12">
                <p class="title"> Đơn hàng của bạn đang được xử lí </p>
                <h1 class="title"> Cảm ơn bạn đã dùng dịch vụ bên chúng tôi.Hẹn gặp lại</h1>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Success',
    mounted(){
        document.title = 'Success | FrankesSus'
    },
}
</script>