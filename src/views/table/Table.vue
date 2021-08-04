<template>
    <div class="container"> 
        <div class="row">
            <div class="col-lg-12 d-flex">
                <div class="mr-auto"> 
                    <form class="form-inline">
                        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
                    </form>
                </div>
                <div class="w-25"> 
                    <button class="btn btn-primary w-100" type="button" data-toggle="modal" data-target="#exampleModal">Add</button>
                    <Modal/>
                </div>
            </div>
        </div>
        <table class="table table-striped table-dark mt-4">
            <thead>
                <tr>
                <th scope="col">#</th>
                <th scope="col">Product Name</th>
                <th scope="col">Price</th>
                <th scope="col">Location</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                <th scope="row">1</th>
                <td>Mark</td>
                <td>Otto</td>
                <td>@mdo</td>
                </tr>
                <tr>
                <th scope="row">2</th>
                <td>Jacob</td>
                <td>Thornton</td>
                <td>@fat</td>
                </tr>
                <tr>
                <th scope="row">3</th>
                <td>Larry</td>
                <td>the Bird</td>
                <td>@twitter</td>
                </tr>
            </tbody>
        </table>
    </div>
</template>

<script>
    import Modal from './Modal.vue'
    export default {
        name: "Table",
        components: {
            Modal
        },
    }
</script>

<style scoped>

</style>