<template>
    <div class="container">
        <div class="login">
            <br>
            <br>
            <br>
            <br>
            <section class="h-100">
              <header class="container h-100">
                <div class="d-flex align-items-center justify-content-center h-100">
                  <div class="d-flex flex-column">
                      <div class="card">
                        <div class="card-header">
                            <h2>MyRCLHome</h2>
                        </div>
                        <div class="card-body">
                          <form>
                            <div class="form-group">
                              <label for="username">Username/Email</label>
                              <input type="email" class="form-control" id="username" aria-describedby="emailHelp" placeholder="Username">
                            </div>
                            <div class="form-group">
                              <label for="password">Password</label>
                              <input type="password" class="form-control" id="password" placeholder="Password">
                            </div>
                            <button type="submit" class="btn btn-primary">Log In</button>
                          </form>
                      </div>
                      </div>
                  </div>
              </div>
              </header>
            </section>
        </div>
    </div>
</template>

<script>
export default {
  name: 'login',
  data () {
    return {
      msg: 'This is For Login'
    }
  }
}
</script>

<style scoped>
</style>
