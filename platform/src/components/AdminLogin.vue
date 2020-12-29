<template>
    <div class="login">
        <div class="row">
            <div class="col-md-12">
                <div class="card">
                    <div class="login-box">
                        <div class="login-snip">
                            <input id="tab-1" type="radio" name="tab" class="sign-in" checked><label for="tab-1" class="tab">Admin</label>
                            <input id="tab-2" type="radio" name="tab" class="sign-up"><label for="tab-2" class="tab">Register Employee</label>
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
                                <div class="sign-up-form">
                                    <div class="group">
                                        <label for="user" class="label">Username</label>
                                        <input id="user" type="text" class="form-control bg-white border-md" placeholder="Create your Username">
                                    </div>
                                    <div class="group">
                                        <label for="pass" class="label">Password</label>
                                        <input id="pass" type="password" class="form-control bg-white border-md" data-type="password" placeholder="Create your password">
                                    </div>
                                    <div class="group">
                                        <label for="pass" class="label">Repeat Password</label>
                                        <input id="pass" type="password" class="form-control bg-white border-md" data-type="password" placeholder="Repeat your password">
                                    </div>
                                    <div class="group">
                                        <label for="pass" class="label">Email Address</label>
                                        <input id="pass" type="text" class="form-control bg-white border-md" placeholder="Enter your email address">
                                    </div>
                                    <div class="group">
                                        <input type="submit" class="btn btn-primary btn-block" value="Sign Up">
                                    </div>
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
    name: 'AdminLogin',
    data() {
        return {
            isAdmin: true 
        }
    }
}
</script>

<style lang="scss" scoped>
    @import '../assets/css/login';
</style>