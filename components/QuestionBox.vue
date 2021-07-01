<template>
<div class="body">
    <li>
        <b class="question">{{question}}</b>
        <p class="answer">{{answer}}</p>
    </li>
</div>
</template>

<script>
export default {
    name: 'QuestionBox',
    props: {
        question: {
            type: String
        },
        answer: {
            type: String
        }
    }
}
</script>

<style>
li {
    font-size: 1.25em;
}

.question {
    font-size: 1.25em;
}

.answer {
    font-size: 1em;
}
</style>