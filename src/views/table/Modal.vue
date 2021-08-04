<template>
    <div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">Kindly fill this</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <form class="form-horizontal">
                        <div class="form-group text-left">
                            <label for="">Product Name</label>
                            <input type="text" class="form-control" placeholder="Product Name"/>
                        </div>

                        <div class="form-group text-left">
                            <label for="">Price</label>
                            <input type="text" class="form-control" placeholder="Price"/>
                        </div>

                        <div class="form-group text-left">
                            <label for="">Location</label>
                            <input type="text" class="form-control" placeholder="Location"/>
                        </div>

                        <div>
                            <button type="submit" class="btn btn-primary">Submit</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default {
        name: "Modal",
    }
</script>

<style scoped>
    label{
        font-weight: bold;
    }
</style>