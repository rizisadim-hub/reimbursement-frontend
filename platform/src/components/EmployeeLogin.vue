<template>
    <div class="login" v-show="isAdmin">
        <div class="row">
            <div class="col-md-12">
                <div class="card">
                    <div class="login-box">
                        <div class="login-snip">
                            <div class="login-space">
                                <div class="login">
                                    <div class="group">
                                        <label for="user" class="label">Username</label>
                                        <input id="username" type="text" name="username" class="form-control bg-white border-md" placeholder="Enter your username">
                                    </div>
                                    <div class="group">
                                        <label for="pass" class="label">Password</label>
                                        <input id="password" type="text" name="password" class="form-control bg-white border-md" data-type="password" placeholder="Enter your password">
                                    </div>
                                    <div class="group">
                                        <input id="check" type="checkbox" class="check" checked>
                                        <label for="check"><span class="icon"></span> Keep me Signed in</label>
                                    </div>
                                    <div class="group">
                                        <input type="submit" class="btn btn-primary btn-block" value="Sign In">
                                    </div>
                                    <div class="hr"></div>
                                    <div class="foot"> <a href="#">Forgot Password?</a> </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'EmployeeLogin',
    data() {
        return {
            isAdmin: false
        }
    }
}
</script>

<style lang="scss" scoped>
    @import '../assets/css/login';
</style>