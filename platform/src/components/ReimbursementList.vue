<template>
    <div class="reimbursement-list-wrapper">
        <div class="row reimbursement-header">
            <div class="col-6 d-flex align-items-center">Reimbursement System</div>
            <div class="col-6 d-flex justify-content-end align-items-center">Profile</div>
        </div>
        <div class="reimbursement-list-content">
            <button class="btn btn-primary">Create Reimbursement</button>
            <table id="table_id" class="table table-striped table-bordered datatable">
                <thead>
                    <tr>
                        <th>ID</th>
                        <th>Reimbursement type</th>
                        <th>Amount</th>
                        <th>Date filed</th>
                        <th>Attached files</th>
                        <th>Approved by</th>
                        <th>Status</th>
                        <th>Action</th>
                    </tr>
                </thead>
                <tr>
                    <td>1</td>
                    <td>Gym allowance</td>
                    <td>2500</td>
                    <td>2021-01-01</td>
                    <td>Files attached</td>
                    <td>Cherry Lou Morcilla</td>
                    <td>Approved</td>
                    <td>
                        <input type="button" class="btn btn-primary" value="Edit">
                    </td>
                </tr>
                <tr>
                    <td>1</td>
                    <td>Gym allowance</td>
                    <td>2500</td>
                    <td>2021-01-01</td>
                    <td>Files attached</td>
                    <td>Cherry Lou Morcilla</td>
                    <td>Approved</td>
                    <td>
                        <input type="button" class="btn btn-primary" value="Edit">
                    </td>
                </tr>
            </table>
        </div>
    </div>
</template>

<script>


export default {
    name: 'ReimbursementList',
    data() {
        return {
            isAdmin: true 
        }
    }
}
</script>

<style lang="scss" scoped>
    @import '../assets/css/reimbursement-list';
</style>