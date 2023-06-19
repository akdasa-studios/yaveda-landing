<template>
    <nav class="navbar py-5">
        <div class="container is-fluid">
            <div class="navbar-brand">
                <a class="navbar-item" href="#">
                    <span class="navbar-item px-0 title is-5 has-text-dark">
                        <img src="assets/yagna.png" alt="" style="height: 20px; margin: 5px;">
                        Ягья. Онлайн участие
                    </span>
                </a>
                <a class="navbar-menu-open navbar-burger" role="button" type="button" data-toggle="side-menu">
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                </a>
            </div>

            <div class="navbar-menu">
                <div class="navbar-end">
                    <ul class="navbar-item">
                        <li><a class="navbar-item" href="#">О нас</a></li>
                        <li><a class="navbar-item" href="#">Расписание</a></li>
                        <li><a class="navbar-item" href="#">Отзывы</a></li>
                    </ul>
                    <div class="navbar-item is-hidden-mobile pl-0">
                        <OrderButton />
                    </div>
                </div>
            </div>
        </div>
    </nav>
</template>