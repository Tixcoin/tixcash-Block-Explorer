<template>
    <ul class="f-social-media-links no-markers">
        <li>
            <a href="https://www.facebook.com/profile.php?id=100084802973550" target="_blank" rel="nofollow" title="Tixcash on facebook">
                <icon data="@/assets/svg/social-media/facebook.svg" width="24" height="24"></icon>
            </a>
        </li>
        <li>
            <a href="https://twitter.com/tixcash?t=iJZ6JCJmlt74kQLRzoFKIQ&s=09" target="_blank" rel="nofollow" title="Tixcash on Twitter">
                <icon data="@/assets/svg/social-media/twitter.svg" width="24" height="24"></icon>
            </a>
        </li>
        <li>
            <a href="https://github.com/tixcoin" target="_blank" rel="nofollow" title="Tixcash on Github">
                <icon data="@/assets/svg/social-media/github.svg" width="24" height="24"></icon>
            </a>
        </li>
    </ul>
</template>

<script>
    export default {
    }
</script>

<style lang="scss">
    .f-social-media-links {
        --f-social-media-links-color: #{$secondary-color-lighter};

        color: var(--f-social-media-links-color);

        li {
            display: inline-block;
            vertical-align: middle;

            &:not(:last-child) {
                padding-inline-end: 24px;
            }

            @include links() {
                color: inherit;
                transition: color $transition-length ease;
            }

            a:not(.btn):hover {
                color: #fff;
            }
        }

        .linkedin {
            position: relative;
            top: -3px;
        }
    }
</style>
