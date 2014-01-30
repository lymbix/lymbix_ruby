= Lymbix

Lymbix is an easy to use wrapper for the Lymbix Tone API service to tonalize a phrase or passage.

To install the Lymbix gem see command below:
	
  gem install lymbix

It is possible to tonalize a phrase like:

  lymbix = Lymbix::Base.new(authentication_key)
  lymbix.api_version = 2.1 (available in gem version 0.4.3)
  lymbix.tonalize("I like ruby.")


To be able to access this resource - please go to <a href="http://www.lymbix.com">Lymbix.com</a> and create an account. You need to agree to the licensing terms, and your account needs to be approved. Once approved, you will be able to get your authentication key.

Note: The Lymbix gem requires the rest-client gem version >= 1.4.2

== Authors and credits

Authors::                Pat Roy, Josh Merchant, Matthew Lagacé, Mathieu Dargavel, Maxime Santerre
Copyright::				 Lymbix Inc
License::				 Subject to licensing terms - see http://www.lymbix.com
