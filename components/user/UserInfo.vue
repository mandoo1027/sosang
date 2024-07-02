<template>
    유저정보 테스트 
    <div>
        <input class="type_button" type="button" value="메인" @click="login()"/>
    </div>
</template>
<script setup> 
    const login = () => {
        const router = useRouter()
        router.push('/')
    }
</script>