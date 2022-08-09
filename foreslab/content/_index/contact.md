+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 1200
background = "secondary"
form_name = "defaultContact"

title = "Contactanos"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://formspree.io/f/mpzbrokw" #default: formspree.io
email = "foreslab.peru@gmail.com"
button = "Send Button" # defaults to theme default
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Nombres *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Email *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Telefono *"
  #error = "--" # defaults to theme default

[fields.message]
  text = "Dejanos un mensaje *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++
