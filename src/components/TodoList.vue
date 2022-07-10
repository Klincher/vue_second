<template>
    <div>
        <ul>
            <TodoItem />
        </ul>
    </div>
</template>

<script>
// импорт компонента TodoItem
import TodoItem from '@/components/TodoItem'
export default{
    components:{
        //регистрируем TodoItem
        TodoItem
    }
}
</script>