<template>
    <div>
        <div class="container">
            <div class="row">
                <p class="lead"> Sisek Portfolio &copy; 
                    <span>
                        {{ currentYear }}
                    </span>
                </p>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name : "FooterComp",

        data(){
            return {
                currentYear : new Date().getFullYear()
            }
        }


        }
    
</script>

<style scoped>

</style>