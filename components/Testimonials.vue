<template>
    <section class="is-relative section py-20">
        <!-- <img class="is-absolute is-left-0 is-top-0 mt-20 is-hidden-mobile"
            src="assets/zeus-assets/icons/dots/blue-dot-left-bars.svg" alt="">
        <img class="is-absolute is-right-0 is-bottom-0 mb-20 is-hidden-mobile"
            src="assets/zeus-assets/icons/dots/yellow-dot-right-shield.svg" alt=""> -->
        <div class="container">
            <div class="has-mw-2xl mx-auto mb-12 mb-20-desktop has-text-centered">
                <h2 class="mt-8 mb-10 title is-2">Отзывы участников</h2>
                <p class="mb-16 is-size-5 has-text-grey-dark">Amet minim mollit non deserunt ullamco est sit aliqua dolor do
                    amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud
                    amet.
                </p>
            </div>
            <div class="columns is-multiline">
                <TestimonialBlock
                    v-for="testimonial, idx in testimonials"
                    :key="idx"
                    :text="testimonial"
                />
            </div>
        </div>
    </section>
</template>

<script setup>
const testimonials = [
    "Я был впечатлен результатами, которые достиг благодаря участию в программе. Мой бизнес получил новый импульс, а мои навыки руководителя значительно улучшились. Большое спасибо команде за их поддержку и экспертизу",
    "Я был впечатлен результатами, которые достиг благодаря участию в программе. Мой бизнес получил новый импульс, а мои навыки руководителя значительно улучшились. Большое спасибо команде за их поддержку и экспертизу",
    "Я был впечатлен результатами, которые достиг благодаря участию в программе. Мой бизнес получил новый импульс, а мои навыки руководителя значительно улучшились. Большое спасибо команде за их поддержку и экспертизу",
    "Я был впечатлен результатами, которые достиг благодаря участию в программе. Мой бизнес получил новый импульс, а мои навыки руководителя значительно улучшились. Большое спасибо команде за их поддержку и экспертизу",
    "Я был впечатлен результатами, которые достиг благодаря участию в программе. Мой бизнес получил новый импульс, а мои навыки руководителя значительно улучшились. Большое спасибо команде за их поддержку и экспертизу",
    "Я был впечатлен результатами, которые достиг благодаря участию в программе. Мой бизнес получил новый импульс, а мои навыки руководителя значительно улучшились. Большое спасибо команде за их поддержку и экспертизу",
]

</script>