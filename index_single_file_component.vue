<!-- 싱글 파일 컴포넌트로 vue 파일로 프로젝트 구조를 구성한 파일로 vue파일 한개당 1개의 컴포넌트를 의미. -->

<!-- html 파일 입력 -->
<template>
    <div>
        <span>
            <button>{{message}}</button>
        </span>
    </div>
</template>

<!-- 뷰 컴포넌트의 내용을 정의하는 영역 (template, data, method 등등..) -->
<script>
export default {
    data: {
        message: 'click this button'
    }
}    
</script>


<style>
span {
    font-size: 1.2em;
}
</style>