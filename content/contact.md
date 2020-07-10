---
title: "Contact"
date: 2020-07-07T12:03:43+01:00
draft: false
menu: "main"
---
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="female">non-stem student</option>
      <option value="male">stem student</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>

 <form action="/details on yoursels">
    <label><input type="radio" name="male-female-prefernottosay"> female</label>
    <label><input type="radio" name="male-female-prefernottosay"> male</label>
    <label><input type="radio" name="male-female-prefernottosay"> prefernototsay/label><br>
    <p>This form is to get an idea on what you are feeling now, so I can tailor more of the content</p>
    <label><input type="checkbox" name="personality"> Work well under pressure</label>
    <label><input type="checkbox" name="personality"> Failure</label>
    <label><input type="checkbox" name="personality"> Risk Taker</label><br>
    <label><input type="checkbox" name="personality"> Perfectionist</label>
    <button type="submit">Submit</button>
  </form>
