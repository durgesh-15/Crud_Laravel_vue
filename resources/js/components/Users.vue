<template>
    <div class="card shadow mb-4">
            <div class="card-header py-3">
                <h6 class="m-0 font-weight-bold text-primary">User Table</h6>
            </div>
            <div class="card-body">
                <div class="table-responsive">
                    <table class="table table-bordered" id="dataTable" width="100%" cellspacing="0">
                        <thead>
                            <tr>
                                <th>ID</th>
                                <th>Name</th>
                                <th>Email</th>
                                <th>Type</th>
                                <th>Modifiy</th>       
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>1</td>
                                <td>System Architect</td>
                                <td>Dy@gmail.com</td>
                                <td>61</td>
                                <td>
                                    <a class="btn btn-primary"><i class="fas fa-fa-edit"></i></a>
                                    <a class="btn btn-dark"></a>
                                </td>
                            </tr>                    
                        </tbody>
                    </table>
                </div>
            </div>
    </div>
</template>
<script>
export default {

}

</script>