<style>
     .aa{
     text-align: center;
        margin-top: 17%;
        
 } 
 .bb{
     margin-left: 22%;
 }
</style>
<form action="..." method="..." class="w-600 mw-full bb"> <!-- w-400 = width: 40rem (400px), mw-full = max-width: 100% -->
  <div class="form-group aa">
    <label for="username" class="required">Username</label>
    <input type="text" class="form-control" id="username" placeholder="Username" required="required">
    <div class="form-text">
      Only alphanumeric characters and underscores allowed.
    </div>
  </div>
  <div class="form-group">
    <label for="password" class="required">Password</label>
    <input type="password" class="form-control" id="password" placeholder="Password" required="required">
    <div class="form-text">
      Must be at least 8 characters long, and contain at least one special character.
    </div>
  </div>
  <div class="form-group">
    <label for="confirm-password" class="required">Confirm password</label>
    <input type="password" class="form-control" id="confirm-password" placeholder="Confirm password" required="required">
    <div class="form-text">
      Must match the above password exactly.
    </div>
  </div>
  <input class="btn btn-primary btn-block" type="submit" value="Sign up">
</form>
