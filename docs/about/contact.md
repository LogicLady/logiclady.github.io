<form 
      id="fs-frm" 
      name="contact-form" 
      accept-charset="utf-8" 
      action="https://formspree.io/f/xjvlzjyd" 
      enctype="multipart/form-data" 
      method="post"
>
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last Name" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.com" required="">
      <label for="telephone">Phone Number &nbsp;<small>(Optional)</small></label>
    <input type="telephone" name="telephone" id="telephone" placeholder="(555) 555-5555">
      <label for="email-subject">Subject</label>
      <input type="text" name="_subject" id="email-subject" placeholder="Reason for Contacting" required="">
    <label for="message">Message</label>
    <textarea rows="6" name="message" id="message" placeholder="Please provide a message explaining your reason for reaching out or how I can be of assistance." required=""></textarea>
    <input type="submit" value="Send Message">
  </fieldset>
</form>
