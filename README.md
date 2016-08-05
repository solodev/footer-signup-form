# Footer Signup Form
Users are 31% more likely to signup for your product or service if there is an easy-to-use form to signup on every page of your website rather than a dedicated page they are required to navigate to. This code will show you how to add a signup footer form to your website.

## Tutorial

For detailed instructions, view Solodev's [Drive Signups with Stylish Footer Forms](https://www.solodev.com/blog/web-design/drive-signups-with-stylish-footer-forms.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/r1bud51d/).

## HTML

The footer form includes the following basic HTML.
```
<section class="form-section">
   <div class="container">
      <div class="row">
         <div class="col-md-10 col-md-offset-1">
            <h3>
               Sign up for WebCorpCo Today!
            </h3>
            <form action="" method="post" id="footer-form">
               <div class="col-md-3 video-form-fields">
                  <div class="form-group has-error has-danger">
                     <label for="your_email" class="sr-only">What is your email?</label> <input type="email" name="member_email" class="form-control" id="member_email2" placeholder="Work Email" required>
                  </div>
               </div>
               <div class="col-md-3 video-form-fields">
                  <div class="form-group has-error has-danger">
                     <label for="visitor_company" class="sr-only">What company do you work for?</label> <input type="text" class="form-control" name="member_company" id="visitor_company" placeholder="Company" required>
                  </div>
               </div>
               <div class="col-md-3 video-form-fields">
                  <div class="form-group has-error has-danger">
                     <label for="visitor_company" class="sr-only">What is your job title?</label> <input type="text" class="form-control" name="member_company" id="visitor_company" placeholder="Job Title" required>
                  </div>
               </div>
               <div class="col-md-3 video-form-fields">
                  <input type="hidden" name="mode" value="saveVisitor" id="mode"> <button type="submit" id="Submit2" class="btn btn-primary btn-solodev">Get Started</button>
               </div>
            </form>
         </div>
         <div class="clearfix"></div>
         <p class="small-text">
            By clicking "Get Started" I agree to WebCorpCo's <a href="">Terms of Service.</a>
         </p>
      </div>
   </div>
   <div class="clearfix"></div>
</section>

```
## CSS

All necessary CSS is in signup-footer.css

## External Includes

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">

```
